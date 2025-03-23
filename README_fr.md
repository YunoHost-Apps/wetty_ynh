<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Wetty pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/wetty)](https://ci-apps.yunohost.org/ci/apps/wetty/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/wetty)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/wetty)

[![Installer Wetty avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wetty)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Wetty rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Terminal sur HTTP et HTTPS. WeTTy est une alternative à ajaxterm et anyterm mais bien meilleure qu'eux car WeTTy utilise xterm.js qui est une implémentation complète de l'émulation de terminal écrite entièrement en JavaScript. WeTTy utilise des websockets plutôt que Ajax et donc un meilleur temps de réponse.


**Version incluse :** 2.7.0~ynh2

## Captures d’écran

![Capture d’écran de Wetty](./doc/screenshots/terminal.png)

## Documentations et ressources

- Dépôt de code officiel de l’app : <https://github.com/butlerx/wetty>
- YunoHost Store : <https://apps.yunohost.org/app/wetty>
- Signaler un bug : <https://github.com/YunoHost-Apps/wetty_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/wetty_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
ou
sudo yunohost app upgrade wetty -u https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
