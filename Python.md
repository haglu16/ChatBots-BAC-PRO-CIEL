---
clavier: true
gestionGrosMots: true
rechercheContenu: true
avatar: https://minio.apps.education.fr/codimd-prod/uploads/upload_dda923136f1c5a0db9a97068d60521b6.jpg
avatarCercle: true
favicon: https://minio.apps.education.fr/codimd-prod/uploads/upload_dda923136f1c5a0db9a97068d60521b6.jpg
obfuscate: true
tags: Python, chatbot
---

# Bot d'apprentissage pour python

<span style="color: #E30037;font-size: 25px">**Apprentissage du langage python** </span>

Bienvenue sur le chatbot d’aide à l'apprentissage du langage python.

![](https://minio.apps.education.fr/codimd-prod/uploads/upload_dda923136f1c5a0db9a97068d60521b6.jpg)

Python est un langage de programmation interprété, multiparadigme et multiplateformes. Il favorise la programmation impérative structurée, fonctionnelle et orientée objet. Il est doté d'un typage dynamique fort, d'une gestion automatique de la mémoire par ramasse-miettes et d'un système de gestion d'exceptions; il est ainsi similaire à Perl, Ruby, Scheme, Smalltalk et Tcl. 

Voici un tutoriel détaillé pour maîtriser les base du langage python.

![](https://minio.apps.education.fr/codimd-prod/uploads/upload_54aacee764f6b8fd117582b853016955.jpg)

1. [acceder au leçons](Différentes leçons)

## Différentes leçons


Quelle leçons voulez-vous réviser aujourd'hui ?

1. [Premiers pas](Les base)
2. [Les boucles en python](Les boucles for)
3. [Les variables](Les variables en python)
4. [Les conditions](if elif else)
5. [Les extentions](Les Librairie)
6. [Lien tuto youtube](Tuto youtube 2h)
7. [Console de test python](Console de test)
8. [Crédit](Crédit) 



## Les boucles for

- boucles

Les boucle serve a faire des actions répétées comme par exemple ajouter 1 a une variable on fera donc

    a=0 ## pour définir la variable "a"
    for loop in range(x):    ## on remplace x par le nombre de fois ou on veux executer la boucle
        a += 1    ## ici nous on ajoute 1 a la variable a il ne faut pas oubler d'incrémenter la ligne pour quelle soit dans la boucle
    print(a) ##Donc a la fin A sera égale a X

Essaie donc de copier et d'executer ce bout de code

1. [retour au leçons](Différentes leçons)

## Les variables en python

- variables
- variables en python


En python nous utilisons des "variables" qui sont données par l'utilisateur, elles peuvent avoir plusieurs fonctions comme des nombres entiers avec le préfixe "int", ou des nombres decimaux avec le préfixe "float".

exemple:

    float(x) ## ici x est le nom de la variable


1. [retour au leçons](Différentes leçons)

##  Tuto youtube 2h

- video

Tuto youtube d'environ 2h :

<iframe width="560" height="315" src="https://www.youtube.com/embed/oUJolR5bX6g?si=5plVLIErM8CmW-0p" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

1. [retour au leçons](Différentes leçons)

## if elif else

- if
- elif 
- else

Nous allons maitenant voir comment fonctione les conditions , pour demander une condition nous utilisons la commande "if" ensuite nous mettons les conditions 
par exemple: 

    a=0 
    for i in range(3):            ##ici nous faisont une boucle
        if a==2:                   ##ici nous regardons si a=2 
            print(a)              ##écrire le contenue de a
        elif a==1:  ##si le if est faux alors la 2nd solution est a=1 
            print(a)
            a+=1
        else: ##si l'autre condition est fausse alors else s'execute
            a+=1


== (deux signes égal) pour tester l'égalité entre deux valeurs
< et > pour faire une comparaison au sens strict
<= et >= pour faire une comparaison au sens large
!= pour tester la différence entre deux valeurs


vous pouvez essayer de copier ce code et de le coller dans la console de la dernière leçon .

1. [retour au leçons](Différentes leçons)

## Les Librairie

- Librairie
- Extention
- Addon

Dans python nous pouvons utiliser des "librairie". Ce sont des scripts crée par des utilisateurs en plus des commandes de base que nous pouvons ajouter et utiliser par exemple la librairie "maths" qui est assez connu pour faire des calculs ou encore "random" qui permet de générer des chiffres aléatoires comme dans l'exemple ci dessous:

    import random    #Ici nous importons l'extention random
    choix = input("Pile ou face ? ")
    n = random.randint(1, 2) #Voici la nouvelle commande pour donner un chiffre entre 1 et 2
    if n == 1:
        choix = "face"
    else:
        choix = "pile"
    print(choix)
    if choix == choix:
        print("gagné")
    else: 
        print("perdu")
voici un code à copier coller pour jouer à pile ou face.

1. [retour au leçons](Différentes leçons)

## Console de test

- console

<iframe width="560" height="315" src="https://capytale2.ac-paris.fr/p/basthon/c/?kernel=python3-legacy&mode=create&id=5149932" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

[*- Documentation de la console "basthon"*](https://basthon.fr/doc.html)
[*- Console "basthon"*](https://console.basthon.fr/)


1. [retour au leçons](Différentes leçons)

## Crédit

- Credit

Hugo Hérault

1. [retour au leçons](Différentes leçons)

## Les base

- base
- print
- insert
- input

Python est un langage dit "parler" qui est accessible facilement par exemple pour écrire du texte on utilise la commande "print":

    print("bonjour!") #La commande écrira bonjour!

1. [retour au leçons](Différentes leçons)    
on peux aussi donner des information par exemple:

    nom = input("Votre nom ? ") #On demande un nom avec "input" 
    print("Bonjour", nom) # attention a ne pas oublier la virgule
    

