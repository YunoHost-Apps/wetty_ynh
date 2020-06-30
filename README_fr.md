# Wetty pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/wetty.svg)](https://dash.yunohost.org/appci/app/wetty) ![](https://ci-apps.yunohost.org/ci/badges/wetty.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/wetty.maintain.svg)
[![Installer wetty avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=wetty)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d'installer wetty rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
Terminal dans un navigateur par http/https. (Alternative à Ajaxterm/Anyterm, mais bien meilleure)

**Version incluse :** 1.3.0

## Captures d'écran

![](https://raw.githubusercontent.com/butlerx/wetty/master/docs/terminal.png)

## Configuration

There is few configuration in Wetty :
* Startup config (listen port, url path, ssh host) is contained in the SystemD service file
* User interface configuration is done through the web gui itself.

## Documentation

 * Documentation officielle : https://github.com/butlerx/wetty/tree/master/docs
 * Documentation YunoHost : Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ?
* L'application peut-elle être utilisée par plusieurs utilisateurs ?

Multi-user doesn't really mean anything. You can log as any *system* user that allows local SSH login.

You can specify at install if users should log into Yunohost first to be able to access Wetty, or if visitors can access it too.

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

Informations pour les développeurs
----------------

**Seulement si vous voulez utiliser une branche de test pour le codage, au lieu de fusionner directement dans la banche principale.**
Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/wetty_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
ou
sudo yunohost app upgrade wetty -u https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
```
