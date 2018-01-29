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

![Schéma site statique et dynamique](http://www.imedias.pro/wp-content/themes/bootstrap-basic4-child/images/cours/page_web/page_statique_dynamique.gif)

<br />

D'après ces deux définitions, on peut déduire que la différence majeure entre un site statique et un site dynamique est le fait que le **premier affiche toujours le même contenue** et le **second varie en fonction de la demande**.

Dans le tableau suivant, qui représente la différence majeur entre ces deux types de sites, vous trouverez des liens vers deux exemples illustrants bien chacun des types.

|Site statique   |Site dynamique|
|:---:|:---:|
|[Affiche toujours le même contenue](https://thebestmotherfucking.website/)|[Affiche un contenue variable en fonction de la demande](https://www.facebook.com/?stype=lo&jlou=AfdhijCDciu4I8pjW2UkSVMjehf_PG6TrRMOprL9_jvSPeM4CJGqLmaqVH74-rnsZ7AR95wT1RxhHJ_9YZLB_r59zcdBJUqKFy7FB44tUWPeWg&smuh=60154&lh=Ac9Fod24CQ2dj7jW)|

<br />



## 2.Le MVC (Model View Controller)

Le modèle-vue-contrôleur est un motif composé de trois modules ayant trois rôles différents :




