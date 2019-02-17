# Reseau-Social-Libre

> Réseaux social libre est un projet de réseau social non censuré et open source sous licence GPLv3.
> 
> Tous le monde peut y participer pour:
> 1. Le modifier.
> 2. L'améliorer.
> 3. Apporter ses idées.

## But de ce projet.

> Ce projet est open source et n'est affilié à aucune organisation ni aucun pays.
>
> RSL a pour but de fournir un espace libre ou les membres peuvent s'exprimer et partager librement sans censure (La pornographie, pédophilie et incitation à la haine y sont prohibé).

## Resources participatives.
1. Page Facebook: [https://www.facebook.com/Resauxsociallibre](https://www.facebook.com/Resauxsociallibre)
2. Discord: [https://discord.gg/jyqvmER](https://discord.gg/jyqvmER ) 

## Installation
> RSL est projet basé qui s'appuie sur le Framework PHP Symfony4.

1. Cloner le projet github.
    > HTTPS:  ``> git clone https://github.com/reseau-social-libre/First-Model.git``
    >
    > SSL: ``> git clone https://github.com/reseau-social-libre/First-Model.git``

2. Installer le projet.
    > ``> cd First-Model/symfony``
    > ``> composer install``
    
3. Installer la base de donnée.
    1. Copiez le fichier .env > .env.local
    2. Modifiez la ligne suivante avec les informations de connection à votre serveur MySql:
        ``DATABASE_URL=mysql://db_user:db_password@127.0.0.1:3306/db_name``
    3. ``> php bin/console doctrine:database:create``
    4. ``> php bin/console doctrine:migration:migrate``
    5. ``> php bin/console doctrine:fixture:load``
