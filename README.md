# Bienvenue sur l'explication de différents concepts rails !

#### Nous allons voir:

* La différence entre un site statique et un site dynamique.
* Le MVC.
* Les routes.
* Les Bases de Données.
* GET / POST.
* Le concept de migration.
* Les relations entre les models des BDD.
* Les fonctions du CRUD.


## 1.La différence entre un site statique et un site dynamique

Tout d'abord voyons la définition de ces deux types de sites selon wikipédia

Un **_site web statique_** est une page dont le contenue ne varie pas en fonction des caractéristiques de la demande, c'est-à-dire qu'à un moment donné tous les internautres qui demandent la page reçoivent le **_même contenue_**.

**_À l'inverse_**, une **_page web dynamique_** est générée à la demande et son contenue **_varie_** en fonction des caractéristiques de la demande (heure, adresse IP de l'ordinateur du demandeur, formulaire rempli par le demandeur, etc..) qui ne sont connues qu'au moment de sa consultation.

<br />
<br />

![Schéma site statique et dynamique](https://image.noelshack.com/fichiers/2018/05/1/1517235670-687474703a2f2f7777772e696d65646961732e70726f2f77702d636f6e74656e742f7468656d65732f626f6f7473747261702d6261736963342d6368696c642f696d616765732f636f7572732f706167655f7765622f706167655f73746174697175655f64796e616d697175652e676966.gif)
<br />
<br />

D'après ces deux définitions, on peut déduire que la différence majeure entre un site statique et un site dynamique est le fait que le **premier affiche toujours le même contenue** et le **second varie en fonction de la demande**.

Dans le tableau suivant, qui représente la différence majeur entre ces deux types de sites, vous trouverez des liens vers deux exemples illustrants bien chacun des types.

|Site statique   |Site dynamique|
|:---:|:---:|
|[Affiche toujours le même contenue](https://thebestmotherfucking.website/)|[Affiche un contenue variable en fonction de la demande](https://www.facebook.com/?stype=lo&jlou=AfdhijCDciu4I8pjW2UkSVMjehf_PG6TrRMOprL9_jvSPeM4CJGqLmaqVH74-rnsZ7AR95wT1RxhHJ_9YZLB_r59zcdBJUqKFy7FB44tUWPeWg&smuh=60154&lh=Ac9Fod24CQ2dj7jW)|

<br />



## 2.Le MVC (Model View Controller)

Le modèle-vue-contrôleur est un motif composé de trois modules ayant trois rôles différents :

* Un modèle (Model) contient les données à afficher.

* Une vue (View) contient la présentation de l'interface graphique.

* Un contrôleur (Controller) contient la logique concernant les actions effectuées par l'utilisateur.

<br />
<br />
![Schéma du MVC](https://image.noelshack.com/fichiers/2018/05/1/1517235673-68747470733a2f2f7777772e737570696e666f2e636f6d2f61727469636c65732f7265736f75726365732f3137353236382f3737372f312e706e67.png)
<br />
<br />

Ce motif MVC a été créé pour mettre en oeuvre des interfaces utilisateur et est donc utilisé, comme vous l'aurez compris, dans la création de site web dynamique !

## 3. Les routes



