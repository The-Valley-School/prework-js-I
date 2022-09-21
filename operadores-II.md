**OPERADORES LÓGICOS**

Como su propio nombre indica, los operadores lógicos van a servir para que podamos realizar operaciones lógicas con nuestras variables. Operadores lógicos:

- OR '||': Se debe cumplir una de las condiciones
- AND '&&': Deben cumplirse las dos condiciones
- NOT '!': Negamos el valor

**OR**

Nos devuelve true en caso de que alguna de las variables de la comparativa sea true, en caso contrario, false.

```js
let tengoNetflix = true;
let tengoHBO = true;
let puedoVerSerie = tengoNetflix || tengoHBO;
```

**AND**

Nos devuelve true en caso de que se cumplan todas las condiciones, en caso contrario, false.

```js
let soyMayorDeEdad = true;
let tengoCarnet = true;
let puedoConducir = soyMayorDeEdad && tengoCarnet;
```

**NOT**

Nos devuelve el valor contrario al expuesto

```js
let noVerdadero = !true;
let noFalso = !false;
```

**OPERADORES DE COMPARACIÓN**

Utilizando símbolos específicos vamos a poder comparar también variables
Operadores comparación:

- '==': Igual
- '!=': Distinto
- '==': Estrictamente igual
- '!=': Estrictamente distinto
- '<': Menor
- '>': Mayor
- '<=': Menor igual
- '>=': Mayor igual

Con '==' y '!=' comparamos variables sin tener en cuenta el valor

```js
    3 == 3      //True
    3 == "3"    //True
    3 == 4      //False
    3 != 4      //True
    3 != "3"    //False
```

Con '===' y '!==' comparamos estrictamente incluyendo el valor de la variable

```jsx
    3 === 3      //True
    3 === "3"    //False
    3 === 4      //False
    3 !== 4      //True
    3 !== "3"    //True
```

Los símbolos '<', '>', '<=' , '>=' sirven para comparar valores numéricos

```js
    3 < 3      //False
    3 <= 3     //True
    3 > 4      //False
    10 >= 4    //True
```
