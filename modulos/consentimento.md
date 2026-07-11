---
title: "Consentimento & Cookies"
nav_order: 5
parent: "Módulos"
permalink: /modulos/consentimento/
role: encarregado
routes: ["/central-de-privacidade/", "#/settings"]
screenshots: [v3rlgpd-21-cookie-banner, v3rlgpd-08b-settings-cookies]
last_verified: 2026-06-23
status: publicado
---

# Consentimento & Cookies

A LGPD trata o **consentimento** como algo que precisa ser **livre, informado e demonstrável**. Este módulo cuida de duas frentes: o **banner de cookies** e o **registro de consentimento em formulários**.

## Banner de cookies

[![Banner de cookies](/assets/screenshots/v3rlgpd-21-cookie-banner.png)](/assets/screenshots/v3rlgpd-21-cookie-banner.png)
*Na primeira visita, o titular escolhe aceitar, recusar não-essenciais ou personalizar.*

O banner aparece na primeira visita ao site. O ponto central:

> 💡 **Por que isso importa**
>
> Cookies de **análise e marketing** (Google Analytics, pixels de redes sociais) só podem ser carregados **depois** que o visitante consente. O V3RLGPD segura esses scripts até haver consentimento — ou seja, recusar significa **não carregar**, não apenas "fingir que não carregou". Isso é o que diferencia um banner de verdade de um aviso decorativo.

O visitante pode:

- **Aceitar Todos** — libera os cookies não-essenciais.
- **Recusar Não-Essenciais** — mantém só o necessário ao funcionamento.
- **Personalizar** — escolhe por categoria.

Ative e ajuste o banner em **Configurações → Banner de Cookies**.

[![Configurações do banner de cookies](/assets/screenshots/v3rlgpd-08b-settings-cookies.png)](/assets/screenshots/v3rlgpd-08b-settings-cookies.png)
*Configuração do banner de cookies no painel.*

### Exibir ou não o banner

A partir da versão 1.2, há uma opção **"Exibir o banner de cookies no site"**. Ela existe porque há discussão na ANPD sobre a real eficácia dos banners — e algumas OSCs podem preferir não usá-lo (por exemplo, quando não carregam scripts de análise/marketing).

> ⚠️ **Desligar o banner desliga os scripts não-essenciais**
>
> Se você **desativar** a exibição do banner, o V3RLGPD **deixa de carregar** os scripts de Analytics e Marketing — porque, sem o banner, não há como coletar o consentimento do visitante. Carregar esses scripts sem consentimento seria justamente o que a LGPD não permite. O painel avisa isso na hora em que você desliga a opção.

> 💡 **Reflexo no Índice de Conformidade**
>
> O item "Consentimento / Cookies" do Dashboard acompanha esse interruptor: banner **ligado** = ✅; **desligado** = pendente. É a sua intenção de uso refletida diretamente no painel.

## Consentimento em formulários

Quando um visitante preenche um formulário do seu site (newsletter, inscrição, contato), o plugin registra o **consentimento**: o quê, quando e com qual finalidade a pessoa concordou — gerando uma **prova consultável**.

O V3RLGPD se integra a plugins de formulário populares por meio de **conectores**, seguindo um padrão único de registro de consentimento.

> ✅ **Boas práticas**
>
> Peça consentimento **específico** ("aceito receber a newsletter"), não genérico ("aceito tudo"). Consentimento amplo demais é frágil: se questionado, é difícil provar que a pessoa entendeu ao que estava concordando.

> ⚠️ **Atenção — consentimentos órfãos**
>
> O [Painel](/modulos/painel/) sinaliza "consentimentos órfãos" — registros que não estão ligados a uma versão de política. Eles indicam que algo foi coletado sem o vínculo correto. Vale revisar quando aparecerem.
