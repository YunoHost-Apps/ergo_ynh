<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Ergo para Yunohost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/ergo)](https://ci-apps.yunohost.org/ci/apps/ergo/)
![Estado funcional](https://apps.yunohost.org/badge/state/ergo)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/ergo)

[![Instalar Ergo con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ergo)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarErgo rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Ergo is a modern IRC server written in Go. Its core design 

### Features

- Being simple to set up and use
- Combining the features of an ircd, a services framework, and a bouncer (integrated account management, history storage, and bouncer functionality)
- Bleeding-edge IRCv3 support, suitable for use as an IRCv3 reference implementation
- High customizability via a rehashable (i.e., reloadable at runtime) YAML config



**Versión actual:** 2.14.0~ynh2

**Demo:** <https://testnet.ergo.chat/>

## Capturas

![Captura de Ergo](./doc/screenshots/textual.jpg)

## Documentaciones y recursos

- Sitio web oficial: <https://ergo.chat/>
- Documentación usuario oficial: <https://github.com/ergochat/ergo/blob/stable/docs/USERGUIDE.md>
- Documentación administrador oficial: <https://github.com/ergochat/ergo/blob/stable/docs/MANUAL.md>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/ergochat/ergo>
- Catálogo YunoHost: <https://apps.yunohost.org/app/ergo>
- Reportar un error: <https://github.com/YunoHost-Apps/ergo_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/ergo_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ergo_ynh/tree/testing --debug
o
sudo yunohost app upgrade ergo -u https://github.com/YunoHost-Apps/ergo_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
