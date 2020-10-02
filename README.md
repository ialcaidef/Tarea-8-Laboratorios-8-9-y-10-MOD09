# Tarea-8-Laboratorios-8-9-y-10-MOD09


Ino Alcaide
02/10/2020

Se añade un manifiesto para soporte fuera de línea.

"Si bien todos los navegadores tienen mecanismos de almacenamiento en caché, estos sistemas no son fiables y no siempre funcionan como debieran. 
HTML5 permite resolver algunas de las molestias asociadas al trabajo sin conexión mediante la interfaz ApplicationCache.

Algunas de las ventajas que conlleva el uso de ésta caché para una aplicación son:

Navegación sin conexión: los usuarios pueden explorar todo el sitio web sin conexión.
Velocidad: los recursos almacenados en caché son locales y, por tanto, se cargan más rápido.
Reducción de carga del servidor: el navegador solo descarga recursos del servidor que han cambiado.
Para poder trabajar sin conexión, una aplicación únicamente necesita de un archivo de manifiesto, el cual indica al navegador que ficheros 
debe almacenar en la caché local. El contenido del manifiesto puede ser tan simple como un listado de archivos. 
Una vez que el navegador ha descargado y almacenado los ficheros (html, CSS, imágenes, javascripts, etc), el navegador hace uso de estos ficheros, 
incluso cuando el usuario actualiza la página en su navegador.

Además de especificar qué ficheros van a ser almacenados en la caché, es posible indicar cuáles no tienen que serlo, y por tanto obligar 
al navegador a realizar una petición de dichos ficheros al servidor. Finalmente, si intentamos acceder a un fichero no almacenado en local, 
y no disponemos de conexión, podemos mostrar un recurso que previamente hemos almacenado en la caché."
https://www.arkaitzgarro.com/html5/capitulo-9.html

También se incluye la persistencia de datos de usuario mediante el uso de la API de almacenamiento local,
lo que nos permite almacenar datos de manera local en el navegador y sin necesidad de realizar alguna conexión a una base de datos.
