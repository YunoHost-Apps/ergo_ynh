<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Ergo para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/ergo.svg)](https://dash.yunohost.org/appci/app/ergo) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/ergo.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/ergo.maintain.svg)

[![Instalar Ergo con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ergo)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Ergo de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

Ergo (formerly known as Oragono) is a modern IRC server written in Go. Its core design 

### Features

- Being simple to set up and use
- Combining the features of an ircd, a services framework, and a bouncer (integrated account management, history storage, and bouncer functionality)
- Bleeding-edge IRCv3 support, suitable for use as an IRCv3 reference implementation
- High customizability via a rehashable (i.e., reloadable at runtime) YAML config



**Versión proporcionada:** 2.13.1~ynh1

**Demo:** <https://testnet.ergo.chat/>

## Capturas de pantalla

![Captura de pantalla de Ergo](./doc/screenshots/textual.jpg)

## Documentación e recursos

- Web oficial da app: <https://ergo.chat/>
- Documentación oficial para usuarias: <https://github.com/ergochat/ergo/blob/stable/docs/USERGUIDE.md>
- Documentación oficial para admin: <https://github.com/ergochat/ergo/blob/stable/docs/MANUAL.md>
- Repositorio de orixe do código: <https://github.com/ergochat/ergo>
- Tenda YunoHost: <https://apps.yunohost.org/app/ergo>
- Informar dun problema: <https://github.com/YunoHost-Apps/ergo_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/ergo_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ergo_ynh/tree/testing --debug
ou
sudo yunohost app upgrade ergo -u https://github.com/YunoHost-Apps/ergo_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
