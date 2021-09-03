# Wetty pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/wetty.svg)](https://dash.yunohost.org/appci/app/wetty) ![](https://ci-apps.yunohost.org/ci/badges/wetty.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/wetty.maintain.svg)
[![Installer Wetty avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wetty)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Wetty rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Un terminal dans le navigateur sur HTTP/HTTPS. (alternative à Ajaxterm/Anyterm)

**Version incluse :** 2.1.1~ynh0



## Avertissements / informations importantes

### Configuration

Il y a peu de configuration dans Wetty :
* La configuration de démarrage (port d'écoute, chemin d'URL, hôte SSH) est contenue dans le fichier de service systemd
* La configuration de l'interface utilisateur se fait via l'interface graphique Web elle-même.

* L'authentification LDAP et HTTP est-elle prise en charge ? **Non**
  * Vous devez vous connecter manuellement.
  * Vous pouvez spécifier l'utilisateur en accédent directement `https://<host>/wetty/ssh/<username>`

* Vous pouvez spécifier à l'installation si Wetty devrait être accessible par des visiteurs non connectés sur Yunohost.

* Vous ne pouvez pas vous authentifier par une clé SSH.

## Documentations et ressources

* Site officiel de l'app : https://github.com/butlerx/wetty
* Documentation officielle de l'admin : https://github.com/butlerx/wetty/tree/main/docs
* Dépôt de code officiel de l'app : https://github.com/butlerx/wetty
* Documentation YunoHost pour cette app : https://yunohost.org/app_wetty
* Signaler un bug : https://github.com/YunoHost-Apps/wetty_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/wetty_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
ou
sudo yunohost app upgrade wetty -u https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps
