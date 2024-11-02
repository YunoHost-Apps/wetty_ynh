<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Wetty для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/wetty.svg)](https://ci-apps.yunohost.org/ci/apps/wetty/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/wetty.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/wetty.maintain.svg)

[![Установите Wetty с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wetty)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Wetty быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Terminal over HTTP and HTTPS. WeTTy is an alternative to ajaxterm and anyterm but much better than them because WeTTy uses xterm.js which is a full fledged implementation of terminal emulation written entirely in JavaScript. WeTTy uses websockets rather then Ajax and hence better response time.


**Поставляемая версия:** 2.5.0~ynh3

## Снимки экрана

![Снимок экрана Wetty](./doc/screenshots/terminal.png)

## Документация и ресурсы

- Репозиторий кода главной ветки приложения: <https://github.com/butlerx/wetty>
- Магазин YunoHost: <https://apps.yunohost.org/app/wetty>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/wetty_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/wetty_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
или
sudo yunohost app upgrade wetty -u https://github.com/YunoHost-Apps/wetty_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
