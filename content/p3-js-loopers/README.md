---
title: Loopers
description: Primera aproximación al concepto de bucles en JS
tags: basics,js
---

## Table of contents

1. [Loopers](#loopers)
1. [Goals](#goals)
1. [Resources needed](#resources-needed)
1. [My first for loop](#my-first-for-loop)
1. [Switch code block](#switch-code-block)
1. [While loop](#while-loop)
1. [Do while](#Do-while)
1. [Advanced Loops](#advanced-loops)
1. [Countdown](#countdown)
1. [Addition](#addition)
1. [Addition of even numbers](#addition-of-even-numbers)
1. [Additional resources](#additional-resources)

## Loopers

Vamos a practicar bucles en JavaScript. Dominar la sintaxis de los bucles en JavaScript es muy importante, ya que podemos usarlos para recorrer estructuras de información y buscar en ellas.

## Goals

Después de esta introducción serás capaz de:

- Comprender y usar las estructuras de bucle en JS

## Resources needed

- Crear una cuenta en https://repl.it/

## My first for loop

Este bucle imprime los números de 1 al 10:

```js
for (let i = 0; i < 10; i++) {
	console.log(i);
}
```

Veamos otro ejemplo:

```js
for (let step = 0; step < 5; step++) {
	// Runs 5 times, with values of step 0 through 4.
	console.log('Walking east one step');
}
```

Vamos a añadir una estructura condicional `if` para que solo se impriman los números pares:

```js
for (let i = 0; i < 10; i++) {
	if (number % 2 == 0) {
		console.log('es par', i);
	}
}
```

La condición lógica `number % 2 == 0` comprueba que el resto de la división entera sea igual a cero. Ese caso solo se cumple para los números pares.

Puedes repasar los operadores en JavaScript en la documentación de [MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Operadores)

## Switch code block

La declaración switch evalúa una expresión, comparando el valor de esa expresión con una instancia case, y ejecuta declaraciones asociadas a ese case, así como las declaraciones en los casos que siguen.

```js
switch (condition) {
  case valor1:
    //Declaraciones ejecutadas cuando el resultado de condition coincide con el valor1
    [break;]
  case valor2:
    //Declaraciones ejecutadas cuando el resultado de condition coincide con el valor2
    [break;]
  ...
  case valorN:
    //Declaraciones ejecutadas cuando el resultado de condition coincide con valorN
    [break;]
  default:
    //Declaraciones ejecutadas cuando ninguno de los valores coincide con el valor de la condition
    [break;]
}
```

## While loop

Crea un bucle que ejecuta una sentencia especificada mientras cierta condición se evalúe como verdadera. Dicha condición es evaluada antes de ejecutar la sentencia.

```js
let n = 0;
while (n < 3) {
	n++;
}
console.log(n);
```

## Do while

La sentencia (hacer mientras) crea un bucle que ejecuta una sentencia especificada, hasta que la condición de comprobación se evalúa como falsa. La condición se evalúa después de ejecutar la sentencia, dando como resultado que la sentencia especificada se ejecute al menos una vez.

```js
let result = '';
let i = 0;

do {
	i = i + 1;
	result = result + i;
} while (i < 5);

console.log(result);
// expected result: "12345"
```

## Advanced Loops

Observa algunos ejemplos prácticos de bucles:

## Countdown

En este bucle, la cuenta sale hacia atrás, empezando en el valor `10`.

```js
for (let i = 10; i > 0; i-) {
  console.log(i);
}
```

## Addition

Este bucle suma todos los dígitos del 1 al 9

```js
let suma = 0;
for (let i = 1; i < 10; i++) {
	console.log(i);
	suma += i;
}
console.log('La suma es', suma);
```

## Addition of even numbers

Ahora vamos a sumar los números pares entre 0 y 50. Para ello, en este caso, hemos extraído la variable `limite` en la que definiremos el número máximo y operado la suma reasignando la variable `suma`. Nota: `suma = suma + i` es equivalente a `suma += i`

```js
let suma = 0;
let limite = 50;
for (let i = 0; i < limite; i++) {
	if (number % 2 == 0) {
		suma = suma + i;
	}
}
console.log('La suma de los números pares es', suma);
```

## Additional resources

- https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Operadores
- https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Sentencias/for
- https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Sentencias/switch
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration
