# Ejercicios Integrados: Funciones, Matrices y Operadores Lógicos

Estos ejercicios combinan los temas de los módulos **08 (Funciones)**, **09 (Matrices)** y **10 (Operadores Lógicos)**.  
Están organizados en tres niveles: Básico, Intermedio y Avanzado.

---

## Nivel 1 – Básico


---

### Ejercicio 1 – Mi primera función

Crea una función llamada `saludar(nombre)` que reciba un nombre como parámetro e imprima:

```
¡Hola, [nombre]! Bienvenido/a al curso.
```

**Ejemplo de uso:**
```python
saludar("Camila")
# ¡Hola, Camila! Bienvenido/a al curso.
```

---

### Ejercicio 2 – Función con retorno

Crea una función llamada `doblar(n)` que reciba un número y **retorne** el doble de ese número.

**Ejemplo de uso:**
```python
resultado = doblar(5)
print(resultado)  # 10
```

> **Recuerda:** `return` devuelve el valor; `print` solo lo muestra en pantalla.

---

### Ejercicio 3 – ¿Es par?

Crea una función llamada `es_par(n)` que retorne `True` si el número es par, o `False` si es impar.

**Ejemplo de uso:**
```python
print(es_par(4))   # True
print(es_par(7))   # False
```

---

### Ejercicio 4 – Mi primera matriz

Crea una matriz 3x3 con los números del 1 al 9 (organízalos como quieras).  
Luego imprime:
- El elemento de la primera fila, segunda columna.
- El elemento de la tercera fila, primera columna.

```python
matriz = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]
# Imprime matriz[0][1] y matriz[2][0]
```

---

### Ejercicio 5 – Imprimir una matriz

Dada la siguiente matriz, usa un doble `for` para imprimir todos sus elementos uno por uno:

```python
tablero = [
    [0, 0, 0],
    [0, 1, 0],
    [0, 0, 0]
]
```

**Salida esperada:**
```
0
0
0
0
1
0
0
0
0
```

---

### Ejercicio 6 – Operadores lógicos simples

Declara dos variables: `tiene_entrada = True` y `es_mayor_de_edad = False`.  
Imprime el resultado de las siguientes expresiones **antes de ejecutarlas**, prediciendo el resultado:

```python
print(tiene_entrada and es_mayor_de_edad)
print(tiene_entrada or es_mayor_de_edad)
print(not es_mayor_de_edad)
```

---

### Ejercicio 7 – ¿Puede votar?

Pide al usuario su edad con `input()`. Luego, usando un operador lógico, determina si puede votar.  
La condición es: tener **18 años o más**.

```
Ingresa tu edad: 17
No puedes votar todavía.

Ingresa tu edad: 20
¡Puedes votar!
```

---

## Nivel 2 – Intermedio

> Para quienes ya dominan lo básico. Los ejercicios combinan dos temas a la vez.

---

### Ejercicio 8 – Función: el mayor de dos

Crea una función llamada `mayor(a, b)` que reciba dos números y retorne el mayor de ellos.  
Si son iguales, retorna cualquiera.

**Ejemplo de uso:**
```python
print(mayor(10, 25))  # 25
print(mayor(8, 3))    # 8
```

---

### Ejercicio 9 – Suma de una fila

Crea una función llamada `suma_fila(matriz, fila)` que reciba una matriz y un número de fila,  
y retorne la **suma de todos los elementos** de esa fila.

**Ejemplo de uso:**
```python
m = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]
print(suma_fila(m, 0))  # 6
print(suma_fila(m, 2))  # 24
```

---

### Ejercicio 10 – ¿Está en rango?

Crea una función llamada `en_rango(n, minimo, maximo)` que retorne `True` si `n` está entre `minimo` y `maximo` (inclusive), o `False` si no.  
Usa el operador `and`.

**Ejemplo de uso:**
```python
print(en_rango(5, 1, 10))   # True
print(en_rango(15, 1, 10))  # False
print(en_rango(1, 1, 10))   # True
```

---

### Ejercicio 11 – Buscar un valor en la matriz

Crea una función llamada `buscar(matriz, valor)` que retorne `True` si el valor existe en la matriz, o `False` si no.

**Ejemplo de uso:**
```python
m = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]
print(buscar(m, 5))   # True
print(buscar(m, 10))  # False
```

---

### Ejercicio 12 – Clasificar por edad

Crea una función llamada `clasificar(edad)` que retorne una cadena según la edad:

| Condición | Retorna |
|-----------|---------|
| Menor de 13 | `"niño/a"` |
| Entre 13 y 17 | `"adolescente"` |
| Entre 18 y 64 | `"adulto/a"` |
| 65 o más | `"adulto/a mayor"` |

Usa `and` y `or` según corresponda.

**Ejemplo de uso:**
```python
print(clasificar(10))   # niño/a
print(clasificar(16))   # adolescente
print(clasificar(30))   # adulto/a
print(clasificar(70))   # adulto/a mayor
```

---

### Ejercicio 13 – Diagonal de una matriz

Dada una matriz cuadrada (3x3), crea una función `diagonal(matriz)` que retorne una lista con los elementos de la **diagonal principal** (es decir, los elementos donde el índice de fila y columna son iguales).

**Ejemplo:**
```python
m = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]
print(diagonal(m))  # [1, 5, 9]
```

---

## Nivel 3 – Avanzado

> Para quienes quieren un desafío mayor. Los ejercicios combinan los tres temas.

---

### Ejercicio 14 – Máximo de la matriz

Crea una función llamada `maximo_matriz(matriz)` que recorra la matriz y retorne el **valor más alto** que encuentre.  
No uses la función `max()` de Python; recórrela manualmente.

**Ejemplo de uso:**
```python
m = [
    [3, 7, 2],
    [9, 1, 5],
    [4, 6, 8]
]
print(maximo_matriz(m))  # 9
```

---

### Ejercicio 15 – ¿Toda la fila es positiva?

Crea una función llamada `fila_positiva(matriz, fila)` que retorne `True` si **todos los elementos** de esa fila son mayores que cero, o `False` si hay al menos uno que no lo es.

**Ejemplo de uso:**
```python
m = [
    [1, 2, 3],
    [-1, 5, 6],
    [7, 8, 9]
]
print(fila_positiva(m, 0))  # True
print(fila_positiva(m, 1))  # False
```

> **Pista:** puedes usar una variable booleana que empiece en `True` y se cambie a `False` si encuentras un negativo, o bien usar `and` dentro del loop.

---

### Ejercicio 16 – Cachipún contra la CPU

Crea un programa con las siguientes funciones:

1. `cpu_juega()`: retorna aleatoriamente `"piedra"`, `"papel"` o `"tijera"`.  
   *(Puedes usar `import random` y `random.choice([...])`)*

2. `determinar_ganador(jugador, cpu)`: recibe las jugadas y retorna `"jugador"`, `"cpu"` o `"empate"` según las reglas del juego.  
   Usa operadores lógicos (`and`, `or`) para construir las condiciones.

3. Un bloque principal que pida la jugada al usuario, llame a ambas funciones e imprima el resultado.

**Reglas:**
- Piedra gana a Tijera
- Tijera gana a Papel
- Papel gana a Piedra

**Ejemplo de salida:**
```
Elige (piedra / papel / tijera): piedra
La CPU eligió: tijera
¡Ganaste!
```

---

### Ejercicio 17 – Promedio por fila

Crea una función `promedios(matriz)` que retorne una **lista con el promedio de cada fila** de la matriz.

**Ejemplo de uso:**
```python
m = [
    [10, 20, 30],
    [4, 8, 12],
    [5, 5, 5]
]
print(promedios(m))  # [20.0, 8.0, 5.0]
```

---

### Ejercicio 18 – Desafío final: Validador de notas

Crea un programa que:

1. Tenga una función `ingresar_notas(filas, columnas)` que pida notas al usuario y las guarde en una matriz de tamaño `filas x columnas`. Cada nota debe estar **entre 1.0 y 7.0** (usa un operador lógico para validar).

2. Tenga una función `estado(promedio)` que retorne:
   - `"Aprobado"` si el promedio es **4.0 o más**
   - `"Reprobado"` si el promedio es **menor que 4.0**

3. Tenga una función `reporte(matriz)` que, para cada fila (estudiante), calcule su promedio e imprima su estado.

**Ejemplo de salida (matriz 3x2):**
```
Ingresa nota [0][0]: 5.5
Ingresa nota [0][1]: 6.0
Ingresa nota [1][0]: 3.0
Ingresa nota [1][1]: 2.5
Ingresa nota [2][0]: 4.0
Ingresa nota [2][1]: 4.5

Estudiante 1: promedio 5.75 → Aprobado
Estudiante 2: promedio 2.75 → Reprobado
Estudiante 3: promedio 4.25 → Aprobado
```

---

