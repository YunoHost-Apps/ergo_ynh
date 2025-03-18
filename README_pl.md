<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Ergo dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/ergo)](https://ci-apps.yunohost.org/ci/apps/ergo/)
![Status działania](https://apps.yunohost.org/badge/state/ergo)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/ergo)

[![Zainstaluj Ergo z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ergo)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Ergo na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

Ergo (formerly known as Oragono) is a modern IRC server written in Go. Its core design 

### Features

- Being simple to set up and use
- Combining the features of an ircd, a services framework, and a bouncer (integrated account management, history storage, and bouncer functionality)
- Bleeding-edge IRCv3 support, suitable for use as an IRCv3 reference implementation
- High customizability via a rehashable (i.e., reloadable at runtime) YAML config



**Dostarczona wersja:** 2.15.0~ynh1

**Demo:** <https://testnet.ergo.chat/>

## Zrzuty ekranu

![Zrzut ekranu z Ergo](./doc/screenshots/textual.jpg)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://ergo.chat/>
- Oficjalna dokumentacja: <https://github.com/ergochat/ergo/blob/stable/docs/USERGUIDE.md>
- Oficjalna dokumentacja dla administratora: <https://github.com/ergochat/ergo/blob/stable/docs/MANUAL.md>
- Repozytorium z kodem źródłowym: <https://github.com/ergochat/ergo>
- Sklep YunoHost: <https://apps.yunohost.org/app/ergo>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/ergo_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/ergo_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ergo_ynh/tree/testing --debug
lub
sudo yunohost app upgrade ergo -u https://github.com/YunoHost-Apps/ergo_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
