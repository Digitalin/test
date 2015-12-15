#Memo Syntaxe Markdown 

## Les Titres en Setext  ##

Titre de niveau 1
=================

Titre de niveau 2 
-----------------

    Titre de niveau 1
    =================

    Titre de niveau 2 
    -----------------

Il suffit de souligner avec plusieurs caractères == ou -- pour avoir un titre


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

> une ligne horizontale s'obtient avec trois ***

***

## Les citations ##


> et un bloc de citation avec un > en début de ligne
>> avec deux pour une réponse
>>> donc, avec 1 ou de multiples > en début de ligne

    > et un bloc de citation avec un > en début de ligne
    >> avec deux pour une réponse
    >>> donc, avec 1 ou de multiples > en début de ligne

## Les listes ##

### Listes non ordonnées ###

*  premier point
*  deuxième point
	* sous-point
	* deuxième sous-point
+  troisième point



    >Les listes non ordonnées s'obtiennent en démarrant la ligne avec le signe * ou + ou - au choix suivi d'au moins deux espaces.
    >Pour faire des sous-listes, ajouter une tabulation ou plusieurs espaces.



### Listes ordonnées ###

1.  Les listes ordonnées s'obtiennent avec un nombre suivi d'un point "." suivi d'au moins deux espaces
2.  Les nombres utilisés n'ont pas d'importance
3.  pour la sortie HTML
4.  par exemple n'importe quel chiffre (108 , 99 sera traduit par sa postion par rapport à la liste, 1 s'il est en premier, 3 s'il est en troisième position

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

>L'intérêt des blocs est que syntaxe Markdown et code ne sont pas interprêtés.

