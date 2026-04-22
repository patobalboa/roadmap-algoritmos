# 04 – Ejercicios: Condicionales en Python

> Para resolver estos ejercicios utilizarás todo lo aprendido hasta ahora:
> variables, `input()`, `print()`, operadores matemáticos y de comparación, y estructuras `if / elif / else`.

---

## 🟢 Nivel Básico

### Ejercicio 1 – Mayor o menor de edad
Pide al usuario que ingrese su edad.  
Muestra un mensaje indicando si es **mayor de edad** (18 o más) o **menor de edad**.

**Ejemplo de salida:**
```
Ingresa tu edad: 15
Eres menor de edad.
```

---

### Ejercicio 2 – Número positivo, negativo o cero
Pide al usuario un número entero.  
Muestra si el número es **positivo**, **negativo** o **cero**.

**Ejemplo de salida:**
```
Ingresa un número: -7
El número es negativo.
```

---

### Ejercicio 3 – Par o impar
Pide al usuario un número entero.  
Indica si el número es **par** o **impar**.

> Pista: usa el operador módulo `%`. Si `numero % 2 == 0` el número es par.

**Ejemplo de salida:**
```
Ingresa un número: 4
El número 4 es par.
```

---

### Ejercicio 4 – Contraseña correcta
Define una variable con una contraseña secreta (por ejemplo `"python123"`).  
Pide al usuario que ingrese la contraseña.  
Muestra `"Acceso concedido"` si es correcta o `"Acceso denegado"` si no lo es.

**Ejemplo de salida:**
```
Ingresa la contraseña: python123
Acceso concedido.
```

---

## 🟡 Nivel Intermedio

### Ejercicio 5 – Calificación con letra
Pide al usuario su calificación numérica (de 0 a 100).  
Muestra la letra correspondiente según la siguiente escala:

| Rango     | Letra |
|-----------|-------|
| 90 – 100  | A     |
| 80 – 89   | B     |
| 70 – 79   | C     |
| 60 – 69   | D     |
| 0 – 59    | F     |

**Ejemplo de salida:**
```
Ingresa tu calificación: 85
Tu calificación es: B
```

---

### Ejercicio 6 – Calculadora básica
Pide al usuario dos números y un operador (`+`, `-`, `*`, `/`).  
Realiza la operación seleccionada y muestra el resultado.  
Si el operador no es válido, muestra un mensaje de error.

> Considera el caso especial: división entre cero.

**Ejemplo de salida:**
```
Primer número: 10
Segundo número: 0
Operador: /
Error: no se puede dividir entre cero.
```

---

### Ejercicio 7 – Año bisiesto
Pide al usuario un año.  
Indica si ese año es **bisiesto** o no.

Un año es bisiesto si:
- Es divisible entre 4 **y**
- No es divisible entre 100, **excepto** si también es divisible entre 400.

**Ejemplo de salida:**
```
Ingresa un año: 2000
El año 2000 es bisiesto.
```

---

### Ejercicio 8 – El mayor de tres números
Pide al usuario tres números enteros.  
Muestra cuál de los tres es el **mayor**.  
Si hay empate, indícalo.

**Ejemplo de salida:**
```
Primer número: 8
Segundo número: 15
Tercer número: 7
El número mayor es: 15
```

---

## 🔴 Nivel Difícil

### Ejercicio 9 – Índice de Masa Corporal (IMC)
Pide al usuario su peso (en kg) y su altura (en metros).  
Calcula el IMC con la fórmula:

$$IMC = \frac{peso}{altura^2}$$

Muestra la categoría correspondiente:

| IMC              | Categoría         |
|------------------|-------------------|
| Menor a 18.5     | Bajo peso         |
| 18.5 – 24.9      | Peso normal       |
| 25.0 – 29.9      | Sobrepeso         |
| 30.0 o más       | Obesidad          |

**Ejemplo de salida:**
```
Ingresa tu peso en kg: 70
Ingresa tu altura en metros: 1.75
Tu IMC es: 22.86
Categoría: Peso normal
```

---

### Ejercicio 10 – Sistema de login con intentos
Define un usuario (`"admin"`) y una contraseña (`"1234"`) dentro del programa.  
El usuario tiene **3 intentos** para ingresar correctamente (simula los intentos con 3 bloques `if/elif`).

- Si acierta en el primer intento → `"Bienvenido, admin. (Intento 1)"`
- Si acierta en el segundo intento → `"Bienvenido, admin. (Intento 2)"`
- Si acierta en el tercer intento → `"Bienvenido, admin. (Intento 3)"`
- Si falla los tres intentos → `"Cuenta bloqueada."`

> Nota: Este ejercicio **no usa bucles**. Pide el usuario y la contraseña tres veces con `input()`.

---

### Ejercicio 11 – Clasificador de triángulos
Pide al usuario los tres lados de un triángulo.  
Primero verifica si los lados **pueden formar un triángulo** (la suma de dos lados siempre debe ser mayor que el tercero).  
Si es válido, clasifícalo:

- **Equilátero**: los tres lados iguales.
- **Isósceles**: exactamente dos lados iguales.
- **Escaleno**: los tres lados diferentes.

**Ejemplo de salida:**
```
Lado 1: 5
Lado 2: 5
Lado 3: 8
El triángulo es: Isósceles
```

---

### Ejercicio 12 – Simulador de semáforo extendido
Pide al usuario el color de un semáforo (`"rojo"`, `"amarillo"`, `"verde"`).  
Luego pide si hay peatones cruzando (`"si"` o `"no"`).  
Muestra la acción que debe tomar el conductor considerando ambas condiciones:

| Color    | Peatones | Acción                                      |
|----------|----------|---------------------------------------------|
| verde    | no       | Avanza con normalidad.                      |
| verde    | si       | Detente, hay peatones cruzando.             |
| amarillo | no       | Prepárate para detenerte.                   |
| amarillo | si       | Detente de inmediato.                       |
| rojo     | no       | Detente y espera.                           |
| rojo     | si       | Detente y espera, hay peatones cruzando.    |
| otro     | —        | Color de semáforo no reconocido.            |

---

## ✅ Criterios de evaluación

| Criterio                              | Descripción                                                   |
|---------------------------------------|---------------------------------------------------------------|
| Uso correcto de `if / elif / else`    | Las condiciones están bien estructuradas y sin redundancias.  |
| Validación de entradas                | Se consideran casos borde (división por cero, valores fuera de rango, etc.). |
| Legibilidad del código                | El código usa nombres de variables descriptivos y es fácil de leer. |
| Uso de f-strings                      | Los mensajes de salida usan f-strings cuando corresponde.     |
| Resultado correcto                    | El programa produce el resultado esperado para distintos valores de entrada. |
