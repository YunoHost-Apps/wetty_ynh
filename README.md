# Wetty for YunoHost

[![Integration level](https://dash.yunohost.org/integration/wetty.svg)](https://dash.yunohost.org/appci/app/wetty) ![](https://ci-apps.yunohost.org/ci/badges/wetty.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/wetty.maintain.svg)
[![Install Wetty with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wetty)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Wetty quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Terminal in browser over HTTP/HTTPS. (Ajaxterm/Anyterm alternative, but much better)

**Shipped version:** 2.0.3

## Screenshots

![](https://raw.githubusercontent.com/butlerx/wetty/v2.0.2/docs/terminal.png)

## Configuration

There is few configuration in Wetty:
* Startup config (listen port, URL path, SSH host) is contained in the systemd service file
* User interface configuration is done through the web GUI itself.

## Documentation

* Official documentation: https://github.com/butlerx/wetty/tree/master/docs
* YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

* Is LDAP and HTTP authentication supported ? **No**
  * Nevertheless, being connected on Yunohost prevents using `/wetty/ssh/<user>`

Multi-user doesn't really mean anything. You can log as any *system* user that allows local SSH login.

You can specify at install if users should log into YunoHost first to be able to access Wetty, or if visitors can access it too.

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/wetty%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/wetty/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/wetty%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/wetty/)

## Limitations

* You can't use ssh key authentication.

## Links

* Report a bug: https://github.com/YunoHost-Apps/wetty_ynh/issues
* Upstream app repository: https://github.com/butlerx/wetty
* YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/wetty_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
or
sudo yunohost app upgrade wetty -u https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
```
