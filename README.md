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
## accediendo a la inrmacion de un array

### propiedad length 
- devuelve la cantidad de elementos del array

### operador [pos]
- permite accerder para leer o modificar el elemento pos del array

### metodo at(pos)
- devuelve el elemtent de la posicion pas. el parametro admite valores negativos, lo que significa que empiezan a contar por el final del array

```Javascript
const letters = ["A", "B", "C"]
console.log(letters.length);
console.log(letters[2]);
console.log(letters[5]);
```

## Añadir o eliminar elementos
- push(ele1, ele2): añade uno o varios elementos al final del array. Devuelve el tamaño del array

```Javascript
let miArray5 = [1, 2, 3];
miArray5.push(4); // Agrega el elemento 4 al final del array.
console.log(miArray5);
```

- pop(): Devielve el último elemento del array y lo elimina

```Javascript
let miArray = [1, 2, 3];
miArray.pop(); // Elimina el último elemento del array.
console.log(miArray);
```

unshift(ele1, ele2): Añade una o varios elementos al inicio, devolviendo el tamaño del array después de añadirlos.

```Javascript
let miArray = [1, 2, 3];
miArray.unshift[0]; // Agrega el elemento 0 al inicio del array.
console.log(miArray);
```

- shift(): Devuelve el primer elemento del array y lo elimina.

```Javascript
let miArray = [1, 2, 3];
miArray.shift[0]; // Agrega el elemento 0 al inicio del array.
console.log(miArray);
```

- concat(ele1, ele2): concatena 2 arrays

```Javascript
let miArray = [1, 2, 3];
miArray.shift[0]; // Agrega el elemento 0 al inicio del array.
console.log(miArray);
```

- split(separador): a partir de una cadena, crear un array dividiendo dicha cadena en elementos delimitados por separador
``` Javascript
let miString="hola, ¿como estas?";
let miArray=miString.split(" ")
console.log(miArray);
```

- join(separador): a partir de un array

``` Javascript
let miArry=["hola", "como", "estas" ]
let miString=mi Array.join(" ")
console.log(miString)
```

## busqueda de un elemento en un array

- include(elemento): devuelve true o false si el elemento existe o no dentra en el array
- indexOf(elemento): devuelve la posicion de la ultima aparicion del elemento. si no existe devuelve -1

## modificar el array o crear elementos 

## Modificar el array o crear fragmentos

- slice(inicio, fin): devuelve un array con los elementos desde la posición inicio hasta la posición fin, ambos excluidos.

## Ordenar elementos de un array
- reverse(): invierte el orden de los elementos del array.
- sort(): ordena el array automáticamente.
-sort(criterio): ordena el array con el criterio determinado por la función criterio.

## Borrar elementos de un array 

- Se puede borrar el contenido de un elemento de un array poniendo su valor a null o asignando una cadena vacía " ".

- Para eliminar completamente un elemento del array se utiliza el operador delete.

## Recorrido de un array

1. Recorrer un bucle clásico pasando por todos los elementos.
```Javascript
var dias = ["lunes", "martes", "miercoles", "jueves", "viernes", "sabado", "domingo"];
for(i=0;1<dias.length;i++)
{
    console.log(dias[i]);
}
```

2. Recorrer con un while, pasando por todos los elementos

```Javascript
var dias = ["lunes", "martes", "miercoles", "jueves", "viernes", "sabado", "domingo"];
while(1<dias.length)
{
    console.log(dias[i]);
    i++;
}
```

3. Usando la sentencia for...in

```Javascript
var dias = ["lunes", "martes", "miercoles", "jueves", "viernes", "sabado", "domingo"];
for(let index in dias)
{
    console.log(dias[index]);
}
```

## Arrays multidimensionales

```Javascript
const matrix = [
    [1,2,3],
    [4,5,6],
    [7,8,9]
];
```

- Recorrer una matriz utilizando bucles anidados

# Ejercicios

1. Dada una lista de números separados por coma, calcular la suma, el mayor, el menor y la media de todos

2. Introducir númdos cadenas con elementos separados por coma, y con un botón concatenar las dos cadenas y mostrarlas en pantalla.

3. . Introducir uno a uno los elementos en un array a través de un boton. Con otro botón se va eliminado el último elemento. Siempre que se pulse alguno de los botones de debe mostrar el contenido del array.

4. Introducir un conjunto de números separados por comas. Cuando se pulsa el botón "Pares" cargar una tabla con los números introducidos y luego crear otra que solo incluya los números pares y mostrarla.