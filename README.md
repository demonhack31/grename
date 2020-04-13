Este script se ha desarrollado por la necesidad de renombrar archivos de manera masiva utilizando un prefijo y un nùmero identificador.

Ejemplo.
Renombrar screenshot_010101.png, 'foto amigo.jpeg', imagen-hoy.jpg por imagen_1.png, imagen_2.jpeg y imagen_3.jpg

A los archivos de imagen una vez que son renombrados se borra tambièn los metadatos haciendo uso de la herramienta 'exiftool' la cual ya debe estar instalada.

Los parametros solicitados son:
Ruta: Se requiere ruta completa de la carpeta que contiene los archivos a renombrar.
Prefijo: Es el nombre con el que se identificaran todos los archivos, despues de este nombre se colocara un numero identificador.

Este script almacena un registro en la carpeta que le diste como ruta, en este registro veràs los nombres anteriores, si fue borrado los metadatos y el nombre del nuevo archivo.
Tambièn se crea un script para regresar los nombres anteriores de todos los archivos afectados.

Si por error renombraste los archivos de la carpeta equivocada, ve a dicha carpeta y ejecuta el script rename_backup.sh, con esto todos tus archivos volveran al nombre anterior, lo unico que no recuperaras seran los metadatos de tus imagenes.

Uso:
cd grename
chmod 777 grename
./grename

Este script lo cree para uso personal, pero creo a mas de uno le serà de ayuda.
