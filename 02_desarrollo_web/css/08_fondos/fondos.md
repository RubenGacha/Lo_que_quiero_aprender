# Fondos


## color
La primera forma de establecer un fondo es darle un color con la propiedad **background-color**

Ejemplo:
```css
p{
    background-color:hsl(195,100%,50%)
} 
```

## imagenes

la segunda forma es colocar una imagene como fondo con la propiedad **background-image**

Ejemplo:
```css
p{
    background-image:url("ruta_imagen");
} 
```

## repetir una imagene

para poder repetir una imagen en el fondo se usa la propiedad **background-repeat** que tiene varios valores:

+ inherit
+ initial
+ no-repeat: no repite la imagen 
+ repeat: por default se tiene este valor que repite la imagen tanto en x como en y
+ repeat-x: repite la imagen horizontalmente
+ repeat-y: repite la imagen verticalmente
+ round:
+ space:
+ unset:

## posicionar el fondo

podemos posicionar el fondo usando la propiedad **background-position** que nos permitira mover el fondo.

Ejemplo:
```css
p{
    background-position:left top;
} 
```

## movimiento

podemos hacer que el fondo no se mueva mientras la pagina se esta moviendo usando la propiedad **background-attachment** 
+ scroll
+ fixed

Ejemplo:
```css
p{
    background-attachment:fixed;
} 
```