Fini de F5 comme un degen pour réussir à obtenir un billet pour un train complet.

## How to

* Faites votre recherche manuellement 1 fois sur le site sncf-connect
* Ouvrez la console développeur avec F12, allez dans l'onglet réseau
* Actualisez la page (F5)
* Dans les requêtes qui s'affichent dans votre onglet réseau, repérer la requête qui contient l'ID de votre recherche :

![](image.jpg)

* copiez l'ID de la requête dans le paramètre "request_id" du notebook
* compléter la variable "range_wanted" pour définir la période qui vous intéresse
* exécutez le notebook

Votre recherche est ainsi relancée toutes les minutes. Vous avez une alerte sonore quand un train se libère dans la période voulue. A vous ensuite de retourner sur votre recherche dans votre navigateur pour réserver la place qui vient de se libérer.
