<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Wetty per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/wetty.svg)](https://dash.yunohost.org/appci/app/wetty) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/wetty.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/wetty.maintain.svg)

[![Installa Wetty con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wetty)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Wetty su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

Terminal over HTTP and HTTPS. WeTTy is an alternative to ajaxterm and anyterm but much better than them because WeTTy uses xterm.js which is a full fledged implementation of terminal emulation written entirely in JavaScript. WeTTy uses websockets rather then Ajax and hence better response time.


**Versione pubblicata:** 2.5.0~ynh3

## Screenshot

![Screenshot di Wetty](./doc/screenshots/terminal.png)

## Documentazione e risorse

- Repository upstream del codice dell’app: <https://github.com/butlerx/wetty>
- Store di YunoHost: <https://apps.yunohost.org/app/wetty>
- Segnala un problema: <https://github.com/YunoHost-Apps/wetty_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/wetty_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
o
sudo yunohost app upgrade wetty -u https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
