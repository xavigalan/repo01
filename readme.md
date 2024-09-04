# [Git & Markdown](https://classroom.google.com/w/NjE4Nzc4ODM0NjQx/tc/NTg5MjUwNTQwNzMw)

### 1. Como crear un repositorio
- Primer paso debemos crear un **directorio** con mkdir *(nombre del directorio)*.
![alt text](image.png)
- Siguiente paso, accedemos dentro del **directorio** generado con cd *(nombre del directorio)*.
![alt text](image-1.png)
- Una vez dentro para generar un **repositorio local** utilizaremos git init dentro del mismo.
![alt text](image-2.png)
- Para comprobar si el repositorio es correcto escribiremos el comando **git status**.
![alt text](image-3.png)

### 2. Estados de Repositorio 
- Al hacer un git add añadimos los cambios realizados al **staging area**.
![alt text](image-5.png)
- Para comprobar si realmente está con **git status** podemos verlo.
![alt text](image-4.png)
- Seguidamente creamos un snapshot utilizando git commit -m "(*descripción del progreso*)".
![alt text](image-6.png)
- En este momento el repositorio se encuentra en **Commited**, si añadimos contenido dentro del fichero estará en **Modified**, si hicieramos un **git add** estaría en **staging area**.
### 3. Sincronizar repositorio local con la nube
1. Primero crear un repositorio en la nube a través de **GIT HUB**.
![alt text](image-7.png)
2. Sincronizar el repositorio local con el de la nube