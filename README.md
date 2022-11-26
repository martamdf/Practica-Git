# Resolución de Práctica del curso de Git & Github
 
### Respuestas ejercicio 1:

#### 1-  ¿Qué comando utilizaste en el paso 11? ¿Por qué?
Utilicé `git reset --hard HEAD~1`. Dado que debíamos perder los cambios en el working copy, el comando `reset` debía llevar el modificador de comportamiento --hard, para que así se ejecutara. 

#### 2-  ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
Utilicé primero `git reflog`, para poder localizar el id del commit que quería recuperar. Una vez localizado el id del commit, ejecuté `git reset <id commit>` y posteriormente `git restore` para dejar working copy y repositorio tal cual estaba antes del reset.

#### 3-  El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No ha causado ningún conflicto, porque no se realizaron ediciones simultáneas de ninguna parte del contenido del archivo.

#### 4-  El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Sí, dado que se habían realizado ediciones simultáneas del contenido del archivo en las dos ramas.

#### 5-  El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No, no hubo conflictos porque no había cambios simultáneos en `master` y `styled`.

#### 6-  ¿Qué comando o comandos utilizaste en el paso 25?
Utilicé `git log --graph`.

#### 7-  El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Sí. Podría haberse hecho Fast Forward, los commits llevaban una progresión lineal en el grafo, por lo que realmente no era necesario un No Fast Forward, pero de este modo, nos aseguramos de no perder commits.

#### 8-  ¿Qué comando o comandos utilizaste en el paso 27?
Utilicé `git reset HEAD~1`.

#### 9-  ¿Qué comando o comandos utilizaste en el paso 28?
Utilicé `git restore git-nuestro.md`.

#### 10- ¿Qué comando o comandos utilizaste en el paso 29?
Utilicé `git branch -D title`.

#### 11- ¿Qué comando o comandos utilizaste en el paso 30?
Primero utilicé `git reflog` para localizar el commit en cuestión y su id y después ejecuté un `git reset <id commit>`.

#### 12- ¿Qué comando o comandos usaste en el paso 32?
Primero utilicé `git reflog` para localizar el commit en cuestión y su id y después ejecuté un `git reset <id commit>`.

#### 13- ¿Qué comando o comandos usaste en el paso 33?
Primero utilicé `git reflog` para localizar el commit en cuestión y su id y después ejecuté un `git reset <id commit>`.
