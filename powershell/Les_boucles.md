# Les Boucles

En PowerShell, on utilise pour les boucles la commande "for", qui s'appuie sur la syntaxe suivante :

![image](https://media.discordapp.net/attachments/408320873876160522/787738273412939826/powershell1.PNG)

Lorsque l'on utilise une boucle for, on suit la logique suivante : on indique une valeur de départ (état initial), une valeur cible dans la condition de répétition (par exemple la valeur 10) puis on incrémente de X la valeur à chaque tour de boucle (à chaque itération) : on peut incrémenter de la valeur que l'on veut.


Il éxiste plusieurs types de boucle "For": la plus connu est la boucle de "For" de base, comme à l'exemple ci-dessus.

Ensuite, il y a la boucle "For" basée sur un nombre d'éléments: 

![image](https://media.discordapp.net/attachments/408320873876160522/787739671731896360/powershell2.PNG)   

On va définir la variable $langages et lui attribuer des valeurs (cela pourrait être dynamique).    
Grâce à $langages.Length, nous allons pouvoir faire une boucle qui traite l'ensemble des éléments du tableau.   
C'est ce que l'on fait habituellement (et plus simplement) avec une boucle ForEach mais on peut le faire aussi avec une simple boucle For, d'où cet exemple ci-dessus.

Enfin, il y a la boucle "For" à conditions multiple.

![image](https://media.discordapp.net/attachments/408320873876160522/787740988332441620/powershell3.PNG) 

Au sein d'une boucle "For", on utilise généralement la variable $i pour gérer l'initialisation et l'incrémentation. Si besoin, on peut utiliser deux conditions afin de créer une boucle For à conditions multiple. Pour l'exemple ci-dessus, on prend $i et $j.  

