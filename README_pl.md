<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Wetty dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/wetty)](https://ci-apps.yunohost.org/ci/apps/wetty/)
![Status działania](https://apps.yunohost.org/badge/state/wetty)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/wetty)

[![Zainstaluj Wetty z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wetty)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Wetty na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

Terminal over HTTP and HTTPS. WeTTy is an alternative to ajaxterm and anyterm but much better than them because WeTTy uses xterm.js which is a full fledged implementation of terminal emulation written entirely in JavaScript. WeTTy uses websockets rather then Ajax and hence better response time.


**Dostarczona wersja:** 2.7.0~ynh2

## Zrzuty ekranu

![Zrzut ekranu z Wetty](./doc/screenshots/terminal.png)

## Dokumentacja i zasoby

- Repozytorium z kodem źródłowym: <https://github.com/butlerx/wetty>
- Sklep YunoHost: <https://apps.yunohost.org/app/wetty>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/wetty_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/wetty_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
lub
sudo yunohost app upgrade wetty -u https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
