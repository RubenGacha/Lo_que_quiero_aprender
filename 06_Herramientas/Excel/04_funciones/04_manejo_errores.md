# manejo de errores


## agregar

En ciertas ocaciones queremos ignorar errores que estan en una fila o columna y aun asi realizar alguna funcion excel tiene la funcion `agregar` que nos permitiria omitir algunos valores y aun asi usar alguna funcion que ya tiene programada. 

la sintaxis es:
+ `=agregar(codigo_funcion;codigo_valor_omitir;rango)` ejemplo `=agregar(9;6;g2:g40)`

## si.error 

Esta funcion nos permite evaluar si hay un error y que hacer cuando exista y que hacer cuando no hay un error se suele usar cuando se formula para un usuario que no sabe mucho excel o para que no se vean los errores por datos mal puestos.

su sintaxis es:

+ `=si.error(parte_funcional;parte_cuando_hay_error)`

