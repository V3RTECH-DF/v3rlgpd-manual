---
title: "O passo a passo da conformidade"
nav_order: 5
permalink: /passo-a-passo-conformidade/
---

# O passo a passo da conformidade com a LGPD

Esta é a página mais importante do guia. Ela descreve, em profundidade, o caminho que uma OSC pode percorrer para chegar **o mais perto possível** da conformidade com a LGPD — e mostra onde o V3RLGPD entra em cada etapa.

> ⚠️ **Atenção — conformidade é um processo, não um botão**
>
> Não existe "ficar 100% conforme" de uma vez e nunca mais pensar nisso. Conformidade é uma rotina: você organiza, mantém atualizado e revisita quando algo muda (uma atividade nova, um sistema novo, um incidente). Este roteiro te coloca no caminho; mantê-lo vivo é o trabalho contínuo do Encarregado.

## Etapa 0 — Patrocínio da liderança

Antes de qualquer planilha, a diretoria precisa comprar a ideia. Adequação à LGPD envolve tempo de pessoas e, às vezes, mudar processos. Sem apoio da liderança, vira tarefa órfã que ninguém prioriza.

> ✅ **Boas práticas**
>
> Apresente a LGPD ao conselho não como "risco de multa", mas como **confiança e profissionalismo**. Financiadores cada vez mais perguntam sobre proteção de dados. Estar organizado é diferencial de captação.

## Etapa 1 — Nomeie o Encarregado

Escolha quem vai responder pelos dados na sua OSC. Pode ser um voluntário, um funcionário ou um setor. O importante é que a pessoa esteja **acessível** e tenha **respaldo** para cobrar as áreas.

**No plugin:** cadastre o Encarregado em **Configurações → Identidade**. Esses dados ficarão visíveis na Central de Privacidade. → [Guia](/guias/configurar-dpo/)

## Etapa 2 — Mapeie os dados (Inventário / ROPA)

Este é o coração da adequação. Liste **todas as atividades** em que sua OSC trata dados pessoais e, para cada uma, responda:

1. **Qual a atividade?** (ex.: cadastro de voluntários, newsletter, inscrição em evento, controle de doações)
2. **Quais dados são coletados?** (nome, CPF, e-mail, telefone, dados sensíveis?)
3. **Para qual finalidade?** (por que você precisa desse dado?)
4. **Qual a base legal?** (consentimento, execução de contrato, obrigação legal…)
5. **Por quanto tempo guarda?** (retenção)
6. **Com quem compartilha?** (operadores, parceiros, transferência internacional?)

> 💡 **Por que isso importa**
>
> Você não consegue proteger o que não sabe que tem. O inventário é o que permite responder a um pedido de titular ("quais dados você tem sobre mim?"), justificar um tratamento à ANPD e descobrir coletas desnecessárias que só aumentam seu risco. **Se você fizer só uma coisa da LGPD, faça o inventário.**

**No plugin:** registre cada atividade no módulo **[Inventário (ROPA)](/modulos/inventario-ropa/)**. Ele alimenta automaticamente o gerador de Política de Privacidade.

## Etapa 3 — Defina as bases legais

Para cada atividade do inventário, escolha a base legal mais adequada (veja [Conceitos](/conceitos-lgpd/#as-bases-legais-art-7º-e-11)). Esse é um exercício de reflexão, não de preenchimento mecânico: pergunte "por que eu posso, legalmente, tratar este dado?".

> ⚠️ **Atenção**
>
> Atividades com **dados sensíveis** (saúde, religião, etnia, opinião política) têm bases legais próprias e mais restritas. Se sua OSC trabalha com grupos vulneráveis, trate esse ponto com cuidado redobrado — é onde o risco é maior.

## Etapa 4 — Escreva e publique as políticas

Com o inventário e as bases definidas, escreva sua **Política de Privacidade** — o documento que explica ao público, em linguagem clara, o que você faz com os dados dele. A LGPD valoriza **transparência**: a pessoa tem direito de saber.

**No plugin:** o módulo **[Políticas](/modulos/politicas/)** tem um **Assistente** que monta um rascunho a partir do Encarregado e do inventário, um **editor** com checklist dos itens obrigatórios e **versionamento** (toda mudança gera uma nova versão, com histórico). → [Guia](/guias/publicar-politica/)

> ✅ **Boas práticas**
>
> Publique também, quando fizer sentido, **Termos de Uso** e uma **Política de Cookies**. O V3RLGPD trata políticas de forma genérica — você cria quantas precisar.

## Etapa 5 — Publique a Central de Privacidade

Dê ao público um lugar único para ler suas políticas, ajustar cookies e exercer direitos.

**No plugin:** **Configurações → Páginas & Integração → Gerar Página Automaticamente**. → [Guia](/guias/publicar-central-privacidade/)

## Etapa 6 — Trate o consentimento de cookies e formulários

Se seu site usa cookies de análise ou marketing, eles só podem ser carregados **após o consentimento** do visitante. E todo formulário que coleta dados deve registrar **o quê, quando e com qual finalidade** a pessoa consentiu.

**No plugin:** ative o **banner de cookies** e use os **conectores de formulário** descritos em **[Consentimento & Cookies](/modulos/consentimento/)**.

## Etapa 7 — Prepare-se para atender titulares

Garanta que sua OSC consegue **receber e responder** pedidos de titulares dentro do prazo. Defina quem trata, como confirma a identidade da pessoa e como executa (localizar, exportar, excluir).

**No plugin:** os pedidos chegam em **[Atendimentos (DSAR)](/modulos/atendimentos/)**, com controle de prazo (SLA), **execução assistida** (o plugin localiza/exporta/elimina sob comando do Encarregado) e **auto-atendimento** para pedidos simples. → [Guia](/guias/atender-solicitacao/)

## Etapa 8 — Tenha um plano de incidentes

Decida, **antes** de acontecer, o que fazer se houver um vazamento: quem avisa, quem decide, em quanto tempo, como comunica os afetados e a ANPD.

**No plugin:** registre e comunique pelo módulo de **[Incidentes](/modulos/incidentes/)**. A notificação oficial à ANPD é feita por você, pelos canais do governo.

> 💡 **Por que isso importa**
>
> Incidente sempre parece distante — até acontecer. OSC que já tem um plano simples ("quem ligo? o que comunico?") reage em horas; quem não tem perde dias decidindo, e o tempo conta contra você (e contra os titulares afetados).

## Etapa 9 — Treine as pessoas

A maioria dos incidentes começa em erro humano: senha fraca, planilha compartilhada sem querer, e-mail no destinatário errado. Treinar a equipe é a medida de segurança de melhor custo-benefício.

> 📚 **Aprofunde com a RIT**
>
> A [formação em LGPD da RIT](https://cursos.rit.org.br/){:target="_blank" rel="noopener"} é desenhada para a realidade de OSCs e ajuda exatamente nessa etapa — e é **gratuita para as organizações integradas à RIT**.

## Etapa 10 — Monitore e revise

Acompanhe o **Índice de Conformidade** no [Painel](/modulos/painel/), gere o **[Relatório de Conformidade](/modulos/relatorios/)** para prestar contas a financiadores e conselho, e **revise o inventário** sempre que sua OSC criar uma atividade nova, adotar um sistema novo ou passar por um incidente.

## A ideia de risco na LGPD

Conformidade não é "fazer tudo perfeito" — é **gerir risco de forma proporcional**. Uma OSC pequena que coleta só nome e e-mail para uma newsletter tem risco baixo; uma que mantém prontuários de saúde de beneficiários tem risco alto e precisa de controles mais fortes. Priorize onde o risco aos titulares é maior: dados sensíveis, grandes volumes, compartilhamento com terceiros, transferência internacional.

> ⚠️ **Atenção — o que esta ferramenta NÃO faz**
>
> O V3RLGPD organiza, registra e dá rastreabilidade. Ele **não** decide por você qual base legal usar, **não** escreve a política "juridicamente perfeita" e **não** garante que sua OSC está conforme. Essas decisões são da sua OSC, idealmente com apoio jurídico. Leia o [Aviso legal](/disclaimer/).
