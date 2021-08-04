REQUISITOS

Nivel apropiado en conocimientos de tecnologías HTML, CSS y JS.
Tomar el curso de desarrollo web profesional te enseña las bases para
iniciar este si es que se te complica. JavaScript profesional y el curso a fondo de CSS. Puedes tomar este curso, el de CSS y el de JS a la par para ir reforzando tus conocimientos.

NPM
NPM es un controlador de paquetes de NodeJS el cuál nos da una forma organizada a través de la cuál podemos agregar dependencias a nuestro proyecto, librerías, frameworks, asistentes, cosas que nos sirvan para nuestro proyecto y eliminar, actualizar o importarlas usando NPM.

La ventaja de usar NPM es que se encarga de instalar las dependencias de nuestras dependencias, o sea, si yo instalo "d3JS" y este necesita alguna otra dependencia, NPM se encarga automaticamente de instalarlo, cada vez que actualizamos intenta actualizar cualquier otra dependencia para que quede listo.

WEBPACK
Las aplicaciones web modernas se componen de multiples archivos, unos que dependen de otros, unos que importan a otros y otros que requieren de otras cosas para que funcionen. El trabajo de webpack es tomar nuestros archivos y generar archivos estaticos de salida que podamos usar en producción. Lo que webpack hace es hacer un grafo que refleje la interacción entre las distintas dependencias de nuestros archivos.

Ej: Una página que use react, instalamos react router y material UI, ambas librerías dependen e importan la librería base de rect. Webpack entiende que ambas importan la misma base y especifica en el grafo que ambas dependen de react, para que cuando genere el archivo final, solo importe una vez react aunque ambos esten usando la misma librería, el proceso se compone de un archivo de entrada a la cuál empieza a formarse el gráfo. Todo lo que el archivo de entrada importa y los archivos que estos nuevos a su vez importan también, son los que van generando la estructura con todas las dependencias de tu aplicación, posteriormente webpack toma todos los archivos que integran el gráfo y genera una salida, este archivo de salida es el que se termina importando en el HTML porque es el que ya tiene todas las dependencias. Webpack puede hacer una gran cantidad de cosas y procesamientos a través de plugins que la comunidad genera.

Otro concepto importante son los loaders, que permiten a webpack entender archivos que no sean JS como CSS, imagenes SVG, etc. El trabajo de los loaders es convertir estos archivos en módulos de JS que pueden agregarse al grafo para eventualmente procesar el grafo y generar salidas que podamos importar en nuestro archivo HTML.

En resumen el trabajo de webpack es tomar un archivo de entrada, generar un gráfo a traves de ese archivo con todas las dependencias que nuestra aplicación genera, necesita y generar una salida, esta salida son archivos estáticos que podemos usar en nuestro sitio web y que han sido optimizados y procesados para cumplir con las mejores practicas de un sitio web.# cody_desarrollo_avanzado
