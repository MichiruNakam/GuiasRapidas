## Hacer console.log a objetos en un instante dado

Cuando uno llama a `console.log(objeto)` se toma la referencia del objeto, por lo que si este objeto es modificado posteriormente,
estos cambios también se verán reflejados en la consola. 

Para hacer un log del objeto en un instante dado se puede hacer:

  `console.log(JSON.parse(JSON.stringify(objeto)));`

`JSON.stringify` retorna un string serializado del objeto.

`JSON.parse` retorna un objeto en base a un string serializado.

