# PRACTICA 1

## COMANDOS

### git clone: clona un repositorio en la dirección que se indica.

PS C:\Users\corsi\OneDrive\Escritorio> git clone https://github.com/gitt-3-pat/hello-world
Cloning into 'hello-world'...
remote: Enumerating objects: 38, done.
remote: Counting objects: 100% (38/38), done.
remote: Compressing objects: 100% (23/23), done.
Receiving objects:  50% (19/38)sed 31 (delta 0), pack-reused 0 eceiving objects:  47% (18/38)
Receiving objects: 100% (38/38), 58.97 KiB | 379.00 KiB/s, done.
Resolving deltas: 100% (1/1), done.


### git status: permite ver el estado de las ramas y de los commits.

PS C:\Users\corsi\OneDrive\Escritorio\ICAI\PAT\hello-world> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   src/test/java/com/mycompany/app/AppTest.java

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README2.md

no changes added to commit (use "git add" and/or "git commit -a")


### git add .: se indica a git que se va a actualizar el repositorio. 

Este comando no devuelve nada


### git commit: se prepara una actualización al repositorio. Se puede indicar un comentario sobre la actualización.

PS C:\Users\corsi\OneDrive\Escritorio\ICAI\PAT\hello-world> git commit -m "README2 added"
[main 03a1395] README2 added
 2 files changed, 19 insertions(+)
 create mode 100644 README2.md


 ### git push: se suben los cambios al repositorio GitHub. En este caso se usa para subir este mismo archivo.

 PS C:\Users\corsi\OneDrive\Escritorio\ICAI\PAT\hello-world> git push
Enumerating objects: 18, done.
Counting objects: 100% (18/18), done.
Delta compression using up to 12 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (10/10), 968 bytes | 242.00 KiB/s, done.
Total 10 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote: This repository moved. Please use the new location:
remote:   https://github.com/NCSanto01/hello-world.git
To https://github.com/NCSanto01/ProgramacionTelematica.git
   48fe276..03a1395  main -> main


### git checkout: sirve para cambiar de rama.

PS C:\Users\corsi\OneDrive\Escritorio\ICAI\PAT\hello-world> git checkout -b feature/1
>>
Switched to a new branch 'feature/1'


PS C:\Users\corsi\OneDrive\Escritorio\ICAI\PAT\hello-world> git checkout main
>>
Switched to branch 'main'
Your branch is up to date with 'origin/main'.




## INSTALACIONES

### Java 17:

PS C:\Users\corsi\OneDrive\Escritorio\ICAI\PAT\hello-world> java -version
java version "17.0.1" 2021-10-19 LTS
Java(TM) SE Runtime Environment (build 17.0.1+12-LTS-39)
Java HotSpot(TM) 64-Bit Server VM (build 17.0.1+12-LTS-39, mixed mode, sharing)


### MAVEN:

C:\Users\corsi>mvn --version
Apache Maven 3.8.4 (9b656c72d54e5bacbed989b64718c159fe39b537)
Maven home: C:\Users\corsi\OneDrive\Escritorio\ICAI\PAT\MAVEN\apache-maven-3.8.4
Java version: 17.0.1, vendor: Oracle Corporation, runtime: C:\Program Files\Java\jdk-17.0.1
Default locale: es_ES, platform encoding: Cp1252
OS name: "windows 10", version: "10.0", arch: "amd64", family: "windows"







