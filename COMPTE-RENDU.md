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
    
    2) Git diff montre ce qui  à été retiré et ajouté au fichier. Le + signifie les ajout au document. 

## Question 3.8
    1) 314a251 (HEAD -> main) Modification pour la question 3.8
        2c8ef20 Création de l'aide mémoire Git
        1471274 Ajout de la question 3.7
        c11e8dc Ajout de l'année scolaire dans le README
        622fe8e Ajout du compte rendu (Question 0 à 3.5)
        e494913 Création du README
        2cc24bf Création du readme
    
    2) Afin de pouvoir différencier plus facilement les commits dans l'historique.
   
## Question 4.1
    1) Git show montre les modifications apporté au commit sélectionner. On y retrouve toute les modifications.
   
## Question 4.2 
    1) Git restore a permis de restorer le fichier avant la dernière modification apporté. On n'aurait pas pu le récupérer si on ne l'avait jamais commité.

## Question 4.3 
    1) test.txt se trouve maintenant dans le répertoire de travail. Le fichier n'a pas été supprimer du disque il a simplement été dé-indexé.

## Question 4.4
    1) les fichiers touch_brouillon.txt, erreurs.log et debug.log ont disparu. *.log signifie tous les fichiers qui ont l'extension .log
    
    2) .gitignore est apparu. il faut le commiter.

## Question 4.5 
    1) Lors du premier commit README.md contenait les questions de 0 à 3.5. Depuis j'y ai ajouté l'année scolaire comme demandé dans la question 3.7.

## Question 5.2
    1) les fichiers id_ed25519 et id_ed25519.pub. la clé avec l'extension .pub est la clé publique.
    
    2) la clé privée comme la clé publique ont "rwx------"

## Question 5.4
    1) Hi Jules-PelBer! You've successfully authenticated, but GitHub does not provide shell access.

    2) Car la clé privée permet de débloquer la clé publique donc donner la publique est sans risque tant qu'on donne pas la clé privée.

## Question 6.3
    1) origin	git@github.com:Jules-PelBer/tp01-git.git (fetch)
       origin	git@github.com:Jules-PelBer/tp01-git.git (push)

    2) oui c'est le même. Le fichier brouillon.txt n'y est pas car il y a le fichier .gitignore.




   





