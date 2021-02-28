# Projet bataille navale : Abalo Lena


Le projet consiste en la réalisation d'un jeu de bataille navale en suivant plusieurs étapes. J'ai réalisé les questions 1 à 8, et n'ai pas pu implémenter les questions bonus. Pour lancer le jeu, il faut faire mvn clean install exec:java en se placant dans le dossier bataille-navale. 
J'ai créé un fichier TestFinal.java pour implémenter la version finale, qui est instanciée dans le pom.

## Exercice 1

Pour réaliser ma fonction print, j'ai créé une fonction qui permet d'afficher le nombre d'espaces voulus. J'ai rencontré un petit problème car dans l'afichage, lorsqu'on passe aux nombres à 2 chiffres, il y a un petit décalage.

## Exercice 3

Lorsque la valeur d'un navire mène en dehors de la grille, une exception est levée.

## Exercice 7 

J'ai décidé d'utiliser sleep(1000) afin d'avoir un temps assez raisonnable entre les différents coups. Cependant, pour certains coups, l'affichage se fait sans attendre. Je ne sais pas trop à quoi ce problème est lié.


## Auteur

* **Lena Abalo** _alias_ [@lena-abalo](https://github.com/lena-abalo)




