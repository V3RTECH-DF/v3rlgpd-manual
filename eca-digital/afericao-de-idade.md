---
title: "Se você for aferir idade: escolher o método"
nav_order: 7
parent: "ECA Digital (Lei 15.211/2025)"
permalink: /eca-digital/afericao-de-idade/
role: encarregado
last_verified: 2026-06-25
status: rascunho
---

# Se você for aferir idade: como escolher o método

> 💡 **Antes de tudo: a maioria das OSCs não precisa disso.**
>
> Se o seu site tem **controle editorial** (conteúdo escolhido pela própria OSC, sem automação), a **aferição de idade é dispensada** — veja o [Enquadramento](/eca-digital/enquadramento/). Esta página é para o **caso incomum** em que a sua OSC realmente vai **verificar a idade** de quem acessa (ex.: oferta de conteúdo impróprio para menores). Se não é o seu caso, pode pular.

Quando a aferição **é mesmo necessária**, a forma de fazer importa tanto quanto o fato de fazer: um método mal escolhido coleta dados demais e cria um risco novo. As orientações preliminares da ANPD apontam **seis cuidados** para escolher um método alinhado à LGPD. Use a lista abaixo como guia.

## A pergunta zero: dá para **não** aferir?

O método menos arriscado é o que **não coleta dado nenhum**. Antes de escolher "como verificar", confirme se você **precisa** verificar — muitas vezes basta a adequação do conteúdo por faixa etária e a mediação dos pais, sem checagem técnica a cada acesso.

## Checklist do método privacy-friendly

- [ ] **Minimização — confirme o *atributo*, não a identidade.** Prefira responder apenas "**é maior de 18?**" (ou a faixa etária) em vez de coletar **data de nascimento, documento ou selfie**. A ANPD cita como exemplos de minimização as **credenciais verificáveis** e as **provas de conhecimento zero (ZKP)** — técnicas que confirmam o atributo sem revelar o dado por trás.
- [ ] **Cautela redobrada com biometria facial.** Imagem do rosto para estimar idade é **dado pessoal sensível** (art. 5º, II da LGPD): exige fundamentação robusta, salvaguardas fortes e atenção a **vieses** (a acurácia costuma ser **desigual entre grupos**, o que pode discriminar). Trate como último recurso, não como padrão.
- [ ] **Faça um RIPD.** A aferição é um tratamento de risco — avalie-o no [módulo RIPD](/modulos/ripd/) antes de implantar: o que coleta, por quê, riscos e mitigações.
- [ ] **Inclusão e não discriminação.** Evite métodos que **excluam pessoas vulneráveis** (exigir só documento oficial barra, por exemplo, quem não tem documento em mãos). Ofereça **mais de um caminho** para comprovar a idade.
- [ ] **Transparência e auditabilidade.** Informe **para que** a verificação serve e **o que** é guardado. Mantenha **logs só com metadados** (que houve verificação, quando) — **sem guardar** biometria, imagens ou cópias de documentos.
- [ ] **Finalidade exclusiva.** Os dados coletados para aferir idade servem **só para isso** — nunca para marketing, perfilamento ou qualquer uso secundário.

## Como o V3RLGPD ajuda aqui

O V3RLGPD **não faz a aferição** (não é provedor de verificação de identidade) — mas apoia a **decisão responsável**: o [enquadramento](/eca-digital/enquadramento/) mostra se você está dispensado; o [RIPD](/modulos/ripd/) documenta a avaliação de risco; e a [política de privacidade](/modulos/politicas/) registra a finalidade exclusiva dos dados de verificação.

## Se alguém contestar a idade aferida

Se um adolescente ou um responsável **discordar** da idade/faixa que o sistema atribuiu, isso é um **direito do titular** — e você **não precisa de nada novo**: trate pelo fluxo de **[Atendimento ao Titular (Art. 18)](/modulos/atendimentos/)** que o V3RLGPD já oferece. A pessoa abre um pedido de **correção/revisão** e a sua OSC responde pelo painel de **Atendimentos**, como em qualquer outra solicitação.

> ⚠️ **Regulamentação ainda preliminar.** Os requisitos técnicos detalhados (transparência, segurança e interoperabilidade dos métodos de aferição) ainda serão objeto de **regulamentação específica da ANPD**. Esta orientação reflete o material **preliminar** disponível e será **atualizada** quando sair a versão definitiva. Não é parecer jurídico.
