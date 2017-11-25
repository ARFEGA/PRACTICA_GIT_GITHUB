- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset —hard HEAD~1 - ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git reset —hard <commit> para conseguir desplazar Head y Styled

 - El merge del paso 13, ¿Causó algún conflicto? ¿Por qué? 
No creo conflicto


- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? 
Si, por ser styles quien absorbe a htmlify y haberse en esta rama realizado un cambio posterior en el fichero.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué? 
No creo conflictos

- ¿Qué comando o comandos utilizaste en el paso 25?
git merge --no-ff title
 - El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 
Creo que no, quedaría un commit “inalcanzable”

- ¿Qué comando o comandos utilizaste en el paso 27? 
git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28? 
git checkout git-nuestro.md

- ¿Qué comando o comandos utilizaste en el paso 29? 
git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30? 
git reset --hard b15aa57 

- ¿Qué comando o comandos usaste en el paso 32? 
git reset --hard 565a1b4

- ¿Qué comando o comandos usaste en el punto 33? 
git reset --hard 4a5b89c
Es el commit concreto cuando se añade el titulo, luego se hace emerge con title, pero has pedido cuando se pone titulo, supongo que es correcto.
