# Compte rendu — TP01 Git

## Partie 1

### Question 1

0. https://github.com/esverys-e 
   
## Partie 2

### Question 2

1. user.name=esverys-e 
user.email=arnaud.espinasse81@gmail.com
init.defaultbranch=main
core.editor=nano    
   2. l'option global signifie le tout l'ensemble des dépôts Git les réglage se trouve dans notre home.

### Question 3.1

1. git status répond ( fatal: ni ceci ni aucun de ses répertoires parents (jusqu'au point de montage /) n'est un dépôt git
Arrêt à la limite du système de fichiers (GIT_DISCOVERY_ACROSS_FILESYSTEM n'est pas défini).) car il y a aucun dépot git qui a était crée.

### Question 3.2 

1. git init a crée un dossier .git on ne peut pas le voir avec ls car c'est un dossier cacher 
2. git status répond maintenant ( Sur la branche main

Aucun commit

rien à valider (créez/copiez des fichiers et utilisez "git add" pour les suivre) )
 
   
### Question 3.3 

1. Dans le répertoire de travail fichier non suivie
### Question 3.4 

1. Avant README.md etait en fichier non suivis et maintenant il est la zone pres a etre enregistré

### Question 3.5

1. La sortie de git log est (commit a1e7a65257ad84a6f45412afdac0918ed1fe6175 (HEAD -> main)
Author: esverys-e <arnaud.espinasse81@gmail.com>
Date:   Thu Oct 1 11:44:40 2026 +0200

    Création du README)

2. Le hash du commit est ( commit a1e7a65257ad84a6f45412afdac0918ed1fe6175 ) (Author: esverys-e ) le message (Création du README)
3. Le hash comporte 40 caractères il est ecrit en base héxadecimal et il représente 160 bits car 40*4=160

### Question 3.7

1. README.md est indiqué comme modified
2. Le + devant la ligne de l’année signifie que cette ligne a été ajoutée. Et le git diff sert a voir les modification

