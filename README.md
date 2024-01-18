# Jade-Nathan-Noella-Aurelien-Git-GithubESGI2


## Versionning avec Git et Github

Les versions servent à gérer du texte, agnostiquer vis-à-vis du langage, sauvegardé l'historique des modification (versions), résolution des conflits entre les différentes versions, aide au changement de version.

Le versionning fonctionne avec un système de commit, un commit est une version du projet. Il permet de sauvegarder l'état du projet à un instant T. Il permet aussi de revenir à une version précédente du projet. Il permet aussi de travailler à plusieurs sur un même projet.

## Système centralisés/distribués

Les systèmes **centralisés** sont des systèmes qui ont un serveur central qui contient toutes les versions du projet. Les systèmes **distribués** sont des systèmes qui ont plusieurs serveurs qui contiennent toutes les versions du projet. 

## Git un système distribué

Git est un système de version distribué, il permet de travailler en local et de pouvoir faire des modifications sans avoir besoin d'être connecté à internet. Il permet aussi de travailler à plusieurs sur un même projet.
Les Server les plus populaires sont : Github, Gitlab


## client interface graphique
Differentes interfaces graphiques pour GitHub sont disponibles pour l'utiliser. GitHub Desktop par exemple pour Mac et Windows, l'integration d'un IDE dans VSCode ou d'autres. Malheureusement tous les clients n'ont pas acces a toutes les memes fonctions. 

## Ignorer les fichiers

Pour ignorer les fichiers, il faut créer un fichier .gitignore à la racine du projet. Dans ce fichier, on peut mettre les fichiers que l'on veut ignorer. Par exemple, si on veut ignorer tous les fichiers .txt, on peut mettre *.txt dans le fichier .gitignore. Il est interessant d'ignorer les fichiers qui ne sont pas utiles au projet, comme les fichiers de configuration, Les fichier d'environnment (.env), les fichiers de logs, les fichiers de cache, les fichiers de dépendances, etc.

## Synchronisation client/serveur

Pour synchroniser le client et le serveur, il faut utiliser la commande git pull. Cette commande permet de récupérer les modifications du serveur et de les appliquer sur le client. Il faut faire attention à ne pas avoir de conflits entre les modifications du client et du serveur. Si il y a des conflits, il faut les résoudre avant de pouvoir faire un git pull. Pour ce faire l'utilisation de Branch et de Pull Request est conseillé. Tout cela permet de travailler à plusieurs sur un même projet et de sauvegarder l'historique d'un projet.

## Création de branches dans Git

Introduction
Dans Git, les branches sont utilisées pour développer des fonctionnalités isolées les unes des autres. La branche principale est généralement appelée master. Lorsque vous créez une branche, vous créez une nouvelle ligne de développement qui est indépendante de la branche principale.

### Commandes de base
git branch
Syntaxe: git branch [nom_de_la_branche]
Description: Crée une nouvelle branche.

Exemple:
git branch ma-nouvelle-branche
git checkout
Syntaxe: git checkout [nom_de_la_branche]

Description: Permet de basculer sur la branche spécifiée.

Exemple:
git checkout ma-nouvelle-branche
Syntaxe alternative: git checkout -b [nom_de_la_branche]

Description: Crée une nouvelle branche et bascule dessus simultanément.

Exemple:
git checkout -b ma-nouvelle-branche


### Utilisation courante

Vérifier la branche actuelle:
git branch

Créer une nouvelle branche:
git branch ma-nouvelle-branche

Basculer sur la nouvelle branche:
git checkout ma-nouvelle-branche
Faire des modifications:

Modifier des fichiers.
Utiliser git add pour préparer les changements.
Utiliser git commit pour enregistrer les changements.


###  Fusionner la branche:

Retourner à la branche principale:
git checkout master

Fusionner la nouvelle branche:
git merge ma-nouvelle-branche


Conclusion
La gestion des branches dans Git est un aspect crucial de la gestion de versions. Elle permet à plusieurs développeurs de travailler sur différentes fonctionnalités en parallèle, sans interférer les uns avec les autres.