<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Ergo voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/ergo)](https://ci-apps.yunohost.org/ci/apps/ergo/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/ergo)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/ergo)

[![Ergo met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ergo)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Ergo snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Ergo is a modern IRC server written in Go. Its core design 

### Features

- Being simple to set up and use
- Combining the features of an ircd, a services framework, and a bouncer (integrated account management, history storage, and bouncer functionality)
- Bleeding-edge IRCv3 support, suitable for use as an IRCv3 reference implementation
- High customizability via a rehashable (i.e., reloadable at runtime) YAML config



**Geleverde versie:** 2.14.0~ynh1

**Demo:** <https://testnet.ergo.chat/>

## Schermafdrukken

![Schermafdrukken van Ergo](./doc/screenshots/textual.jpg)

## Documentatie en bronnen

- Officiele website van de app: <https://ergo.chat/>
- Officiele gebruikersdocumentatie: <https://github.com/ergochat/ergo/blob/stable/docs/USERGUIDE.md>
- Officiele beheerdersdocumentatie: <https://github.com/ergochat/ergo/blob/stable/docs/MANUAL.md>
- Upstream app codedepot: <https://github.com/ergochat/ergo>
- YunoHost-store: <https://apps.yunohost.org/app/ergo>
- Meld een bug: <https://github.com/YunoHost-Apps/ergo_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/ergo_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ergo_ynh/tree/testing --debug
of
sudo yunohost app upgrade ergo -u https://github.com/YunoHost-Apps/ergo_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
