# 06 – Funciones en Python

## ¿Qué es una función?
Una función es un bloque de código reutilizable que realiza una tarea específica. Permite organizar el código en partes más pequeñas y manejables.

## ¿Por qué es útil usar funciones en un programa?
- Facilitan la reutilización del código.
- Mejoran la legibilidad y organización.
- Permiten dividir problemas complejos en partes más simples.

## Sintaxis básica de una función

### Función sin parámetros
```python
def saludo():
    print("¡Hola, mundo!")
```

### Función con parámetros
```python
def suma(a, b):
    print(a + b)
```

### Función con `return`
```python
def multiplicar(a, b):
    return a * b
```

## Diferencia entre `print()` y `return`
- `print()`: Muestra un valor en la consola, pero no lo devuelve.
- `return`: Devuelve un valor que puede ser usado posteriormente en el programa.

Ejemplo:
```python
def ejemplo_print():
    print("Esto es un mensaje.")

def ejemplo_return():
    return "Esto es un mensaje."

# Uso
ejemplo_print()  # Muestra el mensaje en consola.
resultado = ejemplo_return()  # Guarda el mensaje en la variable 'resultado'.
```

## Actividades sugeridas
1. Crear una función `saludo()` que imprima un mensaje de bienvenida.
2. Crear una función `suma(a, b)` que retorne la suma de dos números.
3. Crear una función `es_par(n)` que retorne `True` si el número es par o `False` si es impar.
4. Crear una función `tabla(n)` que retorne la tabla de multiplicar del número `n`.

## Instrucciones para ejecutar el archivo `funciones.py`
1. Asegúrate de tener Python instalado en tu sistema.
2. Guarda el código en un archivo llamado `funciones.py`.
3. Abre una terminal y navega a la carpeta donde guardaste el archivo.
4. Ejecuta el archivo con el comando:
   ```bash
   python3 funciones.py
   ```
