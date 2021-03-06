---
layout: post
title:  "¿Está dentro del círculo?"
category: medium
---


## Problema

Un círculo puede ser expresado como la siguiente ecuación cuadrática:

$ (x - h) ^ 2 + (y - k) ^ 2 = r ^ 2

donde $x$ y $y$ son variables de la ecuación y $h$, $k$ y $r$ son constantes que representan la posición del centro del círculo con sus cordenadas $(h, k)$ y el radio $r$.

Dado un punto $(m, n)$ se les pide calcular si se encuentra dentro 
de los círculos en los datos de entrada.

### Entrada

La primera línea contendrá un número entero positivo _t_ indicando el número de casos de entrada. La segunda línea tendrá dos números enteros indicando el punto $(m, n)$ a evaluar. 

Las siguientes _t_ líneas tendrán 3 números enteros $h$, $k$ y $r$ que representan las constantes de la fórmula del círculo definida anteriormente.  


### Salida
Para cada caso de entrada habrá una línea de salida. Se formatea como:

    Case x: Dentro
    Case x: Fuera

dependiendo de si el punto está dentro o fuera del círculo del caso de entrada.

## Ejemplo

### Entrada
4

8 10

4 5 6

4 5 10

4 -5 10

7 6 5

## Salida

Case 1: Fuera  
Case 2: Dentro  
Case 3: Fuera  
Case 4: Dentro  
