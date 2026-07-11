---
title: "Fazer um RIPD com o Assistente"
nav_order: 9
parent: "Guias por tarefa"
permalink: /guias/fazer-ripd-assistente/
role: encarregado
routes: ["#/ripd/assistant", "#/ripd"]
screenshots: [ripd-04-assistente-triagem, ripd-05-assistente-matriz, ripd-06-assistente-editor]
last_verified: 2026-06-27
status: publicado
---

# Fazer um RIPD com o Assistente

O **RIPD** (Relatório de Impacto à Proteção de Dados) documenta os riscos de um tratamento e as medidas para reduzi-los. É um recurso geral da LGPD (art. 38) e também atende ao ECA (art. 16) quando há dados de menores. O **Assistente do RIPD** ajuda você a montar o rascunho a partir das atividades já registradas no seu Inventário (ROPA).

> ⚠️ **Atenção**
>
> O assistente **estrutura e apoia** a elaboração do RIPD; ele **não** substitui a análise técnica nem garante validade jurídica. A **análise e a decisão final são do Encarregado**. Veja o módulo em [RIPD (Relatório de Impacto)](/modulos/ripd/) e [quando fazer um RIPD](/modelos/ripd/).

## Quando usar

- Você quer saber **se** um tratamento precisa de RIPD.
- Já sabe que precisa e quer um **rascunho organizado** para revisar, em vez de partir do editor em branco.

## Passo a passo

1. **Abra o Assistente do RIPD** no módulo **RIPD**.
2. **Faça a triagem de necessidade.** O assistente apresenta perguntas **sim/não** sobre o tratamento (por exemplo, se envolve dados sensíveis, dados de menores, monitoramento ou decisões automatizadas) e, ao final, dá uma **recomendação** sobre a necessidade de elaborar o RIPD.

   [![Triagem do Assistente do RIPD](/assets/ripd-04-assistente-triagem.png)](/assets/ripd-04-assistente-triagem.png)
   *As respostas sim/não levam a uma recomendação sobre a necessidade do RIPD.*

3. **Defina o escopo a partir do ROPA.** O escopo do RIPD é **ancorado no seu Inventário**: você seleciona **uma ou mais atividades** do ROPA. Os dados dessas atividades aparecem para consulta — e serão **congelados** quando você finalizar a versão.
4. **Revise a matriz de risco pré-preenchida.** O assistente sugere uma **matriz de risco** já com itens iniciais; ela é **totalmente editável**. Para cada risco, escolha **probabilidade** e **severidade** — o **nível** (baixo/médio/alto) é calculado automaticamente. Registre a **mitigação** e o **risco residual**.

   [![Matriz de risco pré-preenchida](/assets/ripd-05-assistente-matriz.png)](/assets/ripd-05-assistente-matriz.png)
   *Cada risco vem com probabilidade, severidade, mitigação e risco residual sugeridos — todos editáveis.*

5. **Preencha necessidade e proporcionalidade.** Descreva por que o tratamento é necessário e proporcional à finalidade.
6. **Registre o parecer e a decisão do Encarregado.** Esta é a parte que **só o Encarregado decide**: o parecer técnico e a decisão final (prosseguir, ajustar, não prosseguir) são responsabilidade da OSC, não do assistente.
7. **Gere o rascunho e finalize no editor.** O assistente entrega um **rascunho** que abre no editor de RIPD. Use **Salvar Rascunho** para guardar sem congelar, ou **Finalizar Versão** para congelar a versão — com a data e o retrato do ROPA daquele momento. Depois de finalizar, você pode **Imprimir / Exportar PDF** e consultar o **histórico de versões**.

   [![Editor do RIPD com o rascunho gerado](/assets/ripd-06-assistente-editor.png)](/assets/ripd-06-assistente-editor.png)
   *O rascunho abre no editor, pronto para refinar e finalizar a versão.*

> 💡 **Por que isso importa**
>
> O RIPD é a melhor evidência de que a OSC **pensou os riscos antes**. As versões congeladas servem de prova de diligência ao longo do tempo. Editar um RIPD finalizado cria um **novo rascunho**, preservando a versão anterior.

> ⚠️ **Quando já existe um RIPD para a atividade**
>
> Se você selecionar uma atividade que **já tem um RIPD**, o assistente **avisa**. Antes de criar um novo, verifique se não é o caso de **revisar o existente** — assim você mantém o histórico em vez de duplicar documentos para o mesmo tratamento.

> ✅ **Boas práticas**
>
> Trate o que o assistente entrega como **ponto de partida para a análise do Encarregado**, não como conclusão. Revise cada risco, ajuste a matriz à realidade da sua OSC e registre um parecer próprio antes de finalizar a versão.
