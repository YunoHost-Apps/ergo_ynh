<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Ergo

[![集成程度](https://dash.yunohost.org/integration/ergo.svg)](https://dash.yunohost.org/appci/app/ergo) ![工作状态](https://ci-apps.yunohost.org/ci/badges/ergo.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/ergo.maintain.svg)

[![使用 YunoHost 安装 Ergo](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ergo)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Ergo。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Ergo (formerly known as Oragono) is a modern IRC server written in Go. Its core design 

### Features

- Being simple to set up and use
- Combining the features of an ircd, a services framework, and a bouncer (integrated account management, history storage, and bouncer functionality)
- Bleeding-edge IRCv3 support, suitable for use as an IRCv3 reference implementation
- High customizability via a rehashable (i.e., reloadable at runtime) YAML config



**分发版本：** 2.13.1~ynh1

**演示：** <https://testnet.ergo.chat/>

## 截图

![Ergo 的截图](./doc/screenshots/textual.jpg)

## 文档与资源

- 官方应用网站： <https://ergo.chat/>
- 官方用户文档： <https://github.com/ergochat/ergo/blob/stable/docs/USERGUIDE.md>
- 官方管理文档： <https://github.com/ergochat/ergo/blob/stable/docs/MANUAL.md>
- 上游应用代码库： <https://github.com/ergochat/ergo>
- YunoHost 商店： <https://apps.yunohost.org/app/ergo>
- 报告 bug： <https://github.com/YunoHost-Apps/ergo_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/ergo_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ergo_ynh/tree/testing --debug
或
sudo yunohost app upgrade ergo -u https://github.com/YunoHost-Apps/ergo_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
