<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Wetty for YunoHost

[![Integration level](https://dash.yunohost.org/integration/wetty.svg)](https://dash.yunohost.org/appci/app/wetty) ![Working status](https://ci-apps.yunohost.org/ci/badges/wetty.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/wetty.maintain.svg)  
[![Install Wetty with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wetty)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Wetty quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Terminal over HTTP and HTTPS. WeTTy is an alternative to ajaxterm and anyterm but much better than them because WeTTy uses xterm.js which is a full fledged implementation of terminal emulation written entirely in JavaScript. WeTTy uses websockets rather then Ajax and hence better response time.


**Shipped version:** 2.5.0~ynh1

## Screenshots

![Screenshot of Wetty](./doc/screenshots/terminal.png)

## Disclaimers / important information

### Configuration

There is few configuration in Wetty:
* Startup config (listen port, URL path, SSH host) is contained in the systemd service file
* User interface configuration is done through the web GUI itself.


* Is LDAP and HTTP authentication supported? **No**
  * You need to manually log in.
  * You can log in as a specific user using `https://<host>/wetty/ssh/<username>`

* You can specify at install if Wetty should be visible by users not logged into YunoHost.

* You can't use ssh key authentication.

## Documentation and resources

* Official app website: <https://github.com/butlerx/wetty>
* Official admin documentation: <https://github.com/butlerx/wetty/tree/main/docs>
* Upstream app code repository: <https://github.com/butlerx/wetty>
* YunoHost documentation for this app: <https://yunohost.org/app_wetty>
* Report a bug: <https://github.com/YunoHost-Apps/wetty_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/wetty_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
or
sudo yunohost app upgrade wetty -u https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
