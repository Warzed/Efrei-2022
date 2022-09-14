ls -l --> Liste les dossiers et fichiers   
ls -a --> Liste les dossiers et fichiers + fichiers cachés
mkdir --> Créer un dossier
cd --> Permet de se déplacer dans l'arborescence 
cat --> Permet de lire le contenu d'un fichier
git init --> Initialisation d'un dépôt git
git branche -M main (master) --> remplace (master) par (main)
git config user.email "@mail" --> configure l'@mail de l'auteur
git config user.name "nom" --> configure le nom l'auteur
vi config --> permet de visualiser et éditer la configuration du dépôt 
:q --> pour quitter vi config
git status Rouge = il faut faire git add "nom fichier"
            Vert = il faut faire git commit "message"

1) git add "nom fichier" --> ajoute des fichiers à l'historique de suivi
    git add. --> ajoute tous les fichiers
2) git commit -m "Message" 
3) git log --> Permet de visualiser les fichiers commit
4) git commit --amend -m "Nouveau message" --> modifie le message

git restore "nom fichier" --> restaure la dernière version d'un fichier
git tag -a "1.0.0" -m "Version 1.0.0" ref --> ajoute un tag à un commit
git reset --soft 1.0.0 --> retourne à la version demandée
          --hard 1.0.0 --> supprime les changement 
git show --> montre le derneir commmit