# Tema 2 - Fases del Programa

## Evolución de los Sistemas Informáticos

En este tema aprenderás:
- Cómo escribir un programa básico.
- Cómo usar los servicios de Entrada/Salida.
- Editar, compilar y ejecutar un programa.
## El lenguaje C

- Lenguaje que usaremos en esta asignatura.
- El lenguaje C fue creado en 1972 por Dennis Ritchie en Bell Labs.
- Objetivo: Codificar UNIX.
- Versiones: ANSI C, ISO C, C99, C11, C18, C2x.

## Primer Programa

Objetivo: Crear un programa que muestre el texto "Hello World!!" por pantalla.

```c
/*
  Nombre: Saludo.c
  Objetivo: Imprimir una línea de texto
*/

#include <stdio.h>

int main() {
    printf("Hello world!!\n");
    return 0;
}
