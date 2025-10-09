# DEV25-G03-P1


# Asalto al Castillo

La práctica consiste en desarrollar el prototipo ejecutable de un videojuego de plataformas 3D para un sólo jugador con mecánicas inspiradas en algunas pruebas de El Castillo de Takeshi.

El punto de partida propuesto para esta práctica, con la documentación e implementación (código y recursos audiovisuales) necesaria, se encuentra en este repositorio de GitHub: [Castle - Base](https://github.com/narratech/castle-base)

# Instalación y uso

Los ficheros más importantes del proyecto están disponible en este repositorio, aunque puede que algunos binarios potencialmente grandes estén en el almacén GitHub LFS y se requiera tener activa la extensión Git LFS. El resto de los ficheros, generalmente de contenido más pesado o creado por terceros y sin intención de ser modificado en este proyecto, tendrá que descargarse de carpetas compartidas en [Google Drive](https://drive.google.com/drive/folders/1TfoB5S3yQw49-onoFfn0q79PTfk2RoSE) con ficheros ZIP, para después descomprirlos directamente en la carpeta Content.

Para este proyecto hace falta descargar los ficheros ZIP:

- 
- 
-
 
# Preproducción

El diseño tiene estas secciones:

- [Estetica]()
    - [Grafico]()
    - [Sonido]()
- [dinamica]()
    - [Objetivo]()
    - [Castigo]()
- [Mecanica]()
- [Contenido 1]()

# Estetica

El entorno virtual se basa en la plantilla Third Person que ofrece Unreal Engine, que recrea un mundo 3D con vista en tercera persona, a través de una cámara que sigue al avatar; además se incluye el contenido del paquete Starter Content.

# Grafico

El juego usa solamente el contenido de la plantilla proporcinada por el profesor.

# Sonido

Musica ambiente (opcional): Se desidira con el equipo de trabajo.

Pastilla energetica: Cuando el jugador coja una pastilla sonara "sonido aun no definido".

Llaves: Cuando el jugador coja una pastilla sonara "sonido aun no definido".

muerte: Si el usuario muere sonara "sonido aun no definido".

Victoria: Cuando el jugador completa el juego y obtiene el trofeo sonaran fuegos artificiales estallando. 

# Dinamica

La dinamica del juego consiste en pasar todos los niveles hasta llegar al final, no hay limite de tiempo y la muerte unicamente supone volver al inicio del nivel y repetirlo.

Posible mejora (a evaluar)
Establecer tiempo para completar el juego.
Establecer parametro de vidas hasta llegar a la muerte. 

# Objetivo

El objetivo del juego es pasar por todas las pruebas hasta conseguir el trofeso que se encuentra en lo más alto del castillo.

# Castigo

El jugador solo puede morir en el caso de ser golpeado por barriles o balas de cañon. Cuando esto pase, volverá al inicio del nivel. En el caso de caer al foso, se le ha proporcionado unas rampas para volver al principio de la prueba en la que se ha caido, con lo que es un castigo mucho más leve.

Posible mejora (a evaluar)
Suponiendo parametro de vida, si el avatar muere supondria "game over" y deberia reiniciar desde el principio.

# Mecanica

# Contenido 1
