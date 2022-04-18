#Mi pagina de HTML
En este codigo podemos ver las diferentes opciones que podemos usar para generar nuestra pagina HTML
```shell
#Para usuarios que no sean propietarios o que no tengan configurado la ssh key
$ git clone git@github.com:KevyJQ/HTML.git
$ cd HTML
```
Si tienes configurado la llave ssh, utiliza este comando

```shell
#Para el propietario y tienes la llave ssh
$ git clone git@github.com:KevyJQ/HTML.git
```
## Como ver informacion del projecto

```shell
$ git branch
* master
$ git branch -va
* master                e5fca6a Descripcion del sistema
  remotes/origin/HEAD -> origin/master
  remotes/origin/master e5fca6a Descripcion del sistema`
## Como subir nuevo codigo

Primero agrega los archivos al cache de git.

```shell
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

    modified:   README.md
```

no changes added to commit (use "git add" and/or "git commit -a")

# Agrega los archivos nuevos y modicados
$ git add README.md

$ git status
On branch master
Your branch is up to date with 'origin/master'.

#Guarda cambios en repositorio local
$ git commit
```
## Haz push de tus cambios

```shell
# Comando: git push remote_repo remote_branch_name:local_branch_name
$ git push origin master:master
```

