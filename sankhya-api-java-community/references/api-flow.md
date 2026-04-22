# API — Workflow / Flow (BPM Sankhya)

Pacote: **`br.com.sankhya.extensions.flow`**
Tipo: API pública oficial de extensão.

O Sankhya tem um motor de processos (Workflow / Flow / BPM) onde processos são modelados graficamente e cada **tarefa** ou **evento** pode delegar lógica para uma classe Java.

---

## Interfaces principais

### `EventoProcessoJava` — para eventos do processo (start, end, gateway, listener)

```java
public interface br.com.sankhya.extensions.flow.EventoProcessoJava {
    void executar(ContextoEvento ctx) throws Exception;
}
```

### `TarefaJava` — para tarefas (atividades) automatizadas em Java

```java
public interface br.com.sankhya.extensions.flow.TarefaJava {
    void executar(ContextoTarefa ctx) throws Exception;
}
```

---

## Hierarquia de contextos

```
ContextoFlowGet  (leitura)
   ↑
ContextoFlow     (leitura + escrita)
   ↑              ↑
ContextoTarefa   ContextoEvento
```

### `ContextoFlowGet` — operações de leitura

```java
public interface br.com.sankhya.extensions.flow.ContextoFlowGet {
    QueryExecutor       getQuery();
    Object              getParametroSistema(String nome);
    BigDecimal          getUsuarioLogado();
    Object              getCampo(String nome);

    Object              buscarDado(String entidade, String campo, String where, Object param) throws Exception;
    Map<String, Object> buscarDados(String[] campos, String entidade, String where, Object param) throws Exception;
    Collection<Map<String, Object>> buscarLinhas(String[] campos, String entidade, String where, Object param) throws Exception;

    Registro[] getLinhasFormulario(String idFormulario) throws Exception;
    Registro[] getLinhasFormularioAtividade(String idForm, String idAtividade, String idInst) throws Exception;
    Registro[] getLinhasFormularioNativo(String idFormulario) throws Exception;
    Registro   carregaLinha(String entidade, Object[] pk) throws Exception;

    Object     getIdInstanceProcesso();   // ID da instância do processo em execução
    Object     getIdInstanceTarefa();     // ID da instância da tarefa
    BigDecimal getCodProcesso();          // código do processo (cadastro)
    BigDecimal getVersao();
    BigDecimal getUsuarioInclusao();
    Object     getDhInclusao();
    Map<String, Object> getIObjectInstanciaProcesso();
    String[]   getCampos();
    String     getEmailSolicitante() throws Exception;
}
```

### `ContextoFlow` — adiciona escrita e e-mail

```java
public interface br.com.sankhya.extensions.flow.ContextoFlow extends ContextoFlowGet {
    void eMail(String para, String assunto, String corpo) throws Exception;

    Registro novaLinhaFormulario(String idForm) throws Exception;
    Registro novaLinhaFormularioNativo(String idForm) throws Exception;
    Registro novaLinha(String entidade) throws Exception;

    void setCampo(String nome, String valor);
    void salvarCamposAlterados();
    void saveAll();
}
```

### `ContextoTarefa` — alias semântico para tarefas

```java
public interface br.com.sankhya.extensions.flow.ContextoTarefa extends ContextoFlow {}
```

Não adiciona métodos — usado como tipo do parâmetro de `TarefaJava.executar()` para indicar contexto de tarefa (vs. evento).

### `ContextoEvento` — adiciona campos específicos de eventos do processo

```java
public interface br.com.sankhya.extensions.flow.ContextoEvento extends ContextoFlow {
    String     getOnde();           // local do evento (start, end, intermediate...)
    String     getAcao();           // ação que o disparou
    String     getQuando();         // momento (before/after)
    BigDecimal getNovoDono();       // novo responsável (em transferência)
    BigDecimal getDonoAnterior();   // dono anterior

    void setCampo(String nome, Object valor);
}
```

---

## Exemplo: tarefa Java que aprova automaticamente solicitações de baixo valor

```java
package com.exemplo.flow;

import br.com.sankhya.extensions.flow.TarefaJava;
import br.com.sankhya.extensions.flow.ContextoTarefa;
import java.math.BigDecimal;

public class AprovacaoAutomaticaPequenosValores implements TarefaJava {

    private static final BigDecimal LIMITE = new BigDecimal("500.00");

    @Override
    public void executar(ContextoTarefa ctx) throws Exception {
        BigDecimal valorSolicitado = (BigDecimal) ctx.getCampo("VLRSOLICITADO");

        if (valorSolicitado == null) {
            ctx.eMail("financeiro@empresa.com",
                      "Solicitação sem valor",
                      "Instância " + ctx.getIdInstanceProcesso());
            return;
        }

        if (valorSolicitado.compareTo(LIMITE) <= 0) {
            ctx.setCampo("STATUS", "APROVADO_AUTOMATICO");
            ctx.setCampo("DH_APROVACAO", new java.sql.Timestamp(System.currentTimeMillis()));
            ctx.salvarCamposAlterados();
        } else {
            ctx.setCampo("STATUS", "PENDENTE_GESTOR");
            ctx.salvarCamposAlterados();
        }
    }
}
```

---

## Pontos de atenção

- `getCampo`/`setCampo` operam sobre os **campos do formulário** do Workflow, não diretamente em entidades do banco.
- Para alterar dados em entidades reais, use `novaLinha("TGFCAB")` ou `carregaLinha("TGFCAB", new Object[]{nunota})`.
- `salvarCamposAlterados()` persiste apenas o que foi alterado via `setCampo`. `saveAll()` força tudo.
- Lançar exceção dentro de `executar(...)` cancela a tarefa e geralmente joga o processo para tratamento de erro do BPM.

---

## Veja também

- `references/api-actionbuttons.md` — `Registro` e `QueryExecutor` retornados aqui têm a mesma API.
- `references/api-eventos.md` — diferença: eventos JAPE são em entidades (`TGFCAB`), eventos de Flow são em **processos** do BPM.
