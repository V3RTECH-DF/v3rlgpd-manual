---
title: "Conceitos da LGPD"
nav_order: 3
permalink: /conceitos-lgpd/
---

# Conceitos da LGPD para OSCs

Antes de mexer na ferramenta, vale entender a lei em linguagem de gente. Esta página é um mini-curso: os conceitos que você precisa para usar o V3RLGPD com segurança e para conversar com financiadores, conselho e titulares sem se perder no juridiquês.

> 💡 **Por que isso importa**
>
> OSC trabalha o tempo todo com dados de pessoas: voluntários, doadores, beneficiários, inscritos em eventos, newsletter. A LGPD não existe para atrapalhar esse trabalho — ela existe para que essas pessoas confiem na sua organização. Entender os conceitos é o que separa "cumprir por medo de multa" de "usar dados com responsabilidade", que é o que sustenta a relação de confiança que toda OSC depende.

## O que é a LGPD

A **Lei Geral de Proteção de Dados (Lei nº 13.709/2018)** regula como qualquer organização — empresa, governo ou OSC — pode **coletar, usar, compartilhar e guardar dados pessoais**. Ela vale para a sua OSC independentemente do tamanho: não há isenção para entidade pequena ou sem fins lucrativos.

A lei é fiscalizada pela **ANPD — Autoridade Nacional de Proteção de Dados**, o órgão federal que edita regras, orienta e pode aplicar sanções.

## Quem é quem

> 📖 **Dado pessoal**
>
> É qualquer informação que **identifique ou possa identificar** uma pessoa: nome, e-mail, CPF, telefone, foto, endereço IP, dados de localização. Se dá para chegar a uma pessoa específica, é dado pessoal.

> 📖 **Dado pessoal sensível**
>
> Subconjunto que merece proteção redobrada: origem racial ou étnica, convicção religiosa, opinião política, filiação a sindicato, dados de saúde, vida sexual, dados genéticos ou biométricos. **Muitas OSCs tratam dados sensíveis sem perceber** — um projeto de saúde, de assistência a um grupo religioso ou a uma minoria, por exemplo. Esses dados exigem cuidado e base legal específica.

> 📖 **Tratamento de dados pessoais**
>
> Esse é o termo que aparece em todo lugar e quase ninguém explica. **Tratamento é qualquer coisa que sua OSC faça com um dado pessoal** — do momento em que ele entra até o momento em que some. A lei lista (Art. 5º, X): coletar, receber, registrar, organizar, usar, acessar, consultar, compartilhar, transmitir, armazenar, arquivar, atualizar, copiar e **eliminar**. Ou seja: digitar o nome de um voluntário numa planilha é tratamento; mandar a newsletter é tratamento; guardar a ficha no armário é tratamento; apagar o cadastro também é tratamento.
>
> A consequência prática é grande: **se é tratamento, precisa de uma [base legal](#as-bases-legais-art-7º-e-11) e de finalidade clara.** Não existe "só estou guardando, não estou usando" — guardar já é tratar. É por isso que o [Inventário (ROPA)](/modulos/inventario-ropa/) mapeia cada operação: cada forma de tratar um dado é uma linha a justificar.

> 📖 **Titular**
>
> É a **pessoa a quem os dados se referem** — o voluntário, o doador, o beneficiário. É ela que tem direitos (acessar, corrigir, excluir) e em nome de quem a lei foi escrita.

> 📖 **Controlador**
>
> É **quem decide** como e por que os dados são tratados. Na prática, é a sua OSC. O controlador é o principal responsável perante a lei.

> 📖 **Operador**
>
> É **quem trata dados em nome do controlador**, seguindo suas instruções — por exemplo, a plataforma de e-mail marketing, o sistema de gestão, o serviço de nuvem. Sua OSC continua responsável por escolher operadores confiáveis.

> 📖 **Encarregado**
>
> É a pessoa (ou setor) que faz a **ponte entre a OSC, os titulares e a ANPD**. Recebe reclamações, presta esclarecimentos e orienta a equipe. Não precisa ser advogado nem ter dedicação exclusiva — mas precisa existir e estar acessível. No V3RLGPD, é o "Encarregado" que você cadastra em Configurações.

## As bases legais (Art. 7º e 11)

Aqui está o conceito que mais confunde — e o mais importante. **Toda vez que sua OSC trata um dado pessoal, precisa de um motivo previsto na lei.** Esse motivo é a *base legal*. Sem base legal, o tratamento é irregular, mesmo que bem-intencionado.

> 📖 **Página dedicada, com exemplos:** veja **[Bases legais (com exemplos)](/bases-legais/)** para cada base explicada com casos reais de OSC e um roteiro de "como escolher".

As bases mais usadas por OSCs:

- **Consentimento** — a pessoa autorizou, de forma livre e informada, aquele uso específico (ex.: aceitar receber a newsletter). Pode ser revogado a qualquer momento.
- **Execução de contrato** — necessário para cumprir um acordo com a pessoa (ex.: dados do voluntário para gerir a escala em que ele se inscreveu).
- **Obrigação legal** — a lei obriga a guardar o dado (ex.: documentos exigidos para prestação de contas).
- **Legítimo interesse** — uso razoável e esperado, que não fere os direitos da pessoa (exige avaliação cuidadosa e documentada).
- **Tutela da saúde, políticas públicas, proteção à vida** — bases específicas para certos contextos.

> ⚠️ **Atenção — consentimento não é a resposta para tudo**
>
> Existe a tentação de "pedir consentimento para tudo". Isso costuma ser um erro: consentimento pode ser revogado, e se você apaga o dado na revogação mas precisava dele para uma obrigação legal, criou um problema. Para cada atividade, escolha a base **mais adequada**, não a mais fácil. É exatamente isso que o [Inventário (ROPA)](/modulos/inventario-ropa/) ajuda a organizar.

## Os direitos do titular (Art. 18)

A pessoa pode, a qualquer momento, pedir à sua OSC:

- **Confirmação** de que há tratamento dos seus dados;
- **Acesso** aos dados que você tem sobre ela;
- **Correção** de dados incompletos, inexatos ou desatualizados;
- **Anonimização, bloqueio ou eliminação** de dados desnecessários ou tratados em desconformidade;
- **Portabilidade** dos dados para outro fornecedor;
- **Eliminação** dos dados tratados com base no consentimento;
- **Informação** sobre com quem os dados foram compartilhados;
- **Revogação do consentimento**.

No V3RLGPD, esses pedidos chegam pelo módulo de **[Atendimentos (DSAR)](/modulos/atendimentos/)**. "DSAR" é a sigla em inglês para *Data Subject Access Request* — pedido de titular.

> 💡 **Por que isso importa**
>
> Responder bem a um pedido de titular é a hora da verdade da LGPD. É barato em esforço e enorme em confiança: a pessoa percebe que sua OSC leva a sério os dados dela. O prazo legal de referência é de **15 dias**; o plugin acompanha esse prazo para você não perder.

## Decisão automatizada e perfilamento (Art. 20)

**Decisão automatizada** é quando um **sistema decide algo sobre uma pessoa sem intervenção humana** — por exemplo, um algoritmo que aprova ou recusa, classifica ou pontua. **Perfilamento** (ou *profiling*) é traçar um **perfil** da pessoa (interesses, comportamento, "tipo") a partir dos dados dela, normalmente para prever ou direcionar algo.

A LGPD (**art. 20**) garante ao titular o **direito de pedir revisão** de decisões tomadas apenas de forma automatizada que afetem seus interesses, e o direito a **informações claras** sobre os critérios usados.

**Na realidade de uma OSC**, isso costuma aparecer em situações como:

- **Seleção automática** de candidatos a uma vaga, bolsa ou voluntariado por um sistema que filtra/pontua currículos.
- **Triagem ou priorização de beneficiários** por um escore calculado automaticamente.
- **Segmentação de contatos** (doadores, inscritos) para campanhas com base num perfil traçado pela ferramenta.

> ✅ **Boas práticas:** mantenha uma **pessoa no circuito** para revisar decisões que afetam alguém de forma relevante; saiba **explicar em palavras simples** como a decisão foi tomada; e seja transparente quando usar perfis. Tratamentos assim costumam ser bons candidatos a um [RIPD](/modulos/ripd/).

> ⚠️ Muitas OSCs **não** fazem decisão totalmente automatizada — uma pessoa sempre decide no fim. Se for o seu caso, o tema te alcança pouco. O cuidado existe quando a **máquina decide sozinha** e isso **impacta** alguém.

## Incidente de segurança

É qualquer evento que comprometa dados pessoais: vazamento, acesso indevido, perda de um arquivo, e-mail enviado para a lista errada. Quando há **risco relevante** aos titulares, a OSC deve **comunicar os afetados** e a **ANPD**. O módulo de [Incidentes](/modulos/incidentes/) ajuda a registrar e comunicar de forma rastreável — mas a notificação oficial à ANPD é feita por você, pelos canais do governo. Veja [como montar um plano de resposta](/modulos/incidentes/#como-se-preparar-um-plano-de-resposta-a-incidentes).

## Para continuar

- Quer o roteiro prático de adequação? → **[O passo a passo da conformidade](/passo-a-passo-conformidade/)**
- Quer começar a usar? → **[Primeiros Passos](/primeiros-passos/)**

## Sites úteis

- [Texto da LGPD (Lei nº 13.709/2018)](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm){:target="_blank" rel="noopener"}
- [ANPD — Autoridade Nacional de Proteção de Dados](https://www.gov.br/anpd/pt-br){:target="_blank" rel="noopener"}
- [Formação em LGPD para OSCs — RIT](https://cursos.rit.org.br/){:target="_blank" rel="noopener"} — **gratuita para as organizações integradas à RIT**.
