<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Ergo pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/ergo.svg)](https://dash.yunohost.org/appci/app/ergo) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/ergo.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/ergo.maintain.svg)  
[![Installer Ergo avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ergo)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d'installer Ergo rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Ergo (formerly known as Oragono) is a modern IRC server written in Go. Its core design 

### Features

- Being simple to set up and use
- Combining the features of an ircd, a services framework, and a bouncer (integrated account management, history storage, and bouncer functionality)
- Bleeding-edge IRCv3 support, suitable for use as an IRCv3 reference implementation
- High customizability via a rehashable (i.e., reloadable at runtime) YAML config



**Version incluse :** 2.10.0~ynh2

**Démo :** https://testnet.ergo.chat/

## Captures d'écran

![Capture d'écran de Ergo](./doc/screenshots/textual.jpg)

## Avertissements / informations importantes

* Known Limitations:
    * WebIRC has not been setup correctly for now

* Other Information
    * Command to become operator is `/OPER admin password_set_during_install`

## Documentations et ressources

* Site officiel de l'app : <https://ergo.chat/>
* Documentation officielle utilisateur : <https://github.com/ergochat/ergo/blob/stable/docs/USERGUIDE.md>
* Documentation officielle de l'admin : <https://github.com/ergochat/ergo/blob/stable/docs/MANUAL.md>
* Dépôt de code officiel de l'app : <https://github.com/ergochat/ergo>
* Documentation YunoHost pour cette app : <https://yunohost.org/app_ergo>
* Signaler un bug : <https://github.com/YunoHost-Apps/ergo_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/ergo_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/ergo_ynh/tree/testing --debug
ou
sudo yunohost app upgrade ergo -u https://github.com/YunoHost-Apps/ergo_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** <https://yunohost.org/packaging_apps>
