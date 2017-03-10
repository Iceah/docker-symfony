# docker-symfony
Docker Symfony sous Apache-PHP7-Mysql

Pour installer le conteneur :

1 - Télécharger via Git le contenu complet

2 - Se rendre dans le dossier via le terminal de Docker
Renommer le fichier cp.env en .env
Vous pouvez modifier les paramètres de Mysql (user,password) dans le fichier docker-compose.

3 - Executer docker-compose.exe build

4 - Executer docker-compose.exe up -d

5 - Executer docker-compose exec php bash

6 - Exectuer symfony new nomduprojet et enjoy !

Modifier vos fichiers Symfony dans le dossier html de votre ordinateur, et particulièrement /web/app_dev.php où vous devez commenter la partie relative à l'IP autorisée. 
Pour afficher votre site sous Symfony : 192.168.99.100/nomdevotreprojet/web/app_dev.php


