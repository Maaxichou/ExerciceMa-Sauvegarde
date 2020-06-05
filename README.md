# ExerciceMa-Sauvegarde

Cloner le projet


Faire un composer install


Créer le .env.local avec la DATABASE_URL dedans (en se basant sur celle qu'il y a dans le .env).


(optionnel) Faire un bin/console doctrine:database:create pour créer la bdd si elle n'existe pas


Faire un bin/console doctrine:migrations:migrate pour exécuter les dernière migrations et mettre à jour la base de données


Faire un bin/console doctrine:fixtures:load pour charger les données de test


Si ça ne marche pas, faire un bin/console doctrine:database:drop et reprendre à l'étape 4
