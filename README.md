# ca-hello-world-2025 {

## Table of contents

1. [What is programming?](#what-is-programming?)
1. [Introduction to javascript](#introduction-to-Javascript)

## What is programming?

La `programación` es un proceso mediante el cual, gracias a diversas herramientas y procesos, logramos comunicarnos con un ordenador. Por norma general esta comunicación pretende una traducción del lenguaje-persona (lenguaje) al lenguaje-máquina (código) en un conjunto de instrucciones paso-a-paso comprensibles para ambas partes (programa). El objetivo final es la transformación de una información inicial (inputs) a una información final (outpus).

> [!NOTE]  
> `Programación`: composición de instrucciones secuenciales (programas) que sigue un ordenador para ejecutar una tarea. Agrupa el diseño e implementación de algoritmos y/o procedimientos específicos step-by-step declarados a través de un lenguaje de programación.

![programming](./img/img1.png)

Un ejemplo cotidiano de programación es la `cocina` como proceso con idéntica lógica interna:

- El `programa` es la receta completa
- El `código` son las instrucciones paso a paso (mezclar harina, agregar leche, batir, calentar la sartén, etc.)
- Las `variables` son los ingredientes, como la cantidad de harina, huevos, leche. Podemos modificarlas para ajustarlas al número de comensales
- Las `funciones` son acciones específicas que puedes reutilizar, como "batir los ingredientes" o "cocinar en el horno". En JavaScript podemos escribir algo así:

```js
// Declaración de la función
function recetaTortitas(harina, leche, huevos) {
	return `Mezcla de ${harina}g de harina, ${leche}ml de leche y ${huevos} huevos lista.`;
}

// Invocación de la función
console.log(recetaTortitas(200, 300, 2));
```

Cuando seguimos todas las instrucciones correctamente, obtenemos un plato terminado (el resultado del programa funcionando). Así funciona la programación en JavaScript: definimos instrucciones, usamos datos (ingredientes) y creamos algo útil (como una página web interactiva) 🚀.

## Introduction to Javascript

`JavaScript` es uno de los [lenguajes de programación más empleados](https://2020.stateofjs.com/en-us/demographics/) en el desarrollo web, móvil, juegos, etc. Abreviado comúnmente como JS se trata de un lenguaje de programación interpretado, dialecto del estándar ECMAScript. Se define como orientado a objetos,​ basado en prototipos, imperativo, débilmente tipado y dinámico.

¿Qué significa todo esto? ¡Pues muchas cosas! Pero no te preocupes. Esta es solo una definición estándar que iremos entendiendo poco a poco. Lo importante viene ahora.

Sobre JS hay mucho que leer y mucho que aprender, pero es ideal si estás empezando en el mundo de la programación por una sencilla razón: se trata de un `lenguaje de alto nivel`. Es decir, su sintaxis es muy similar a la que usamos las personas por lo que en muchas ocasiones tendrás la sensación de estar escribiendo comandos en inglés para comunicarte con tu ordenador.

JS es un lenguaje vivo y hay que estar al día para conocer las últimas tendencias y herramientas. Compartimos contigo dos de las muchas fuentes de información que veremos a lo largo del bootcamp: [stateofjs](https://2020.stateofjs.com/en-US/) y [ecma-international.org](https://www.ecma-international.org/publications-and-standards/standards/ecma-262/).

## Objetivos

Después de esta introducción serás capaz de:

- Entender el propósito del lenguaje JavaScript
- Declarar variables
- Componer expresiones lógicas

## Recursos necesarios

- Crear una cuenta en https://repl.it/

## 1. Hello world

Vamos a escribir nuestro primer código en JavaScript. En este código imprimimos por consola el texto "Hello World!".

```js
console.log('Hello World!');
```

Para probar el código, puedes acceder a la plataforma [repl.it](https://repl.it). Crea una cuenta y pega el código creando un nuevo `repl` usando el botón azul "+", selecciona el lenguaje `node.js`.
