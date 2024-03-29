<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Ergo per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/ergo.svg)](https://dash.yunohost.org/appci/app/ergo) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/ergo.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/ergo.maintain.svg)

[![Installa Ergo con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ergo)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Ergo su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

Ergo (formerly known as Oragono) is a modern IRC server written in Go. Its core design 

### Features

- Being simple to set up and use
- Combining the features of an ircd, a services framework, and a bouncer (integrated account management, history storage, and bouncer functionality)
- Bleeding-edge IRCv3 support, suitable for use as an IRCv3 reference implementation
- High customizability via a rehashable (i.e., reloadable at runtime) YAML config



**Versione pubblicata:** 2.13.0~ynh1

**Prova:** <https://testnet.ergo.chat/>

## Screenshot

![Screenshot di Ergo](./doc/screenshots/textual.jpg)

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://ergo.chat/>
- Documentazione ufficiale per gli utenti: <https://github.com/ergochat/ergo/blob/stable/docs/USERGUIDE.md>
- Documentazione ufficiale per gli amministratori: <https://github.com/ergochat/ergo/blob/stable/docs/MANUAL.md>
- Repository upstream del codice dell’app: <https://github.com/ergochat/ergo>
- Store di YunoHost: <https://apps.yunohost.org/app/ergo>
- Segnala un problema: <https://github.com/YunoHost-Apps/ergo_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/ergo_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ergo_ynh/tree/testing --debug
o
sudo yunohost app upgrade ergo -u https://github.com/YunoHost-Apps/ergo_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
