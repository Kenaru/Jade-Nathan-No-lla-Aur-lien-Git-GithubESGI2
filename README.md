# Jade-Nathan-Noella-Aurelien-Git-GithubESGI2

## Sommaire
### Les fonctions principales
- Initialiser un depot(init), consulter l'etat de l'espace de travail (status)
- Ecrire dans l'historique (add, commit)
- Afficher l'historique (log) et les modifications en cours (diff) 
- Ignorer les fichiers indesirables (.gitignore)
- Synchronisation client-serveur (push, pull, clone)
- Ecrire sur une branche de travail (checkout, branch)
- Fusionner une branche dans une autre (merge)

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


## Understanding `git log` in Git

The `git log` command is used to display the commit history of a Git repository. It shows a list of commits along with their details like the hash, author, date, and commit message.

## Basic Usage

To view the commit history, simply type:

This command will show a list of all commits starting with the most recent. By default, it displays the commit hash, author, date, and the commit message.

## Viewing Specific Details

You can customize the output of `git log` with various options:

- To see a condensed, one-line version of the history:

- To include which files were altered and the relative number of changes in each file:

- To view the complete diff of each commit:

## Filtering the Log

You can also filter the output based on time, author, or files:

- To show commits by a specific author:

- To show commits before a specific date:

- To show commits that include a particular file:

## Visualizing Commit History

For a graphical representation of the commit history:

- Use the `--graph` option to see an ASCII graph of the branch and merge history:

Combining `--graph` with `--oneline` and `--all` gives a clear overview of the entire history, including all branches:

`git log` is a powerful tool to understand the evolution of a project. With its various options and filters, you can get detailed insights into the history of your repository.
