---
title: "Refactoring: Introducción"
date: 2019-03-15T18:48:02Z
draft: false
toc: false
images:
  - /images/refactoring-introduccion.jpg
tags: 
  - refactoring
---
Este es el primero de una serie de artículos en los que voy a tratar sobre mis experiencias con la refactorización (refactoring en inglés), siendo un novato en proceso de aprendizaje sobre dicha materia, mientras avanzo en mi lectura del libro Refactoring Workbook, por William C. Wake.

Comienzo este artículo por el que fue mi primer encuentro con este tema: La definición. Más concretamente, la que puedes encontrar en {{< rawhtml >}}<a href="https://es.wikipedia.org/wiki/Refactorizaci%C3%B3n" target="_blank">este artículo de Wikipedia</a>{{< /rawhtml >}}.

## La primera definición (no tan buena)

>“La refactorización es una técnica de la ingeniería de software para reestructurar un código fuente, alterando su estructura interna sin cambiar su comportamiento externo.”
>
>-- <cite>Wikipedia</cite>

Estas fueron las primeras palabras con las que me transmitieron (o intentaron) el significado de refactoring.

La definición es correcta desde el punto de vista de un formador, alguien que **ya posee este conocimiento** que se quiere hacer llegar. Sin embargo, las palabras no transmiten nada más allá de lo que meramente expresan. Es decir, de ella podemos extraer:

* Técnica (La **acción**)
* Ingeniería de software (El **ámbito**)
* Reestructurar un código (El **qué**)
* Sin cambiar su comportamiento (El **cómo**) 

Si nos paramos a pensar un momento y somos capaces de ponernos en el punto de vista de un aprendiz, seremos capaces de detectar en ella la ausencia de las dos partes que de verdad importan, las más esenciales para transmitir el concepto. Estas son el **por qué** y el **para qué**.

Definiciones con una estructura similar a esta están presentes en todos los ámbitos y se llevan escribiendo y repitiendo durante décadas. Fracasan miserablemente en el cumplimiento de su objetivo, carecen de la capacidad de plasmar el significado que pretenden comunicar y por ende el sentido mismo de su existencia.

Además, en su esfuerzo de utilizar un vocabulario técnico se vuelven frías y vacuas. Características que hacen parecer como si no hubiesen sido escritas para ser leídas y reflexionadas por otro ser humano. Sobretodo si aún está aprendiendo sobre su ámbito.

## La segunda definición (mucho mejor)

Veamos ahora por el contrario, como es descrito el refactoring en la siguiente definición, extraída del libro citado en el inicio de este artículo.

>“La refactorización es el arte de mejorar el diseño de un código existente de una manera segura. Nos provee de formas para organizar un código problemático y nos da las pautas para mejorarlo.”
>
>-- <cite>William C. Wake</cite>

A diferencia de la primera definición, esta se centra completamente en cumplir su objetivo de transmitir el concepto al que se refiere.

De ella, seguimos extrayendo:
* La **acción**, de una forma quizá más acertada, enfocada a la artesanía en “el arte de”.
* El **ámbito**, en “el diseño de un código”.
* El **qué**, en “organizar un código”.
* El **cómo**, en “de una forma segura”. 

Y finalmente:
* El **por qué**, en “código problemático”.
* El **para qué**, en “mejorar el diseño”. 

## Conclusión

Primero, que siempre es útil consultar distintas fuentes sobre una materia en concreto, pues te ayudarán a despejar las posibles dudas que te puedan surgir si has dado con una única explicación incompleta.

Por último, que el fin de la refactorización es la mejora en el diseño del código existente.