# Chapitre 3 : Représentation des données : types construits
---
Dans notre premier cours sur Python, nous avons vu les différents types simples permettant de stocker de l’information : **int**, **float**, **bool**.  
Le type **str** est aussi un type simple mais on peut sur ce type particulier accéder aux éléments de celui-ci. Par exemple si on crée une chaîne avec la commande ```ch='bonjour'``` alors l’expression ```ch[0]``` nous renverra la valeur ```'b'``` et l’expression ```ch[3:7]``` la valeur ```'jour'``` valeurs qui seront également du type str.  

Avec ces types simples, nous pouvons définir des variables qui représenteront chacune **une** donnée avec **une** valeur. Ceci est suffisant pour traiter un petit nombre de données, mais lorsque nous allons vouloir traiter un plus gros volume de données, ceci peut devenir contraignant complexe à gérer.  
Par exemple, si nous voulons gérer un ensemble de points en géométrie, chacun comporte une abscisse et une ordonnée, il nous faudra donc deux valeurs par objet, si nous gérons un train, il sera composé d’une locomotive et d’un ou plusieurs wagons (dont nous ne connaissons pas le nombre à l’avance).  

Pour répondre à ce type de besoins, nous allons donc étudier trois nouveaux types d’objets : le type **tuple** (p-uplet), le type **list** (tableau indexé) et le type **dict** (dictionnaire par clés et valeurs). Ces types présentent des **points communs** mais aussi des **différences**, ils nous permettront d’adresser des besoins similaires et leur différences nous aideront à faire notre choix en fonction du problème à résoudre.

## p-uplets et p-uplets nommés
>| Contenu | Capacités attendues |
>| :-- | :-- |
>| p-uplets et p-uplets nommés | Écrire une fonction renvoyant un p-uplet de valeurs |

- Cours : [p-uplets et p-uplets nommés](https://notebook.basthon.fr/?from=https://raw.githubusercontent.com/cyrillearduini/NSI/main/NSI_1ERE/_ressources/3.TYPES_CONSTRUITS/3.1-Cours_p-uplets.ipynb)

- TP : [p-uplets et p-uplets nommés](https://notebook.basthon.fr/?from=https://raw.githubusercontent.com/cyrillearduini/NSI/main/NSI_1ERE/_ressources/3.TYPES_CONSTRUITS/3.2-TP_p-uplets.ipynb)

## Tableau indexé, tableau donné en compréhension
| Contenu | Capacités attendues |
| :-- | :-- |
| Tableau indexé, tableau donné en compréhension | Lire et modifier les éléments d’un tableau grâce à leurs index<br>Construire un tableau par compréhension<br> Utiliser des tableaux de tableaux pour représenter des matrices : notation `a[i][j]` <br>Itérer sur les éléments d’un tableau |

- Cours : 

- TP : 

## Dictionnaires par clés et valeurs
| Contenu | Capacités attendues |
| :-- | :-- |
| Dictionnaires par clés et valeurs | Construire une entrée de dictionnaire <br>Itérer sur les éléments d’un dictionnaire |

- Cours

- TP : 

