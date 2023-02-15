>[DIAPOSITIVAS](S5-recursos/introduccion.pdf)

---

## INTRODUCCIÓN A LA SESIÓN

Bienvenidos a esta quinta sesión del bloque del prework. Tras haber trabajado con HTML y CSS, habiendo hecho nuestra primera landing, vamos ahora a adentrarnos en el mundo de JS para poder darle lógica y funcionalidad a las estructuras y diseños que estamos aprendiendo a hacer. a lo largo de la sesión:

- Haremos una pequeña introducción a Javascript como lenguaje de programación e implementaremos nuestro primer 'Hello World'

- Aprenderemos a declarar y a trabajar con variables

- Veremos los tipos de datos más importantes que tienen las variables

- Veremos también los operadores con los que podemos actuar

- Trabajaremos con condicionales

- Consoles y debuggers para poder entender la ejecución de código y poder solucionar errores.

- Ejercicios y tareas

## INTRODUCCIÓN A JAVASCRIPT

Como hemos comentado Javascript es un lenguaje de programación que nos va a servir para poder crear esa interactividad que necesitamos en una página web. Por ejemplo:

- Acciones relacionadas a la pulsación de un botón
- Carruseles y galerías de imágenes
- Animaciones
- Integración con servicios y bases de datos.

Esta base de Javascript la utilizan React y Node, con los que trabajaremos a lo largo del curso.

## NUESTRO PRIMER HELLO WORLD

Vamos ahora a crear nuestro primer Hello World. Para ello crearemos un proyecto base con nuestro **index.html** genérico.
Debemos crear también un fichero **main.js** que será donde introduzcamos el código de JS.
Para incluir este script en el fichero raíz de html usaremos la a etiqueta `<script>`.

```js
<script src="main.js"></script>
```

Una vez definido el script vamos a aprender nuestra primera función, que seguro que vais a utilizar mucho a lo largo de vuestra carrera como desarrolladores. Es la función **console.log()** y sirve para mostrar por consola en el navegador cierta información. En nuestro caso vamos a mostrar la frase **"Hello World!"** de tal manera:

```js
console.log("Hello World!"); //muestra por consola la cadena Hello World!
```

Si vamos a la consola de nuestro navegador vamos a ver que se muestra esa frase.
¡Con este ejemplo ya habríamos hecho nuestro primer script!

Otra forma de mostrarlo de manera más visual es con la función **alert()** de tal manera:

```js
alert("Hello World!"); //muestra una alerta con la cadena Hello World!
```

Como habéis visto, para trabajar con comentarios en JS se hace de la misma manera que en CSS. Disponemos tanto de comentarios de línea **'//'** como de bloque **'/* */’**

```js
//Comentario de línea en JS

/*
	Comentario de bloque 
	en JS
*/
```


