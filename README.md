# Flutter Paso a Paso
El fin de este objetivo es tener una primer induccion a este lenguaje y armar una base solida para comprender conceptos mas complejos.

## Prerequisites

1. IDE de Desarrollo, en mi caso voy a usar Visual Code disponible en https://code.visualstudio.com/download 
2. Android Studio, y deben agregar la configuracion https://flutter.dev/docs/get-started/editor#androidstudio.
3. Ingresar Android Studio y verificar dentro del Adnroid Virtual Device Manager poseer algun dispositivo configurado para hacer funcionar la App.
4. Flutter SDK, el mismo se puede descargar en https://flutter.io, en mi caso particular tengo windows (https://flutter.dev/docs/get-started/install/windows) y el mismo lo instale en C:\opt\flutter.
5. Configurar la variable de entorno Path con la carpeta en donde instalamos el SDK.
6. En mi caso instale la extension de Dart en VS Code (https://marketplace.visualstudio.com/items?itemName=Dart-Code.dart-code), si en el IDE hacemos CTRL + Shift + P y seleccionamos la opcion de "Run Flutter Doctor" nos va a decir si esta todo bien configurado. Adicionalmente a la hora de desarrollar van a tener que instalar esta otra extension https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter 
Si todo anduvo OK esta sera nuestra salida
 ```
[flutter] flutter doctor -v

  ╔════════════════════════════════════════════════════════════════════════════╗
  ║                 Welcome to Flutter! - https://flutter.dev                  ║
  ║                                                                            ║
  ║ The Flutter tool uses Google Analytics to anonymously report feature usage ║
  ║ statistics and basic crash reports. This data is used to help improve      ║
  ║ Flutter tools over time.                                                   ║
  ║                                                                            ║
  ║ Flutter tool analytics are not sent on the very first run. To disable      ║
  ║ reporting, type 'flutter config --no-analytics'. To display the current    ║
  ║ setting, type 'flutter config'. If you opt out of analytics, an opt-out    ║
  ║ event will be sent, and then no further information will be sent by the    ║
  ║ Flutter tool.                                                              ║
  ║                                                                            ║
  ║ By downloading the Flutter SDK, you agree to the Google Terms of Service.  ║
  ║ Note: The Google Privacy Policy describes how data is handled in this      ║
  ║ service.                                                                   ║
  ║                                                                            ║
  ║ Moreover, Flutter includes the Dart SDK, which may send usage metrics and  ║
  ║ crash reports to Google.                                                   ║
  ║                                                                            ║
  ║ Read about data we send with crash reports:                                ║
  ║ https://github.com/flutter/flutter/wiki/Flutter-CLI-crash-reporting        ║
  ║                                                                            ║
  ║ See Google's privacy policy:                                               ║
  ║ https://www.google.com/intl/en/policies/privacy/                           ║
  ╚════════════════════════════════════════════════════════════════════════════╝

[√] Flutter (Channel stable, v1.12.13+hotfix.5, on Microsoft Windows [VersiÃ³n 10.0.19041.1], locale es-AR)
    • Flutter version 1.12.13+hotfix.5 at C:\opt\flutter
    • Framework revision 27321ebbad (5 weeks ago), 2019-12-10 18:15:01 -0800
    • Engine revision 2994f7e1e6
    • Dart version 2.7.0

[X] Android toolchain - develop for Android devices
    X Unable to locate Android SDK.
      Install Android Studio from: https://developer.android.com/studio/index.html
      On first launch it will assist you in installing the Android SDK components.
      (or visit https://flutter.dev/setup/#android-setup for detailed instructions).
      If the Android SDK has been installed to a custom location, set ANDROID_HOME to that location.
      You may also want to add it to your PATH environment variable.


[!] Android Studio (not installed)
    • Android Studio not found; download from https://developer.android.com/studio/index.html
      (or visit https://flutter.dev/setup/#android-setup for detailed instructions).

[√] VS Code (version 1.41.1)
    • VS Code at C:\Users\Joseph\AppData\Local\Programs\Microsoft VS Code
    • Flutter extension version 3.7.1

[!] Connected device
    ! No devices available

! Doctor found issues in 3 categories.
exit code 0
```

## Ejemplos
- El clasico "Hello World"  [Leer más](test01/README.md)



 [GitHub Pages](https://pages.github.com/)