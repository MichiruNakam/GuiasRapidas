# Resumen
Lenguaje de programación de alto nivel.
# Listas
### Crear lista vacía
`l = []`
### Agregar elemento
`l.append(x)`
### Obtener último elemento
`l[-1]` ó `l[len(l) - 1]`
# Stack
`stack = [] #Crear`

`stack.append(x) #Push`

`stack.pop() #Pop (retorna el objeto)`
# Queue
`queue = [] #Crear`

`queue.append(x) #Enqueue`

`queue.popleft() #Dequeue (retorna el objeto)`
# Diccionarios
### Crear diccionario vacío
`d = {}`
### Agregar elemento
`d[key] = value`
### Iterar sobre diccionario
`for key, value in d.items():`
# Funciones
### Expandir lista a argumentos
`foo(*l)` es equivalente a `foo(l[0], l[1], ...)`
### Map: Aplicar función a cada elemento de una lista

`def foo(a): return a + 5`

`l = [1, 2, 3]`

`result = map(foo, l)`

`print(list(result))`

>[6, 7, 8]

### Reduce: Aplicar función a todos los elementos de una lista
`from functools import reduce`

`def foo(a, b): return a + b`

`l = [1, 2, 3] `

`print(reduce(foo, l))`

> 6
