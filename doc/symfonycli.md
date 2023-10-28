# Commandes symfony-cli utilisée pour le projet
```
symfony new symfo-basic-app --version="6.3.*" --webapp
#creation de la BDD
symfony console d:d:c
#creation table utilisateur et liaison avec firewall symfony
symfony console make:user
symfony console make:migration
symfony console d:m:m

```