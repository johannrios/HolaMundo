# Hola Mundo – Primera app Android

Primera aplicación Android desarrollada para la **Actividad 4: Configurando un IDE y GitHub**
de la asignatura *Programación en Plataformas Móviles I* – Universidad Manuela Beltrán.

La app muestra el texto "Hola Mundo" en pantalla, definido como recurso en `strings.xml`.

## Tecnologías
- **IDE:** Android Studio Rabbit 1 (2026.2.1) sobre Ubuntu Linux
- **Lenguaje:** Java
- **Sistema de compilación:** Gradle con Kotlin DSL (`build.gradle.kts`)
- **SDK mínimo:** API 24 (Android 7.0)
- **SDK de compilación:** API 37 (Android 17)
- **Plantilla:** Empty Views Activity
- **Compatibilidad Java:** Java 11

## Archivos principales
- `app/src/main/java/com/example/holamundo/MainActivity.java`: pantalla principal (método `onCreate`)
- `app/src/main/res/layout/activity_main.xml`: diseño de la interfaz
- `app/src/main/res/values/strings.xml`: textos de la app
- `app/src/main/AndroidManifest.xml`: configuración y punto de entrada de la app

## Cómo ejecutarla
1. Clonar el repositorio y abrirlo en Android Studio.
2. Esperar la sincronización de Gradle.
3. Conectar un dispositivo con depuración USB activada (o usar un emulador).
4. Ejecutar con el botón Run (▶).

## Autor
Darling Johann Rios – Ingeniería de Software, Universidad Manuela Beltrán