# GITPROJECT
![Alt text](/git.jpg) ![Alt text](/github.png)
# Git
Pour télécharger **git**, voici le lien (https://git-scm.com/downloads)
## Définition:
Git est un outil de versioning, les outils de versioning ont pour objectif de mémoriser toute création, modification ou supression des différents fichiers d'un projet afin de vous permettre de retracer toute l'évolution du projet.
#### 1ère étape
Initialise Git dans le projet : **git init**
#### 2ème étape
Faire le **lien** entre votre respository **distant** et **local**, pour cela créer un respository sur github. Lorsqu'il est fait récupérer la commande suivante => git remote add origin (https://urlDuDepot.git). Le lien doit être bien évidemment celui de votre respository. Entrez cette commande sur votre terminal.
#### 3ème étape *(non obligatoire)*
vérification du lien entre git et github : **git remove -v**
Si les liens de votre repository github apparait tout est bon!
A partir de maintenant vous n'aurez plus besoin de faire les étapes au-dessus!
**Maintenant vous n'avez plus qu'à prendre les photos de votre projet à chaque fois que vous avez fait des modifications et les mettre sur github**
#### Le Commit
Réaliser un commit, deux étapes doivent être réalisées:
1. D'abord l'ajout des fichiers à prendre en photo **git add .**
2. Ensuite la prise de photo elle même : **git commit -m "commentaire à mettre ici"**
3. Mettre votre repository Github à jour : **git push origin master**
#The End...
