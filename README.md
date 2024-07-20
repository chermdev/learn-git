[[# Learn Git

Guide to remember the most common git commands.

---

## Basics (init, clone)

### git init

|             command              |                  description            |
|----------------------------------|-----------------------------------------|
|<pre>git init</pre>| initialize git in a folder to start from zero. |


### git clone

|             command              |                  description            |
|----------------------------------|-----------------------------------------|
|<pre>git clone _\<repo url>_ _\<optional: path>_</pre>| start from another repo. (clone a repo) |

Examples

|name|code|notes|
|---|---|---|
|clone this repo|<pre>git clone https://github.com/chermdev/learn-git</pre>|This will create `learn-git` folder<br><br>by default the path will be the name of the repo.|
|clone this repo with a custom path (e.g.: `/git-learn`)|<pre>git clone https://github.com/chermdev/learn-git git-guide</pre>||

---

## Config

### git config --global 

It's important to identify you in your commits, so add your info with:

```bash
git config --global user.name "<your name>"
git config --global user.email "<your email>"
```
 This will add it globally.

 _**important:**_ Make sure to use the same email from your [github emails](https://github.com/settings/emails) to allow github link your changes with your account.

---

## Origin (set, rename, change)

The origin is where the repo comes from.

### Set origin

You can set the origin with:



### Change origin

## Branch (create, rename, switch, delete, etc)


## Rebase (change commit history)

## Reset (undo changes)



```
git config --global user.name "<your name>"
git config --global user.email "<your email>"

git config --list (ver lista de git config)

git config user.name (ver usuario guardado)
git config user.email (ver correo guardado)

git init (inicializa git en la carpeta)

git add archivo.txt
git status (archivo en verde porque se agrego al stage, rojo es que no se a agregado /git add)
git add --a (agrega todos los archivos)

git commit (aparecera en la terminal que se agrege el comentario, para terminar dar clic en ESC y escribir ":qw")
git commit -m "comentario"

git log (ver historial de commits)

git remote add origin https://github.com/Usuario/Repositorio.git
git remote -v (ver lista de archivos remoto)

git push origin master (enviarlo a master remoto)

git pull origin master (traer cambios nuevos de alguien mas a tu computadora local)
```

](url)](url)
