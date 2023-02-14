Os dejamos unas tareas para que practiquéis con operadores y condicionales:

## Ejercicio 1 - Calculadora

- Crea un fichero llamado ejercicio1.js e inclúyelo dentro de tu html
- Define una variable llamada **x** y asígnale un valor 30
- Define una variable llamada **y** y asígnale un valor 40
- Utilizando el operador de suma y asignación, suma a la variable y el valor de x
- Utilizando el operador de resta y asignación, resta a la variable y el valor de x
- Utilizando el operador de multiplicación y asignación, multiplica la variable y el valor de x
- Utilizando el operador de division y asignación, divide la variable y el valor de x
- Ve mostrando los resultados por consola para poder ver que se ejecuta correctamente.

```js
let x = 30;
let y = 40;

y += x;
y -= x;
y /= x;
y *= x;

console.log(y);
```

## Ejercicio 2 - Comida favorita

- Crea un fichero llamado ejercicio2.js e inclúyelo dentro de tu html
- Define una variable llamada ciudad y asígnale el valor de tu lugar favorito
- Define una variable llamada mejorAmigo y asígnale el nombre de tu mejor amigo.
- Define una variable llamada estacion donde indiques si eres más de verano, otoño…
- Muestra por consola la frase: “Me encanta XXX, me gustaría ir con XXX el próximo XXXX”
    
    (por ejemplo ‘Me encanta Barcelona, me gustaría ir con Fran el próximo verano’)
    

```js
let ciudad = "Barcelona";
let mejorAmigo = "Fran";
let estacion = "verano";

let mensaje = "Me encanta " + ciudad + ",me gustaría ir con " + mejorAmigo + " el próximo " + estacion; 
console.log(mensaje);
```

## Ejercicio 3 - Conducir coche

- Crea un fichero llamado ejercicio3.js e inclúyelo dentro de tu html
- Define una variable llamada edad y asígnale un valor 18
- Define una variable tengoCarnet y asígnale un valor true
- Define una variable tengoCoche y asígnale un valor true
- Define una variable tengoMoto y asígnale un valor false
- Define una variable heBebidoAlcohol y asígnale un valor true
- Declara una variable puedoConducir donde comprobemos si tengo edad para conducir, tengo carnet, tengo coche o tengo moto, y no he bebido.
- Mostrar la variable puedoConducir por consola e ir probando las diferentes opciones

```js
let edad = 18;
let tengoCarnet = true;
let tengoCoche = true;
let tengoMoto = false;
let heBebidoAlcohol = true;

let puedoConducir = edad >= 18 && tengoCarnet && (tengoCoche || tengoMoto) && !heBebidoAlcohol;
console.log(puedoConducir);
```

## Ejercicio 4 - PH Piscina

- Crea un fichero  ejercicio4.js e inclúyelo dentro de tu html
- Define una variable llamada ph con un valor 7
- Crea una condición que muestre un mensaje por consola indicando que:
    - Si tienes un ph mayor o igual a 0 y menor que 7, el agua está ácida
    - Si tienes un ph igual a 7, el agua está neutra
    - Si tienes un ph mayor a 7 y menor o igual a 14, el agua está alcalina
    - Validar que si el ph no está entre 0 y 14, no es un ph correcto
- Prueba a cambiar el valor de la ph para comprobar que dependiendo del valor sale un mensaje u otro por consola.

```js
let ph = 7;

if(ph > 0 && ph <= 7) {
	console.log("El agua está ácida");
} else if (ph == 7) {
	console.log("El agua está neutra");
} else if (ph > 7 && ph <= 14) {
	console.log("El agua está alcalina");
} else {
	console.log("El ph no es correcto");
}
```

## Ejercicio 5 - Calculadora 3

- Crea un fichero  ejercicio5.js e inclúyelo dentro de tu html
- Define una variable llamada a con valor 3
- Define una variable llamada b con valor 10
- Define una variable llamada operacion con valor SUMA
- Define una variable llamada resultado sin valor definido;
- En función de la variable operacion (SUMA, RESTA, DIVISIÓN, MULTIPLICACIÓN) realizar la operación con las variables a y b sobre la variable resultado [Ayuda: Hay que hacer un switch]
- En caso de que no sea ninguna de esas operaciones el resultado tiene que ser 0
- Mostrar por consola el resultado de la operación
- Probar con las diferentes opciones.

```js
let a = 3;
let b = 10;
let resultado;
let operacion = "SUMA";

switch (operacion){
    case "SUMA":
       resultado = a + b;
       break;
    case "RESTA":
			 resultado = a - b;
       break;
    case "MULTIPLICACIÓN":
       resultado = a * b;
       break;
    case "DIVISIÓN":
       resultado = a / b;
       break;
    default:
        resultado = 0;
        break;
}

console.log(resultado);
```
