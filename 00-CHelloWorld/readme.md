# 00-CHelloWorld

Este trabajo práctico tiene como objetivo demostrar la capacidad de editar, compilar y ejecutar programas en C.

## Compilador Utilizado

- **Compilador**: GCC (MinGW)
- **Versión del Compilador**: 6.3.0
- **Versión de C soportada**: C11

## Archivos del Trabajo

- **hello.c**: Código fuente del programa "Hello, World!".
- **output.txt**: Archivo con la salida del programa.

## Ejecución del Programa

1. Compilar el programa con el comando:
   ```bash
   gcc --std=c11 -o hello hello.c
   ```
2. Ejecutar el programa con:
   ```bash
   ./hello
   ```
3. Redirigir la salida a un archivo con:
   ```bash
   ./hello > output.txt
   ```