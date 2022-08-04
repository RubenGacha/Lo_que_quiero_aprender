# Manejo de string

## Concatenacion

En muchos casos nos vemos obligados a unir strings ya sea para personalizar un respues o para formatear un texto en javascript la forma facil de hacerlo es usando el simbolo del mas.

Ejemplo:

```javascript
var nombre="ruben"
var apellido="gacha"
var nombreCompleto=nombre + " " + apellido
```

con javascript se puede directamente concatenar numeros con string sin ocasionar ningun tipo de error ya que javascript convierte todo a string para poder concatenarlo. 

aunque si se concatena con numeros toca tener presente el orden ya que puede darnos resultados que no queremos ya que puede realizar la operacion si encuentra primero los numeros antes del string

```javascript
var var_1=1+2+"ruben" //devuelve 3ruben
var var_2="ruben"+1+2 //devuelve ruben12
var var_3="ruben"+(1+2) //devuelve ruben3


/*
una forma de que se concatenen los numeros cuando se inicia la expresion con numeros es colocando una cadena vacia al inicio.
*/
var var_4=""+1+2+"ruben" //devuelve 12ruben
```