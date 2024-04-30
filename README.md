## Comandos basicos de Git y Github


    Configurar Git:
        git config --global user.name "Tu Nombre": Configura tu nombre de usuario en Git.
        git config --global user.email "tu@email.com": Configura tu dirección de correo electrónico en Git.

    Crear un repositorio:
        git init: Inicializa un nuevo repositorio Git en el directorio actual.
        git clone <URL>: Clona un repositorio Git existente desde una URL remota a tu directorio local.

    Hacer cambios:
        git status: Muestra el estado de los archivos en tu repositorio local.
        git add <nombre_archivo>: Agrega un archivo al área de preparación (staging) para ser commitado.
        git add .: Agrega todos los archivos modificados y nuevos al área de preparación.
        git commit -m "Mensaje de commit": Guarda los cambios confirmados en el repositorio.

    Trabajar con ramas:
        git branch: Muestra las ramas en tu repositorio local.
        git branch <nombre_rama>: Crea una nueva rama.
        git checkout <nombre_rama>: Cambia a una rama específica.
        git merge <nombre_rama>: Fusiona una rama específica con la rama actual.

    Sincronizar con repositorios remotos:
        git remote add origin <URL>: Agrega un repositorio remoto llamado "origin".
        git push -u origin <nombre_rama>: Sube la rama actual al repositorio remoto.
        git pull origin <nombre_rama>: Obtiene y fusiona los cambios del repositorio remoto en tu rama local.
        git fetch origin: Obtiene los cambios del repositorio remoto sin fusionarlos con tu rama local.

    Otros comandos útiles:
        git log: Muestra el historial de commits.
        git diff: Muestra las diferencias entre cambios realizados y el estado actual.
        git reset <nombre_archivo>: Quita un archivo del área de preparación (staging), pero conserva los cambios.
        git reset --hard: Descarta todos los cambios locales y regresa al último commit.

¡Estos comandos deberían ayudarte a empezar con Git y GitHub!
