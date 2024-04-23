# arrays
 
- un arrays es una zona de alacenamiento continuo en donde s pueden alacernar varios valores, cada un de ellos esta ubicado por la posicion que ocupa el array.
- tambien son denominados arreglos o vecres y cuand son de dos dimesiones se les llama matrices 
- los arrays nos brindan la capacidad de almacenar una coleccion de elemnetos y acceder a ellos de manera individua
- cada elemento se identifica medisante su posicion en el array, denominada  **indice** y estos indices son siempre secuenciales
- En Javascript son altamente flexibles en términos de los diferentes tipos de datos que podemos almacenar en cada posición del array.

## Crear un array

1. Declarando un array con elementos en línea

```Javascript
// Declarando un array con elementos en línea
let miArray = [1, 2, 3];
console.log(miArray);
```

2. Declarando un array con la sintaxis **newArray**

```Javascript
// Declarando un array con la sintaxis new Array
let miArray = new Array(1, 2, 3);
console.log(miArray);
```

3. Declarando un array con un tamaño específico utilizando la sintaxis **new Array**

```Javascript
// Declarando un array con un tamaño específico utilizando la sintaxis new Array
let miArray = new Array(3);
miArray[0] = 1;
miArray[1] = 2;
miArray[2] = 3;
console.log(miArray);
```

4. Declarando un array con elementos de diferentes tipos de datos.

```Javascript
// Declarando un array con elementos de diferentes tipos de datos.
let miArray4 = [1, "dos", true, {nombre: "Juan", edad: 30}];
console.log(miArray4);
```
