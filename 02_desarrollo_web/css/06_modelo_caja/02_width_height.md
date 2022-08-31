# propiedades width y height

lo primero que tenemos que tener presente es que la propiedad width y height, no son aplicables en los elementos de linea ya que estos no contienen medidas, el tamaño lo da su contenido. 

por lo tanto podemos intentar darle valores de width y height a un elemento de linea pero no se aplicaran.

Ejemplo:

```css
.block{
    background-color:purple;
    width:200px;
    height:200px;
}

.inline{
    background-color:lightcoral;
    width:200px;
    height:200px;
}
```

## maximos
tanto para height como para width podemos indicarle el tamaño maximo que podran tener para que cuando se ajuste el navegador estos puedan adaptarse si se llega a un punto mas bajo que el maximo del elemento. 

los valores que admiten pueden ser en pixeles o en porcentaje.

Ejemplo:

```css
.block{
    max-width:80%;
    max-height:200px;
}
```

## minimos

tambien podemos especificar que nuestra caja no puede ser mas pequeña que lo que le indiquemos con la propiedad min

Ejemplo:

```css
.block{
    min-width:80%;
    min-height:200px;
}
```