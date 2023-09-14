# Como Crear un Repositorio en Git
El primer paso para poder usar Git es instalarlo desde su pagina. 

https://git-scm.com/download/win

Una ves instalado git, se podra usar la consola llamada **Git Bash**.

Dentro de la consola de **Git Bash**,usaras el siguiente comando.
```
git init
```
Esto creara un archivo de git dentro de la carpeta en uso. (Este archivo estara oculto)

## Crear un Repositiorio en GitHub
Abriras la pagina de **GitHub** en tu navegador de confianza.

Crearas un nuevo repositorio en la opción ***New***.

Decidir si se va a hacer *publico* o *privado* el repositorio.

NO añadir archivo **Readme** o **Ignore**.

## Juntar el archivo con Git

- Dentro de la consola **Git Bash** se pondra lo siguiente.
```js
git config --global user.name "Nombre"
git config --global user.email "Correo"
git config --global init.defaultBranch main
```
Esto para configurar **Git** con tus credenciales y cambiar el nombre de la rama principal a ***main***.

- Añadir los cambios
 ```js
git add .
git commit -m "First Commit"
 ```
Con esto los cambios ya estan en la nube

- Para unir los cambios a tu repositorio
```js
git remote add origin https://github.com/usuario/repositorio.git
git push -u origin main
```
Esto tambien te lo da la paginade **Git** al crear el repositorio.

Con esto ya tendras ligado todo y podras empezar a subir cambios.

# Agregar Cambios a tu repositorio

Hay 3 pasos que tendras que seguir cada ves que quieras agregar un cambio.

```js
git add .
git commit -m "Comentario"
git push
```
Haciendo esto **Git** añadira todos los cambios, subira tus archivos a la nuve con el comentario puesto y se juntara con lo subido al repositorio.

Hay que tener en cuenta que siempre puedes ver tus antiguos **Commits** y descargarlos cuando quieras.