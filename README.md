# webpack-template
Plantilla para desarrollo web sobre webpack.

No olvides visitar nuestro repositorio en github: [webpack-template](https://github.com/vis97c/webpack-template)

## Caracteristicas

vue-webpack-template integra por defecto:

- - jQuery

- - Sass

- - - Custom CSS animations

- - - CSS normalization

- - - Custom mixins

- - - Autoprefixing

- - - Minification

- - - Css purge

- - - Custom pseudo components 

- - Bundling

- - - Imagenes: jpg/jpeg, png, gif y svg

- - - Video: mp4, avi, 3gp y webm

- - - Fuentes: eot, otf, ttf y woff/woff2

- - - Notificaciones del sistema

- - Y lo mas importante: ¡Completamente personalizable!


## Instalacion

Para instalarla se requiere un entorno de trabajo con node.js y composer. Recuerde clonar el repositorio.

- - Instale los paquetes npm:

```bash
     yarn
     #O en su defecto
     npm install
```

Con esto listo ya cuenta con todo lo necesario para crear y adaptar su nuevo proyecto web.

- Recuerde que para poder ver su proyecto en el navegador debe primero compilarlo con alguno de los siguientes comandos:

```bash
     #compilado + debug
     npm run dev
     # compilado instantaneo (refresca la pagina)
     npm run watch
     # compilado y listo para el publico
     npm run production

```

Configuracion adicional.

- Si desea modificar alguno de los parametros de webpack basta con sobreescribir su configuracion a travez del archivo "**webpack.config.js**". Para mas informacion acerca del mismo remitase a la documentacion de [webpack.js](https://webpack.js.org/configuration/).

## Uso

Los archivos que debe editar se encuentran en su mayoria en la carpeta "**src/**". Todos los archivos presentes en la misma se compilaran y copiaran al directorio "**public_html**", este se creara automaticamente tras la primera compilacion.

- - Tambien recuerde que solo debe editar los archivos presentes en la carpeta "**src/**", como por ejemplo el **"index.original.html"**.

- - - Si edita su contraparte presente en "**public_html**", todas sus modificaciones se sobreescribiran en la siguiente compilacion del codigo.

- - El archivo "**index.original.html**" es la plantilla de tu sitio web, las modificaciones al mismo se preservaran en tu sitio, personalizelo acordemente.

- - Si deseas copiar archivos sin necesidad de compilarlos, solo basta con copiarlos a la carpeta respectiva en el directorio "**to_public/production**". Por defecto esta funcion solo esta disponible al compilar produccion. tambien soporta el uso de subcarpetas:

- - - Por ejemplo al agregar el archivo a "**to_public/production/images/thumbnail.jpg**" tras compilar podras encontrar este archivo en "**public_html/images/thumbnail.jpg**".

- - - El funcionamiento es equivalente para la carpeta "**to_public/dev**" ideal si su entorno de desarollo difiere de produccion.

No olvides tambien reemplazar el repositorio remoto con uno de tu propiedad.

## Contribuciones

Este es un proyecto personal y no tiene ningun animo de lucro, pero los aportes son bienvenidos.

- - Correcciones mediante "pull" pueden aceptarse.

- - Para cambios grandes abran por favor un nuevo "issue" para discutir los cambios que desean hacer.

- - - No olviden testear con antelacion.

## Acerca de vue-webpack-template

Esta plantilla hace uso de software libre y su uso es libre en la misma medida .  

Puedes encontrarme en twitter [@vis97c](https://twitter.com/vis97c) o visita mi pagina web: [victorsaa.ml](https://victorsaa.ml/)