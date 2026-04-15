### Inicializar Git:  
git init

### Cambiar de nombre la rama principal a main:  
git branch -m main

![imagen1][img1]

### Hacer un primer commit llamado "Estructura inicial del proyecto":   
git commit -m "Estructura incial del proyecto"

![imagen2][img2]

### Verificar el historial de commmits de forma resumida en una sola línea:   
git log --graph --decorate --all --oneline

### Crear nueva rama llamada “desarrollo” y pasarse a trabajar en ella:  
git branch desarrollo
git switch desarrollo

### Realice un nuevo commit llamado "Agrega contenido en index":  
git commit -m "Agrega contenido en index"

### Unir ramas main y desarrollo:  
git merge main

![imagen3][img]

### Crear un commit llamado "Cambio temporal":  
git commit -m "Cambio temporal"

### Eliminar el último commit y sus cambios:  
git reset --hard HEAD~1

### Recupere el último commit:  
git reset --hard HEAD@{1}

![imagen5][img5]

### Haga otro commit llamado "Agrega gitignore":  
git commit -m "Agrega gitignore"

### Crear una rama nueva llamada login:  
git branch login
![imagen6][img6]

### Hacer otro commit llamado "Agrega login":  
git commit -m "Agrega login"

![imagen7][img7]
