 preguntas:
-¿Qué comando utilizaste en el paso 11? ¿Por qué? 
Git reset --hard HEAD~1   para perder los cambios
-¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué? 
primero un git log  
despues mire el sitio donde estaba y era este:
$ git reset --hard ea6d9cf


-El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

no, creo que he escrito en el primer commit algo que no debia y por esos 
no me da error, pero hasta el
momento no me da error


-El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? 
si

se repetian lieneas



-El merge del paso 21, ¿Causó algún conflicto? ¿Por qué? 

No.
Updating 8732c18..ea6d9cf
Fast-forward
 nuestro.md | 21 ++++++++++-----------
 1 file changed, 10 insertions(+), 11 deletions(-)



¿Qué comando o comandos utilizaste en el paso 25? 
git log --graph

-El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

no, porque modifica el commit

-¿Qué comando o comandos utilizaste en el paso 27?
 git reset --hard HEAD~1


-¿Qué comando o comandos utilizaste en el paso 28?
$ git checkout nuestro.md

-¿Qué comando o comandos utilizaste en el paso 29?

$ git branch -D title



-¿Qué comando o comandos utilizaste en el paso 30?
$ git branch title
con el nombre de la rama



-¿Qué comando o comandos usaste en el paso 32?





-¿Qué comando o comandos usaste en el punto 33?
$ git reset --hard 7c4822c

