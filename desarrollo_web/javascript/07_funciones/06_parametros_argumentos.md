# Parametros y Argumentos

la gran diferencia entre parametros y argumentos es que cuando hablamos de parametros nos referimos a la variables que son necesarias para que la funcion pueda hacer su labor. 

mientras cuando hablamos de argumentos hablamos del valor final que se le pasa a la funcion. 

Ejemplo.

```javascript
//a y b son los parametros
function miFuncion(a,b) {
    console.log(a+b);
}

//4 y 5 son los argumentos dentro de la funcion
miFuncion(4,5);
```

Aunque en forma cotidiana no se hace la diferencia sino la tratamos como si fuera lo mismo.

## Parametros Opcionales

en algunos casos deseamos que nuestras funciones tengan parametros opcionales lo que permite invocarlas sin pasarle todos los argumentos, para esto se les da un valor por defecto al momento de crear la funcion. 

Ejemplo:

```javascript
const sumar=function(a=5,b=3){
    console.log(arguments[0]);
    console.log(arguments[1]);

    console.log(a+b);
}

//al no pasar los argumentos en la funcion estos quedan como undefined pero como tienen valores por defecto la funcion puede hacer su trabajo. 
resultado=sumar();

```

## cantidad de argumentos

En javascript los parametros y los argumentos pueden no tener la misma cantidad dentro de la funcion se puede acceder a estos con el array **arguments**

```javascript
const sumar=function(a=5,b=3){
    console.log(arguments[0]);
    console.log(arguments[1]);
    console.log(arguments[2]);
    console.log(a+b);
}

resultado=sumar(1,2,3,4);

```