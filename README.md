# Learn Git

Guide to remember the most common git commands.

---

## Start in git

### git init

|             command              |                  description            |
|----------------------------------|-----------------------------------------|
|<pre>git init</pre>|initialize git in a folder to start from zero.|


### git clone

|             command              |                  description            |
|----------------------------------|-----------------------------------------|
|<pre>git clone _\<repo url>_ _\<optional:path>_</pre>| start from another repo. (clone a repo)|

Examples

|command|action|notes|
|---|---|---|
|<pre>git clone https://github.com/chermdev/learn-git</pre>|clone this repo|This will create `learn-git` folder<br><br>by default the path will be the name of the repo.|
|<pre>git clone https://github.com/chermdev/learn-git git-guide</pre>|clone this repo with a custom path (e.g.: `/git-learn`)||

---

## Config

Apply configuration to git.

### git config --global user.name and user.email

|             command              |                  description            |
|----------------------------------|-----------------------------------------|
|<pre>git config --global user.name _\<your name>_<br>git config --global user.email _\<your email>_</pre><br>This will add it globally.|It's important to identify you in the commits, with this option your commits will be linked with your account.<br><br>_**important:**_ Make sure to use the same email from your [github emails](https://github.com/settings/emails) to allow github link your changes with your account.|

## Origin (set, rename, change)

The origin is where the repo comes from.

### git remote

|             command              |                  description            |
|----------------------------------|-----------------------------------------|
|<pre>git remote add origin _\<url>_</pre>|Add a new origin.|
|<pre>git remote set-url origin _\<url>_</pre>|Change the url of an existing remote repository.|
|<pre>git remote -v|View remote git list.</pre>|
|<pre>git remote rename origin _\<new name>_</pre>|Rename remote git.|

## Branch

### git checkout (create, rename, switch, delete, etc)

|             command              |                  description            |
|----------------------------------|-----------------------------------------|
|<pre></pre>||
|<pre></pre>||

### git switch

|             command              |                  description            |
|----------------------------------|-----------------------------------------|
|<pre></pre>||
|<pre></pre>||

## Rebase and merge changes

### git rebase

|             command              |                  description            |
|----------------------------------|-----------------------------------------|
|<pre>git rebase -i _\<branch>_</pre>|Rebase (edit commit history)|

### git merge

|             command              |                  description            |
|----------------------------------|-----------------------------------------|
|<pre></pre>||
|<pre></pre>||

## Undo changes

### git reset

|             command              |                  description            |
|----------------------------------|-----------------------------------------|
|||

## Commit changes

### git add

|             command              |                  description            |
|----------------------------------|-----------------------------------------|
|<pre></pre>||
|<pre></pre>||

### git status

|             command              |                  description            |
|----------------------------------|-----------------------------------------|
|<pre></pre>||
|<pre></pre>||

### git commit

|             command              |                  description            |
|----------------------------------|-----------------------------------------|
|<pre></pre>||
|<pre></pre>||

### git log

|             command              |                  description            |
|----------------------------------|-----------------------------------------|
|<pre></pre>||
|<pre></pre>||

### git push

|             command              |                  description            |
|----------------------------------|-----------------------------------------|
|<pre></pre>||
|<pre></pre>||

### git pull

|             command              |                  description            |
|----------------------------------|-----------------------------------------|
|<pre></pre>||
|<pre></pre>||

### git cherry-pick

|             command              |                  description            |
|----------------------------------|-----------------------------------------|
|<pre></pre>||
|<pre></pre>||
