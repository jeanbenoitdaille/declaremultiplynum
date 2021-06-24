# declaremultiplynum
Afficher la table de muliplication d'un nombre 
Ici, nous faisons tous les calculs nécessaires directement à l'intérieur de la méthode format.

Pour commencer, nous bouclons à travers une liste contenant les nombres de 0 à 10, grâce à la fonction range :

    for i in range(11):

Nous affichons ensuite dans la chaîne de caractère formattée, le nombre courant de la boucle, contenu dans la variable i, le nombre pour lequel nous affichons la table de multiplication, contenu dans la variable nombre, puis la multiplication de l'un par l'autre (i * nombre).
