# Control de Versiones

### Control de versiones distribuidos

- Git, el mas conocido y popular
- Mercurial
- Bazaar

## Git

### Pasos para Git

- git init -> En la consola o terminal iniciar con este comando, con el se inicia el historial de commits de git.

- Podemos iniciar enviando un mensaje directo a los commits con 
1. echo hola > mensaje, aqui creamos un archivo en blanco llamado mensaje
2. git add mensaje, anexamos el archivo a la cola de espera de git.
3. git commit -am "Mensaje Inicial", le damos al commit un nombre con el cual se puede buscar de vuelta despues, junto con este commit se sube el archivo al historial de commits y queda pendiente por ingresarse al repositorio principal.
4. echo adios > mensaje, cambiamos el contenido del archivo y luego subimos los cambios
5. touch nuevo-fichero, esto crea un nuevo archivo dentro de la carpeta en la que estamos trabajando, este los vamos a subir tambien al arbol de trabajo
6. git add nuevo-fichero
7. git commit nuevo-fichero -m "otro fichero mas", para subir el nuevo archivo al arbol de trabajo con un comentario nuevo.


## Github, Gitlab, Bitbucket, Sourceforge
