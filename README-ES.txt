CALCULADORA CHOCOLA — PROYECTO ANDROID

Este proyecto envuelve la calculadora HTML en una app Android nativa sencilla.
La calculadora y la imagen de Chocola están guardadas localmente: funciona sin Internet.

PARA GENERAR EL APK EN ANDROID STUDIO

1. Instala Android Studio.
2. Abre la carpeta "Calculator_Chocola_Android" desde Android Studio
   (File > Open).
3. Espera a que Gradle sincronice y descargue el Android Gradle Plugin/SDK
   si todavía no están instalados.
4. En Tools > SDK Manager, instala Android SDK Platform 35 y Build Tools.
5. Conecta tu celular con depuración USB o usa un emulador.
6. Pulsa Run para probarla.
7. Para crear el APK: Build > Build Bundle(s) / APK(s) > Build APK(s).
8. Android Studio mostrará la ubicación del APK al terminar.

REQUISITOS
- Android Studio reciente.
- JDK 17 (Android Studio suele incluirlo).
- Android SDK Platform 35.
- Gradle descargará los componentes necesarios la primera vez.

DETALLES
- Nombre: Calculadora de Chocola
- Paquete: com.lyluxs.chocolacalculator
- Android mínimo: 6.0 (API 23)
- Versión: 1.0

La carpeta app/src/main/assets contiene el HTML completo. Puedes modificar
index.html para cambiar el diseño sin tocar el código Java.
