# Bajamos un theme de

```
https://startbootstrap.com/themes/resume/
```

## Variables globales que siempre hay que configurar por primera vez ni bien se instala git

```
git config --global user.name
git config --global user.email

git config --global user.name "Juan Carlos Valdés"
git config --global user.email "idevkingos@gmail.com"
```

## Clonar Repositorios

```
git clone https://github.com/jcvaldes/github-repo.git
```

## Crear branches

```
git branch [rama]
git checkout -b [rama]

Elimino una rama
git branch -d [rama] (editado) 
```

# crea un repositorio local
git init
# chequea los nuevos cambios que tengo pero no han sido registrados
git status

## los archivos pasan al stage area para posteriorment formar parte de un snapshoot que vamos a hacer con commit
git add . o git add -A o git add --all
git add miarchivo.html
git add *.png

## agrego al stage todos los css que modifique
git add css/

## creo un snapshot es decir crea un respaldo historico en el tiempo
git commit -m "Primer commit"
luego hacer git status

#revertir un desastre

git checkout -- .
o
git reset --hard

## Crear Alias
git config --global alias.lg "log --oneline --decorate --all --graph"
git config --global alias.s "status -sb"
