- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1
 He usado este comando para mantener los cambios realizados en el working copy

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git reflog
git reset --hard identificador commit (f01700c)
He usado esos comandos primero para localizar el commit qye quiero recuperar y el siguiente para ponerme en el commit que quiero recuperar.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No, causo ningún conflicto porque es un merge fast-forward y al estar en una lista no genera conflicto.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Si, genera conflicto porque se han tocado las mismas lineas de dos ramas que no están en la misma lista.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No, crea ningún conflicto porque es un merge entre dos ramas que forman una lista.

- ¿Qué comando o comandos utilizaste en el paso 25?
git log --graph --decorate --pretty=oneline

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Si se podría generar un merge fast forward ya que están en la misma lista y no crearía conflictos.

- ¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28?
git checkout -- gitnuestro.md

- ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?
git reflog
git checkout identificasdor merge (af2cb8e)

- ¿Qué comando o comandos usaste en el paso 32?
git reflog
git checkout identificador commit (a0f7649)

- ¿Qué comando o comandos usaste en el punto 33?
git reflog
git checkout identificador commit (bcc2bb6)
