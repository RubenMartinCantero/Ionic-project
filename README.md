# Ionic_proyect


Instalación previa necesaria: 
	
	node.js
	npm
	angular
	react

Para instalar ionic: 

	npm install -g ionic

Instalar cordova apache:
	
	npm install -g cordova

Inicializar ionic y crear un proyecto nuevo:

	ionic start: automaticamente podrás ir seteando la configuración que desees para tu proyecto.

Arrancar ionic una vez instalado todo:

	entrar en el directorio a arrancar y escribir en consola (sin comillas) "ionic serve"





Reglas del proyecto.
	
	Rama develop tiene la configuración inicial, de la cual divergen ramas según se desarrolle el proyecto.
Cada rama nueva estará enlazada con una funcionalidad nueva a incluir en la app, una vez esa funcionalidad esté 
revisada por todos los participantes del proyecto y deba ser incluida en "develop" se realizará un merge a dicha
rama. Si se encuentra un error en la rama develop, a través de la rama release se arreglará antes de subir a master. 
Y si en master se encuentra algún error, se hará uso de la rama hotfix para subsanarlo.

A continuación se explica con mayor profundidad dicho funcionamiento:

Git-flow

	En el proyecto se seguirá una dinámica de estructura basada en Git-flow, donde cada rama deben tener los 
siguientes nombres:

	Rama master: cualquier commit que pongamos en esta rama debe estar preparado para subir a producción.

	Rama develop: rama en la que está el código que conformará la siguiente versión planificada del proyecto.

	feature: se utilizan para desarrollar nuevas características de la aplicación que, una vez terminadas, 
		 se incorporan a la rama develop.

	release: se utilizan para preparar el siguiente código en producción. En estas ramas se hacen los últimos ajustes 
	         y se corrigen los últimos bugs antes de pasar el código a producción incorporándolo a la rama master.

	hotfix:  se utilizan para corregir errores y bugs en el código en producción. Funcionan de forma parecida a las 
		 Releases Branches, siendo la principal diferencia que los hotfixes no se planifican.



Cosas a incluir
	Añadir reglas al proyecto
	Estructura del projyecto (que hacer, como hacerlo)
	Reglas de lintado de codigo
	Reglas de otro tipo
	Actualizar github para poner pullrequest o bloquear master/develop a la hora de hacer push-merge (si no sabemos, 
investigar como se hace o dejarlo así, como veamos)

	



