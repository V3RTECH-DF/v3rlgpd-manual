---
title: "Configurar a proteção de crianças e adolescentes (ECA Digital)"
nav_order: 10
parent: "Guias por tarefa"
permalink: /guias/proteger-menores-eca/
role: encarregado
routes: ["#/settings", "#/ripd"]
screenshots: [v3rlgpd-54-eca-mapa-triagem, v3rlgpd-55-formulario-menores]
last_verified: 2026-06-27
status: publicado
---

# Configurar a proteção de crianças e adolescentes (ECA Digital)

Se a sua OSC trabalha com **crianças e adolescentes** — projetos sociais, esporte de base, oficinas, programas de juventude — ou se o seu site tem **probabilidade real** de ser acessado por menores de 18 anos, o **ECA Digital** (Lei nº 15.211/2025) cria deveres extras de proteção. Este guia mostra, na ordem, o que fazer no V3RLGPD para dar conta deles, em linguagem simples.

> ⚠️ **Atenção**
>
> O ECA Digital é uma **lei distinta** da LGPD. O V3RLGPD **ajuda** a sua OSC a se organizar diante dela, mas **não é parecer jurídico** e **não garante conformidade** — a responsabilidade é da organização. A lei é recente e parte da regulamentação ainda é preliminar na ANPD.

> 💡 **Por que isso importa**
>
> O terceiro setor é um dos públicos **mais alcançados** por essa lei, porque muitas OSCs lidam diretamente com menores. A boa notícia: na maioria dos casos o que pega **não** é "verificar a idade de quem entra no site", e sim alguns **cuidados com os dados das crianças**. Este guia te leva por eles.

## Antes de começar

Tenha o **Encarregado** já cadastrado — vários dos passos abaixo usam esse contato. Se ainda não fez, comece por [Configurar o Encarregado](/guias/configurar-dpo/).

## Passo 1 — Descobrir o que se aplica a você (enquadramento)

Não saia ativando tudo. Primeiro responda ao **classificador de enquadramento**: ele mostra **apenas os deveres do seu caso**.

1. No menu, abra **Auditoria de Conformidade** (aba **Mapa de Conformidade**) e role até a seção **ECA Digital**.
2. Clique em **Iniciar Triagem** e responda às poucas perguntas (se o site é direcionado a / de acesso provável por menores, se tem **controle editorial**, se coleta dados de menores, se tem conteúdo gerado por usuário).
3. Clique em **Salvar Enquadramento**.

[![Seção ECA Digital no Mapa de Conformidade](/assets/screenshots/v3rlgpd-54-eca-mapa-triagem.png)](/assets/screenshots/v3rlgpd-54-eca-mapa-triagem.png)
*A seção ECA Digital no Mapa, com a triagem de enquadramento e os deveres aplicáveis.*

O Mapa passa a listar **só os deveres aplicáveis**, cada um ligado ao artigo da lei.

> 💡 **A maioria dos sites de OSC tem uma "folga".** Se o conteúdo do seu site é **escolhido pela própria OSC, sem automação** (um site institucional comum), ele costuma ter **controle editorial** — e a **aferição de idade fica dispensada**. Nesse caso, o que importa são os deveres de **proteção de dados de menores** dos próximos passos. Detalhes em [Enquadramento](/eca-digital/enquadramento/).

> ⚠️ O enquadramento é **autodeclarado** pela sua OSC e serve de orientação. A autoridade competente pode reenquadrar o serviço.

## Passo 2 — Pedir o consentimento dos pais nos formulários

Quando a sua OSC coleta **dados de crianças**, a LGPD (art. 14) exige, em regra, o **consentimento de um dos pais ou responsável**. O V3RLGPD registra esse consentimento como **parental**, com a identificação do responsável como prova.

1. Em **Formulários**, marque o formulário que **coleta dados de menores**.
2. Informe **qual campo** do formulário recebe o **nome/e-mail do responsável** — o V3RLGPD lê esse campo no envio.
3. A partir daí, cada envio gera um consentimento com **selo parental** na tela de **Consentimentos**.

[![Marcação de dados de menores no mapeamento de formulários](/assets/screenshots/v3rlgpd-55-formulario-menores.png)](/assets/screenshots/v3rlgpd-55-formulario-menores.png)
*No Mapeamento de Formulários, marque o formulário que coleta dados de menores e indique o campo do responsável.*

> ✅ **Boas práticas**
>
> Inclua no formulário um campo claro para o **responsável** (nome e e-mail) e explique ali mesmo por que ele é necessário. Sem essa identificação, o consentimento do menor fica incompleto.

Passo a passo completo em [Consentimento dos pais](/eca-digital/consentimento-parental/).

## Passo 3 — Tratar os dados no nível mais protetivo (privacidade por padrão)

O ECA Digital (art. 7º) pede que, com dados de menores, a configuração padrão seja a **mais protetiva possível**: coletar só o necessário, não expor publicamente sem razão e não reaproveitar os dados para outras finalidades.

Quando o enquadramento indica que você coleta dados de menores, o **checklist do editor de Política de Privacidade** ganha um item dedicado — **"Privacidade por padrão p/ menores (ECA Digital)"**. Use-o como lembrete para a política deixar claro **o que** você coleta de menores e **por quê**, que **não há exposição pública desnecessária** e que os dados **não são usados para outro fim**.

> ⚠️ **Atenção**
>
> Imagem de criança é, na prática, dado delicado: só publique fotos de menores com **base e autorização adequadas** dos responsáveis. Na dúvida, não publique.

Mais em [Privacidade por padrão](/eca-digital/privacidade-por-padrao/).

## Passo 4 — Não fazer publicidade dirigida a menores

O ECA Digital (arts. 22 e 26) **proíbe** usar perfilamento para direcionar **publicidade** a crianças e adolescentes. Quando o enquadramento indica público menor, a aba **Banner de Cookies** (em **Configurações**) exibe um aviso recomendando **não** usar scripts de **Analytics** e **Marketing** nesse cenário.

> ✅ **Boas práticas**
>
> Em site de acesso provável por menores, mantenha apenas cookies **essenciais**. Evite tags de redes sociais, remarketing e analytics comportamental. O V3RLGPD **avisa e recomenda**, mas não bloqueia automaticamente — a decisão é da OSC.

Mais em [Perfilamento e publicidade](/eca-digital/perfilamento-publicidade/).

## Passo 5 — Informar os pais na página pública (transparência)

O ECA Digital (art. 16) pede que pais, responsáveis e os próprios menores acessem, de forma independente, informações sobre os dados de crianças e as medidas de segurança adotadas.

Coloque o shortcode `[v3rlgpd_transparencia_menores]` na sua **Central de Privacidade** (ou em outra página pública). Quando o enquadramento indica dados de menores, ele exibe um card com uma explicação acessível, o **contato do Encarregado** e links para a Política de Privacidade e para abrir uma solicitação de direitos. Você pode complementar com um texto próprio em **Configurações → Páginas & Integração**.

> ✅ **Boas práticas**
>
> Escreva pensando que **um adolescente** pode ler: diga o que você coleta, por quê, e como falar com o encarregado.

Mais em [Transparência aos pais](/eca-digital/transparencia-aos-pais/).

## Passo 6 — Avaliar os riscos com um RIPD

Tratar dados de **crianças e adolescentes** é um caso clássico em que vale fazer um **Relatório de Impacto (RIPD)** — recurso da LGPD (art. 38) que o ECA Digital (art. 16) reforça. Ele documenta o que você coleta de menores, por quê, os riscos e as medidas para reduzi-los.

1. No menu, abra **Relatório de Impacto (RIPD)** e clique em **+ Novo RIPD**.
2. Selecione, no **escopo**, as atividades do seu Inventário (ROPA) que envolvem menores.
3. Preencha necessidade e proporcionalidade, a **matriz de risco** e o parecer.
4. **Finalize a versão** para congelar uma prova de diligência (com data).

> 💡 **Comece simples.** Um RIPD de uma ou duas páginas para o tratamento mais sensível já é um grande avanço. Veja [quando fazer um RIPD](/modelos/ripd/) e o passo a passo em [Módulo RIPD](/modulos/ripd/).

## Passo 7 — Canal de denúncia (só se houver conteúdo de usuário)

Este passo **só se aplica** se o seu site tem **conteúdo gerado por usuário** (comentários, fórum, mural, depoimentos abertos). Aí o ECA Digital (arts. 28–30) pede um **canal de denúncia** acessível.

Coloque o shortcode `[v3rlgpd_denuncia]` numa página pública. Em **Denúncias**, o encarregado vê o que chegou, muda o status (Recebida → Em análise → Conteúdo removido / Improcedente) e registra a justificativa. Ao marcar **Conteúdo removido**, o sistema lembra o art. 30 (notificar o autor e abrir prazo de recurso).

> ⚠️ **Atenção**
>
> A **retirada** do conteúdo acontece no seu site/CMS — o V3RLGPD **registra e orienta** a denúncia, não remove o conteúdo automaticamente. Sites institucionais com controle editorial (sem conteúdo de usuário) tendem a ser dispensados desse dever.

Mais em [Canal de denúncia](/eca-digital/canal-de-denuncia/).

## E a verificação de idade?

Para a OSC típica, **não** é necessária. Se o seu site tem controle editorial, a aferição de idade é **dispensada**. Só no caso incomum de a sua OSC realmente precisar verificar a idade de quem acessa (ex.: oferta de conteúdo impróprio para menores) é que vale escolher um método com cuidado — veja [Aferição de idade](/eca-digital/afericao-de-idade/).

## Resumo do caminho

1. **Enquadramento** no Mapa — descobre o que se aplica.
2. **Consentimento parental** nos formulários que coletam dados de menores.
3. **Privacidade por padrão** — item no checklist da Política de Privacidade.
4. **Sem publicidade dirigida** — só cookies essenciais.
5. **Transparência aos pais** — shortcode na Central.
6. **RIPD** para os tratamentos de menores.
7. **Canal de denúncia** — apenas se houver conteúdo de usuário.

Visão geral de tudo isso em [ECA Digital](/eca-digital/).
