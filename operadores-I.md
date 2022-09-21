Vamos ahora a trabajar con operadores. Son símbolos matemáticos que nos van a permitir trabajar sobre dos valores para conseguir un resultado.

**OPERADORES ARITMÉTICOS**

El primer grupo de operadores que vamos a ver es el aritmético.
Nos van a permitir realizar operaciones matemáticas. Utilizamos los signos que conocemos de sobra:

- **'='** Asignación
- **'-', '/', '*'** Resta, división y multiplicación
- **'+'** Suma, concatenación

**ASIGNACIÓN**

Lo utilizamos para asignarle un valor a nuestra variable

```js
let a = 3;
let b = 10;
```

**RESTA, DIVISIÓN, MULTIPLICACIÓN**

Para realizar las operaciones necesarias sobre las variables

```js
let resultadoResta = a - b;
let resultadoDivisión = a / b;
let resultadoMultiplicacion = a * b;
let resultadoEcuacion = (a - b) * a / b;
```

**SUMA Y CONCATENACIÓN**

Para realizar operaciones numéricas o concatenación de cadenas de caracteres.

```js
let resultadoSuma = a + b;                  // Suma numérica, resultado 13
let frase = "Hola me llamo" + " " + "Edu";  //Concatenación, el resultado sería la cadena 'Hola me llamo Edu'
let resultadoSuma2 = "3" + "10";            //Se trataría de una concatenación, el resultado sería 310
let resultadoSuma3 = "3" + 10;              //Javascript lo seguiría interpretando como cadena, resultado 310
```

**OPERADORES DE OPERACIÓN Y ASIGNACIÓN**

A la hora de trabajar en Javascript podemos operar y asignar de manera simultánea para poder conservar ciertos valores. Estos operadores serían:

- **"+="** Suma y asignación
- **"-="** Resta y asignación
- **"*="** Multiplicación y asignación
- **"/="** División y asignación

```js
let a = 3;
let b = 10;

a += b; // a = a + b
a -= b; // a = a - b
a /= b; // a = a / b
a *= b; // a = a * b

let frase1 = "Hola me llamo ";
let frase2 = "Eduardo";

frase1 += frase2; // frase1 = frase1 + frase2, resultado 'Hola me llamo Eduardo'
```
