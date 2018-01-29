### Bienvenue sur l'explication de différents concepts rails !

#### Ici nous allons voir

* La différence entre un site statique et un site dynamique.
* Le MVC.
* Les routes.
* Les Bases de Données.
* GET / POST.
* Le concept de migration.
* Les relations entre les models des BDD.
* Les fonctions du CRUD.

---

# La différence entre un site statique et un site dynamique

Tout d'abord voyons la définition de ces deux types de sites selon wikipédia

Un _site web statique_ est une page dont le contenue ne varie pas en fonction des caractéristiques de la demande, c'est-à-dire qu'à un moment donné tous les internautres qui demandent la page reçoivent le **_même contenue_**.

**_À l'inverse_**, une _page web dynamique_ est générée à la demande et son contenue **_varie_** en fonction des caractéristiques de la demande (heure, adresse IP de l'ordinateur du demandeur, formulaire rempli par le demandeur, etc..) qui ne sont connues qu'au moment de sa consultation.

D'après ces deux définitions, on peut déduire que la différence majeure entre un site statique et un site dynamique est le fait que le premier affiche toujours le **même contenue** et le **second varie** en fonction de la demande.

<center>

|Site statique    |Site dynamique    |
|-----------------|------------------|
|même contenue    |contenue variable |

</center>


# Le MVC (Model View Controller)

Le modèle-vue-contrôleur est un motif composé de trois modules ayant trois rôles différents :




