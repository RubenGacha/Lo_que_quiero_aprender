# Array
En javascript los array son estructuras de datos que pueden almacenar varios datos con las siguientes caracteristicas:

1. los arrays en javascript permiten guardar datos de diferente tipo.
2. los arrays en javascript son mutables pueden cambiar el tamaño. En otras palabras pueden almacenar mas o menos elementos.
3. se puede acceder al valor de un elemento dependiendo su posicion comenzando en 0
4. personalmente pienso que los array en javascript se comportan como listas de otros lenguajes.

```javascript
const array=["ruben",'dario',32,1.73]
console.log(array[1])
array[1]='gacha'
console.log(array[1])


//**********************forma antigua no usar 

let autos=new Array("bmw","volvo","toyota")

```
## Recomendaciones
1. se recomienda que se declare un array con la palabra clave reservada **const** ya que no se va a modificar la referencia en memoria del arreglo.
2. No se recomienda agregar un valor directamente por la posicion del array ya que esto puede crear muchos valores vacios.
3. Se deberia intentar mantener un solo tipo de dato en el array

## Propiedades
|Propiedades| Descripcion|
| --- | --- |
|.length| nos da la cantidad de elementos |

## Metodos
|Metodos| Descripcion|
| --- | --- |
|.push(elem)| agrega un elemento al array al ultimo |
|.unshift(elem)|agrega un elemento al inicio del array |
|.pop()| elimina el ultimo elemento del array |
|.shift()| elimina el primer elemento del array|
|.indexOf(elem) | busca un elemento dadonos la primera posicion sino lo encuentra devuelve -1|
|.lastIndexOf(elem) | busca un elemento dadonos la ultima posicion sino lo encuentra devuelve -1|
|.splice(posicion_inicio[,cantidad ,[, items ]])| Cambia el contenido de un array eliminando elementos existentes o agregando nuevos elementos.|
|.slice()| nos permite pasar los valores de un array para que sea copiado |
|.slice([inicio [, final]])| nos permite extraer elementos de un array desde la posicion inicio a posicion final sin tener encuenta el elemento de la posicion final |
|.reverse() | invierte el orden de los elementos |
|.join(separador) | une todo el array y nos devuelve un string sepearado por el separador|


Ejemplos:
```javascript
const array=["ruben",'dario',32,1.73]
array.push("gacha")
array.length

//se puede guardar los elementos que se eliminan en una variable
let itemEliminado=array.pop()
```


Ejemplos splice:
```javascript
const numeros=[1,2,3,4,5,6];

// elimina desde la posicion indicada hasta el final
numeros.splice(3);

//Elimina desde la posicion indicada la cantidad de datos del segundo parametro

numeros.splice(1,2);

//Eliminar desde la posicion dada, la cantidad de elementos dados y agrega los elementos que queramos insertar desde uno a x elementos.

numeros.splice(1,2,6,7,8,9,10);
numeros.splice(10,1,9);


//agregar elementos desde una posicion sin eliminar elementos, lo unico que se debe hacer es en cantidad colocar 0.
numeros.splice(1,0,6,7,8,9,10);
numeros.splice(10,0,9);

```

## Saber si una variables es un array

podemos usar el objeto array para validar si una variable es de tipo array o no

Ejemplo:

```javascript
const array=["ruben",'dario',32,1.73]

//forma 1
Array.isArray(array) // devuelve true

//forma 2

array instanceof Array // devuelve true
```

