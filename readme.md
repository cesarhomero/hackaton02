RETO 01:

1. ¿Qué es un control de versiones?
    Un control de versiones es una herramienta que sirve para crear historiales de información sobre algún proyecto de desarrollo que estemos realizando mediante repositorios en su plataforma.

2. ¿Cuáles son los problemas al no usar un control de versiones?
    - Que no se puede identificar quien o cuando se hizo cambios en una versión.
    - La identificación de los archivos de una manera desordenada.
    - Sensible a factores externos cuando se pierde la información.
    - No se puede trabajar en conjunto mediante ramas.

3. ¿Cuáles son los beneficios?
    - Un mejor control sobre las versiones y cambios realizados.
    - Los proyectos se pueden compartir en internet.
    - Se puede volver a versiones anteriores sin complicaciones.
    - Se puede trabajar simultáneamente en diferentes ramas, haciendo más eficiente el flujo de trabajo.

4. ¿Qué tipos de control de versiones existen?

    - Control de versiones locales: Utilizan una base de datos local para el repositorio.
    - Control de versiones centralizado: se utiliza un servidor en línea para almacenar la información.
    - Control de versiones Distribuidos: Cada desarrollador tiene una copia del proyecto y puede  avanzar simultáneamente el código sin afectar a los demás.

    RETO 02:

    
PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02
$ git init
Initialized empty Git repository in C:/Users/PC/Desktop/PRACTICAS/HACKATON_02/.git/

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ git touch index.html
git: 'touch' is not a git command. See 'git --help'.

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ mkdir images

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ mkdir readme.md

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ touch readme.md

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ touch index.HTML

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ touch index.html

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ touch styles.css

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ mkdir styles

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ mkdir java

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ touch resources.js

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ git remote add origin https://github.com/cesarhomero/hackaton02.git

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html
        java/
        readme.md
        styles/

nothing added to commit but untracked files present (use "git add" to track)

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/cesarhomero/hackaton02.git'

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ git branch

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ git add .

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/cesarhomero/hackaton02.git'

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/cesarhomero/hackaton02.git'

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ git git status
git: 'git' is not a git command. See 'git --help'.

The most similar command is
        init

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html
        new file:   java/resources.js
        new file:   readme.md
        new file:   styles/styles.css


PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ git remote add origin https://github.com/cesarhomero/hackaton02.git
error: remote origin already exists.

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/cesarhomero/hackaton02.git'

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ git branch -M
fatal: branch name required

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ git branch

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ git commit -m "first commit"
[master (root-commit) aba8d63] first commit
 4 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index.html
 create mode 100644 java/resources.js
 create mode 100644 readme.md
 create mode 100644 styles/styles.css

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ git git push -u origin mai
git: 'git' is not a git command. See 'git --help'.

The most similar command is
        init

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/cesarhomero/hackaton02.git'

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$ git push -u origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (5/5), 384 bytes | 384.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/cesarhomero/hackaton02.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

PC@LAPTOP-AERDGA7H MINGW64 ~/Desktop/PRACTICAS/HACKATON_02 (master)
$

RETO 03: