# Balises

Les exercices ci-après nécessitent de combiner plusieurs balises.

## Ressources
|Balise|Lien|
|------|----|
|`table`|[tableau](https://www.w3schools.com/tags/tag_table.asp)|
|`tr`|[ligne](https://www.w3schools.com/tags/tag_tr.asp)|
|`td`|[colonne](https://www.w3schools.com/tags/tag_td.asp)|

## Exercice 1

Dans le texte ci-dessous :
- Informatique est un titre de niveau 1
- Définition et Histoire sont des titres de niveau 2
- Chaque autres portions de texte est un paragraphe
- Chaque titre et les paragraphes le suivant constitue une section
- L'ensemble du document constitue un article
 
@[Texte]({"stubs": ["informatique.html"], "command": "/bin/bash run.sh informatique article--[section--[h1--(p--){2}]section--[h2--(p--){3}]section--[h2--(p--){2}]]"})