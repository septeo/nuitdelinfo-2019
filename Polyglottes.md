# Team Polyglottes 

Vous trouverez les sources de notre dépôt ici : https://github.com/TitouanCao/Nuit-de-l-info-12-2019 !

Pour répondre à votre défi, nous avons choisi d'implémenter deux microservices, un en Rust gérant le système de questionnaires, et un deuxième microservice en Python gérant l'authentification.

Ces deux services se trouvent dans le dossier Services, ceux-ci sont utilisés par les fichiers HTML et JS du dossier View à l'aide de requêtes Ajax.

## Démarrer le webservice python

Suivre le README dans le dossier python-flask-server

## Démarrer le werbservice python

Nécessite Rust nightly (https://rustup.rs/)

Installer diesel_cli (`cargo install diesel_cli`) pour utiliser les commandes de déploiement d'initialisation de la DB.

`diesel migration run` en étant dans le dossier du service Rust après avoir set une variable d'environnement DATABASE_URL du type `'postgres://localhost/my_db'`.

Puis lancer `cargo run` toujours en étant dans le même dossier
