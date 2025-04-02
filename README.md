# Tarea-Git-1-Comandos-Basicos-en-Local
Escribe los comandos según su descripción:
Transforma el directorio actual en un repositorio de Git. Se añade un subdirectorio de .git con todos los archivos necesarios del repositorio
git init

Especifica qué archivos quieres añadir al repositorio (a staging area, staged). Prepara los archivos modificados
git add test1.txt

Confirma los cambios (a directorio git, committed)
git commit -m “el mensaje”

Clona un repositorio existente
git clone

Muestra el estado de los archivos
git status

Muestra estado abreviado
git status -s

Ignora archivos
.gitignore

Mostrar los cambios: líneas exactas que fueron añadidas y eliminadas. Compara lo que tienes en tu directorio de trabajo con lo que está en el área de preparación
git diff 

Mostrar los cambios: líneas exactas que fueron añadidas y eliminadas. Compara tus cambios preparados con la última instantánea confirmada
git diff - -stage

Confirma los cambios sin pasar por el área de preparación (a directorio git, committed)
git commit
Eliminar archivos del directorio de trabajo y del área de preparación
git rm

Renombrar archivos del directorio de trabajo y del área de preparación
git mv
Muestra el historial de confirmaciones
git log
Muestra sólo las dos últimas confirmaciones indicando las diferencias introducidas en cada confirmación 
git log -2



Rectifica el último commit
git commit - - amend
