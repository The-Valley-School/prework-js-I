Vamos ahora a practicar operadores y condicionales:

## Ejercicio 1 - Calculadora

- Crea un fichero llamado ejercicio1.js e inclúyelo dentro de tu html
- Define una variable llamada **x** y asígnale un valor 100
- Define una variable llamada **y** y asígnale un valor 10
- Define una variable llamada resultadoSuma cuyo valor sea la suma de X-Y
- Define una variable llamada resultadoResta cuyo valor sea la resta de X-Y
- Define una variable llamada resultadoMultiplicacion cuyo valor sea la multiplicación de X-Y
- Define una variable llamada resultadoDivision cuyo valor sea la division de X-Y
- Muestra los resultados por consola, indicando la operación realizada más el resultado de la misma.

```js
let x = 100;
let y = 10;

let resultadoSuma = x + y;
let resultadoResta = x - y;
let resultadoMultiplicacion = x * y;
let resultadoDivision = x / y;

console.log("El resultado de la suma es: " + resultadoSuma);
console.log("El resultado de la resta es: " + resultadoResta);
console.log("El resultado de la multiplicación es: " + resultadoMultiplicacion);
console.log("El resultado de la división es: " + resultadoDivision);
```

## Ejercicio 2 - Película favorita

- Crea un fichero llamado ejercicio2.js e inclúyelo dentro de tu html
- Define una variable llamada peliculaFavorita y asígnale el valor de tu película favorita
- Define una variable llamada actor y asígnale el nombre de un actor que salga en esa película
- Define una variable llamada visualizaciones donde indiques el número de veces que has visto la película
- Muestra por consola la frase: “Mi película favorita es XXX, me encanta la actuación de XXX, he podido verla unas XXXX veces”

```js
let peliculaFavorita = "7 Almas";
let actor = "Will Smith";
let visualizaciones = 10;

let mensaje = "Mi película favorita es " + peliculaFavorita + ",me encanta la actuación de " + actor + ",he podido verla unas " + visualizaciones + " veces"; 
console.log(mensaje);
```

## Ejercicio 3 - Concierto Rosalía

- Crea un fichero llamado ejercicio3.js e inclúyelo dentro de tu html
- Define una variable llamada quedanEntradas y asígnale un valor true
- Define una variable dineroEnCuenta y asígnale un valor 100
- Define una variable meDejanDinero y asígnale un valor true
- Declara una variable puedoIrAlConcierto donde comprobemos si quedan entradas y en caso de ser así, comprobemos si tengo suficiente dinero ( las entradas cuestan 80€ ) o me dejan dinero para pagarlo.
- Mostrar la variable puedoIrAlConcierto por consola e ir probando las diferentes opciones

```js
let quedanEntradas = true;
let dineroEnCuenta = 100;
let meDejanDinero = true;

let puedoIrAlConcierto = quedanEntradas && (dineroEnCuenta <= 80 || meDejanDinero);
console.log(puedoIrAlConcierto);
```

## Ejercicio 4 - Nota

- Crea un fichero llamado ejercicio4.js e inclúyelo dentro de tu html
- Define una variable llamada nota con un valor 7
- Crea una condición que muestre un mensaje por consola indicando que estás aprobado si la nota es mayor o igual que 5, en caso contrario, que muestre un mensaje diciendo que has suspendido.
- Prueba a cambiar el valor de la nota para comprobar que dependiendo del valor sale un mensaje u otro por consola.

```js
let nota = 7;

if(nota >= 5) {
	console.log("Has aprobado");
} else {
	console.log("Has suspendido");
}
```

## Ejercicio 5 - Nota 2

- Vamos a darle una vuelta de tuerca al ejercicio4, crea un fichero  ejercicio5.js e inclúyelo dentro de tu html
- Define una variable llamada nota con un valor 3
- Crea una condición que muestre un mensaje por consola indicando que:
    - Si tienes una nota mayor o igual a 0 y menor que 5, estás suspenso
    - Si tienes una nota mayor o igual a 5 y menor que 6, has aprobado con un suficiente
    - Si tienes una nota mayor o igual a 6 y menor que 7, has aprobado con un bien
    - Si tienes una nota mayor o igual a 7 y menor que 9, has aprobado con un notable
    - Si tienes una nota mayor o igual a 9, has aprobado con sobresaliente
    - Validar que si la nota no está entre 0 y 10, no es una nota correcta
- Prueba a cambiar el valor de la nota para comprobar que dependiendo del valor sale un mensaje u otro por consola.

```js
let nota = 7;

if(nota > 0 && nota <= 5) {
	console.log("Has suspendido");
} else if (nota >= 5 && nota < 6) {
	console.log("Has aprobado con suficiente");
} else if (nota >= 6 && nota < 7) {
	console.log("Has aprobado con bient");
} else if (nota >= 7 && nota < 9) {
	console.log("Has aprobado con notable");
} else if (nota >= 9 && nota <= 10) {
	console.log("Has aprobado con sobresaliente");
} else {
	console.log("La nota no es válida");
}
```

## Ejercicio 6 - Pescadería

- Crea un fichero  ejercicio6.js e inclúyelo dentro de tu html
- Define una variable llamada pescado con un valor lubina
- En función del pescado que el cliente pida (variable pescado) mostrar por consola el precio:
    - Si es atún el precio será de 20€ el kilo
    - Si es salmón el precio será de 15€ el kilo
    - Si es trucha el precio será de 10€ el kilo
    - Si es lubina el precio será de 20€ el kilo
    - Si es mero el precio será de 30€ el kilo
    - Con cualquier otro pescado indicaremos que no tenemos ahora mismo en la pescadería
- Prueba a cambiar el valor del pescado para comprobar que dependiendo del valor sale un mensaje u otro por consola.

```js
let pescado = "lubina";

switch (pescado){
    case "atún":
       console.log('El precio del atún es de 20€ el kilo');
       break;
    case "salmón":
		  console.log('El precio del salmón es de 15€ el kilo');
       break;
    case "trucha":
       console.log('El precio de la trucha es de 10€ el kilo');
       break;
    case "lubina":
       console.log('El precio de la lubina es de 20€ el kilo');
       break;
    case "mero":
       console.log('El precio del mero es de 30€ el kilo');
       break;
    default:
        console.log('Lo sentimos, no tenemos ahora en la pescadería');
        break;
}
```
