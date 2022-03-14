# CONFIGURACIÓN DE RED EN TINY CORE LINUX PERMANENTE

## INTRODUCIÓN

Veremos como podemos crear un script para asignarle una configuración de red y que esta no se pierda cuando apaguemos el TC en GNS3.

El disco ya viene con el script creado y con una configuración puesta la cual podremos editar a nuestro gusto y necesidad.


## CONFIGURACIÓN

1. Descargar https://github.com/Pacodiz02/Permanent_IP_TC/archive/refs/heads/main.zip y lo descomprimimos.

2. Tendremos que importar un Firefox(v.Firefox31.1.1~2-1) en nuestro project de GNS3 y dar clic derecho > "Show in filemanager".
   Se abrirá el explorador de archivos del sistema y reemplazaremos los tres archivos que nos aparecen por los tres que tenemos en el fichero descomprimido.

3. Iniciamos el Firefox y abrimos una terminal.

4. Escribimos el comando `vi /opt/eth0` para editar el script que afecta a eth0. Nota: Si la tarjeta de red que vamos a configurar no tiene ese nombre solo tenemos que cambiarselo.

5. Una vez dentro del fichero tendremos que situarnos encima de la fila que queramos editar y pulsaremos `a` y seguidamente editaremos lo que desemos.

6. Por último, con `esc` saldremos del modo edición y con `:wq` guardaremos los cambios. Con esto ya lo tendremos todo hecho y solo tendremos que reiniciarlo para aplicar los cambios y comprobar que se realizaron correctamente.
