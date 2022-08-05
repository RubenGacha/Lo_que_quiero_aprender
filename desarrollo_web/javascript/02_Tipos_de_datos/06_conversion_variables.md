# conversion de tipos de datos

En algunos casos tendremos numero que son tratados como texto y para poder operarlos como numeros tendremos que hacer una conversion de tipo de string a numeric para esto usamos la funcion **Number**.

Ejemplo:

```js
let miEdad="30"
let edad=Number(miEdad)

typeof edad //debe ser number
```
## Funcion isNaN

lo que sucede en muchos casos es que el string que queremos convertir a numero no es un numero y la conversion devuelve **NaN** (Not a Number), por lo tanto debemos validar que nos devuelva un numero la conversion para esto usamos la **funcion** ***isNaN***.

Ejemplo:

```js
let miEdad="treinta"
let edad=Number(miEdad)

if(isNaN(edad)){
    console.log("No es un numero")
}else{
    console.log("Realizar las operaciones con edad")
}
```
