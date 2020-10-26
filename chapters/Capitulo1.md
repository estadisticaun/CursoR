---
title: 'Capítulo 1: Iniciando'
description:
  'Este capítulo enseña los fundamentos de R.'
prev: null
next: /Capitulo2
type: chapter
id: 1
---

<exercise id="1" title="Introducción" type="slides">

<slides source="chapter1_01_introduction">
</slides>

</exercise>

<exercise id="2" title="Empezando">

Esto es solo un test, vamos a probar caracteres especiales con tildés y ñame

<choice>
<opt text="Answer one">

This is not the correct answer.

</opt>

<opt text="Answer two" correct="true">

Good job!

</opt>

<opt text="Answer three">

This is not correct either.

</opt>
</choice>

</exercise>

<exercise id="3" title="Fundamentos de R">

This is a code exercise. The content can be formatted in simple Markdown 
you can have **bold text**, `code` or [R basico](https://rbasico.netlify.app/) or lists, like
the one for the instructions below.

- These are instructions and they can have bullet points.
- The code block below will look for the files `exc_01_03`, `solution_01_03` and
  `test_01_03` in `/exercises`.

`EJERCICIO 1`

<codeblock id="01_03_01">

Esto es una ayuda para el ejercicio 1

</codeblock>

Es decir, en la igualdad del ejemplo propuesto `"1" == 1` R, al detectar que los tipos de datos involucrados en la igualdad son de diferentes tipologías, lo primero que hace es igualarlos según la jereraquía propuesta. Según la regla, un dato de tipo textual o caracter tiene mayor jerarquía que un dato de tipo numérico (_caracter > numérico_) hecho que conduce a R a convertir el dato de tipo numérico **1** en un dato de tipo textual **"1"** para garantizar que los tipos de datos involucrados en la expresión lógica sean del mismo tipo. En conclusión, al evaluar la operación lógica `"1" == 1` en R, por la regla de coherción, lo que el lenguaje efectivamente evaluará es la operación `"1" == "1"` cuyo resultado es TRUE. A continuación, se presentan otros ejemplos en lo que se invita al lector a reflexionar sobre la forma como R está aplicando en ellos la regla de coerción.

<p style="color:#e6550d";><i>Ejercicio 2</i></p>

<codeblock id="01_03_02">

Esto es una ayuda para el ejercicio 2

</codeblock>


</exercise>


<exercise id="4" title="Último capítulo">
</exercise>
