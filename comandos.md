$ git clone https://github.com/DavidBernalGonzalez/practicaGit.git  
$ git cd practicaGit  
$ git checkout practica01  
$ git status 
$ git add . 
$ git commit -m "Hago un commit de los ficheros editados"  
$ git branch practica01_APELLIDOS_NOMBRE  
$ git checkout practica01_APELLIDOS_NOMBRE 
*Creamos el fichero practica01_APELLIDOS_NOMBRE.txt y ponemos cualquier cosa  
$ git status  
$ git add .
$ git commit -m "Creo el archivo practica01_APELLIDOS_NOMBRE.txt"  
*Editamos el fichero para poner nuestro nombre y apellidos  
$ git add .  
$ git commit -m "Editamos el fichero para añadr nuestro nombre"  
$ git push origin practica01_APELLIDOS_NOMBRE  
*Da error al no tener permisos con DavidBernalGonzalez  
$ git remote rv origin  
*Eliminamos el remote actual  
$ git remote add origin https://github.com/RogerPuig1997/repo07.git  
*Connectamos con un nuevo remote en nuestra cuenta de GitHub  
$ git push origin practica01_APELLIDOS_NOMBRE  
*Ahora si que nos deja hacer un push de los commits  
$ git checkout practica01  
$ git merge --no-ff practica01_APELLIDOS_NOMBRE -m "Hacemos un merge con practica01"  
*Merge entre las ramas practica01 y practica01_APELLIDOS_NOMBRE  