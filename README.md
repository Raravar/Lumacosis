# Lumacosis

ABRIR EN PANTALLA COMPLETA
**************************************************************************************************************************************************************
						COMANDOS GITHUB
 _____________________________________________________________________________________________________________________________________________________________
|      Comando		 --			Ejemplo				--	Descripción							     |
|                            																     |
|git clone URL  	 --	 git clone https://github.com/user/test.git 	--	Clona el repositorio a nuestro directorio		             |
|git pull origin RAMA	 --	 git pull origin user-brench			--									     |
|git pull origin main	 --      git pull origin main				--	Actualiza el repositorio local en base al remoto		     |
|																			     |
|git branch 		 --	 git branch 					--	Muestra las ramas disponibles y la actual con *			     |
|git branch nombre	 --	 git branch nueva-Rama				--	Crea una nueva brench						     |
|git checkout nombre	 --	 git checkbout nueva-rama			--	Se mueve a la brench nueva-rama					     |
|																			     |
|git add 		 -- 	 git add .					--	Guarda los cambios en el repositorio local . para agregar todo       |
|git commit -m "descrip" --	 git commit -m "Nueva modificacion de ..."	--	Genera commit al repositorio local con un comentario.                |
|git push origin RAMA	 --	 git push origin master				--	Sube todo al repositorio en la rama principal (MASTER)               |
_____________________________________________________________________________________________________________________________________________________________|
																	   
**************************************************************************************************************************************************************
Subir ediciones al repositorio:
1. git add .      				-- Añade todos los cambios
2. git commit -m "descripcion del cambio"	-- Confirma los cambios
3. git push origin master			-- Sube los cambios a la rama principal MASTER
**************************************************************************************************************************************************************
Trabajar en otra rama:
1. git checkout nombre-brench			-- Se mueve a la rama nombre-brench
2. git add .					-- Se añaden todos los cambios
3. git commit -m "descripcion del cambio"	-- Confirma los cambios
4. git push origin nombre-branch		-- Sube los cambios al repositorio remoto.
**************************************************************************************************************************************************************
Clonar otra rama a repo local:
git clone -b raravar-branch https://github.com/Raravar/Lumacosis.git
