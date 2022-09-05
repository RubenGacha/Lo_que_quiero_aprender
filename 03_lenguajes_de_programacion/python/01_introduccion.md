# Introduccion

1. Fue creado por Guido van Rossum a comienzos de los 90.
2. lenguaje de alto nivel con una gramatica sencilla, clara y muy legible.
3. tipado dinamico y fuerte
4. orientado a objetos
5. codigo open Source
6. multiplataforma
7. interpretado
8. multiproposito
9. multiparadigma
10. multihilo
11. case sensitive

## Estructura base

python no tiene una estructura base se puede iniciar en cualquier editor de texto teniendo en cuenta que debe tener extension .py el archivo que creamos con el codigo y el programa python para poder interpretarlo.

En una consola o terminal podemos ejecutar nuestro codigo de la siguiente forma.

```python
python Nombre_archivo.py
```

## Variables, comentarios y Constantes

En Phyton solo se tiene que dar un nombre a la variable que normalmente se usa el estilo lowercamelcase. por otro lado si se desea saber el tipo de dato de estas variables se usa **type()**

cuando escribes el nombre de una variable en mayuscula podemos suponer que es una constante. por buenas practicas.

las triples comillas pueden permitir comentarios de varias lineas, y el simbolo numeral permite comentarios de una linea

```python
'''
comentario de varias lineas
'''

nombre="ruben" #variable de tipo string
edad=30 #variable de tipo numerico

texto="""cuando se quiere escribir un texto
de multiples lineas en una variable
se debe usar 3 veces comillas dobles.
"""

FIJO="mueres" #constante

print(type(nombre))
print(type(edad))
print(type(texto))

```

## Tipos de datos primitivos en python

En python existe cuatro tipos de datos primitivos:

1. **Numeros enteros**: int()
2. **Numeros de punto flotante**: float()
3. **Texto (cadenas de caracteres)**: str()
4. **Booleanos (True y False)** bool() 

En python debe ser en mayuscula la primera letra para que tome el valor booleano.

## Entrada y salida en consola

se tiene una entrada que ingresa el valor siempre como texto que es **input()** y una salida que es **print()** aunque este ultimo tiene varios formatos.

```python
nombreVariable=input("Escribe tu nombre") #entrada

print("hola mundo") #escribe en consola hola mundo

#escribe en consola hola mundo pero al finalizar no da enter sino lo que se especifique en end.
print("hola mundo",end="")

#formatea el texto permitiendo el ingreso del valor de la variable
print(f"hola {nombreVariable}") 

print("el valor de la variable es {} ".format(variable))

#escapa el carracte \ para que no lo interprete como caracter especial.
print(r"C:\algun\nombre") 

#en python print permite imprimir datos separados por comas
print(variable, "algo", variable)

```

## Conversion de datos

Para pasar de un tipo a otro solo se debe usar la case del tipo de valor primitivo y este cambiara su tipo se debe recordar que la conversion sea logica ya que "a" no puede convertirse en un numero.

|comando|descripcion|
|---|---|
|int("10")|Convertir el string numerico en numero|
|float("10.8")|Convertir el string numerico en numero flotante|
|str(1)|Convertir un valor numerico a string|
|bin(10)|Convierte un valor decimal a binario|
|hex(10)|Convierte un valor decimal a hexadecimal|
|int("0b1010",2)|Convierte un valor binario a decimal|
|int("0xa",16)|Convierte un valor hexadecimal a decimal|
|abs(-10)|muestra el valor absoluto de un numero|
|round(5.5)|redondea un numero a entero|
|round(15.565485484,2)|redondea un numero y le deja dos decimales|

```python
numero="5.4"
int(numero)
float(numero)
str(numero)
bool(0) #bool convierte solo 0 y 1 a false a true
```

## Otros tipos numericos

1. Decimal
2. Fraction
3. Complejos usando j como la parte imaginaria: 3+4j

## Convencion en los nombres

tanto en funciones como nombre de variables se crean en minuscula y se separan las palabras con _, mientras que en la clase las palabras van juntas y cada palabra inicia en mayuscula.

```python

mi_variable=1

def mi_funcion():
    pass

class MiClase:
    pass
