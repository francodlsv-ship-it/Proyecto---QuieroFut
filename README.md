-Mi Proyecto: QuieroFut

* Repositorio: https://github.com/francodlsv-ship-it/Proyecto---QuieroFut
* Sitio publicado: https://proyecto-quiero-fut.vercel.app/ utilizando la pagina Vercel recomendada.

Este es mi proyecto para el curso, llamado QuieroFut. Es un sitio web básico que armé sobre mi pasión por el fútbol, donde la idea principal es subir análisis de partidos y datos de este mundo, para de esta manera poder compartir esta pasion con personas que compartan y amen este deporte como yo.

- Organizacion de la Web
El proyecto está dividido en carpetas estrictas como se solicita en las pautas de entrega:
* index.html: Es la página principal y de inicio. Está ubicada afuera, al comienzo del proyecto.
* Carpeta pages: Contiene las páginas internas del sitio para mantener un orden correcto en los archivos. 
Estas páginas son:
    * sobre-mi.html
    * proyectos.html
    * contacto.html
    * servicios.html.
* Carpeta imagenes: Almacena las fotos y recursos visuales que se muestran en la web.

- Sobre los estilos (SCSS)
Antes tenia todo el css en un solo archivo, pero lo fui separando en varios archivos mas chicos para que sea mas facil de entender y de modificar. Ahora funciona asi:
* styles/scss/main.scss: es el archivo principal, ahi adentro solo llamo a todos los demas archivos con @use.
* styles/scss/utilities: aca puse las diferentes variables y algunos mixins que arme para no repetir codigo, como uno para las transiciones y otros para cuando la pantalla es chica o grande.
* styles/scss/base: los estilos mas generales, como el fondo de la pagina, los titulos y los parrafos.
* styles/scss/layout: los estilos del menu de arriba  y del pie de pagina.
* styles/scss/components: los estilos de cosas que se repiten en varias paginas, como los botones y las cards.

Todo eso se junta y se convierte en un solo archivo, styles/style.css, que es el que usa la pagina. Para que funcione hay que correr este comando:
sass styles/scss/main.scss styles/style.css
- Con que lo hice
* HTML5
* SCSS (despues se compila a CSS)
* Bootstrap 5
como solicitaba la consigna del curso 
