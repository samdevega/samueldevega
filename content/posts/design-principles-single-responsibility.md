---
title: "Design Principles: Single Responsibility"
date: 2019-06-23T10:24:50Z
draft: true
toc: false
images:
  - /posts/design-principles-single-responsibility.jpg
tags: 
  - design-principles
---
## SOLID

Es el acrónimo de cinco principios básicos de la programación orientada a objetos. La aplicación de este conjunto de principios de programación conlleva al desarrollo de sistemas más simples, fáciles de mantener y ampliables a lo largo del tiempo. Si bien debemos. entender los principios como directrices y no como leyes.

Se dice que un desarrollador junior debería aplicarlos siempre. Con el paso del tiempo y la adquisición de experiencia e interiorización de estos y otros conceptos de desarrollo de software, podrá decidir acertadamente en qué grado debe aplicar cada uno de ellos en función de sus necesidades, moldeando la arquitectura del sistema a su conveniencia.

## Single Responsibility Principle

Primer principio de *SOLID*, abreviado como *SRP* y conocido como el principio de responsabilidad única.

Este principio busca fomentar la cohesión en el código enunciando que si cada clase de nuestro sistema tiene una única responsabilidad (finalidad u objetivo) esta será más sencilla de mantener.

Vamos a verlo con un ejemplo: