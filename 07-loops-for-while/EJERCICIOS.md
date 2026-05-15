# 07 – Ejercicios: Bucles `for` y `while` en Python

> Para resolver estos ejercicios utilizarás todo lo aprendido hasta ahora:
> variables, `input()`, `print()`, operadores matemáticos, condicionales, y bucles `for` / `while`.

---

## 🟢 Nivel Básico

### Ejercicio 1 – Contar del 1 al 10
Usando un bucle `for`, muestra en pantalla los números del **1 al 10**, uno por línea.

**Ejemplo de salida:**
```
1
2
3
...
10
```

---

### Ejercicio 2 – Tabla de multiplicar
Pide al usuario un número entero.  
Muestra su **tabla de multiplicar** del 1 al 10 usando un bucle `for`.

**Ejemplo de salida:**
```
Ingresa un número: 5
5 x 1 = 5
5 x 2 = 10
...
5 x 10 = 50
```

---

### Ejercicio 3 – Suma de números
Pide al usuario un número entero `n`.  
Calcula y muestra la **suma de todos los números del 1 hasta n** usando un bucle.

> Pista: inicializa una variable `total = 0` antes del bucle y ve sumando dentro de él.

**Ejemplo de salida:**
```
Ingresa un número: 5
La suma del 1 al 5 es: 15
```

---

### Ejercicio 4 – Contar hacia atrás
Pide al usuario un número entero positivo.  
Muestra una cuenta regresiva desde ese número hasta **0**, usando un bucle `while`.

**Ejemplo de salida:**
```
Ingresa un número: 5
5
4
3
2
1
0
¡Despegue!
```

---

## 🟡 Nivel Intermedio

### Ejercicio 5 – Adivina el número
El programa elige un número fijo (por ejemplo, `secreto = 7`).  
Pide al usuario que lo adivine usando un bucle `while`.  
El bucle termina cuando el usuario acierta.  
Muestra cuántos intentos necesitó.

**Ejemplo de salida:**
```
Adivina el número (entre 1 y 10): 3
Incorrecto. Intenta de nuevo.
Adivina el número (entre 1 y 10): 9
Incorrecto. Intenta de nuevo.
Adivina el número (entre 1 y 10): 7
¡Correcto! Lo adivinaste en 3 intentos.
```

---

### Ejercicio 6 – Números pares e impares
Pide al usuario un número entero `n`.  
Usando un bucle `for`, muestra por separado los **números pares** y los **números impares** del 1 al `n`.

**Ejemplo de salida:**
```
Ingresa un número: 10
Pares: 2, 4, 6, 8, 10
Impares: 1, 3, 5, 7, 9
```

---

### Ejercicio 7 – Factorial
Pide al usuario un número entero positivo `n`.  
Calcula su **factorial** usando un bucle.

$$n! = 1 \times 2 \times 3 \times \ldots \times n$$

**Ejemplo de salida:**
```
Ingresa un número: 5
El factorial de 5 es: 120
```

---

### Ejercicio 8 – Menú con while
Crea un programa con un menú de opciones que se repita usando un bucle `while`  
hasta que el usuario elija **salir**.

Las opciones pueden ser:
1. Saludar
2. Mostrar la fecha actual
3. Salir

> Usa condicionales dentro del bucle para responder a cada opción.

**Ejemplo de salida:**
```
=== MENÚ ===
1. Saludar
2. Mostrar fecha
3. Salir
Elige una opción: 1
¡Hola! Bienvenido.

=== MENÚ ===
...
Elige una opción: 3
Hasta luego.
```

---

## 🔴 Nivel Difícil

### Ejercicio 9 – Pirámide de asteriscos
Pide al usuario un número entero `n`.  
Dibuja una **pirámide** de asteriscos de `n` filas usando bucles anidados.

**Ejemplo de salida con n = 5:**
```
*
**
***
****
*****
```

> Desafío extra: centra la pirámide usando espacios.

---

### Ejercicio 10 – Calculadora acumulativa
Crea una calculadora que sume números ingresados por el usuario en un bucle `while`.  
El bucle termina cuando el usuario escribe `"listo"`.  
Al final muestra la **suma total** y la **cantidad de números ingresados**.

**Ejemplo de salida:**
```
Ingresa un número (o escribe "listo" para terminar): 10
Ingresa un número (o escribe "listo" para terminar): 5
Ingresa un número (o escribe "listo" para terminar): 20
Ingresa un número (o escribe "listo" para terminar): listo

Números ingresados: 3
Suma total: 35
```

---

### Ejercicio 11 – FizzBuzz
Muestra los números del 1 al 100 pero con estas reglas:
- Si el número es divisible entre 3, muestra `"Fizz"`.
- Si es divisible entre 5, muestra `"Buzz"`.
- Si es divisible entre ambos, muestra `"FizzBuzz"`.
- Si no cumple ninguna condición, muestra el número.

**Ejemplo de salida (primeros):**
```
1
2
Fizz
4
Buzz
Fizz
7
...
```

> Este es uno de los ejercicios clásicos de entrevistas de programación.
