# Premier laboratoire de programmation

Ceci est un fichier README.md.

Un fichier README est un fichier qui contient des informations sur d'autres fichiers dans un répertoire. Il est générajsonalement affiché sur la page principale du répertoire.

> Expliquez ce que fait votre programme et comment il fonctionne.

>Les explications sont donnees par ligne de code, de haut en bas et de gauche a droite

## #include <stdio.h>
1. Inclue la bibliotheque pour l'utilisation des entrees et sorties

## int main(void)
1. **"int"** signifie que les variables sont en entier dans ce bloc
2. **"main"** permet l'execution en priorite de cette fonction
3. **"(void)"** signifie que la fonction ne renvoie rien
4. **"{...}"** designe quelles instructions sont dans le bloc int main(void) 

## int val1 = 12;
1. Creation d'une variable
2. **"int"** signifie que cette variable est entiere
3. **"val1"** est le nom de notre variable
4. **"="** cette valeur est egale a 
5. **"12"** valeur en int de notre variable
6. **";"** fin de l'instruction

## int val2 = 34;
1. Creation d'une variable
2. **"int"** signifie que cette variable est entiere
3. **"val2"** est le nom de notre variable
4. **"="** cette valeur est egale a 
5. **"34"** valeur en int de notre variable
6. **";"** fin de l'instruction

## int sum = val1 + val2;
1. **"int"** signifie que cette variable est entiere
2. **"sum"** est le nom de notre variable
3. **"="** cette valeur est egale a
4. **"val1 + val2"** = addition de nos deux variables initialisee precedement, ceci sera la valeur de "sum", donc 46
5. **";"** fin de l'instruction

## printf("La ... de %d et %d fait : %d\n", val1, val2, sum);
1. **"printf"** Fonction de la bibliotheque <stdio.h> permet d'imprimer/afficher ce qui est entre parenthese.
Le premier "%d" est la valeur en int de la premiere variable "val1". Le deuxieme "%d" est la valeur en int de la deuxieme variable "val2". Le troisieme "%d" est la valeur en int de la troisieme variable "sum".
2. **"val1"** Nom de la variable qui vaut 12
3. **"val2"** Nom de la variable qui vaut 34
4. **"sum"** Nom de la troisieme variable calculant la somme de "val1" et "val2" : 12 + 34 = 46
5. **";"** fin de l'instruction

## return 0;
1. **"return"** initialise les valeurs de toutes les variables a une certaine valeur
2. **"0"** valeur d'initialisation des variables
3. **";"** fin de l'instruction