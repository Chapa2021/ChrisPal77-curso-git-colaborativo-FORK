# GIT STASH
El git stash guarda lo que está en el working directory en un area temporal.

## Crea un stash

```bash
git stash
```

## Lista los stash 
```bash
git stash list
```

# .gitignore
Este archivo es un blacklist de archivo. Todos archivos que coloque dentro de el archivo .gitignore, van ser descartados

# GIT Log
Cuando estoy dentro del comando para salir tengo presionar la tecla **q** del teclado

# Corregir el última descripción del commit
Si me equivoco en el última descripción del commit puedo corregirlo con git amend

```bash
git commit --amend -m "Agrego lo de git log"
```
# ADD y COMMIT todo junto
**IMPORTANTE:** Tengo que tener en el Staging AREA.

```bash
git commit -am "Nombre del commit"
```


