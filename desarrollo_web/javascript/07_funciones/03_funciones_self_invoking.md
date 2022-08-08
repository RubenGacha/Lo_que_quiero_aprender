# Funciones de tipo self invoking

Este tipo de funciones se invocan a si mismas, y solo se pueden usar una vez ya que no tienen nombre para ser llamadas de nuevo.

para crear esta funcion se debe encerrar entre parentesis ya que cuando se finaliza se colocan otros parentesis para indicar que es una funcion y se pasaran los parametros que usa la funcion. 

Ejemplo:

```javascript
//sin parametros
(function(){
    console.log("Ejecutando la funcion")
})();

//con parametros
(function(a,b){
    console.log(`suma: ${a+b}`)
})(4,5);
```
