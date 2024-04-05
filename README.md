# Ejecutar "Hello World" en C++

Este es un ejemplo básico para compilar y ejecutar un programa "Hello World" en C++.

## Paso 1: Preparación del código fuente

Crea un archivo llamado `hello.cpp` y escribe el siguiente código:

cpp
#include <iostream>

int main() {
    std::cout << "Hello, world!" << std::endl;
    return 0;
}


## Paso 2: Compilar el código

Abre una terminal y navega hasta el directorio donde se encuentra `hello.cpp`. Luego, ejecuta el siguiente comando para compilar el código:


g++ -o hello hello.cpp


## Paso 3: Ejecutar el programa

Una vez compilado, ejecuta el programa con el siguiente comando:


./hello
