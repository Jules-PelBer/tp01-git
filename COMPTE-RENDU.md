# Compte rendu - TP01 Git

## Question 0
    La version installée est la 2.43.0.
    ~/tp-git/tp01-git$ git --version git version 2.43.0

## Question 1
    https://github.com/Jules-PelBer

## Question 2
    jpelatan@d116-08:~/tp-git$ git config --list --global 
    filter.lfs.clean=git-lfs clean -- %f
    filter.lfs.smudge=git-lfs smudge -- %f
    filter.lfs.process=git-lfs filter-process
    filter.lfs.required=true
    user.name=Jules Pelatan Berger
    user.email=j.pelatanberger@gmail.com
    init.defaultbranch=main
    core.editor=nano
      
    -l'option --global signifie que la commande fais la liste des config de ce fichier. Ces réglages sont donc enregistrés dans le fichier global.


## Question 3.1
    1) fatal: ni ceci ni aucun de ses répertoires parents (jusqu'au point de montage /) n'est un dépôt git
    Arrêt à la limite du système de fichiers (GIT_DISCOVERY_ACROSS_FILESYSTEM n'est pas défini).
    
    
    Car on a pas encore  initaliser le fichier tp01 comme un git.
    
## Question 3.2 
    1) Le git init à crée un dossier .git/. on ne le voit pas car c'est un fichier caché. Git status répond maintenant: 
        Sur la branche main

        Aucun commit

        rien à valider (créez/copiez des fichiers et utilisez "git add" pour les suivre)

## Question 3.3
    1) git status range readme.md dans la section fichiers non suivis. Il se trouve dans le répertoire de fichiers.

## Question 3.4
     readme.md se trouve dans maintenant dans la section "modifications qui seront validées"
    
## Question 3.5 
    1)    commit e4949139f0598f4f8e5988c4d09ae3f025dc561e (HEAD -> main)
        Author: Jules-PelBer <j.pelatanberger@gmail.com>
        Date:   Thu Oct 8 09:17:55 2026 +0200

        Création du README

    2) Son auteur: Jules-PelBer / Sa date: Jeudi 8 octobre / son message: Création du README/ son hash :e4949139f0598f4f8e5988c4d09ae3f025dc561e

    3) Il est écrit en base hexadécimale. Il représente 160 bits.
    
## Question 3.7
    1) Git status décrit readme.md comme modification qui ne seront pas validées.
    
    2)Git diff montre ce qui  à été retiré et ajouté au fichier. Le + signifie les ajouts au document. 



