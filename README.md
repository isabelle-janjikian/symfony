# symfony
Simple liste sur Symfony en générant un base de donnée et un CRUD en commande ligne.
Visible sur https://127.0.0.1:8000/post/

> CREER UNE BDD en ligne de commande
>
Installer Doctrine
> composer require symfony/orm-pack
> composer require --dev symfony/maker-bundle
>
pour créer la bdd :
> php bin/console doctrine:database:create
>
Créer une entité (table)
> php bin/console make:entity
>
Générer le fichier sql
> php bin/console make:migration
>
faire la migration
> php bin/console doctrine:migrations:migrate

> CREER UN CRUD EN LIGNE DE COMMANDE
1 - créer une entity
> php bin/console make:entity

nom entité : 
> post

2 - créer un CRUD
>php bin/console make:crud

 The class name of the entity to create CRUD:
 > Post

 Choose a name for your controller class:
 > PostController
