<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Ergo pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/ergo.svg)](https://dash.yunohost.org/appci/app/ergo) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/ergo.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/ergo.maintain.svg)

[![Installer Ergo avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ergo)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Ergo rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Ergo (anciennement connu sous le nom d'Oragono) est un serveur IRC moderne écrit en Go. Sa conception de base

### Caractéristiques

- Être simple à configurer et à utiliser
- Combinant les fonctionnalités d'un ircd, d'un framework de services et d'un videur (gestion de compte intégrée, stockage de l'historique et fonctionnalité de videur)
- Prise en charge IRCv3 de pointe, adaptée à une utilisation comme implémentation de référence IRCv3
- Haute personnalisation via une configuration YAML réutilisable (c'est-à-dire rechargeable au moment de l'exécution)


**Version incluse :** 2.13.1~ynh1

**Démo :** <https://testnet.ergo.chat/>

## Captures d’écran

![Capture d’écran de Ergo](./doc/screenshots/textual.jpg)

## Documentations et ressources

- Site officiel de l’app : <https://ergo.chat/>
- Documentation officielle utilisateur : <https://github.com/ergochat/ergo/blob/stable/docs/USERGUIDE.md>
- Documentation officielle de l’admin : <https://github.com/ergochat/ergo/blob/stable/docs/MANUAL.md>
- Dépôt de code officiel de l’app : <https://github.com/ergochat/ergo>
- YunoHost Store : <https://apps.yunohost.org/app/ergo>
- Signaler un bug : <https://github.com/YunoHost-Apps/ergo_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/ergo_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ergo_ynh/tree/testing --debug
ou
sudo yunohost app upgrade ergo -u https://github.com/YunoHost-Apps/ergo_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
