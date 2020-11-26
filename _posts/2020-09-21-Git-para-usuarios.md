---
title: "Primera reunión de expertos"
date: 2020-09-21
---
# Git para usuarios de Dropbox (o Google Drive)

Git es  parecido a Dropbox: coge los archivos de tu ordenador, los pone en la nube, y permite que otras personas trabajen sobre ellos. Permite que varias personas trabajen en el mismo archivo al mismo tiempo.  
Incluso si no tienes un equipo de personas, git sigue teniendo ventajas importantes. 

Puede funcionar como una máquina del tiempo, permitiéndote volver a ver lo que hiciste la semana pasada, o incluso el año pasado, ayudarte a recuperar archivos que borraste, y llevar un registro del progreso a lo largo del tiempo además de ser genial para hacer copias de seguridad. 

Git no asume que tú quieras enviar cada cambio guardado a la nube. Mientras Dropbox sube automáticamente todo lo que guardas, Git añade un nuevo paso: la confirmación (o *commit* en lenguaje Git). Después de guardar un archivo, debes indicar a Git que quieres confirmar ese cambio.

Para hacer esto, haces lo que se llama “staging”. Esto realmente sólo significa decir a Git cuáles son los cambios de los que estás seguro. De esta forma, Git no hace perder el tiempo a los demás si haces un borrador que al final no te gusta.

En Git, subir a la nube se llama *push*. Estás literalmente empujando tus cambios desde tu ordenador a la nube. Sólo entonces podrán los demás descargarlos a sus propios ordenadores.

Debes pedir explícitamente a Git que quieres traer los cambios desde la nube (*pull* en lenguaje Git) a tu ordenador

Cada *commit* hace una pequeña marca en una línea temporal. Git lleva un registro de CADA UNA de estas pequeñas marcas.

El segundo paso 6 (volviendo a hacer pull desde la nube) en tu flujo de trabajo es cuando es más probable que tengas que “combinar (o *merge*) conflictos”

Los conflictos resuelvelos, guárdalo (haz commit) y haz *push*. Pero asegúrate de hacer otro *pull* antes

Cada vez que guardas (o haces *commit*, más bien) de algunos cambios, Git te pide un “mensaje de *commit*”. Esto son un par de frases que describen los cambios que hiciste: un breve resumen para que alguien pudiera revisar la lista de cambios en este documento, sin tener que leerlo entero.