1. Flujo colaborativo
Supón que quieres colaborar con el repositorio de otro desarrollador. Ordena y explica los siguientes elementos:
Push, Fork, Pull Request, Clone, Merge, Commit, Review, Branch y Modificar archivos. Agrega cualquier
operación que consideres necesaria.

Fork: Copia el repositorio a tu cuenta.
Clone: Descarga el proyecto a tu computadora.
Branch: Crea una rama de trabajo.
Modificar archivos: Realiza cambios al código.
Commit: Guarda los cambios.
Push: Sube los cambios a GitHub.
Pull Request: Solicita integrar los cambios al original.
Review: Revisa los cambios.
Merge: Integra los cambios al repositorio original.

2. Fork y Clone
Analiza la afirmación: “Clone crea una copia del proyecto dentro de mi cuenta de GitHub”. Indica si es correcta
y explica la diferencia entre Fork y Clone.

No es correcta, el clone crea la copia del proyecto en tu vscode, no en tu cuenta de github, el que copia el repositorio original en tu cuenta de github es el fork.

3. Pull Request
Supón que realizaste Fork, Clone, Branch, Modificar, Commit y Push. Responde: ¿los cambios ya forman parte
del repositorio original? ¿Qué debe ocurrir para incorporarlos?

Si trabajaste en una rama secundaria, aun no forman parte del proyecto original, tienes que subirlos a tu fork y despuies hacer un pull request.

4. Request Changes
El propietario revisa tu Pull Request y selecciona Request Changes. Explica qué debes hacer, si necesitas crear
otro Pull Request y qué ocurre cuando realizas nuevamente push.

No necesito hacer otro pull request, los cambios aparecen en el mismo cuando los hago.

5. Merge y repositorio local
Un Pull Request fue aceptado y se realizó Merge en GitHub. Sin embargo, el repositorio local del propietario no
contiene los cambios. Explica por qué sucede y qué operación debe realizarse. 

Debe actualizar su proyecto haciendon git pull.

6. Sync Fork
Tu Fork fue creado varios días atrás y el repositorio original recibió nuevos commits. Explica qué herramienta
utilizarías, qué repositorio se actualiza y qué diferencia existe entre Sync Fork y git pull.
Registra este cambio en un cuarto commit con un mensaje descriptivo y súbelo a github.

Utilizaría Sync fork para actualizar mi Fork en GitHub, git pull solo actualiza mi repositorio local, Sync fork actualiza mi copia remota.