# Wetty pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/wetty.svg)](https://dash.yunohost.org/appci/app/wetty) ![](https://ci-apps.yunohost.org/ci/badges/wetty.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/wetty.maintain.svg)  
[![Installer Wetty avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=wetty)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d'installer Wetty rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
Terminal dans un navigateur par http/https. (Alternative à Ajaxterm/Anyterm, mais bien meilleure)

**Version incluse :** 2.0.2

## Captures d'écran

![](https://raw.githubusercontent.com/butlerx/wetty/master/docs/terminal.png)

## Configuration

Il y a peu de configuration dans Wetty :
* La configuration de démarrage (port d'écoute, chemin d'url, hôte ssh) est contenue dans le fichier de service SystemD
* La configuration de l'interface utilisateur se fait via l'interface graphique Web elle-même.

## Documentation

 * Documentation officielle : https://github.com/butlerx/wetty/tree/master/docs
 * Documentation YunoHost : Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ?
* L'application peut-elle être utilisée par plusieurs utilisateurs ? 

La notion de multi-utilisateur ne s'applique pas. Vous pouvez vous connecter en tant que n'importe quel utilisateur *système* qui autorise la connexion SSH locale.

Vous pouvez spécifier lors de l'installation si les utilisateurs doivent d'abord se connecter à YunoHost pour pouvoir accéder à Wetty, ou si les visiteurs peuvent également y accéder.

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/wetty%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/wetty/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/wetty%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/wetty/)

## Limitations

* Vous ne pouvez pas vous authentifier avec des clés SSH.

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/wetty_ynh/issues
 * Dépôt de l'application principale : https://github.com/butlerx/wetty
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/wetty_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
ou
sudo yunohost app upgrade wetty -u https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
```
