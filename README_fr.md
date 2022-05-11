# Spacedeck pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/spacedeck.svg)](https://dash.yunohost.org/appci/app/spacedeck) ![](https://ci-apps.yunohost.org/ci/badges/spacedeck.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/spacedeck.maintain.svg)  
[![Installer Spacedeck avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=spacedeck)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Spacedeck rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

A web based, real time, collaborative whiteboard application with rich media support


**Version incluse :** 2022.05.09~ynh1



## Captures d'écran

![](./doc/screenshots/spacedeck.png)

## Avertissements / informations importantes

* The app can only be installed at the root of a domain
* There is no integration with YunoHost SSO
* A email is send at the end of the installation with the Beta Invite Code

## Documentations et ressources

* Site officiel de l'app : https://spacedeck.com
* Dépôt de code officiel de l'app : https://github.com/spacedeck/spacedeck-open
* Documentation YunoHost pour cette app : https://yunohost.org/app_spacedeck
* Signaler un bug : https://github.com/YunoHost-Apps/spacedeck_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/spacedeck_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/spacedeck_ynh/tree/testing --debug
ou
sudo yunohost app upgrade spacedeck -u https://github.com/YunoHost-Apps/spacedeck_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps