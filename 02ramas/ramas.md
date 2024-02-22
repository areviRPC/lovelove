
# comando para listar las ramas

git branch

# comando para crear una nueva rama

git branch nombre_rama

# comando para eliminar

git branch -D nombre_rama

# comando para eliminar una rama

git branch -D nombre_rama

# cambiar entre ramas

git switch nombre_rama
git checkout nombre_rama
git checkout -b nombre_rama

# desvincular un archivo de git que se le estaba dando seguimiento

git rm --cached nombre_archivo

# crear una nueva version con archivos que ya se estaban dando seguimiento

git commit -am "nombre commit"

# comando para unir ramas

git merge nombre_rama

# comando para hacer una conexion remota

git remote add nombre_conexion url_conexion

# comando para listar las conexiones remotas

git remote -v

# eliminar una conexion remota

git remote remove nombre_conexion

# cambiar nombre de la rama "master"

git branch -M nombre_rama