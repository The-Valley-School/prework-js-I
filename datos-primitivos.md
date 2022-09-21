**INTRODUCCIÓN A TIPOS DE DATOS PRIMITIVOS**

Vamos a ver ahora una serie de tipo de datos primitivos que vamos a poder asignar a nuestras variables. Son los siguientes:

- STRING (cadena de texto)
- NUMBER (numérico)
- BOOLEAN (booleno)
- NULL (nulo)
- UNDEFINIED (no declarado / no valor)

**STRING**

Asignación de valores de texto. Esta secuencia de texto se denomina cadena / cadena de caracteres y siempre tiene que ir entre comillas.

```js
let libro = "Viaje al centro de la tierra";
let autor = "Julio Verne";
```

Para escribir cadenas en las que hay comillas simples o dobles, tendremos que jugar con las que utilicemos para asignarles un valor:

```js
let noticia = "Cervantes escribió: 'En un lugar de la mancha...'";
```

En caso de querer mostrar comillas dobles dentro del texto jugaríamos con las simples al contrario.

**NUMBER**

Asignación de valores numéricos. Pudiendo ser un número entero, decimal o negativo.

```js
let nEntero = 3;
let nDecimal = 3.5;
let nNegativo = -10;
```

Cuidado con poner números entre comillas ya que serán interpretados como una cadena de caracteres.

**BOOLEAN**

Asignación de un valor lógico a la variable. Pudiendo ser true o false. No servirán para almacenar sobre todo información de si cumplen o no cumplen una condición, si esa es verdadera o falsa...
Tienen dos estados: **TRUE/FALSE**

```js
let tieneCarnet = true;     // Si es verdadero
let tieneCarnet = false;    // Si es falso
```

**NULL**

Asignación de un valor nulo que no corresponde a dato concreto.

```js
let nombre = null;
```

**UNDEFINED**

Nos indica que a una variable no se le ha dado un tipo de valor.

```js
let nombre;
console.log(nombre); // Devuelve undefined por que no se le ha dado ningún valor.
```

Podríamos volver a asignarle a una variable el tipo undefined una vez declarada.

```js
nombre = undefined;
```
