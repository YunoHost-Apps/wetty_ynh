<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Wetty

[![集成程度](https://apps.yunohost.org/badge/integration/wetty)](https://ci-apps.yunohost.org/ci/apps/wetty/)
![工作状态](https://apps.yunohost.org/badge/state/wetty)
![维护状态](https://apps.yunohost.org/badge/maintained/wetty)

[![使用 YunoHost 安装 Wetty](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wetty)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Wetty。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Terminal over HTTP and HTTPS. WeTTy is an alternative to ajaxterm and anyterm but much better than them because WeTTy uses xterm.js which is a full fledged implementation of terminal emulation written entirely in JavaScript. WeTTy uses websockets rather then Ajax and hence better response time.


**分发版本：** 2.7.0~ynh2

## 截图

![Wetty 的截图](./doc/screenshots/terminal.png)

## 文档与资源

- 上游应用代码库： <https://github.com/butlerx/wetty>
- YunoHost 商店： <https://apps.yunohost.org/app/wetty>
- 报告 bug： <https://github.com/YunoHost-Apps/wetty_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/wetty_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
或
sudo yunohost app upgrade wetty -u https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
