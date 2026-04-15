### Inicializar Git:  
git init

### Cambiar de nombre la rama principal a main:  
git branch -m main

![Imagen 1](src/main/resources/static/img/imagen1.png)

### Hacer un primer commit llamado "Estructura inicial del proyecto":   
git commit -m "Estructura incial del proyecto"

![Imagen 2](src/main/resources/static/img/imagen2.png)

### Verificar el historial de commmits de forma resumida en una sola línea:   
git log --graph --decorate --all --oneline

### Crear nueva rama llamada “desarrollo” y pasarse a trabajar en ella:  
git branch desarrollo
git switch desarrollo

### Realice un nuevo commit llamado "Agrega contenido en index":  
git commit -m "Agrega contenido en index"

### Unir ramas main y desarrollo:  
git merge main

![Imagen 3](src/main/resources/static/img/imagen3.png)

### Crear un commit llamado "Cambio temporal":  
git commit -m "Cambio temporal"

### Eliminar el último commit y sus cambios:  
git reset --hard HEAD~1

### Recupere el último commit:  
git reset --hard HEAD@{1}

![Imagen 5](src/main/resources/static/img/imagen5.png)

### Haga otro commit llamado "Agrega gitignore":  
git commit -m "Agrega gitignore"

### Crear una rama nueva llamada login:  
git branch login
![Imagen 6](src/main/resources/static/img/imagen6.png)

### Hacer otro commit llamado "Agrega login":  
git commit -m "Agrega login"

![Imagen 7](src/main/resources/static/img/imagen7.png)







