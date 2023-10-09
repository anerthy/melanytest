# Como subir un proyecto a un repositorio en GITHUB
Despues de crear el repositorio ir a la **terminal** o **git bash** y seguir los siguientes pasos:

1. Inicia un nuevo repositorio Git en el directorio actual.
    `git init`

2. Establece un enlace remoto llamado "origin" a un repositorio en GitHub.
    `git remote add origin https://github.com/anerthy/melanytest.git`

3. Agrega todos los archivos modificados al área de preparación (staging area).
    `git add .`

4. Muestra el estado actual de los archivos en el repositorio y la área de preparación. ( paso opcional! )
    `git status`

5. Crea un nuevo commit con un mensaje descriptivo.
    `git commit -m "first commit"`

6. Renombra la rama actual a "main".
    `git branch -M main`

7. Sube los cambios al repositorio remoto en la rama "main" y establece "main" como la rama predeterminada para futuros empujes.
    `git push -u origin main`