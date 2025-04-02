# Tarea-Git-1-Comandos-Basicos-en-Local
Escribe los comandos según su descripción:<br/><br/>
Transforma el directorio actual en un repositorio de Git. Se añade un subdirectorio de .git con todos los archivos necesarios del repositorio<br/>
**git init**<br/><br/>
Especifica qué archivos quieres añadir al repositorio (a staging area, staged). Prepara los archivos modificados<br/>
**git add test1.txt**<br/><br/>
Confirma los cambios (a directorio git, committed)<br/>
**git commit -m “el mensaje”**<br/><br/>
Clona un repositorio existente<br/>
**git clone**<br/><br/>
Muestra el estado de los archivos<br/>
**git status**<br/><br/>
Muestra estado abreviado<br/>
**git status -s**<br/><br/>
Ignora archivos<br/>
**.gitignore**<br/><br/>
Mostrar los cambios: líneas exactas que fueron añadidas y eliminadas. Compara lo que tienes en tu directorio de trabajo con lo que está en el área de preparación<br/>
**git diff**<br/><br/>
Mostrar los cambios: líneas exactas que fueron añadidas y eliminadas. Compara tus cambios preparados con la última instantánea confirmada<br/>
**git diff - -stage**<br/><br/>
Confirma los cambios sin pasar por el área de preparación (a directorio git, committed)<br/>
**git commit**<br/><br/>
Eliminar archivos del directorio de trabajo y del área de preparación
**git rm**<br/><br/>
Renombrar archivos del directorio de trabajo y del área de preparación<br/>
**git mv**<br/><br/>
Muestra el historial de confirmaciones<br/>
**git log**<br/><br/>
Muestra sólo las dos últimas confirmaciones indicando las diferencias introducidas en cada confirmación<br/> 
**git log -2**<br/><br/>
Rectifica el último commit<br/>
**git commit - - amend**<br/><br/>
