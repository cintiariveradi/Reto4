# reto4
reto4
reto colaborativo con kathy pero faltó otorgar permisos asi que hice el mio propio con dos archivos de ella.
Estos fueron los comandos que utilicé 

Cintia: Nuevo archivo repositorio reto 4

1) clonar --- "git clone" https://github.com/Kathefuenzalida/reto4.git

🔹 2. Acceder a la carpeta del repositorio
Después de clonar, mover a la carpeta con: "cd reto4"

🔹3.  "git status"

🔹 4. Modificar archivos txt 


🔹 5. Agregar los cambios a Git con "git add ."

🔹 6. Realizar un commit  "git commit -m "mi segundo commit""

🔹 7. Subir los cambios a GitHub con "git push origin main" aqui es donde no se otorgaron permisos asi que hice el mío:

Cintismac:reto4 cintillo$ git branch -M main
Cintismac:reto4 cintillo$ git remote add origin https://github.com/cintiariveradi/Reto4.git
Cintismac:reto4 cintillo$ git push -u origin main
remote: Permission to Kathefuenzalida/Reto4.git denied to cintiariveradi.
fatal: unable to access 'https://github.com/Kathefuenzalida/Reto4/': The requested URL returned error: 403
Cintismac:reto4 cintillo$ git remote -v
origin	https://github.com/Kathefuenzalida/Reto4 (fetch)
origin	https://github.com/Kathefuenzalida/Reto4 (push)
Cintismac:reto4 cintillo$ git remote set-url origin https://github.com/cintiariveradi/Reto4.git
Cintismac:reto4 cintillo$ git push -u origin main
Counting objects: 12, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (9/9), done.
Writing objects: 100% (12/12), 2.16 KiB | 2.16 MiB/s, done.
Total 12 (delta 0), reused 0 (delta 0)
To https://github.com/cintiariveradi/Reto4.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
Cintismac:reto4 cintillo$ 



🔹 8. Descargar cambios recientes (git pull)

NOnecesario: 
git pull origin main
