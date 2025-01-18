<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Wetty voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/wetty)](https://ci-apps.yunohost.org/ci/apps/wetty/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/wetty)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/wetty)

[![Wetty met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wetty)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Wetty snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Terminal over HTTP and HTTPS. WeTTy is an alternative to ajaxterm and anyterm but much better than them because WeTTy uses xterm.js which is a full fledged implementation of terminal emulation written entirely in JavaScript. WeTTy uses websockets rather then Ajax and hence better response time.


**Geleverde versie:** 2.7.0~ynh1

## Schermafdrukken

![Schermafdrukken van Wetty](./doc/screenshots/terminal.png)

## Documentatie en bronnen

- Upstream app codedepot: <https://github.com/butlerx/wetty>
- YunoHost-store: <https://apps.yunohost.org/app/wetty>
- Meld een bug: <https://github.com/YunoHost-Apps/wetty_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/wetty_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
of
sudo yunohost app upgrade wetty -u https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
