## Estructuras de datos

### Terminología

* `s`: Estructura
* `x`: Elemento
* `i`: Índice
* `k`: Llave
* `v`: Valor
* `type`: Tipo de dato
* `val`: Paso por valor
* `ref`: Paso por referencia
* `--`: No soportado

### Listas / Arrays

#### Métodos y atributos
Operación | Python | Javascript | C++
--- | --- | --- | ---
Crear vacío| `s = []` | `s = []` | `<type> s[size];` 
Leer elemento | `s[i]` | `s[i]`|  `s[i];`
Cambiar elemento | `s[i] = x`| `s[i] = x`| `s[i] = x;` 
Agregar elemento al final | `s.append(x)` | `s.push(x)` | --
Agregar elemento al principio | `s.insert(0, x)`| `s.unshift(x)`| --
Agregar elemento por índice | `s.insert(i, x)` | --| --
Eliminar elemento al final | `s.pop()` | `s.pop()`| --
Eliminar elemento al principio | `s.pop(0)`| `s.shift()`| --
Eliminar elemento por índice | `s.pop(i)`| -- | --
Obtener índice de un elemento | `s.index(x)`| `s.indexOf(x)`| --
Tamaño | len(s)| |

#### Características
Característica | Python | Javascript | C++
--- | --- | --- | ---
Paso de argumento | ref | ref | ref
Soporta índice negativo | ✔️ | ✔️ | X

### Diccionarios

#### Métodos y atributos
Operación | Python | Javascript | C++
--- | --- | --- | ---
Crear vacío | `s = {}`| `s = {}`| `map<type k,type v> s;`
Leer valor de llave | `s[k]`| `s[k]`| `s[k];`
Añadir(Actualizar) llave / valor | `s[k] = v`| `s[k] = v`| `s[k] = v;`
Eliminar llave | `s.pop(k)`|    | `s.erase(k);`
Tamaño (Cantidad de llaves) | len(s)| |

#### Características
Característica | Python | Javascript | C++
--- | --- | --- | ---
Paso de argumento | ref | ref | ref
Soporta multitipo de llaves o valores | ✔️ | ✔️ | X

### Sets
#### Métodos y atributos
Operación | Python | Javascript | C++
--- | --- | --- | ---
Crear vacío | `s = set()` | | `set<type> s;`
Añadir | `s.add(x)`| | `s.insert(x);`
Eliminar | | | `s.erase(x);`
Verificar existencia | `x in s`| `s.has(x)`| `s.count(x) != 0;`
Verificar inexistencia | `x not in s`| `!s.has(x)`| `s.count(x) == 0;`
Contar ocurrencias | --| --| `s.count(x);`
Tamaño | `len(s)`| | `s.size();`

#### Características
Característica | Python | Javascript | C++
--- | --- | --- | ---
Paso de argumento | ref | ref | ref
Unicidad de elementos | ✔️ | ✔️ | X
