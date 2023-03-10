# MasterPidgey-Examen
## Examen de entornos de desarrollo: Segunda evaluación.(Parte 1)
- Creo un repositorio en GitHub llamado **masterpidgey-examen**.
![Crear](img/Captura%20desde%202023-03-10%2008-22-27.png)
- Copio el urld del repositorio.
![Copiar](img/Captura%20desde%202023-03-10%2008-23-42.png)
- Hago la clonación del repositorio en local.
![Clonar](img/Captura%20desde%202023-03-10%2008-24-53.png)
- Me meto en el repositorio MasterPidgey-Examen.
![MasterPidjeyExamen](img/Captura%20desde%202023-03-10%2008-26-48.png)
## Commit inicial

- Como al crear el repositorio en GitHub, ya puso automaticamente el README, voy a escribir un cambio en este para hacer un commit.
![readme](img/Captura%20desde%202023-03-10%2008-27-25.png)
- Hago un cambio con **nano**.
![nanoreadme](img/Captura%20desde%202023-03-10%2008-29-06.png)
- Confirmo que se ha guardado con **cat**.
![catreadme](img/Captura%20desde%202023-03-10%2008-30-02.png)
- Añado el cambio con **add** y por ultimo hago el **commit**.
![addreadme](img/Captura%20desde%202023-03-10%2008-32-06.png)

## Push inicial

- Subo los cambios al repositorio remoto con **git push**.
![Pushreadme](img/Captura%20desde%202023-03-10%2008-37-21.png)

## Ignorar archivos

- Aquí he creado una carpeta llamada **Privada** y dentro de esta, un archivo con formato **.txt** llamado **Privado**.
![privad@](img/Captura%20desde%202023-03-10%2008-39-28.png)
- Para luego usar **.gitignore** con **nano** y escribir el nombre de la carpeta **Privada** para que el contenido dentro de esta sea ignorado.
![gitignore](img/Captura%20desde%202023-03-10%2008-46-08.png)
![gitignore2](img/Captura%20desde%202023-03-10%2008-45-44.png)
## Añadir fichero 1.txt

- Añado el fichero llamado **1.txt** al repositorio local.
![1txt](img/Captura%20desde%202023-03-10%2008-46-55.png)

## Hacer un commit de lo anterior y un push para actualizar

- Hago un **git status** para ver el estado actual de mi repositorio 
para saber a que le tengo que hacer **git add**.
![gitstatus](img/Captura%20desde%202023-03-10%2008-51-48.png)
- Realizo el **commit**.
![commit2](img/Captura%20desde%202023-03-10%2008-54-28.png)
- Y lo subo todo al repositorio remoto con **push**.
![push2](img/Captura%20desde%202023-03-10%2008-55-43.png)

## Crear el tag v0.1

- Creo un tag llamado **v0.1**.
![tag1](img/Captura%20desde%202023-03-10%2008-58-16.png)

## Subir el tag v0.1

- Subo los cambios al repositorio remoto con **push**.
![push3](img/Captura%20desde%202023-03-10%2009-01-08.png)

## Visualizar los commits realizados hasta el momento

- Escribo un **git log** para visualizar todos los commits hasta el momento.
![gitlog](img/Captura%20desde%202023-03-10%2009-57-14.png)

## Crear una tabla

- Creo una tabla con MarkDown en el **README.md**
con la información del docente del módulo:

|        NOMBRE          |                     GITHUB                        |
|------------------------|---------------------------------------------------|
| Máximo Fernández Riera | [maximofernandezriera](https://github.com/maximofernandezriera)|

## Colaboradores

- Poner a [github.com/maximofernandezriera](http://github.com/maximofernandezriera)
como colaborador del repositorio **MasterPidgey-Examen**
![maximocolaborador](img/Captura%20desde%202023-03-10%2010-06-30.png)

# Examen de entornos de desarrollo: Segunda evaluación.(Parte 2)

## Contribución al proyecto first-contributions

### Usando Fork y clonando repositorio en local
- Para empezar, he realizado un **fork** para bifurcar el proyecto.
![fork1](img/Captura%20desde%202023-03-10%2010-16-34.png)
- Le he dado el mismo nombre.
![fork2](img/Captura%20desde%202023-03-10%2010-19-01.png)
- Y por último he realizado el **git clone** para tener el repositorio local.
![clonefork](img/Captura%20desde%202023-03-10%2010-26-43.png)
### Creamos una rama
- Usando **switch** podemos cambiar a una rama especifica, aunque tambien se puede usar para crear la rama en caso de que el nombre escrito no exista. (Ahora vamos acceder al repositorio)
![switch](img/Captura%20desde%202023-03-10%2010-27-05.png)
- Y ahora si, escribimos el comando con **switch**.
![switch2](img/Captura%20desde%202023-03-10%2010-28-20.png)
### Modificando el archivo Contributors
- Ahora lo que voy a hacer es entrar en el arhivo **Contributors.md** con **nano** para añadir mi nombre en el la lista.
![nanomdcontributors2](img/Captura%20desde%202023-03-10%2010-31-50.png)
![nanomdcontributors](img/Captura%20desde%202023-03-10%2010-31-29.png)
- Y cuando hayamos escrito y guardado nuestro nombre, realizaremos un **git add** para luego pasar a hacer el **commit**.
![gitaddcontributors](img/Captura%20desde%202023-03-10%2010-32-54.png)
- Y ahora hacemos un **commit** de nuestro cambio.
![gitcommitcontributors](img/Captura%20desde%202023-03-10%2010-33-50.png)
### Hacemos un push
- Por ultimo vamos a hacer un **git push** de nuestro **commit** de la rama para tenerlo actualizado.
![pushcontributors](img/Captura%20desde%202023-03-10%2010-34-40.png)
### Enviar los cambios para que sean revisados
- Ahora nos redirigimos a github, y en nuestro repositorio bifurcado, nos saldrá una notificación con **Compare & Pull request**.
![pullcompare](img/Captura%20desde%202023-03-10%2010-35-36.png)
- Pulsamos el boton verde y le ponemos el comentario que queramos.
![pullcompare2](img/Captura%20desde%202023-03-10%2010-36-13.png)
- Y cuando l hayamos dado al boton de Create pull request, se nos confirmará que nuestra rama no tiene ningń problema y solo quedará que el administrador revise su llegada de nuestro pull request.
![pullcompare3](img/Captura%20desde%202023-03-10%2010-36-30.png)
