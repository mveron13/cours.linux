# Les Conditions


En général, un script va agir de façon adapter a la demande, pour ainsi donner le résultat attendu

Par exemple, si je veux demander à mon programme si le nombre X est strictement plus grand que le nombre Y, il faut que mon programme affiche le résultat 1) dans un cas (par exemple "oui", si X est bien plus grand que Y); ou le résultat 2) dans un cas différent (par exemple "non", si X est plus petit ou égal à Y).

Pour ceci, nous allons nous servir le plus souvent de "if" et de "else".


## If


If permet de prendre en considération la condition qui le suit, par exemple:

![image](https://media.discordapp.net/attachments/408320873876160522/788101145461391400/cond1bis.PNG)

Ici, if vérifie si la condition "min est plus grand ou égal à max". Si la condition est vrai, l'action comme ci dessous est exécuté:

![image](https://media.discordapp.net/attachments/408320873876160522/788102827712446474/cond2.PNG)


## Else


Cependant dans le cas où la condition imposé par le "if" n'est pas rempli, il faut que le programme puisse afficher un résultat différent; par exemple si un programme, une fois la condition rempli, affiche 1, il doit afficher un autre résultat que 1 si la condition n'est en revanche pas rempli. C'est pour cela que nous allons utiliser "else"

Else fonctionne de façon similaire à if, sauf qu'il se place obligatoirement après un if et son action, et n'a pas besoin de condition (car il regroupe de base toute les conditions qui ne sont pas les conditions du if)

![image](https://media.discordapp.net/attachments/408320873876160522/788106239997116447/cond3.PNG)

[← Retour au menu](https://github.com/mveron13/cours.linux/blob/main/README.md)

[Suivant →](https://github.com/mveron13/cours.linux/blob/main/powershell/Les_boucles.md)
