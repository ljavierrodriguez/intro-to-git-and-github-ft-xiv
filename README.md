### Configurar nuestros datos de usuario

    $ git config --global user.name "Luis J. Rodriguez O."
    $ git config --global user.email "ljavierrodriguez@gmail.com"

    $ git config user.name "Luis J. Rodriguez O."
    $ git config user.email "lrodriguez@4geeks.co"

### Inicializar un repositorio vacio o nuevo 

    $ git init

### Ver el estado o estatus de nuestro repositorio 

    $ git status

### Preparar archivos a guardar (staged)

    $ git add .
    $ git add -A
    $ git add <filename>
    $ git add *

### Guardar archivos en el repositorio 

    $ git commit -m "Mensaje Descriptivo de la tarea que se realizo"

### Ver todos los commits realizados

    $ git log