<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Wetty para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/wetty.svg)](https://ci-apps.yunohost.org/ci/apps/wetty/) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/wetty.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/wetty.maintain.svg)

[![Instalar Wetty con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wetty)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarWetty rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Terminal over HTTP and HTTPS. WeTTy is an alternative to ajaxterm and anyterm but much better than them because WeTTy uses xterm.js which is a full fledged implementation of terminal emulation written entirely in JavaScript. WeTTy uses websockets rather then Ajax and hence better response time.


**Versión actual:** 2.7.0~ynh1

## Capturas

![Captura de Wetty](./doc/screenshots/terminal.png)

## Documentaciones y recursos

- Repositorio del código fuente oficial de la aplicación : <https://github.com/butlerx/wetty>
- Catálogo YunoHost: <https://apps.yunohost.org/app/wetty>
- Reportar un error: <https://github.com/YunoHost-Apps/wetty_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/wetty_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
o
sudo yunohost app upgrade wetty -u https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
