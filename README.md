# Música Maestro


JaviLR@Uchiha MINGW64 ~
$ git clone https://github.com/JaviLRZ/repoNotas.git
Cloning into 'repoNotas'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

JaviLR@Uchiha MINGW64 ~
$ git config --global user.name "JaviLRZ"

JaviLR@Uchiha MINGW64 ~
$ git config --global user.email javierlopezramirez.97@gmail.com

JaviLR@Uchiha MINGW64 ~
$ nano prueba1.txt

JaviLR@Uchiha MINGW64 ~
$ nano re.txt

JaviLR@Uchiha MINGW64 ~
$ nano mi.txt

JaviLR@Uchiha MINGW64 ~
$ nano fa.txt

JaviLR@Uchiha MINGW64 ~
$ nano do.txt

JaviLR@Uchiha MINGW64 ~
$ git status
fatal: not a git repository (or any of the parent directories): .git

JaviLR@Uchiha MINGW64 ~
$ git commit -m pruebasubida1
fatal: not a git repository (or any of the parent directories): .git

JaviLR@Uchiha MINGW64 ~
$ cd users
bash: cd: users: No such file or directory

JaviLR@Uchiha MINGW64 ~
$ cd c
bash: cd: c: No such file or directory

JaviLR@Uchiha MINGW64 ~
$ ls
'3D Objects'/
 AppData/
'Application Data'@
'Configuración local'@
 Contacts/
 Cookies@
'Datos de programa'@
 Desktop/
 Documents/
 Downloads/
'Entorno de red'@
 Favorites/
 Impresoras@
 IntelGraphicsProfiles/
 Links/
'Local Settings'@
'Menú Inicio'@
 MicrosoftEdgeBackups/
'Mis documentos'@
 Music/
'My Documents'@
 NTUSER.DAT
 NTUSER.DAT{917fb190-630d-11ea-8bb7-9c5c8e15739d}.TM.blf
 NTUSER.DAT{917fb190-630d-11ea-8bb7-9c5c8e15739d}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{917fb190-630d-11ea-8bb7-9c5c8e15739d}.TMContainer00000000000000000002.regtrans-ms
 NetHood@
 OneDrive/
 Pictures/
 Plantillas@
 PrintHood@
 Recent@
 Reciente@
'Saved Games'/
 Searches/
 SendTo@
'Start Menu'@
 Templates@
 Videos/
'VirtualBox VMs'/
 ansel/
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini
 repoNotas/

JaviLR@Uchiha MINGW64 ~
$ cd repoNotas/

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ ls
README.md  do.txt  fa.txt  mi.txt  re.txt

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        do.txt
        fa.txt
        mi.txt
        re.txt

nothing added to commit but untracked files present (use "git add" to track)

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git commit-m subida1
git: 'commit-m' is not a git command. See 'git --help'.

The most similar command is
        commit-tree

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git commit -m subida1
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        do.txt
        fa.txt
        mi.txt
        re.txt

nothing added to commit but untracked files present (use "git add" to track)

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git tag notasMusicales

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git tag
notasMusicales

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git log --online --all --graph
fatal: unrecognized argument: --online

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git log --oneline --all --graph
* 8edc6a4 (HEAD -> main, tag: notasMusicales, origin/main, origin/HEAD) Initial commit

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git push origin main --tags
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/JaviLRZ/repoNotas.git
 * [new tag]         notasMusicales -> notasMusicales

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git push
Everything up-to-date

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git add -A
warning: LF will be replaced by CRLF in do.txt.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in fa.txt.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in mi.txt.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in re.txt.
The file will have its original line endings in your working directory

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git add -A

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   do.txt
        new file:   fa.txt
        new file:   mi.txt
        new file:   re.txt


JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git push
Everything up-to-date

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git pull
Already up to date.

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git branch claveSol

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git branch claveFa

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git branch sostenido

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git branch
  claveFa
  claveSol
* main
  sostenido

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git push
Everything up-to-date

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   do.txt
        new file:   fa.txt
        new file:   mi.txt
        new file:   re.txt


JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git add -A

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git push origin main --tags
Everything up-to-date

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git init
Reinitialized existing Git repository in C:/Users/JaviLR/repoNotas/.git/

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git add -A

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git commit -m subida2
[main d59e657] subida2
 4 files changed, 4 insertions(+)
 create mode 100644 do.txt
 create mode 100644 fa.txt
 create mode 100644 mi.txt
 create mode 100644 re.txt

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/JaviLRZ/repoNotas.git'

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (6/6), 510 bytes | 510.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/JaviLRZ/repoNotas.git
   8edc6a4..d59e657  main -> main

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git branch
  claveFa
  claveSol
* main
  sostenido

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git push origin
Everything up-to-date

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git branch
  claveFa
  claveSol
* main
  sostenido

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git bash
git: 'bash' is not a git command. See 'git --help'.

The most similar command is
        stash

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git push
Everything up-to-date

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git pull
Already up to date.

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git checkout claveSol
Switched to branch 'claveSol'

JaviLR@Uchiha MINGW64 ~/repoNotas (claveSol)
$ nano sol.txt

JaviLR@Uchiha MINGW64 ~/repoNotas (claveSol)
$ nano la.txt

JaviLR@Uchiha MINGW64 ~/repoNotas (claveSol)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git merge claveSol
Already up to date.

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git branch -D claveFA
Deleted branch claveFA (was 8edc6a4).

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git push origin
Everything up-to-date

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git push origin main --tags
Everything up-to-date

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git push origin main
Everything up-to-date

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git add .

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git commmit -m RamasFusionadas
git: 'commmit' is not a git command. See 'git --help'.

The most similar command is
        commit

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git commmit -m "ramasFusioanadas"
git: 'commmit' is not a git command. See 'git --help'.

The most similar command is
        commit

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git commit -m "ramasFusioanadas"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

JaviLR@Uchiha MINGW64 ~/repoNotas (main)
$ git push
Everything up-to-date


