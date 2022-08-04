# Uso de var, let o const

En todos los lenguajes existen variables que son contenedores de informacion que ira cambiando dependiendo al algoritmo ejemplo el contador de vidas de un juego este puede aumentar o disminuir dependiendo a ciertas sircunstancias. 

## variables globales no declaradas

en javascript se puede crear una variable dando un nombre a la variable seguido del signo igual y luego el valor que queremos que almacene.

Ejemplo
```javascript
vidas=3
```
## variables declaradas con var

## variables declaradas con let

## constantes declaradas con const

En algunos casos necesitamos que una variable no cambie su valor durante la ejecucion del algoritmo para esto se usan las constantes y para poder indicarle a javascript que queremos que la variable la trate como constante debemos decirle al momento de crear la variable, poniendo la palabra reservada **const** seguido del nombre de la variable, el simbolo igual y por ultimo el valor de la constante.

Ejemplo:

```javascript
const nombre="ruben"
```

## Declaracion de multiples variables

se puede declarar multiples variables en una sola linea separando cada variable con una coma.

```javascript
var nombre="ruben" , apellido="gacha", x, y
```