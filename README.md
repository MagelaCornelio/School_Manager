# School Manager (Flutter)

![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)

Una aplicación sencilla desarrollada en Flutter para mostrar información básica sobre una escuela, incluyendo su ubicación en un mapa y una galería de fotos con persistencia local en el navegador.

## Descripción

Esta aplicación fue creada como un ejercicio paso a paso para aprender Flutter. Su objetivo es proporcionar una interfaz simple para que los usuarios puedan ver detalles de una escuela, localizarla en Google Maps y visualizar/añadir fotos a una galería. La persistencia de las fotos añadidas se maneja localmente en el navegador utilizando IndexedDB (a través de `sembast_web`).


## 🛠️ Construido Con

*   [Flutter](https://flutter.dev/) - El framework de UI.
*   [Dart](https://dart.dev/) - El lenguaje de programación.
*   [google_maps_flutter](https://pub.dev/packages/google_maps_flutter) - Para la integración de Google Maps.
*   [image_picker](https://pub.dev/packages/image_picker) - Para seleccionar imágenes de la galería/cámara.
*   [sembast](https://pub.dev/packages/sembast) & [sembast_web](https://pub.dev/packages/sembast_web) - Para la persistencia local en web usando IndexedDB.
*   [path_provider](https://pub.dev/packages/path_provider) - (Aunque no se usa directamente para archivos web, puede ser una dependencia interna).

---

