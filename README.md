# Wetty for YunoHost

[![Integration level](https://dash.yunohost.org/integration/wetty.svg)](https://dash.yunohost.org/appci/app/wetty) ![](https://ci-apps.yunohost.org/ci/badges/wetty.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/wetty.maintain.svg)
[![Install wetty with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=wetty)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install wetty quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Terminal in browser over http/https. (Ajaxterm/Anyterm alternative, but much better)

**Shipped version:** 1.3.0

## Screenshots

![](https://raw.githubusercontent.com/butlerx/wetty/master/docs/terminal.png)

## Configuration

There is few configuration in Wetty :
* Startup config (listen port, url path, ssh host) is contained in the SystemD service file
* User interface configuration is done through the web gui itself.

## Documentation

 * Official documentation: https://github.com/butlerx/wetty/tree/master/docs
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

Multi-user doesn't really mean anything. You can log as any *system* user that allows local SSH login.

You can specify at install if users should log into Yunohost first to be able to access Wetty, or if visitors can access it too.

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

Developer info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/wetty_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
or
sudo yunohost app upgrade wetty -u https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
```

# TODO
- Add a `LICENSE` file for the package.
- Edit `README_fr.md`.
