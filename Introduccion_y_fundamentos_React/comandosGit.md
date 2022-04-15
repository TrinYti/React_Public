# git config credential.helper
devuelve : manager-core

-------------------------------------------------------
error
# git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/TrinYti/React_Public.git'

# git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/TrinYti/React_Public.git'

 PEKOS PAUL K LEE@PEKOSPAULKLEE MINGW64 /d/PrOgRamEIcHoN/2-MERN/React_Public (main)
# $ git push -u origin main
remote: Permission to TrinYti/React_Public.git denied to
Lomachk.
fatal: unable to access 'https://github.com/TrinYti/React_Public.git/': The requested URL returned error: 403
-------------------------------------------------------
SOLUCIONANDO ERROR
 
cambiando usuario
# git config user.name TrinYti
# git config credential.username TrinYti

# git push -u origin main
(Devolveria todo lo que se deberia subir)

Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (6/6), 715 bytes | 357.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/TrinYti/React_Public.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

*** FUENTE DE LA SOLUCION :
https://stackoverflow.com/questions/47465644/github-remote-permission-denied
-------------------------------------------------------

------------
# Crear Repositorio
- git init name_repository
------------
# Directoriaos , carpetas y Archivos

Crear carpeta
- mkdir name_folder

Moverse a una carpeta
- cd

editar un Archivo
- vim file.xt

Mostrar carpetas o Archivos creados
- ls

Borrar Carpetas o Archivos
rm file.txt

Forzr Borrado
rm -rf file.txt

Limpiar consola
- clear




------------
# Branchs
Crear una nueva rama
# git branch name_branch

Borrar una nueva rama
# git branch -d name_branch

Forzar Borrar una nueva rama
# git branch -D name_branch

Mostrar listas de las Ramas
# git branch -l

Renombrar una Rama
# git branch -m name_branch new_name_branch

Moverse entre Ramas
# git checkout name_branch

Crear una Rama y moverse a ella
# git checkout -b name_branch
***Importante para subir la rama creada usar:
git push --set-upstream origin colaborador-1



