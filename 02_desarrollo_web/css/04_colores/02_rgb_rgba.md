# RGB

igual que el hexadecimal utiliza los colores Rojo, Verde y Azul solo que debemos usar una funcion que informara que color deseamos.

## RGB %

con esta opcion indicamos el porcentaje que le damos a cada color de 0 a 100%, debemos usar la funcion rgb para convertir estos porcentajes en el color deseado, su sintaxis es **rgb(rrr%,ggg%,bbb%)**.

Ejemplo:
```css
p{
    color:rgb(100%,0%,80%);
} 
```
## RGB Absoluto

El rgb absoluto toma el metodo rgb pero de vez de usar porcentajes usamos valores de 0 a 255 para definir el valor de cada color rgb, su sintaxis es **rgb(rrr,ggg,bbb)**

Ejemplo:
```css
p{
    color:rgb(255,0,200);
} 
```

## rgba

con esta funcion podemos indicar la transparencias del color que va de 0 a 1, donde 0 es lo mas transparente mientras 1 es lo mas fuerte posible.

Ejemplo:
```css
p{
    color:rgba(255,0,200,0.8);
} 
```