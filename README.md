#Memo Syntaxe Markdown Github
![logo Markdown](/images/Markdown.png)

    
    ![logo Markdown](/images/Markdown.png)


Projet d'écriture : [Syntaxe Markdown Versus HTML](rep/syntaxe.md/ "En cours d'écriture")

    Projet d'écriture : [Syntaxe Markdown Versus HTML](rep/syntaxe.md/ "En cours d'écriture")

<p>&nbsp; </p>
<p>&nbsp; </p>

- [ ] Page à compléter 
  - [x] Memo 
  - [ ] Ajouter les [fonctionnalités supplémentaires Markdown de Github](https://help.github.com/articles/github-flavored-markdown/)
  - [ ] Étiquettes de liens

*** 
##Table des matières 

  * [Introduction](#introduction)
  * [Les titres](#les-titres-en-setext)
    * [Les titres en Setext](#les-titres-en-setext)
    * [Les titres en atx](#les-titres-en-atx)
  * [Les Sauts de ligne et ligne horizontale](#sauts-de-ligne-et-ligne-horizontale)  
  * [Les citations](#les-citations)
  * [Les listes](#les-listes)
    * [Les listes  non ordonnées](#listes-non-ordonnées)
    * [Les listes  ordonnées](#listes-ordonnées)
        * [Les sous-listes  ordonnées](#sous-listes-ordonnées)
  * [Les blocs de texte et code dans le texte](#les-blocs-de-texte-et-code-dans-le-texte)
  * [Emphase du texte et caractère d'échappement](#emphase-du-texte-et-caractère-déchappement)
    * [Caractère d'échappement](#caractère-déchappement)
    * [Emphase du texte](#emphase-du-texte) 
  * [Les liens](#les-liens) 
    * [Liens internes](#liens-internes) 
    * [Liens externes](#liens-externes)
    * [Étiquette des liens](#Étiquettes-des-liens)
  * [Aérer le texte](#aérer-le-texte)  
 
 ***   
     
## Introduction  ##

<u>John Gruber</u> a créé le langage Markdown est 2004, avec la participation significative de Aaron Swartz pour la syntaxe. Ce langage permet d'écrire et de lire aisément dans un format en texte plein, sans être distrait par les balises de formatage. De plus, il accepte toute balise HTML. Sa forme est très proche de la syntaxe wiki comme celle de Dokuwiki et il est donc facile de passer de l'un à l'autre. En fait, cet espace de test est pour moi l'occasion d'apprendre à utiliser les commandes Git et, en faisant d'une pierre deux coups, la syntaxe Markdown.
Github a ajouté des fonctionnalités au langage Markdown qui seront détaillés à part ou signalés comme tels.

<p>&nbsp; </p>

## Les Titres ##

### Les Titres en Setext  ###

Titre de niveau 1
=================

Titre de niveau 2 
-----------------

    Titre de niveau 1
    =================

    Titre de niveau 2 
    -----------------

Il suffit de souligner avec plusieurs caractères == ou -- pour avoir un titre. Le nombre importe peu.

<p>&nbsp; </p>

### Les Titres en atx  

# Titre de niveau 1
    # Titre de niveau 1  

## Titre de niveau 2  
    ## Titre de niveau 2  

*ou en entourant du même nombre de signes # le titre*

### Titre de niveau 3 ###
    ### Titre de niveau 3 ###

#### Titre de niveau 4 ####
    #### Titre de niveau 4 ####

##### Titre de niveau 5 #####
    ##### Titre de niveau 5 #####

###### Titre de niveau 6 ######
    ##### Titre de niveau 6 #####

<p>&nbsp; </p>

## Sauts de ligne et ligne horizontale ##

> pour faire un saut de ligne, il suffit de finir une ligne par deux espaces puis de taper sur Entrée. 

> une ligne horizontale s'obtient avec au moins trois *** 

***

<p>&nbsp; </p>


## Les citations ##


> et un bloc de citation avec un chevron en début de ligne
>> avec deux pour une réponse comme dans les courriels
>>> donc, avec 1 ou de multiples > en début de ligne

    > et un bloc de citation avec un chevron > en début de ligne
    >> avec deux pour une réponse comme dans les courriels
    >>> donc, avec 1 ou de multiples > en début de ligne

<p>&nbsp; </p>

## Les listes ##

### Listes non ordonnées ###

*  premier point
*  deuxième point
	* sous-point
	* deuxième sous-point
+  troisième point
-  quatrième point


>Les listes non ordonnées s'obtiennent en démarrant la ligne avec le signe * ou + ou - au choix suivi d'au moins deux espaces. Pour faire des sous-listes, ajouter une tabulation ou plusieurs espaces.



### Listes ordonnées ###

1.  Les listes ordonnées s'obtiennent avec un nombre suivi d'un point "." suivi d'au moins deux espaces
108.  Les nombres utilisés n'ont pas d'importance
99.  pour la sortie HTML
4.  n'importe quel chiffre sera traduit en rapport de sa position dans la liste, 1 s'il est en premier, 3 s'il est en troisième position, et non par sa valeur en tant que nombre. Vous pouvez commencer votre liste avec 1099 si cela vous chante, il sera traduit en 1. Cette liste est créée pour le test avec dans l'ordre 1, puis 108 puis 99 puis 4. 



#### Sous-listes ordonnées ####

1.  Liste
	10.  sous liste
	12.  détail sous-liste
		1. encore plus détaillé
		2. et retour au premier niveau
2. retour à la liste 
3. s'obtient en ajoutant au moins trois espaces ou une tabulation. Le formatage liste sous-liste...(1., i., a.) est déjà défini.

<p>&nbsp; </p>

##Les blocs de texte et code dans le texte ##

    4 indentations (4 espaces ou une tabulation) en début de ligne créent un bloc de texte.
	

		avec la possibilité d'ajouter une indentation dans le bloc en ajoutant une tabulation ou 4 espaces.
    

    Pour sortir d'un bloc, il faut une ligne sans indentation

Sorti du bloc. 

>L'intérêt des blocs est que la syntaxe Markdown et n'importe quel code ne sont pas interprétés. Il est également possible d'entourer une étendue de code à l'intérieur d'un paragraphe. 

> Par exemple :
Pour retrouver des fichiers d'un certain type désiminés dans des sous répertoires afin de les regrouper dans un répertoire désigné, utilisez la commande `find -type f -name "*.mp4" -exec cp {} ~/mon_repertoire_destination/ \;` et vous aurez tous vos fichiers mp4 copiés dans ce nouveau répertoire. 

Il suffit d'entourer votre commande avec un guillemet  oblique\` `Alt Gr + 7`

<p>&nbsp; </p>

## Caractère d'échappement et emphase du texte ##

### Caractère d'échappement ###

La barre oblique inverse \\ permet d'échapper des caractères qui seraient interprétés autrement comme du langage Markdown. Pour avoir littéralement ces caractères : 

     \  `  *  _  {}  [] () # + - . ! 

on utilisera la barre oblique inverse \\ 

### Emphase du texte ###

*Italique*

    *Italique*

    _Italique_

**Gras**
    
    **Gras**

    __Gras__

~~ texte barré ~~

    ~~barré~~ (uniquement sur Github)

<p>&nbsp; </p>

## Les liens ##

Les liens font référence à des ressources internes ou externes. Pour les liens internes faisant référence à une ressource locale sur le serveur, il est possible d'utiliser une adresse relative, que ce soit pour un lien de page ou d'image. Il est également possible d'affecter une étiquette à un lien et de l'appeler n'importe où dans la page (comme une ancre ou note de bas de page ?). 

###Liens internes ###

    Voir mon projet de page [Syntaxe Markdown Versus HTML](rep/syntaxe.md/ "En cours d'écriture")
> pour une page locale dans le répertoire "rep" avec une description au survol de la souris  donnera :

Voir mon projet de page [Syntaxe Markdown Versus HTML](rep/syntaxe.md/ "En cours d'écriture")

    ![logo Markdown](/images/Markdown.png)
> affichera l'image Markdown.png se trouvant dans le répertoire image comme en haut de page.

Le lien est entre crochets et l'adresse est entre parenthèses avec une description possible entre guillemets. 

Pour les images, il faut ajouter ! un point d'exclamation devant.
  
### Liens externes ###


Pour aller sur le site de [Dokuwiki](https://dokuwiki.org "Un wiki cool")   

    Pour aller sur le site de [Dokuwiki](https://dokuwiki.org "Un wiki cool")

Pour afficher une image externe 
![image travaux](https://upload.wikimedia.org/wikipedia/commons/a/ab/Warning_icon.png "Travaux en cours")

    ![image travaux](https://upload.wikimedia.org/wikipedia/commons/a/ab/Warning_icon.png"Travaux en cours")

*le langage Markdown ne permet pas de spécifier une taille d'image ou son emplacement par rapport au texte. En cas de besoin, il faudra utiliser une balise HTML.*

### Étiquettes des liens ###

<p>&nbsp; </p>
## Aérer le texte ##

        <p>&nbsp; </p>
   
>Cette balise permet d'aérer le texte.