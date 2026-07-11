---
title: "Detector de Conformidade"
parent: "Módulos"
nav_order: 1
permalink: /modulos/detector/
---

# Detector de Conformidade

O **Detector de Conformidade** varre o seu site publicado e gera um **relatório em linguagem clara** apontando o que precisa de atenção na conformidade com a LGPD. A diferença para o resto do painel: ele confronta o que você **configurou** no V3RLGPD com o que está **de fato no ar** no seu site — o "espelho externo".

Fica na aba **Detector**, dentro de **Auditoria de Conformidade** (primeira aba).

[![Tela do Detector de Conformidade](/assets/screenshots/v3rlgpd-90-detector.png)](/assets/screenshots/v3rlgpd-90-detector.png)
*O Detector: escolha o modo, inicie a análise e leia o relatório por gravidade.*

> 💡 **Por que isso importa**
>
> Você pode ter configurado tudo certo no plugin, mas um detalhe no ar passar despercebido: uma tag de rastreamento que o tema instalou, a política que não está linkada no rodapé, a página do titular fora do ar. O Detector encontra essas lacunas do jeito que um auditor externo (ou a ANPD) veria.

## Como rodar uma análise

1. Abra **Auditoria de Conformidade → Detector**.
2. Escolha o **modo**:
   - **Rápido** — checa o essencial (página inicial + Central de Privacidade). Resultado na hora.
   - **Padrão** — início, Central e páginas institucionais.
   - **Completo (análise profunda)** — varre **todo o site**. Roda em segundo plano: você pode **sair da página e voltar mais tarde**, e recebe um **e-mail** quando terminar.
3. Clique em **Iniciar análise**.

> No modo Completo, enquanto a análise roda, a tela mostra o progresso ("X de Y páginas"). O e-mail de conclusão vai para quem iniciou a análise **e** para o Encarregado.

## Como ler o relatório

No topo, você vê a **situação geral** ("Atenção necessária", "Bom" ou "Excelente") e a contagem por gravidade:

- 🔴 **Crítico** — lacuna objetiva que um auditor apontaria (ex.: política inexistente, rastreador sem consentimento).
- 🟡 **Atenção** — algo a melhorar ou confirmar.
- 🟢 **Conforme** — item verificado que está em ordem.

Cada achado explica **o que encontramos**, **por que importa** (com o artigo da lei) e traz um botão **Resolver** que leva direto ao lugar certo do painel — **quando possível, já preenchido**. Você pode **ordenar** por gravidade, tema ou ordem alfabética, e **Exportar / Imprimir** o relatório (útil para levar ao conselho, a um financiador ou a um auditor).

## O caso dos rastreadores (cookies sem consentimento)

Um dos achados mais úteis: o Detector encontra **scripts de rastreamento** (Google Analytics, Google Tag Manager, Pixel do Facebook, Google Ads, LinkedIn, TikTok, Hotjar, Clarity) que estão disparando no seu site **antes** do visitante consentir — geralmente porque foram colados direto no tema ou por outro plugin.

Ao clicar em **Resolver** nesse achado, o V3RLGPD **leva o código do script já preenchido** para a aba [Cookies & Analytics](/modulos/configuracoes/) das Configurações, onde ele passa a carregar **só após o consentimento**. Basta você **revisar e salvar** — e depois **remover a tag original** de onde ela estava (tema ou outro plugin), senão ela dispara duas vezes.

> ⚠️ **O Detector ajuda, não garante**
>
> O relatório aponta pontos de melhoria e ajuda a organizar a conformidade, mas **não garante validade jurídica** nem **substitui a análise por um profissional**. Uma análise mais aprofundada da política (com apoio de inteligência artificial) está prevista para uma próxima versão.
