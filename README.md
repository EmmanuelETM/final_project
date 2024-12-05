# Emmanuel Torres Malena | 2021-1097
### Spotify Clone
Una aplicación desarrollada con Flutter que replica funcionalidades esenciales inspiradas en Spotify. Incluye autenticación de usuarios, gestión de canciones favoritas y listas de reproducción, soporte para modos claro y oscuro, y más. Utiliza Firebase como backend para autenticación y almacenamiento, siguiendo principios de arquitectura limpia y manejo de estados con Bloc.

#### Funcionalidades principales
- Autenticación
- Registro e inicio de sesión mediante Firebase.
- Recuperación de información de usuarios autenticados.
- Gestión de canciones
- Agregar y eliminar canciones de la lista de favoritos.
- Acceso a una lista de canciones recientes.
- Compatible con temas claros y oscuros.
- Pantalla de inicio animada.
- Persistencia de estados mediante Hydrated Bloc.
- Almacenamiento local con la librería path_provider.
- Arquitectura modular
- División en capas: datos, dominio y presentación.
- Configuración de inyección de dependencias utilizando GetIt.

#### Configuración del proyecto
Requisitos previos
- Flutter
- Firebase CLI
- Un proyecto activo en la consola de Firebase.

#### Instalación de dependencias
Ejecuta el comando para instalar las dependencias del proyecto:

```dart
flutter pub get
```
Inicialización de Firebase
El archivo firebase_options.dart está preconfigurado con la CLI de Firebase. Asegúrate de inicializar Firebase en el método main:

```dart
await Firebase.initializeApp(
  options: DefaultFirebaseOptions.currentPlatform,
);
```

#### Dependencias principales
El proyecto utiliza las siguientes dependencias:

```dart
dependencies:
  flutter:
    sdk: flutter
  cupertino_icons: ^1.0.2
  flutter_svg:
  flutter_bloc:
  hydrated_bloc:
  path_provider:
  firebase_core:
  firebase_auth:
  get_it:
  dartz:
  cloud_firestore:
  just_audio:
```

#### Tecnologias Utilizadas
- Flutter Bloc: Gestión de estados reactivos.
- Hydrated Bloc: Persistencia local de estados.
- GetIt: Inyección de dependencias.
- Firebase Core y Auth: Autenticación y servicios de backend.
- Path Provider: Acceso al sistema de archivos del dispositivo.


### Video

[Video](https://miucateciedu-my.sharepoint.com/:f:/g/personal/20211097_miucateci_edu_do/Epex5p0FSFNCkzZScsdgB04BVlx8P88Uq-axLOJKMSYSyA?e=ua3J7H )


