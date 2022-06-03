# Como se ha creado el repositorio
## Por Jorge Ramírez Molina

<!--Hola! no me puedes ver 😁-->

_Curso de formación_ - **T-System**

>“Los españoles son muy españoles y mucho españoles ” – Mariano Rajoy 💀

1. Crear repositorio
2. Incluirlos en repositorio
3. Hacer el commit
4. Subirlo al repositorio remoto.

![La imagen no puede cargar](https://www.srperro.com/media/post/361ff609-8f85-471e-9cf8-06ff981b448e.600x429.png "Corgi saltando al agua, se le ve fresco 💦💦")

1. Para empezar a crear el repositorio, primero crearemos una carpeta donde almacenar los archivos que va a contener el mismo. Procedemos a usar el comando mkdir en el Bash de Git que es lo que utilizaremos durante todo este tutorial.

    Una vez creado el directorio nuevo nos movemos con cd a ese lugar.

    Y realizamos un **Git Commit** para inicializar un repositorio en ese lugar.

2. Ahora podremos colocar los ficheros que queramos añadir al repositorio en el directorio.
Usaremos **Git Add .** para que se actualizen al repositorio los ficheros añadidos al directorio.

3. Ahora si realizamos un **Git Commit -u -m"Dejamos aquí un comentario sobre los cambios que hemos hecho"** y ya tendríamos los cambios registrados.

4. En este paso necesitaremos crear el repositorio en alguna nube de GIT, en mi caso crearé un repositorio en GitHub y copiaré el enlace para linkearlo con el siguiente comando **git remote add "NombreDelRepo" "URL"**
con el comando **git Branch -M main** seleccionaremos la rama principal del repositorio y ya prodremos hacer **git push -u origin main** Y tenerlo en nuestro repositorio de GitHub.

Espero que les haya servido, un saludo.