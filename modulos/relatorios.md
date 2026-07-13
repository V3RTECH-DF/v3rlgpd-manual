---
title: "Relatórios & Backup"
nav_order: 10
parent: "Módulos"
permalink: /modulos/relatorios/
role: encarregado
routes: ["#/compliance-report", "#/settings"]
screenshots: [v3rlgpd-10-compliance-report, v3rlgpd-08e-settings-saida, v3rlgpd-08c-settings-webhooks]
last_verified: 2026-06-23
status: publicado
---

# Relatórios & Backup

Dado registrado só vale se vira **informação para prestar contas**. Este módulo reúne o **Relatório de Conformidade** e o **backup/exportação total** dos dados.

## Relatório de Conformidade

[![Relatório de Conformidade](/assets/screenshots/v3rlgpd-10-compliance-report.png)](/assets/screenshots/v3rlgpd-10-compliance-report.png)
*Panorama em PDF: status de conformidade, gestão de direitos (DSAR) e transparência.*

Acessível pelo botão **Exportar Relatório** no [Painel](/modulos/painel/), o relatório consolida num documento que você **baixa em PDF** com um clique (botão **Baixar PDF**, com logo e cabeçalho da organização) ou envia para a impressão do navegador:

- **Status de Conformidade** — política publicada, Encarregado nomeado, inventário mapeado, banner de cookies.
- **Gestão de Direitos (DSAR)** — total de pedidos, concluídos, pendentes (no prazo e atrasados) e tempo médio de resposta.
- **Transparência** — visualizações da Central de Privacidade.

> 💡 **Por que isso importa**
>
> Financiadores e conselhos pedem cada vez mais evidência de cuidado com dados. Um relatório de uma página, com o cabeçalho da sua organização, transforma trabalho invisível em **prova concreta** de governança — ótimo para captação e para a assembleia.

> ⚠️ **Atenção**
>
> O relatório reflete o que está registrado no plugin e serve a **controle interno e prestação de contas**. Ele **não** é um certificado de conformidade. Veja o [Aviso legal](/disclaimer/).

## Backup / Exportação total

[![Saída de Dados](/assets/screenshots/v3rlgpd-08e-settings-saida.png)](/assets/screenshots/v3rlgpd-08e-settings-saida.png)
*Em Configurações → Saída de Dados, gere um arquivo de backup completo (ZIP).*

Em **Configurações → Saída de Dados**, o botão **Gerar Arquivo de Backup (ZIP)** exporta **todos os dados** geridos pelo plugin (políticas, versões, inventário, consentimentos, pedidos, incidentes e auditoria) num pacote ZIP com:

- arquivos **CSV** e **JSON** de cada tabela;
- um **manifesto** com a versão e a data;
- **checksums (SHA-256)** para verificar a integridade do pacote.

> ✅ **Boas práticas**
>
> Guarde um backup periódico em local seguro. Além de proteção contra perdas, ele dá **portabilidade**: se um dia sua organização mudar de sistema, leva os dados consigo, num formato aberto.

> 💡 O backup abre em nova aba e baixa o ZIP — você não perde a tela em que estava.

## Integração via Webhooks

Em **Configurações → Webhooks**, sua organização pode conectar o V3RLGPD a ferramentas de automação (como **n8n** e **Zapier**). Eventos essenciais — nova solicitação de titular, alteração/aceite de política, incidente, consentimento — disparam um webhook para o endereço que você configurar.

[![Configuração de Webhooks](/assets/screenshots/v3rlgpd-08c-settings-webhooks.png)](/assets/screenshots/v3rlgpd-08c-settings-webhooks.png)
*Configurações → Webhooks.*

> ✅ **Boas práticas**
>
> Webhooks são úteis para avisar a equipe (ex.: mensagem no chat quando chega um pedido de titular) sem ninguém precisar ficar olhando o painel. Comece simples: um aviso de "novo atendimento" já ajuda a não perder prazo.
