# Syntax

```c
#include <stdio.h>

int main() {
    printf("Hello World!");
    return 0;
}
```
Usaremos este ejemplo para desglosarlo y entender mejor la sintaxis:

1. ***Primer linea*** en  ``C``.
    ```c
    #include <stdio.h>
    ```
    - Esta linea es una biblioteca de archivos para el encabezado.
    - Esto no permite trabajar con funciones de entrada y salida
    - Ejemplo: ``printf()``
    - Los archivos de encabezado agregan funcionalidades a los programas en ``C``.

1. ***Segunda linea:*** en ``C`` es un espacio, ``C`` ignora los espacios, esto se usa para mejorar la lectura.

1. ***Tercera linea:*** Algo que siempre aparece en los programas en ``C`` es ``main()``. Esto es una funcion e indica que todo lo que este dentro de las llaves ``{}`` tiene que ser ejecutado.

1. ***Cuarta linea:*** ``printf()`` es una funcion usada para crear una salida e imprimir texto en la pantalla. En nuestro ejemplo la salida en "Hello World!".

    > Nota: Cada declaracion en ``C`` termina con ``;``.

1. ***Quinta linea:*** ``return 0`` termina la funcion ``main()``. 

1. ***Sexta linea:*** No olvidemos cerrar la llave ``}`` que termina la funcion ``main()``.


