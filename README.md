# project

#1 Entramos a github y nos logueamos;

#2 Creamos un repositorio;

#3 Entramos a git y nos logueamos;

#4 Ingresamos el comando "pwd" para ver en que ubicación nos encontramos; Ingresamos el comando "cd" para dirigirnos a la carpeta creada;

#5 Una vez dirigidos ingresamos el comando "git init" que creara un repositorio vacion en una carpeta oculta, luego ingresamos "git status" y nos comunicara que estamos en la rama maestra y que no tenemos conpromiso todavía porque no hay nada que confirmar (Crear/Copiar archivos y usar "git add" para rastrear);

#6 Agregamos los archivos a la carpeta creada;

#7 Ingresamos el comando "git add nombreArchivo" para entrarlos al staging area y luego el comando "git status"

#8 Ingresamos el comando "git commit -m "Comentario" " para entrarlos al ultimo estado "3" y comprometer nuestros archivos;

#9 Ingresamos el comando "git log" y nos mostrara nuestro ID, autor y fecha;

#10 Ingresamos el comando "git branch" para ver nuestra rama principal; Luego ingresamos el comando "git branch nombreArchivo" para crear una rama; y por ultimo "git branch -l" para ver nuestras ramas;

#11 Ingresamos el comando "git checkout nombreRama" para controlar el estado de una rama;

#12 Ingresamos el comando "git log --oneline" para ver los commits realizados;

#13 Ingresamos el comando "git checkout alfaNumerico" con el identificador que nos indica al principio en amarillo para ver el estado;

#14 Ingresamos el comando "touch nombreArchivo" y creamos un archivo vacio por defecto; Ingresamos el comando "echo Texto" >> nombreArchivo | le asigna el contenido especificado al archivo;

#15 Ingresamos el comando "ssh-keygen -t ed25519 -C email@email"  y generara una clave SSH en el entorno local ".ssh";

#16 Luego de haber creado la clave se podra sincronizar con github en la sección "configuraciones SSH and GPG keys";

#17 Ingresamos en la sección "<>code local clon SSH" en nuestro repositorio de github y copiamos el enlace en git bash con el siguiente codigo "git clone Enlace" previamente eligiendo la ruta con el comando "cd /"

#18 Se clona el repositorio de github en nuestro entorno local;

#19 Procedemos a cargar la carpeta ingresando el comando "cd /" y luego ingresamos el comando "ls" para ver los archivos dentro del mismo;

#20 Creamos un archivo con el comando "echo name" luego lo agregamos con el comando "git add name" a la staging area y verificamos con "git status";

#21 Y finalmente ingresamos el comando "git commit -m "Comentario" " que captura una instantánea de los cambios preparados en ese momento del proyecto, luego veo en que rama estoy con "git branch" y lo subo a github con el comando "git push -u origin main";
