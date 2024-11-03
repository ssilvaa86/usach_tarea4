# usach_tarea4
Este es un proyecto de prueba para a aprender a usar git en colaboración

# Comandos 

## Iniciales luego de crear el repositorio
echo "# usach_tarea4" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ssilvaa86/usach_tarea4.git
git push -u origin main

## Ramas

### Listar
git branch

### Crear
git branch rama-oscar
### Cambiar de rama y posicionar
git checkout rama-oscar
### Borrar rama
git branch -d rama-oscar

## Commits

### Ver estado de los cambios
git status
### Agregar los cambios
git add .
### Crear el commit y un mensaje del cambio
git commit -m "Nuevo cambio"
### Resetear para volver a un punto anterior (borra todos los cambios por el --hard)
git reset --hard 6a75c78708d7edd3afd72e52bbac926a081a5610

## Comandos para trabajar con el repositorio en la nube

### Clonar repositorio
git clone https://github.com/ssilvaa86/usach_tarea4.git
### Enlazar repositorio
git remote add origin https://github.com/ssilvaa86/usach_tarea4.git
### Subir cambios al repositorio en la nube
git push origin main
### Bajar cambios
git fetch
### Combinar cambios
git merge
