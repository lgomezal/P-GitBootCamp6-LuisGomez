# Respuestas a las preguntas de la práctica
- ¿Qué comando utilizaste en el paso 11? ¿Por qué?

	git reset --hard HEAD~1 , para dejar la 	WorkingCopy como estaba en el commit 	anterior o padre.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

	git reflog , para buscar el commit al 	que debemos ir.
	
	git reset --hard ba5a878 , para ir al commit que 	tenía la modificación y para que 	modifique la 	WorkingCopy ponemos el --hard.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

	git merge master , no hace el merge ya que no es 	necesario, no causó ningún conflicto ya 	que la rama styled es hija de master y por tanto 	el comit que actualmente tiene master ya es 	visible desde style. 
	

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

	git merge --no-ff htmlify , causa conflicto porque 	se han modificado las mismas líneas en el archivo 	git-nuestro.md, editamos y nos quedamos con la 	parte 	de la rama styled.


- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

	git merge styled, no causa conflicto, realiza un 	merge fast-forward y master apunta al último 	commit de styled 


- ¿Qué comando o comandos utilizaste en el paso 25?

	git log --graph --decorate --pretty=oneline


- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 

	Si, de hecho debería porque este es recursivo


- ¿Qué comando o comandos utilizaste en el paso 27?

	git reset HEAD~1


- ¿Qué comando o comandos utilizaste en el paso 28? 

	git checkout git-nuestro.md


- ¿Qué comando o comandos utilizaste en el paso 29? 

	git branch -D title	


- ¿Qué comando o comandos utilizaste en el paso 30? 

	git reflog
	
	git reset --hard 99f1c48


- ¿Qué comando o comandos usaste en el paso 32?

	git reflog

	git reset --hard a9004cf


- ¿Qué comando o comandos usaste en el punto 33?

	git reflog

	git reset --hard 99f1c48

