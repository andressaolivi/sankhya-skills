# API — ServiceBroker (chamadas HTTP/JSON ao Sankhya)

O **ServiceBroker** é o mecanismo de RPC do Sankhya: clientes (web, mobile, integrações) postam para um endpoint do servidor com JSON ou XML, indicando o serviço (`serviceName="<NomeSP>.<metodo>"`) e o broker invoca a lógica correspondente no servidor.

Este arquivo cobre o **padrão de uso** e os serviços públicos mais comuns. Para a lista completa de serviços disponíveis num ambiente específico, consulte a documentação oficial do Sankhya.

---

## Modelo conceitual

```
HTTP POST → endpoint do ServiceBroker
    ↓ filtro identifica serviceName="<NomeSP>.<metodo>"
        ↓ servidor invoca o método correspondente
            ↓ método lê dados do request, executa lógica, escreve resposta
        ↑ retorna XML/JSON ao cliente
```

Cada serviço (chamado **Service Provider — SP**) é uma classe no servidor com métodos públicos que recebem um único parâmetro: **`ServiceContext`** (objeto que carrega request + response).

---

## `ServiceContext` — request/response

Pacote: `br.com.sankhya.ws`. Carrega o estado completo de uma chamada de service.

### Métodos comuns em customização

```java
public class ServiceContext implements Serializable {

    // ─── status (constantes) ──────────────────────────────────────────────
    public static final int STATUS_OK;
    public static final int STATUS_ERROR;
    public static final int STATUS_INFO;
    public static final int STATUS_ERROR_BUSINESS;

    // ─── current (ThreadLocal) ────────────────────────────────────────────
    public static ServiceContext getCurrent();

    // ─── request ──────────────────────────────────────────────────────────
    public HttpServletRequest getHttpRequest();
    public boolean            isJsonRequest();
    public Element            getRequestBody();          // XML
    public Element            getBodyElement();          // alias

    // ─── parâmetros tipados (atalhos) ─────────────────────────────────────
    public BigDecimal getParameterAsBigDecimal(String nome);
    public Boolean    getParameterAsBoolean   (String nome);
    public String     getParameterAsString    (String nome);
    public Timestamp  getParameterAsTimestamp (String nome);

    // ─── response ─────────────────────────────────────────────────────────
    public void       setJsonResponse(JsonObject json);
    public JsonObject getJsonResponse();

    // ─── arquivos temporários ─────────────────────────────────────────────
    public File getTempFolder();
}
```

### Padrões de uso

```java
// Ler parâmetro:
BigDecimal nunota = ctx.getParameterAsBigDecimal("nunota");

// Ler corpo XML:
org.jdom.Element body = ctx.getRequestBody();
String acao = body.getAttributeValue("acao");

// Resposta JSON:
JsonObject resp = new JsonObject();
resp.addProperty("status", "ok");
ctx.setJsonResponse(resp);

// Recuperar contexto em qualquer ponto da pilha (ThreadLocal):
ServiceContext atual = ServiceContext.getCurrent();
```

---

## Serviços públicos comuns

A Sankhya documenta no portal de parceiros os serviços para integração. Os mais usados em projetos:

### `GatewayServiceProviderSP` — CRUD genérico de entidades

CRUD genérico para entidades dinâmicas — equivalente "REST" do Sankhya, mas via XML/JSON do broker.

| Método | Para quê |
|---|---|
| `find` | SELECT por critério (entidade + filtros + campos) |
| `save` | INSERT/UPDATE de uma entidade |
| `saveAll` | Batch de saves |
| `getPriceList` | Tabela de preços de um cliente |
| `getCustomerCredit` | Crédito do cliente |

Payload típico de `find` (JSON):

```json
{
  "serviceName": "GatewayServiceProviderSP.find",
  "requestBody": {
    "entityName": "Parceiro",
    "criteria":   { "expression": { "$": "this.CODPARC = 1234" } },
    "fields":     { "field": [{ "name": "CODPARC" }, { "name": "NOMEPARC" }] }
  }
}
```

### `ActionButtonsSP` — invocação de botões de ação

| Método | Para quê |
|---|---|
| `getActions` | Lista os botões disponíveis para um determinado contexto (tela + permissões) |
| `executeJava` | Executa botão de ação tipo Java (`AcaoRotinaJava`) |
| `executeScript` | Executa botão de ação tipo Script |
| `executeSTP` | Executa botão tipo Stored Procedure |

### `DatasetSP` — leitura de datasets

Usado para popular grids e cards com dados parametrizados, sem precisar conhecer entidade exata.

### `PesquisaSP` — pesquisas (popup F3)

Suporta as pesquisas configuradas no Sankhya (lookup de parceiro, produto, etc.) com paginação e filtros.

---

## Exemplo: chamar o ServiceBroker via HTTP (JSON)

```http
POST /mge/service.sbr?serviceName=GatewayServiceProviderSP.find&outputType=json HTTP/1.1
Host: sankhya.cliente.com.br
Cookie: JSESSIONID=...
Content-Type: application/json

{
  "serviceName": "GatewayServiceProviderSP.find",
  "requestBody": {
    "entityName": "Parceiro",
    "criteria":   { "expression": { "$": "this.CODPARC = 1234" } },
    "fields":     { "field": [{ "name": "CODPARC" }, { "name": "NOMEPARC" }] }
  }
}
```

Resposta:

```json
{
  "serviceName": "GatewayServiceProviderSP.find",
  "status": "1",
  "responseBody": {
    "entities": {
      "entity": [{ "CODPARC": "1234", "NOMEPARC": "Cliente Exemplo" }]
    }
  }
}
```

> Para autenticação, consulte a documentação oficial Sankhya — em geral envolve uma chamada prévia a `MobileLoginSP.login` ou login web tradicional para obter a sessão.

---

## Criando um SP customizado

Em versões modernas do Sankhya, há duas formas:

1. **EJB Stateless (clássico)** — interface, bean, home seguindo o padrão EJB 2.x, registrado nos descritores. Cada método recebe `ServiceContext`. Mais comum em customizações legadas.

2. **REST API customizada (moderno)** — via biblioteca de Easy API do Sankhya, com anotações estilo JAX-RS (`@Path`, `@GET`, `@POST`). **Preferir essa abordagem** para integrações novas.

Verifique a documentação oficial do portal de parceiros para a forma recomendada na sua versão de Sankhya.

---

## Pontos de atenção

- Os SPs são geralmente **stateless** — não armazene estado em campos de instância.
- Erros lançados como `MGEModelException` viram mensagens amigáveis ao usuário; outras exceções viram "erro interno".
- Em integrações via HTTP, sempre tratar timeout e reautenticação — sessões expiram.
- `ServiceContext.getCurrent()` (ThreadLocal) é útil dentro de eventos/regras chamadas a partir de um SP, para acessar dados do request original.

---

## Veja também

- `references/api-actionbuttons.md` — `executeJava` do `ActionButtonsSP` chama um `AcaoRotinaJava`.
- `references/api-utils.md` — convenções de `BigDecimal`, `Timestamp`, exceções.
