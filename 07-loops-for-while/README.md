# 08 – Bucles en Python: `for` y `while`

Los bucles son estructuras fundamentales en programación que permiten repetir un conjunto de instrucciones de manera eficiente. En Python, los bucles más comunes son `for` y `while`.

## ¿Qué es un bucle?

Un bucle es una herramienta que permite ejecutar un bloque de código varias veces, ya sea recorriendo elementos de una colección o repitiendo instrucciones mientras se cumpla una condición.

## Cuándo usar `for`

El bucle `for` se utiliza cuando sabemos de antemano cuántas veces queremos iterar, como al recorrer rangos de números o elementos de una colección (listas, tuplas, etc.).

### Ejemplo básico:
```python
for i in range(5):
    print(i)  # Imprime los números del 0 al 4
```

## Cuándo usar `while`

El bucle `while` se utiliza cuando queremos repetir un bloque de código mientras una condición sea verdadera. Es útil cuando no sabemos cuántas iteraciones serán necesarias.

### Ejemplo básico:
```python
contador = 0
while contador < 5:
    print(contador)
    contador += 1  # Incrementa el contador
```

## Actividades sugeridas

1. Mostrar los números del 1 al 10 usando un bucle `for`.
2. Recorrer una lista de nombres y saludar a cada uno.
3. Usar un bucle `while` para contar hasta que el usuario escriba "salir".
4. Generar la tabla de multiplicar de un número ingresado por el usuario utilizando un bucle `for`.

## Instrucciones para ejecutar el archivo `bucles.py`

1. Asegúrate de tener Python instalado en tu computadora.
2. Guarda el archivo con el nombre `bucles.py` en la misma carpeta que este README.
3. Abre una terminal o consola y navega hasta la carpeta `08-loops-for-while`.
4. Ejecuta el archivo con el comando:
   ```bash
   python3 bucles.py
   ```
