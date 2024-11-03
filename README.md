# usach_tarea4
Este es un proyecto de prueba para a aprender a usar git en colaboración

# Comandos 

## Iniciales
echo "# usach_tarea4" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ssilvaa86/usach_tarea4.git
git push -u origin main

## Clonar repositorio
git clone https://github.com/ssilvaa86/usach_tarea4.git

## Ramas
### Listar
git branch

### Crear
git branch rama-oscar

### Cambiar de rama y posicionar
git checkout rama-oscar

## Commits
### Agregar los cambios
git add .
### Crear el commit y un mensaje del cambio
git commit -m "Nuevo cambio"
### Resetear para volver a un punto anterior (borra todos los cambios por el --hard)
git reset --hard 6a75c78708d7edd3afd72e52bbac926a081a5610
