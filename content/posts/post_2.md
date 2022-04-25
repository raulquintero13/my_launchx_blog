---
title: "el 1,2,3 de git"
date: 2022-04-24
description: 'Una manera basica de empezar a usar git en tus proyectos'
---

En este caso veremos conoceremos los commandos basicos para empezar a usar git desde la consola,
todos los comandos seran para la terminal de linux.

Basicamente son 4 comandos en los que nos enfocaremos en este post: init, add, commit y log
Para inicializar un Proyecto con git, crearemos una carpeta y nos cambiaremos a ella


> mkdir project1
> cd project1


ahora ejecutaremos el commando init


project1> git init


esto creara una carpeta oculta llamada    .git
esta la podremos ver con el comando ls

project1> ls –la


ahora ya podemos crear nuestro archivos y carpetas de nuestro Proyecto

project1> touch file.txt


ya que hayamos trabajdo en nuestro Proyecto,  podremos hacer commits las veces que sea necesario
para ir haciendo un histrial de nuestros cambios

con status podremos ver los cambios que hemos hecho y si no estan versionados en nuestro historial de git


project1> git status


ahora tenemos  que agregar todos los archivos que han sido modificados con el commando add

project1> git add .


en este caso usaremos el “.” Para agregar automaticamente todos los archivos modificados, tambien se puede especificar un archivo en caso de que haya mas de uno, 
y asi se requiera, una vez hecho esto, ahora le pondremos un comentario a esta version con el comando commit


project1> git commit –m “primer commit”


y esta seria la primera version de nuestro Proyecto, para poder ver un hstorial de todas las versiones de nuestro Proyecto, 
utilizaremos el commando log con el parametro “—oneline”, para que nos muestre cada version en una linea


project1> git log --oneline


  
