# Página Web 

## Despliegue de una página web a traves de github. 

Lo primero es crear el repositorio de github, luego copiamos el enlace https que podemos encontrar en el repositorio que acabamos de crear. Después necesimos decargarnos la aplicación [Git](https://git-scm.com/downloads). Después de haber efectuado la descarga nos dirigimos al archivo que descargamos y ejecutamos el archivo git-bash.exe. Luego crearemos una carperta de igual el sitio ya sea en el esccritorio como en la carpeta de descargas. Cuando ejecutemos dicho archivo se nos va a abrir una especie de Terminal. Atraves del comando '$ cd + {carpeta creada}' nos meteremos dentro de la carpeta a traves del terminal luego intruduciremos el comando ' $ git clone {pegamos la url copiada}'  y ejecutamos.

Después nos metemos en la carpeta y vemos que nos ha creado una carpeta que es lo que tenemos en Github, es decir, el repositorio creado. Con el comando '$ cd {nombre carpeta github}' no meteremos dentro de esa carpeta a traves del Terminal. Dentro de esta carpeta copiaremos todos los archivos de la pagina web que nos hemos descargado anteriormente en [Free Website Templates](https://freewebsitetemplates.com) a través de la interfaz de Windows. Más tarde en el Terminal meteremos el comando '$ git add .' esto significa que esta añadiendo los archivos, después pondremos el comando '$ git commit -m "Comentario"' (Ejemplo de comentario "Primera Subida") intro y esto hace que se cree todo en el github. Por último pondremos el comando '$ git push origin main', nos aparecera una nueva ventana y en ella le daremos a manager + select, y nos aparecera una ventana para poder enlazar nuestro github con Git. Otra vez volvemos a introducir el comando '$ git push origin main' y haremos el mismo procedimiento. 

Después de haber hecho todos los pasos en el apartado de configuracion de Github o Settings nos aparecera un menú a la izquierda en el que pone "Pages" entramos y en el apartado de "Branch" seleccionamos "main" y guardamos. Luego de unos minutos nos debería de aparecer en la parte de arriba el enlace creado a nuestra pagina web. 

Finalmente ya estaria creado el despliegue de una página web a través de Github.


- [Mi página web](https://larrywestbrook.github.io/Pagina-Web/)
