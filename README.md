#Memo Syntaxe Markdown 
![logo Markdown](/images/Markdown.png)

    
    ![logo Markdown](/images/Markdown.png)


Projet d'écriture : [Syntaxe Markdown Versus HTML](rep/syntaxe.md/ "En cours d'écriture")

    Projet d'écriture : [Syntaxe Markdown Versus HTML](rep/syntaxe.md/ "En cours d'écriture")


## Introduction  ##

John Gruber a créé le langage Markdown est 2004, avec la participation significative de Aaron Swartz pour la syntaxe. Ce langage permet d'écrire et de lire aisement dans un format en texte plein, sans être distrait par les balises de formatage. Sa forme est très proche de la syntaxe wiki comme celle de Dokuwiki et il est donc facile de passer de l'un à l'autre. En fait, cet espace de test est pour moi l'occasion d'apprendre à utiliser les commandes Git et, en faisant d'une pierre deux coups, à utiliser la syntaxe Markdown.


## Les Titres en Setext  ##

Titre de niveau 1
=================

Titre de niveau 2 
-----------------

    Titre de niveau 1
    =================

    Titre de niveau 2 
    -----------------

Il suffit de souligner avec plusieurs caractères == ou -- pour avoir un titre. Le nombre importe peu.


## Les Titres en atx  ##

# Titre de niveau 1#
    # Titre de niveau 1  #

## Titre de niveau 2  ##
    ## Titre de niveau 2  ##

### Titre de niveau 3 ###
    ### Titre de niveau 3 ###

#### Titre de niveau 4 ####
    #### Titre de niveau 4 ####

##### Titre de niveau 5 #####
    ##### Titre de niveau 5 #####

###### Titre de niveau 6 ######
    ##### Titre de niveau 6 #####

## Sauts de ligne et ligne horizontale ##

> pour faire un saut de ligne, il suffit de finir une ligne par deux espaces puis de taper sur Entrée. 

> une ligne horizontale s'obtient avec au moins trois *** 

***

## Les citations ##


> et un bloc de citation avec un chevron en début de ligne
>> avec deux pour une réponse comme dans les courriels
>>> donc, avec 1 ou de multiples > en début de ligne

    > et un bloc de citation avec un chevron > en début de ligne
    >> avec deux pour une réponse comme dans les courriels
    >>> donc, avec 1 ou de multiples > en début de ligne

## Les listes ##

### Listes non ordonnées ###

*  premier point
*  deuxième point
	* sous-point
	* deuxième sous-point
+  troisième point
-  quatrième point

>    *  premier point
>    *  deuxième point
>	    * sous-point
>	    * deuxième sous-point
>    +  troisième point
>    -  quatrième point

    >Les listes non ordonnées s'obtiennent en démarrant la ligne avec le signe * ou + ou - au choix suivi d'au moins deux espaces.
    >Pour faire des sous-listes, ajouter une tabulation ou plusieurs espaces.



### Listes ordonnées ###

1.  Les listes ordonnées s'obtiennent avec un nombre suivi d'un point "." suivi d'au moins deux espaces
108.  Les nombres utilisés n'ont pas d'importance
99.  pour la sortie HTML
4.  par exemple n'importe quel chiffre (108 , 99 sera traduit par sa postion par rapport à la liste, 1 s'il est en premier, 3 s'il est en troisième position

>1.  Les listes ordonnées s'obtiennent avec un nombre suivi d'un point "." suivi d'au moins deux espaces
>108.  Les nombres utilisés n'ont pas d'importance
>99.  pour la sortie HTML
>4.  par exemple n'importe quel chiffre (108 , 99 sera traduit par sa postion par rapport à la liste, 1 s'il est en premier, 3 s'il est en troisième position

#### Sous-listes ordonnées ####

1.  Liste
	10.  sous liste
	12.  détail sous-liste
		1. encore plus détaillé
		2. et retour au premier niveau
2. retour à la liste 
3. s'obtient en ajoutant au moins trois espaces ou une tabulation. Le formatage liste sous-liste...(1., i., a.) est déjà défini.

###Les blocs###

    4 indentations (4 espaces ou une tabulation) en début de ligne créent un bloc de texte.
	

		avec la possibilité d'ajouter une indentation dans le bloc en ajoutant une tabulation ou 4 espaces.
    

    Pour sortir d'un bloc, il faut une ligne sans indentation

Sorti du bloc. 

>L'intérêt des blocs est que la syntaxe Markdown et n'importe quel code ne sont pas interprêtés.

