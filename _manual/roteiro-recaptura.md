# Roteiro de recaptura — manual V3RLGPD (#19)

Ambiente: dev-wp `http://localhost:3080/wp-admin/` · plugin ativo + semeado · viewport **desktop 1920×1080** (padrão atual; telas cheias = página inteira com 1920 de largura; recortes = elemento capturado do render 1920) salvo indicado. Nomes de arquivo = os atuais (não mudar). Captura via e2e-runner (login DEV autorizado).

## Lote 1 — Admin, capturável JÁ (com o admin atual + seed) — ~44 prints

### Painel / Primeiros Passos
- `v3rlgpd-01-dashboard` — Dashboard (menu V3RLGPD)
- `v3rlgpd-01b-dashboard-selo` — Dashboard, card de conformidade com o selo/medalha abaixo do anel
- `v3rlgpd-40-anpd-news` — Dashboard, bloco "Notícias da ANPD" (rolar até o fim)
- `v3rlgpd-40-onboarding-card` — Dashboard, card "Primeiros Passos"
- `v3rlgpd-41-onboarding-roteiro` — tela Onboarding (checklist)

### Auditoria de Conformidade
- `v3rlgpd-50-mapa-conformidade` — Mapa de Conformidade
- `v3rlgpd-90-detector` — aba Detector (relatório)
- `v3rlgpd-33-mapeamento-formularios` — Verificador de Formulários (lista)
- `v3rlgpd-34-verificador-relatorio` — Verificador, relatório de um form
- `v3rlgpd-38-ropa-rascunho-formulario` — form → ROPA rascunho
- `v3rlgpd-39-google-forms` — cadastro/leitura Google Forms

### Políticas
- `v3rlgpd-02-policies` — lista de políticas
- `v3rlgpd-03-policy-editor` — editor de política (abrir a de Privacidade)
- `v3rlgpd-03b-policy-externa` — política externa (source_type external)
- `v3rlgpd-09-wizard` — Assistente de Políticas
- `v3rlgpd-11-templates` — galeria de modelos

### Inventário (ROPA) + Assistente
- `v3rlgpd-06-ropa` — lista ROPA
- `v3rlgpd-34-assistente-intro` — Assistente de Inventário, intro
- `v3rlgpd-35-assistente-perguntas` — Assistente, questionário
- `v3rlgpd-37-assistente-conclusao` — Assistente, conclusão

### Atendimento ao Titular
- `v3rlgpd-04-dsar` — lista de atendimentos
- `v3rlgpd-04c-dsar-detalhe-auto` — detalhe DSAR com "Responder automaticamente"
- `v3rlgpd-04d-dsar-banner-revisar` — banner "revisar" no detalhe
- `v3rlgpd-05-incidents` — lista de incidentes

### Retenção
- `v3rlgpd-30-retencao-fila` — fila de retenção
- `v3rlgpd-31-retencao-config` — config de retenção
- `v3rlgpd-32-ropa-retencao` — retenção por atividade do ROPA

### Ações do Encarregado
- `v3rlgpd-dpo-01-lista` — lista
- `v3rlgpd-dpo-02-form` — formulário (modal)
- `v3rlgpd-dpo-03-relatorio` — relatório imprimível

### Relatórios
- `v3rlgpd-10-compliance-report` — Relatório de Conformidade

### ECA
- `v3rlgpd-54-eca-mapa-triagem` — Mapa, seção ECA (triagem)

### Configurações
- `v3rlgpd-08-settings-dpo`, `08b-settings-cookies`, `08c-settings-webhooks`, `08d-settings-paginas`, `08e-settings-saida`, `08f-settings-aparencia`, `08g-settings-aparencia-custom`, `08h-settings-desinstalacao`, `08i-settings-import`, `69-config-encarregado`, `70-encarregado-autofill`

### Equipe/Acessos (admin)
- `v3rlgpd-60-equipe-acessos`, `61-equipe-toast`, `68-admin-menu-completo`, `71-acessos-distincao`, `72-papeis-cargos`, `73-editor-matriz`, `74-excluir-migracao`

### Feedback
- `v3rlgpd-30-feedback` — modal de feedback (já rebrandizado #18)

## Lote 2 — Precisa de USUÁRIOS COM PAPÉIS (setup) — 6 prints
Exige criar 2 usuários WP com papéis V3RLGPD e logar como eles:
- Auditor: `v3rlgpd-62-auditor-menu`, `63-auditor-ropa`, `64-auditor-settings`
- Atendente: `v3rlgpd-65-atendente-menu`, `66-atendente-dsar`, `67-atendente-incidentes`

## Lote 3 — Páginas PÚBLICAS (setup) — 6 prints
Exige publicar as páginas públicas do plugin (Central de Privacidade com shortcodes) + habilitar o banner de cookies:
- `v3rlgpd-72-central-encarregado` — Central de Privacidade (pública)
- `v3rlgpd-22-dsar-form` — formulário de direitos (público)
- `v3rlgpd-21-cookie-banner` — banner de cookies (front público)
- `v3rlgpd-53-ropa-publico-grid` — ROPA público (grid)
- `v3rlgpd-55-formulario-menores` — formulário de menores (público)
- `v3rlgpd-04b-dsar-declaracao-escopo` — (admin config; pode ir no Lote 1)

## Estados especiais a garantir no seed antes de capturar
- Selo dourado/medalha visível (índice de conformidade > limiar) para `01b`.
- Pelo menos 1 DSAR aberto informativo p/ o botão "Responder automaticamente" (`04c`).
- 1 política publicada como página p/ Central (`72-central`).

## Lote de recaptura — mudanças v1.47.0 → v1.51.2 (2026-07-13)

> Só as telas que **de fato** mudaram. Mesmos nomes de arquivo (sobrescrever). Captura via e2e-runner (login DEV autorizado) — a skill não autentica.

**Prioridade (conteúdo desatualizado):**
- `v3rlgpd-69-config-encarregado` — **Configurações → Encarregado SEM o campo "Prefixo de Versionamento"** (removido no #34). Print atual mostra o campo que não existe mais.
- `v3rlgpd-03b-policy-externa` — editor de **política Externa** com o novo seletor **"Ou escolha uma página publicada do site"** abaixo do campo de URL (#27).

**Valor médio (feature nova visível):**
- `v3rlgpd-10-compliance-report` — Relatório de Conformidade com o botão **"Baixar PDF"** (#21/#29).
- `v3rlgpd-dpo-03-relatorio` — Relatório de Ações do Encarregado com **"Baixar PDF"**.
- (ROPA/RIPD) — telas de relatório do Inventário e do RIPD finalizado com **"Baixar PDF"** (nomes atuais dos prints de ROPA/RIPD).
- *(Opcional)* incluir um print de um **PDF gerado** (cabeçalho com logo) como ilustração — novo asset, nomear `v3rlgpd-XX-relatorio-pdf`.

**Baixo valor (polish; recapturar só se sobrar tempo):**
- `v3rlgpd-dpo-02-form` e demais **modais** — botão "X" de fechar maior (#28). Diferença sutil; só recapturar oportunisticamente.
