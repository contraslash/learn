+++
date = "2018-01-18T22:49:05-05:00"
title = "03 Condicionales"
type = "post"

+++

# Estructuras de decisión

Las estructuras de decisión son bloques de código que se ejecutan en función del valor de verdad de una sentencia.

Las estructuras de decisión mas comunes son las de tipo IF-THEN, IF-THEN-ELSE y SWITCH-CASE

* IF-THEN

  Esta estructura de código es muy usada para la ejecución exclusiva de un bloque de código si ocurre una condición. Es por definición la estructura de decisión mas simple. Python usa la palabra reservada `if` para realizar estas acciones

  ```python
  if x:
      print("Hola")  
  ```
* IF-THEN-ELSE

  Aumentando la semántica del lenguaje, tenemos situaciones donde además de ejecutar una acción en función de otra, si no ocurre, debemos ejecutar otro conjunto de acciones. Python nos permite realizar eso con la palabra reservada `else`
  
  ```python
  if x:
      print("Hola")
  else:
      print("Adios")
  ```

  La estructura sintáctica de `else` solo se permite una vez, después y bajo el mismo bloque de identación del `if`

* SWITCH-CASE

  Por último, las estructuras condicionales complejas, donde se ejecutan bloques de código en estructuras n-arias pueden implementarse en python utilizando la palabra reservada `elif`
  
  ```python
  if x == 1:
      print("Hola")
  elif x == 2:
      print("Adios")
  elif x == 3:
      print("Hasta luego")
  else:
      print("Buena vida")
  ```
  
  El uso de `elif` está condicionado a la existencia de un `if` anterior, seguido de uno o mas `elif` y la presencia o no de un único `else`