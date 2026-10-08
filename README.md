# TP01 - Découverte de Git

Dépôt réalisé par Jules PELATAN BERGER, 1CIEL-IR.

Ce dépôt contient mon compte rendu du TP01.

# Partie 0

## 0. 
    La version installée est la 2.43.0.
    ~/tp-git/tp01-git$ git --version git version 2.43.0

# Partie 1

## 1. 
    https://github.com/Jules-PelBer

# Partie 2

## 2. 
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

# Partie 3

## 3. 
    1) fatal: ni ceci ni aucun de ses répertoires parents (jusqu'au point de montage /) n'est un dépôt git
    Arrêt à la limite du système de fichiers (GIT_DISCOVERY_ACROSS_FILESYSTEM n'est pas défini).
    
    
    Car on a pas encore  initaliser le fichier tp01 comme un git.
    
    2) Le git init à crée un dossier .git/. on ne le voit pas car c'est un fichier caché. Git status répond maintenant: 
        Sur la branche main

        Aucun commit

        rien à valider (créez/copiez des fichiers et utilisez "git add" pour les suivre)

    3) git status range readme.md dans la section fichiers non suivis. Il se trouve dans le répertoire de fichiers.

    4) readme.md se trouve dans maintenant dans la section "modifications qui seront validées"