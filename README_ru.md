<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Magic-Wormhole для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/wormhole)](https://ci-apps.yunohost.org/ci/apps/wormhole/)
![Состояние работы](https://apps.yunohost.org/badge/state/wormhole)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/wormhole)

[![Установите Magic-Wormhole с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wormhole)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Magic-Wormhole быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

This repository implements the Magic-Wormhole "Transit Relay", a server that helps clients establish bulk-data transit connections even when both are behind NAT boxes. Each side makes a TCP connection to this server and presents a handshake. Two connections with identical handshakes are glued together, allowing them to pretend they have a direct connection.

**Поставляемая версия:** 0.4.0~ynh1
## Документация и ресурсы

- Репозиторий кода главной ветки приложения: <https://github.com/magic-wormhole/magic-wormhole-transit-relay>
- Магазин YunoHost: <https://apps.yunohost.org/app/wormhole>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/wormhole_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/wormhole_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/wormhole_ynh/tree/testing --debug
или
sudo yunohost app upgrade wormhole -u https://github.com/YunoHost-Apps/wormhole_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
