# Flutter Paso a Paso
El fin de este objetivo es tener una primer induccion a este lenguaje y armar una base solida para comprender conceptos mas complejos.

## Ejemplo 1

1. Dentro de Visual Code presionamos CTRL + Shift + P o F1, seleccionamos la opcion de "Flutter: New Project", nos solicita el nombre del proyecto y en que carpeta se va a generar la nueva solucion. En este caso introducimos que el proyecto se llama hello_world y se va alojar en la carpeta test01.
2. Inmediatamente despues de creado el proyecto, nos va a abrir otra instancia de VS Code dentro de este proyecto.
3. Dentro de la estructura de proyecto, vamos a notar que tenemos la carpeta 'lib'con nuestro main del proyecto.
4. Eliminamos las clases dentro de la carpeta test, ya que en esta primera etapa no vamos a profundizar en el uso de test unitarios.
5. Reemplazos nuestra clase main.dart con el siguiente codigo
 ```
import 'package:flutter/material.dart';

void main() {
  runApp(Center(
    child: new Text(
      "Hello World!",
      textDirection: TextDirection.ltr,
    ),
  ));
}
 ```
5. Analizamos el codigo que ingresamos
6. Presionamos F5 para debugear nuestra app, si no tenemos un emulador el mismo VS Code nos va a ayudar a crear uno.
7. Una vez funcionamos comprendemos los puntos importantes de este codigo:
    - TBD
    - TBD
    - TBD
    - TBD


[Volver al indice principal](../README.md)