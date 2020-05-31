Instrucciones de instalación y configuración y versiones necesarias  de los diferentes grupos que forman el equipo de Proyecto Software:
----------------------------------------------------
VERSIONES NECESARIAS
- Front-End Web: Angular 9.0.6
- Front-End Movil: Android Studio 3.5.3 y Flutter 44.0.1
- Back-End: Python 3.7.5 y Pip 18.1
----------------------------------------------------
INSTALACIÓN Y CONFIGURACIÓN
- Front-End Web y Móvil
Front-End Web:
Para trabajar con Ángular, se requiere de utilizar el comando "npm install" al principio del proyecto, esto instalará las dependencias que se emplean indicadas en el fichero "package.json". Al utilizar este comando, se creará una nueva carpeta llamada "node_modules", donde se descagarán todas las dependencias.
Las dependencias que se necesiten se descargarán mediante el comando "npm install" con el nombre de la biblioteca.

Cuando se quiera lanzar la página web se utilizará el comando "ng serve TuneIT", así se podría acceder usando localhost:4200 y observar la interfaz web
Front-End Movil:
Para añadir bibliotecas en móvil, se necesitará modificar el fichero "pubspec.yaml", dentro dell apartado dependencies,  añadiendo el nombre de la biblioteca a usar y la version de dicha biblioteca, para que nuestro proyecto reconozca las nuevas clases añadidas se tendrá que utilizar el comando "pub get", de esta manera, se actualizarán e instalarán.
