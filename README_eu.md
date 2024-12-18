<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Ergo YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/ergo)](https://ci-apps.yunohost.org/ci/apps/ergo/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/ergo)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/ergo)

[![Instalatu Ergo YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ergo)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Ergo YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Ergo (formerly known as Oragono) is a modern IRC server written in Go. Its core design 

### Features

- Being simple to set up and use
- Combining the features of an ircd, a services framework, and a bouncer (integrated account management, history storage, and bouncer functionality)
- Bleeding-edge IRCv3 support, suitable for use as an IRCv3 reference implementation
- High customizability via a rehashable (i.e., reloadable at runtime) YAML config



**Paketatutako bertsioa:** 2.14.0~ynh1

**Demoa:** <https://testnet.ergo.chat/>

## Pantaila-argazkiak

![Ergo(r)en pantaila-argazkia](./doc/screenshots/textual.jpg)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://ergo.chat/>
- Erabiltzaileen dokumentazio ofiziala: <https://github.com/ergochat/ergo/blob/stable/docs/USERGUIDE.md>
- Administratzaileen dokumentazio ofiziala: <https://github.com/ergochat/ergo/blob/stable/docs/MANUAL.md>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/ergochat/ergo>
- YunoHost Denda: <https://apps.yunohost.org/app/ergo>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/ergo_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/ergo_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ergo_ynh/tree/testing --debug
edo
sudo yunohost app upgrade ergo -u https://github.com/YunoHost-Apps/ergo_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
