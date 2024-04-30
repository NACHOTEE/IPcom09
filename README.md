# IPcom09

La tarea consiste en clonar este repositorio, modificarlo, y subir los cambios realizados de nuevo al repositorio remoto.
---

# Paso a paso:
### Paso 1: clonar el repositorio
```bash
$ git clone https://github.com/LuciaSoria5/IPcom09.git
```

### Paso 2: modifcar el archivo
- Deben abrir el archivo prueba.py, buscarse en la lista, y escribir algo en donde dice "ESCRIBIR AQUI".
- Una vez que realizaron los cambios, guardan el archivo.

### Paso 3: agregar cambios al stage
```bash
$ git add .
```

### Paso 4: confirmar cambios
```bash
$ git commit -m "Mensaje descriptivo del cambio"
```

### Paso 5: actualizar el repositorio local
```bash
$ git pull
```
_Nota_: como todos modifican en renglón que corresponde a sus nombres, no debería haber conflictos.

### Paso 6: subir el commit a remoto
```bash
$ git push -u origin main
```

## Extras:
## Para ver el estado actual del repositorio local:
```bash
$ git status
```
## Para configurar GitBash por primera vez:
```bash
$ git config --global user.name "Tu nombre"
$ git config --global user.email "tu_email_de_github@ejemplo.com"
```