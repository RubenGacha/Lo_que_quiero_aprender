# Comandos basicos de git


## Iniciando git

Lo primero que debemos hacer es ejecutar un comando en la raiz del proyecto que nos permitira iniciar el seguimiento de nuestros archivos, para esto el comando crea dos areas una de ensayo y la otra local. con lo que despues de ejecutar el comando tendremos 3 area.

1. primer area: es el area que tiene todos los archivos los que tienen seguimiento y los que no.
2. segunda area: es el area de ensayo y aqui estan los archivos que tienen seguimiento.
3. tercera area: es el area local donde se encuentran las instantaneas de los archivos que se estan monitoreando.

Comando:
```git
git init
```

## Estatus de los documentos que seguimos

Algo que nos podemos preguntar es como saber cuales archivos tienen seguimiento y cuales no para esto tenemos el siguiente comando.

Comando:
```git
git status -s
```

donde nos muestran cuatro posibles resultados por archivo que no este monitoreado o no se ubiese guardado cambios en git.


