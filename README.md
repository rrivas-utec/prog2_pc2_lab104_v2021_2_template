# PC2: Práctica Calificada 2
**course:** Programación II  
**unit:** 3, 4 y 5  
**cmake project:** prog2_pc2_lab104_v2021_2

## Indicaciones Específicas
- El tiempo límite para la evaluación es 100 minutos.
- Cada pregunta deberá ser respondida en un archivo fuente (`.cpp`) y un archivo cabecera (`.h`) con el número de la pregunta:
    - `p1.cpp, p1.h`
    - `p2.cpp, p2.h`
    - `p3.cpp, p3.h`
- Deberás subir estos archivos directamente a [www.gradescope.com](https://www.gradescope.com) o se puede crear un `.zip` que contenga todos ellos y subirlo.

## Competencias
- Para los alumnos de la carrera de Ciencia de la Computación
    - Aplica conocimientos de computación apropiados para la solución de problemas definidos y sus requerimientos en la disciplina del programa.(nivel 2)
    - Diseña, implementa y evalúa soluciones a problemas complejos de computación.(nivel 2)
    - Crea, selecciona, adapta y aplica técnicas, recursos y herramientas modernas para la práctica de la computación y comprende sus limitaciones.(nivel 2)

- Para los alumnos de las carreras de Ingeniería
    - Capacidad para aplicar conocimientos de matemática.(nivel 2)
    - Capacidad para diseñar un sistema, un componente o un proceso para satisfacer las necesidades deseadas dentro de restricciones realistas(nivel 2)

### Pregunta #1 - Sumas de filas y columnas opuestas (7 points)

Escribir un programa que utilizando matrices y arreglos dinámicos, lea desde el teclado una matriz de números enteros de tamaño `n x n`, que calcule el producto de cada fila, almacenado los resultados en un arreglo de tamaño `n`, de igual modo realizar el mismo cálculo con las columnas, almacenado también los resultados en un arreglo de tamaño `n`.

Finalmente, el programa debe imprimir la suma de los valores en las posiciones opuestas de los arreglos generados (primera fila + última columna, segunda fila + penúltima columna, ..., última fila + primera columna).

**Ejemplo #1**
#### Input Format
```cpp
3
2 2 2
3 3 3
4 2 1
```

#### Constraints
```cpp
No se requiere textos al ingresar valores (std::cout)
```

#### Output Format
```cpp
48 324 192
```

**Ejemplo #2**
#### Input Format
```cpp
2
1 1
4 3
```
#### Output Format
```cpp
3 48
```

### Pregunta #2 - Multiplicación del resto (6 points)

Escribir un programa que utilizando vectores, lea desde el teclado un vector de números enteros de tamaño `n`, que reemplace cada valor con el producto del resto de los otros números y muestre los nuevos valores del vector.

**Ejemplo #1**
#### Input Format
```cpp
6
2 3 1 2 3 4
```

#### Constraints
```cpp
No se requiere textos al ingresar valores (std::cout)
```

#### Output Format
```cpp
72 48 144 72 48 36
```

**Ejemplo #2**
#### Input Format
```cpp
4
1 1 2 2
```
#### Output Format
```cpp
4 4 2 2
```

### Pregunta #3 - Suma de Fuerzas (7 points)

La fuerza en planos cartesianos de 3 dimensiones se representa por tres componentes de la forma: `F = (ai + bj + ck)` donde `a` es el componente en el eje `x`, `b` es el componente de la fuerza en el eje `y` y `c` es el componente de la fuerza en el eje `z`.  
Definir una clase que represente una fuerza `class fuerza_t` y escribir un programa que permita generar un vector de fuerzas de tamaño `n` que lea desde el teclado los 3 componentes para cada uno de los `n` fuerzas.
El programa deberá ordenar las fuerzas de menor magnitud a mayor magnitud y generar de ese vector ordenado una nueva fuerza resultante de la suma de las `n/2` primeras fuerzas.

**Ejemplo #1**
#### Input Format
```cpp
5
2 3 4
4 3 1
7 2 5
1 2 3
4 5 3
```

#### Constraints
```cpp
No se requiere textos al ingresar valores (std::cout)
```

#### Output Format
```cpp
(5.00i 5.00j 4.00k)
```

**Ejemplo #2**
#### Input Format
```cpp
6
10 5 4
1 1 2
2 2 2
3 4 6
2 1 3
8 5 1
```
#### Output Format
```cpp
(5.00i 4.00j 7.00k)
```
