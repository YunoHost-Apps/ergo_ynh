<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Ergo for YunoHost

[![Integration level](https://dash.yunohost.org/integration/ergo.svg)](https://dash.yunohost.org/appci/app/ergo) ![Working status](https://ci-apps.yunohost.org/ci/badges/ergo.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/ergo.maintain.svg)

[![Install Ergo with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ergo)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Ergo quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Ergo (formerly known as Oragono) is a modern IRC server written in Go. Its core design 

### Features

- Being simple to set up and use
- Combining the features of an ircd, a services framework, and a bouncer (integrated account management, history storage, and bouncer functionality)
- Bleeding-edge IRCv3 support, suitable for use as an IRCv3 reference implementation
- High customizability via a rehashable (i.e., reloadable at runtime) YAML config



**Shipped version:** 2.13.0~ynh1

**Demo:** https://testnet.ergo.chat/

## Screenshots

![Screenshot of Ergo](./doc/screenshots/textual.jpg)

## Documentation and resources

* Official app website: <https://ergo.chat/>
* Official user documentation: <https://github.com/ergochat/ergo/blob/stable/docs/USERGUIDE.md>
* Official admin documentation: <https://github.com/ergochat/ergo/blob/stable/docs/MANUAL.md>
* Upstream app code repository: <https://github.com/ergochat/ergo>
* YunoHost Store: <https://apps.yunohost.org/app/ergo>
* Report a bug: <https://github.com/YunoHost-Apps/ergo_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/ergo_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/ergo_ynh/tree/testing --debug
or
sudo yunohost app upgrade ergo -u https://github.com/YunoHost-Apps/ergo_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
