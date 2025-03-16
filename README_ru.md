<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Ergo для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/ergo)](https://ci-apps.yunohost.org/ci/apps/ergo/)
![Состояние работы](https://apps.yunohost.org/badge/state/ergo)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/ergo)

[![Установите Ergo с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ergo)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Ergo быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Ergo (formerly known as Oragono) is a modern IRC server written in Go. Its core design 

### Features

- Being simple to set up and use
- Combining the features of an ircd, a services framework, and a bouncer (integrated account management, history storage, and bouncer functionality)
- Bleeding-edge IRCv3 support, suitable for use as an IRCv3 reference implementation
- High customizability via a rehashable (i.e., reloadable at runtime) YAML config



**Поставляемая версия:** 2.15.0~ynh1

**Демо-версия:** <https://testnet.ergo.chat/>

## Снимки экрана

![Снимок экрана Ergo](./doc/screenshots/textual.jpg)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://ergo.chat/>
- Официальная документация пользователя: <https://github.com/ergochat/ergo/blob/stable/docs/USERGUIDE.md>
- Официальная документация администратора: <https://github.com/ergochat/ergo/blob/stable/docs/MANUAL.md>
- Репозиторий кода главной ветки приложения: <https://github.com/ergochat/ergo>
- Магазин YunoHost: <https://apps.yunohost.org/app/ergo>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/ergo_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/ergo_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ergo_ynh/tree/testing --debug
или
sudo yunohost app upgrade ergo -u https://github.com/YunoHost-Apps/ergo_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
