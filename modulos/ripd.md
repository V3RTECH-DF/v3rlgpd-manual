---
title: "RIPD (Relatório de Impacto)"
nav_order: 13
parent: "Módulos"
permalink: /modulos/ripd/
role: encarregado
routes: ["#/ripd", "#/ripd/assistant", "#/ripd/edit/:id", "#/ripd/view/:id"]
screenshots: [ripd-07-modulo-assistente, ripd-04-assistente-triagem, ripd-05-assistente-matriz, ripd-01, ripd-02, ripd-03]
last_verified: 2026-06-27
status: rascunho
---

# Módulo RIPD — Relatório de Impacto à Proteção de Dados

O **RIPD** documenta os riscos de um tratamento de dados e as medidas para mitigá-los. É um recurso **geral da LGPD** (art. 38) e também atende ao ECA Digital (art. 16) quando há dados de menores. Sobre **quando** fazer um RIPD, veja [Relatório de Impacto: quando fazer](/modelos/ripd/).

## Assistente do RIPD

Não sabe se precisa de um RIPD nem por onde começar? Use o **✨ Assistente do RIPD** (botão na tela do módulo RIPD). Em vez de encarar um documento técnico em branco, você **responde perguntas simples** e o assistente monta um **rascunho** para revisar.

[![Módulo RIPD com o botão do Assistente](/assets/ripd-07-modulo-assistente.png)](/assets/ripd-07-modulo-assistente.png)
*O botão "Assistente de RIPD" fica no topo da tela do módulo.*

Como funciona, em poucos passos:

1. **Triagem de necessidade** — perguntas **sim/não** (atende menores? coleta dados sensíveis? faz perfilamento ou decisão automatizada? trata em larga escala? faz monitoramento?). Ao final, o assistente **recomenda** — ou não — elaborar o RIPD, explicando o porquê.
2. **Escopo a partir do ROPA** — você seleciona as **atividades do Inventário** que o RIPD vai cobrir. Se uma atividade já tem um RIPD, o assistente **avisa** e sugere revisar o existente (em vez de duplicar).
3. **Matriz de risco pré-preenchida** — o assistente sugere os riscos comuns daquele tipo de tratamento, já com probabilidade, severidade, mitigação e risco residual. Tudo **editável**.
4. **Necessidade e proporcionalidade** — texto inicial montado a partir do ROPA, editável.
5. **Parecer e decisão do Encarregado** — campos para o Encarregado preencher (com exemplos de redação como referência).
6. **Gerar rascunho** — o assistente cria o RIPD e abre no **editor**, onde você refina e **finaliza a versão**.

[![Triagem do Assistente do RIPD](/assets/ripd-04-assistente-triagem.png)](/assets/ripd-04-assistente-triagem.png)
*Triagem de necessidade: perguntas sim/não e a recomendação ao final.*

[![Matriz de risco pré-preenchida](/assets/ripd-05-assistente-matriz.png)](/assets/ripd-05-assistente-matriz.png)
*A matriz de risco já vem com itens sugeridos — todos editáveis.*

> 💡 Passo a passo detalhado em [Fazer um RIPD com o Assistente](/guias/fazer-ripd-assistente/).

> ⚠️ O assistente **estrutura e apoia**, mas a **análise e a decisão final são do Encarregado** — não é parecer jurídico nem garante validade.

## Criar manualmente

Prefere montar do zero, sem o assistente? O editor manual segue disponível:

1. No menu, abra **Relatório de Impacto (RIPD)** e clique em **+ Novo RIPD**.
   <!-- screenshot: ripd-01 — editor de RIPD com seleção de atividades do ROPA -->
2. **Escopo:** selecione **uma ou mais atividades** do seu Inventário (ROPA). Os dados dessas atividades aparecem para consulta e são **congelados** quando você finalizar.
3. Preencha **necessidade e proporcionalidade**, a **matriz de risco** e o **parecer/decisão**.
4. Na **matriz de risco**, para cada risco escolha **probabilidade** e **severidade**; o **nível** (baixo/médio/alto) é calculado automaticamente. Registre a **mitigação** e o **risco residual**.
   <!-- screenshot: ripd-02 — matriz de risco -->
5. **Salvar Rascunho** guarda sem congelar. **Finalizar Versão** congela uma versão (com a data e o retrato do ROPA daquele momento).
6. Depois de finalizar, você pode **Imprimir / Exportar PDF** e consultar o **histórico de versões**. Editar um RIPD finalizado cria um **novo rascunho**, preservando a versão anterior.
   <!-- screenshot: ripd-03 — RIPD finalizado / impressão -->

> 💡 **Por que isso importa**
>
> O RIPD é a melhor evidência de que a organização **pensou os riscos antes**. As versões congeladas servem de prova de diligência ao longo do tempo.

> ⚠️ O V3RLGPD estrutura o RIPD; o conteúdo e a decisão são da organização. Não é parecer jurídico.
