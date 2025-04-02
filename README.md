# Tarea-Git-1-Comandos-Basicos-en-Local
Escribe los comandos según su descripción:<br/><br/>
1-Transforma el directorio actual en un repositorio de Git. Se añade un subdirectorio de .git con todos los archivos necesarios del repositorio<br/>
**git init**<br/><br/>
2-Especifica qué archivos quieres añadir al repositorio (a staging area, staged). Prepara los archivos modificados<br/>
**git add test1.txt**<br/><br/>
3-Confirma los cambios (a directorio git, committed)<br/>
**git commit -m “el mensaje”**<br/><br/>
4-Clona un repositorio existente<br/>
**git clone**<br/><br/>
5-Muestra el estado de los archivos<br/>
**git status**<br/><br/>
6-Muestra estado abreviado<br/>
**git status -s**<br/><br/>
7-Ignora archivos<br/>
**.gitignore**<br/><br/>
8-Mostrar los cambios: líneas exactas que fueron añadidas y eliminadas. Compara lo que tienes en tu directorio de trabajo con lo que está en el área de preparación<br/>
**git diff**<br/><br/>
9-Mostrar los cambios: líneas exactas que fueron añadidas y eliminadas. Compara tus cambios preparados con la última instantánea confirmada<br/>
**git diff - -stage**<br/><br/>
10-Confirma los cambios sin pasar por el área de preparación (a directorio git, committed)<br/>
**git commit**<br/><br/>
11-Eliminar archivos del directorio de trabajo y del área de preparación
**git rm**<br/><br/>
12-Renombrar archivos del directorio de trabajo y del área de preparación<br/>
**git mv**<br/><br/>
13-Muestra el historial de confirmaciones<br/>
**git log**<br/><br/>
14-Muestra sólo las dos últimas confirmaciones indicando las diferencias introducidas en cada confirmación<br/> 
**git log -2**<br/><br/>
15-Rectifica el último commit<br/>
**git commit - - amend**<br/><br/>
