**DECLARACIÓN DE VARIABLES**

Hay que entender las variables como contenedores o cajas donde podemos guardar información.
Para declarar una variable usamos la palabra 'var' o 'let' y a continuación el nombre que le queramos dar.

```js
var pelicula;
let pelicula;
```

Recomendamos el uso de **'let'** en vez de **'var'.** De momento quedaros con que se utilizaba **'var'** en versiones antiguas de Javascript y surgió **'let'** en versiones más modernas para solucionar problemas en la forma que se trabajaba con **'var'**. Profundizaremos más en esto en las sesiones de javascript del máster. Por ahora, cuando tengáis que declarar una variable, usar siempre **'let'**.

Es importante que todas las líneas en Javascript terminen con un **';'** para indicar que ha terminado una acción. Aquí cada maestrillo tiene su librillo, por lo que hay desarrolladores que entienden que en determinadas ocasiones no es necesario usarlo. Nosotros, de momento, cada vez que terminemos una acción, pondremos **';'**

¿Cómo nombramos variables? Antes de pasar a ver como les asignamos valor, tenemos que tener claro como nombrar variables.

- Utilizaremos siempre una palabra descriptiva de lo que vaya a contener

```js
let manzana;    // Mal nombre para una variable si queremos indicar el título de una serie
let a;          // Mal nombre para una variable si queremos indicar el título de una serie
let serie;      // Buen nombre para una variable si queremos indicar el título de una serie
```

- Utilizaremos  nomenclatura lowerCamelCase. Cuando declaramos variables con más de una palabra estas se unen quitando los espacios, y empezando cada palabra siguiente en mayúsculas.

```js
let Actor Principal;    // Mala forma de declarar si queremos indicar el actor principal
let ActorPrincipal;     // Mala forma de declarar si queremos indicar el actor principal
let actorPrincipal;     // Buena forma de declarar si queremos indicar el actor principal
```

- Como los equipos de desarrollo son cada vez más internacionales, es recomendable que el nombremos las variables en inglés
- Es muy importante también que el nombre de la variable sea único para impedir que se produzcan errores en el código

**ASIGNACIÓN DE VALOR**

Para asignar un valor a una variable lo hacemos de la siguiente forma:

```js
actorPrincipal = "Leonardo DiCaprio";
```

Podemos declarar y asignar un valor a la vez

```js
let actrizPrincipal = "Halle Berry";
```

**OBTENCIÓN Y ASIGNACIÓN DE VALOR**

Para obtener el valor de una variable basta con llamarlo por su nombre

```js
actrizPrincipal;
```

Para poder trabajar con estos ejemplos vamos a usar la función console que nos va a permitir mostrar por consola en el navegador esta variable.

```js
console.log(actrizPrincipal); //Por la consola del navegador saldrá 'Halle Berry'
```

El valor de una variable declarada con 'let' puede modificarse de esta forma:

```js
actrizPrincipal = "Jennifer Aniston";

console.log(actrizPrincipal); //Ahora saldría por consola 'Jennifer Aniston'
```
