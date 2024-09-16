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
```
### Elementos clave del código

- `#include <stdio.h>`: Directiva del preprocesador para incluir el archivo de cabecera de entrada/salida.
- `main()`: Punto de entrada del programa.
- `printf`: Imprime en pantalla.
- `return 0;`: Informa al sistema operativo que el programa terminó correctamente.

### Segundo Programa

**Objetivo**: Imprimir dos líneas de texto.

```c
/*
  Nombre: Saludo2.c
  Objetivo: Imprimir dos líneas de texto
*/

#include <stdio.h>

int main() {
    printf("Hello world!!\n");
    printf("Welcome to C! ");
    return 0;
}
```
### Imprimiendo números en diferentes formatos
```c
#include <stdio.h>

int main() {
    int number;
    printf("Introduce un número: ");
    scanf("%d", &number);
    printf("Hexadecimal: %X\nOctal: %o\n", number, number);
    return 0;
}
```
### Sumando dos números
Escribe un programa que lea dos números reales de teclado y muestre la suma de ambos.
```c
#include <stdio.h>

int main() {
    float number1, number2, result;
    printf("Introduzca el primer número: ");
    scanf("%f", &number1);
    printf("Introduzca el segundo número: ");
    scanf("%f", &number2);
    result = number1 + number2;
    printf("La suma es: %f\n", result);
    return 0;
}
```
### Programa para calcular el precio final de un videojuego con descuento
```c
#include <stdio.h>

int main() {
    float initial_price, final_price;
    int percentage; // descuento en porcentaje
    
    printf("Introduzca el precio inicial: ");
    scanf("%f", &initial_price);
    
    printf("Introduzca el porcentaje de descuento: ");
    scanf("%d", &percentage);
    
    final_price = initial_price - initial_price * percentage / 100;
    printf("El precio final es %g\n", final_price);
    
    return 0;
}

```
# TAREAS PLANTEADAS
## Actividad 1
Escriba un programa que pida dos números enteros por teclado, los sume y muestre el resultado de la suma por pantalla.

## Actividad 2
Escriba un programa que pida dos numeros reales por teclado, los sume y muestre el resultado de la suma por pantalla.

## Actividad 3 
Escriba un programa que pida una letra por teclado y muestre su código ASCII en hexadecimal por pantalla.

## Actividad 4 
Escriba un programa que muestre por pantalla la letras del abecedario inglés. Recomendación: use un bucle.

## Actividad 5
Escriba un programa que pida un número positivo por teclado y muestre la secuencia desde 0 al número leído. consejo: usar una variable extra para contar entrada: number​salida: la secuencia de números en pantalla.​

Si el número introducido es 6 el programa mostrará:

0 1 2 3 4 5 6

## Actividad 6
Modifique el programa anterior para que use una función para realizar la cuenta y la visualización de los números por pantalla.

## Actividad 7
Modifique el programa anterior para que pueda repetir la secuencia con 5 números. Es decir, una vez finalizada la cuenta de un número, solicite otro para realizar la cuenta nuevamente.

Consejo: use otro bucle más.

Consejo: Reutilice el código anterior y cree una función con el código agrupado en el bucle.


### Enlace a la solución de las tareas planteadas
[Soluciones](https://colab.research.google.com/drive/128EF4-_flBWGG9FDNc9I9APfl5iiQNKi?usp=sharing)

### Para terminar unas preguntas sobre la actividad
[Cuestionario sobre la tarea](https://app.wooclap.com/PXPZDH?from=event-page)

### Completa la siguiente encuesta para valorar la actividad
[Encuesta](https://app.wooclap.com/PZEYMR?from=event-page)

