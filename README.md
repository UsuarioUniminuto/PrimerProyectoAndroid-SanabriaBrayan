# Mi primer proyecto Android

Proyecto Android Studio en Java que reproduce la pantalla de bienvenida del ejemplo.

## Requisitos
- Android Studio (versión compatible con Android Gradle Plugin 8.7.3)
- JDK 17
- Android SDK 35

## Abrir y ejecutar
1. Descomprime el ZIP.
2. En Android Studio selecciona **Open** y elige la carpeta `PrimerProyectoAndroid`.
3. Espera la sincronización de Gradle y ejecuta en un emulador o dispositivo.

## Características
- Español predeterminado; inglés, francés y alemán.
- Selector de idioma dentro de la aplicación. La selección se conserva al reiniciar.
- `fondo_android.9.png` es el fondo Nine-patch: las zonas laterales y el cielo se pueden estirar, mientras que la franja central inferior que contiene el marcianito queda fija.
- La pantalla usa distribución flexible y permite orientación vertical u horizontal.

El recurso Nine-patch se obtuvo de la imagen de fondo incluida en el PDF de referencia proporcionado, ya que la URL externa no estuvo accesible durante la creación.

## Cambios realizados
- Documentación del proyecto.
- Soporte multilingüe.
- Interfaz adaptable.
- Fondo Nine-patch.
