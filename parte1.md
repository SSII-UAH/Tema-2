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
    printf("Ingrese el primer número: ");
    scanf("%f", &number1);
    printf("Ingrese el segundo número: ");
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
    
    printf("Ingrese el precio inicial: ");
    scanf("%f", &initial_price);
    
    printf("Ingrese el porcentaje de descuento: ");
    scanf("%d", &percentage);
    
    final_price = initial_price - initial_price * percentage / 100;
    printf("El precio final es %g\n", final_price);
    
    return 0;
}

```



