# Git & Github

![Image Git](Image1.png =250x)

### Git

Pour télécharger **Git**, voici le lien [https://git-scm.com/downloads](https://git-scm.com/downloads)

### Définition 

Git est un outil de versionning, les outils de versionning ont pour objectif de mémoriser toute création, modification ou suppression des différents fichiers d'un projet afin de vous permettre de retracer toute l'évolution du projet, fichier par fichier. 

#### 1er étape

Initialise Git dans le projet : **git init**

#### 2ème étape

Faire le **lien** entre votre repository **distant** et **local**, pour cela créer un repository sur github. Lorsqu'il est fait récupérer la commande suivante => git remote add origin [https://urlDuDepot.git](https://urlDuDepot.git). Le lien doit être bien évidemment celui de votre repository. Entrer cette commande sur votre terminal.

#### 3ème étape *(Non obligatoire)*

vérification du lien entre git et gihub : **git remote -v**

Si les liens de votre repository github apparaît tout est bon !

A partir de maintenant vous n'aurez plus besoins de faire les étapes au-dessus !

**Maintenant vous n'avez plus qu'à prendre les photos de votre projet à chaque fois que vous avez fait des modifications et les mettres sur gihub.**

#### Le Commit

Réaliser un commit, deux étapes doivent être réalisées:

1. D'abord, l'ajout des fichiers à prendre en photo : **git add .**

2. Ensuite, la prise de photo elle-même : **git commit -m "commentaire à mettre ici"**

3. Mettre votre repository Github à jour : **git push origin master**

# The End...
