 ## Présentation
 Application Symfony 7 pour gérer une bibliothèque. Les utilisateurs réservent des livres, les admins gèrent livres et réservations.

 ## Démo en ligne
 [https://bibliotheque-symfony.herokuapp.com](https://bibliotheque-symfony.herokuapp.com)

 ## Fonctionnalités
 - **Authentification** (2 points) : Inscription, connexion, déconnexion (ROLE_USER, ROLE_ADMIN).
 - **CRUD complet** (1 point) : Livre, Catégorie, Réservation.
 - **CRUD réservé** (1 point) : Livres gérés par admins.
 - **Relations** (1 point) : Livre-Catégorie, Réservation-User/Livre.
 - **Affichage conditionnel** (1 point) : Disponibilité des livres.
 - **Mise à jour métier** (2 points) : Validation des réservations.
 - **Affichage utilisateur** (1 point) : Réservations utilisateur.
 - **Bonnes pratiques** (1 point) : Code MVC propre.

 ## Installation locale
 1. Cloner :
    ```bash
    git clone https://github.com/tonusername/bibliotheque.git
    cd bibliotheque
    ```
 2. Installer :
    ```bash
    composer install
    ```
 3. Configurer `.env` :
    ```
    DATABASE_URL="sqlite:///%kernel.project_dir%/var/data.db"
    ```
 4. Créer DB :
    ```bash
    php bin/console doctrine:database:create
    php bin/console doctrine:migrations:migrate
    ```
 5. Lancer :
    ```bash
    symfony server:start
    ```

 ## Captures d’écran
 - [Accueil](docs/accueil.png)
 - [Réservations](docs/reservations.png)

 ## Auteur
DIABY Karfalla
