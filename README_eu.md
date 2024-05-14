<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Wetty YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/wetty.svg)](https://dash.yunohost.org/appci/app/wetty) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/wetty.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/wetty.maintain.svg)

[![Instalatu Wetty YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wetty)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Wetty YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Terminal over HTTP and HTTPS. WeTTy is an alternative to ajaxterm and anyterm but much better than them because WeTTy uses xterm.js which is a full fledged implementation of terminal emulation written entirely in JavaScript. WeTTy uses websockets rather then Ajax and hence better response time.


**Paketatutako bertsioa:** 2.5.0~ynh3

## Pantaila-argazkiak

![Wetty(r)en pantaila-argazkia](./doc/screenshots/terminal.png)

## Dokumentazioa eta baliabideak

- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/butlerx/wetty>
- YunoHost Denda: <https://apps.yunohost.org/app/wetty>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/wetty_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/wetty_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
edo
sudo yunohost app upgrade wetty -u https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
