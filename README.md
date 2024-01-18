
# Comprendre `git log` dans Git

git log

Cette commande affiche la liste de tous les commits à partir du plus récent. Par défaut, elle montre le hash du commit, l'auteur, la date et le message du commit.

## Affichage de Détails Spécifiques

git log --oneline

## Pour inclure les fichiers modifiés et le nombre relatif de changements

git log --stat

## Pour voir le diff complet de chaque commit

git log -p

## Pour montrer les commits par un auteur spécifique

git log --author="Nom de l'Auteur"

## Pour montrer les commits avant une date spécifique

git log --before="AAAA-MM-JJ"

Pour montrer les commits comprenant un fichier spécifique :

git log -- <chemin_du_fichier>

## Visualisation Graphique de l'Historique

## Pour une représentation graphique de l'historique des commits

Utilisez l'option --graph pour voir un graphique ASCII de l'historique des branches et des fusions :

git log --graph

Combine --graph avec --oneline et --all pour un aperçu clair de tout l'historique, incluant toutes les branches :

git log est un outil puissant pour comprendre l'évolution d'un projet. Avec ses nombreuses options et filtres, il vous offre un aperçu détaillé de l'historique de votre dépôt.

