---
title: "Painel"
nav_order: 1
parent: "Módulos"
permalink: /modulos/painel/
role: encarregado
routes: ["#/", "#/wizard"]
screenshots: [v3rlgpd-01-dashboard, v3rlgpd-01b-dashboard-selo, v3rlgpd-50-mapa-conformidade, v3rlgpd-40-anpd-news]
last_verified: 2026-06-28
status: publicado
---

# Painel

O **Dashboard** é a primeira tela do V3RLGPD: o cockpit onde o Encarregado vê, de relance, como anda a conformidade da OSC e o que falta fazer.

[![Dashboard do V3RLGPD](/assets/screenshots/v3rlgpd-01-dashboard.png)](/assets/screenshots/v3rlgpd-01-dashboard.png)
*Visão geral com Índice de Conformidade, indicadores de atendimentos e visualizações das políticas.*

## Índice de Conformidade (MVP)

O card mostra, de um lado, a **lista do que é verificado pelo sistema** (Política de Privacidade ativa, Encarregado configurado, Consentimento/Cookies, Central de Privacidade, Inventário) — cada item com o **artigo da LGPD** correspondente; do outro, um **anel** com o **percentual verificado** e, separado e em roxo, o indicador **"Atestado: X de 4"** (a parte autodeclarada, que **não** infla o percentual).

O selo **"ⓘ Por que isto importa (LGPD)"** abre uma explicação curta com o artigo da Lei e links para o Manual, o texto oficial (Planalto) e a ANPD.

### O Selo de Conformidade no painel

[![Painel — Selo de Conformidade](/assets/screenshots/v3rlgpd-01b-dashboard-selo.png)](/assets/screenshots/v3rlgpd-01b-dashboard-selo.png)
*Abaixo do anel, o Selo de Conformidade (faixa bronze/prata/ouro) e o atalho para copiar o shortcode.*

Logo abaixo do anel aparece o **Selo de Conformidade** (o mesmo que você pode exibir publicamente no seu site), com a **faixa** correspondente ao seu nível (bronze, prata ou ouro). Ali também há a dica e o botão **Copiar** do shortcode `[v3rlgpd_selo]` — cole-o em qualquer página do site para mostrar o selo aos visitantes.

> O selo reflete o **mesmo índice** do anel e **não** é um certificado: comunica o seu compromisso, sem garantir validade jurídica.

> ℹ️ Os **atestados** (autodeclaração) e o detalhamento artigo a artigo ficam no **[Mapa de Conformidade](#mapa-de-conformidade)** — acesse pelo botão **"Ver mapa completo"** ou pelo menu.

> ℹ️ Se você **[inativar](/modulos/politicas/#inativar-e-reativar-uma-politica)** a Política de Privacidade, o item "Política de Privacidade Ativa" deixa de contar aqui — reative-a para o indicador voltar.

> ⚠️ **Atenção**
>
> O Índice é um **indicador de progresso interno**, não um certificado de conformidade. O próprio painel reforça: *"não constitui garantia jurídica de conformidade com a LGPD"*. Veja o [Aviso legal](/disclaimer/).

## Indicadores de atendimentos (DSAR)

Quatro números acompanham a saúde do atendimento aos titulares:

- **Pendentes (No Prazo)** e **Pendentes (Atrasadas)** — quantos pedidos aguardam e se estão dentro do SLA.
- **Concluídas** — pedidos já resolvidos.
- **Tempo Médio de Resposta** — quanto sua OSC costuma levar.

Há ainda o **Ranking de Solicitações** (quais tipos de pedido mais aparecem) e as **Visualizações das Políticas** (quantas vezes o público acessou suas políticas).

> 💡 **Por que isso importa**
>
> Esses números são ótimos para **prestar contas**: mostram a financiadores e ao conselho que a OSC atende titulares com agilidade e que suas políticas são efetivamente lidas. É accountability na prática — você demonstra cuidado com dados, não só afirma.

## Alertas e pendências

O painel sinaliza pontos de atenção — por exemplo, **nenhuma política de privacidade vigente** (com atalho para criar uma). São pistas do que organizar a seguir.

## Ações rápidas

No alto do painel:

- **Exportar Relatório** — abre o [Relatório de Conformidade](/modulos/relatorios/) em PDF.
- **Ver mapa completo** — abre o [Mapa de Conformidade](#mapa-de-conformidade) (detalhe artigo a artigo + autodeclaração).

## Mapa de Conformidade

Acessível pelo menu **"Mapa de Conformidade"** (ou pelo botão "Ver mapa completo"), é a tela-síntese que organiza a conformidade em **três camadas**, cada item ligado ao artigo da LGPD:

[![Mapa de Conformidade](/assets/screenshots/v3rlgpd-50-mapa-conformidade.png)](/assets/screenshots/v3rlgpd-50-mapa-conformidade.png)
*As três seções: o que o sistema verifica, o que você atesta e o que é responsabilidade sua fora da ferramenta.*

- ✅ **Verificado pelo sistema** — o que a ferramenta confere automaticamente, com status e atalho para resolver.
- 📝 **Você atesta** — as 4 autodeclarações sob responsabilidade da OSC (contrato com operadores, treinamento, dados sensíveis, transferência internacional). Marque **Sim / Não / Não se aplica**.
- ⚪ **Sob sua responsabilidade** — deveres que acontecem **fora** do plugin (comunicar incidente à ANPD, avaliar o RIPD, responder a fiscalizações).

## Notícias da ANPD

Na seção superior do Painel, na **3ª coluna** (à direita do anel de conformidade), há um bloco **"📰 Notícias da ANPD"** com as **últimas manchetes** da Autoridade Nacional de Proteção de Dados (regulação, orientações, prazos, consultas públicas).

[![Notícias da ANPD no Painel](/assets/screenshots/v3rlgpd-40-anpd-news.png)](/assets/screenshots/v3rlgpd-40-anpd-news.png)
*A seção superior do Painel em três colunas: Índice de Conformidade, o anel de % com o selo, e as Notícias da ANPD. Cada manchete tem data e abre a matéria no site da ANPD em nova aba.*

- Cada manchete mostra a **data** e abre a notícia no **site da ANPD** (gov.br) em **nova aba**.
- O bloco é só informativo, para você **se manter atualizado** sem sair do painel — não coleta nem envia nenhum dado da sua organização.
- Se as notícias não carregarem (a fonte da ANPD pode ficar instável), o painel **continua funcionando normalmente** e o bloco mostra um link para o site da ANPD.

## Veja também

- [O passo a passo da conformidade](/passo-a-passo-conformidade/)
- [Relatórios & Backup](/modulos/relatorios/)
