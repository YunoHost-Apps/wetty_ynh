<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Wetty untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/wetty.svg)](https://ci-apps.yunohost.org/ci/apps/wetty/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/wetty.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/wetty.maintain.svg)

[![Pasang Wetty dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wetty)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Wetty secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Terminal over HTTP and HTTPS. WeTTy is an alternative to ajaxterm and anyterm but much better than them because WeTTy uses xterm.js which is a full fledged implementation of terminal emulation written entirely in JavaScript. WeTTy uses websockets rather then Ajax and hence better response time.


**Versi terkirim:** 2.7.0~ynh1

## Tangkapan Layar

![Tangkapan Layar pada Wetty](./doc/screenshots/terminal.png)

## Dokumentasi dan sumber daya

- Depot kode aplikasi hulu: <https://github.com/butlerx/wetty>
- Gudang YunoHost: <https://apps.yunohost.org/app/wetty>
- Laporkan bug: <https://github.com/YunoHost-Apps/wetty_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/wetty_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
atau
sudo yunohost app upgrade wetty -u https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
