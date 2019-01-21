#Preguntas:

- ¿Qué comando utilizaste en el paso 11?¿Por qué? git reset --hard HEAD~1 .Porque se me pedia que Deshacer el último commit perdiendo los cambios realizados en el working copy, si 
hubise hecho git reset HEAD~1 no hubiera borrado el commit pero hubiera mantenido lo que tenia en mi working copy.

- ¿Qué comando o comandos utilizaste en el paso 12?¿Por qué? git reset e19a72c Por que necesitamos rehacer el último comit, le indico el hash del comit al que me referia. 

- ¿El merge del paso 13, ¿Causó algún conflicto? ¿Por qué? git merge master. Me dijo que ya estaba uptodate, por que no detectava diferencias.

- ¿El merge del paso 19, ¿Causó aĺgún conflicto? ¿Por qué? Si encontramos un conflicto. Se encuentra dos  archivos iguales con distinto contenido. Tal y como nos dice el ejercicio 
guardamos el de la rama Styled.

- ¿EL merge del paso 21, ¿Causó algún conflicto? ¿Por qué?  No creamos conflicto por que hacemos un commit fast forward entre master y styled. 

- ¿Qué comando o comandos utilizaste en el paso 25? Hacemos git los --graph. 

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? Si podría ser fast forward por que los diferentes commit estan en una sola lista. En este caso master absorve el trabajo en 
style.

- ¿Qué comando o comandos utilizaste en el paso 27? Hacemos un git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28? Hacemos git checkout --git-nuestro.md

- ¿Qué comando o comandos utilizaste en el paso 29? Lo hacemos con git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30? Hago un git reflog para ver todas las referencias.  Despues hacemos git checkout + el identificador  al punto donde estava la rama 
antes. , hacemos git branch title para ponernos en la rama correcta, git checkout master git merge --no-ff title 

- ¿Qué comando o comandos utilizaste en el paso 32? Primero hacemos un git reflog, despues hago un git checkout + el identificador del comet donde queremos ir.

- ¿Qué comando o comandos utilizaste en el paso 33? Primero hacemos un git reflog, despues hago un git checkout + el identificador del commit donde queremos ir. 

