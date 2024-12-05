--Comandos básicos de Git

--Configuración inicial

-Configurar nombre de usuario y correo electrónico:
git config --global user.name "Tu Nombre"
git config --global user.email "tuemail@example.com"

--Trabajar con el repositorio

-Clonar un repositorio remoto:
git clone URL_DEL_REPOSITORIO

-Inicializar un repositorio nuevo:
git init

--Rastrear y confirmar cambios

-Ver el estado del repositorio:
git status

--Agregar archivos al área de preparación:

-Agregar un archivo específico:
git add nombre_del_archivo

-Agregar todos los archivos modificados:
git add .

-Confirmar los cambios:
git commit -m "Descripción de los cambios"

-Ver el historial de commits:
git log

--Trabajar con ramas

-Crear una nueva rama:
git branch nombre_de_la_rama

-Cambiar a una rama existente:
git checkout nombre_de_la_rama
git switch nombre_de_la_rama

-Crear y cambiar a una nueva rama directamente:
git checkout -b nombre_de_la_rama

--Actualizar y compartir cambios

-Subir cambios al repositorio remoto:
git push origin nombre_de_la_rama

-Traer cambios del repositorio remoto:
git pull

--Sincronizar con la rama principal (merge):

-Cambiar a la rama principal:
git checkout main

-Unir otra rama a la actual:
git merge nombre_de_la_rama

--Resolver conflictos

-Ver archivos en conflicto después de un merge:
git status