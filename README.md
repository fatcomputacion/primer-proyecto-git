# Curso de _Git_ & _Github_

Hola esta es mi primera prueba de uso de GIT.

# agregar los cambios de un archivo al staged

git add archivo/directorio

# agregar todos los cambios de todos los archivos al staged

git add .

# para que los cambios tengan efecto

git commit -m "mensaje descriptivo del cambio"

# se agrega el origen remoto de tu repositorio de GitHub

git remote add origin https://github.com/usuario/repositorio.git

# la primera vez que vinculamos el repositorio remoto con el local

git push -u origin master

# para las subsecuentes actualizaciones, sino cambias de rama

git push

# para descargar los cambios del repositorio remoto al local

git pull
