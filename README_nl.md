<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Magic-Wormhole voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/wormhole)](https://ci-apps.yunohost.org/ci/apps/wormhole/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/wormhole)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/wormhole)

[![Magic-Wormhole met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wormhole)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Magic-Wormhole snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

This repository implements the Magic-Wormhole "Transit Relay", a server that helps clients establish bulk-data transit connections even when both are behind NAT boxes. Each side makes a TCP connection to this server and presents a handshake. Two connections with identical handshakes are glued together, allowing them to pretend they have a direct connection.

**Geleverde versie:** 0.4.0~ynh1
## Documentatie en bronnen

- Upstream app codedepot: <https://github.com/magic-wormhole/magic-wormhole-transit-relay>
- YunoHost-store: <https://apps.yunohost.org/app/wormhole>
- Meld een bug: <https://github.com/YunoHost-Apps/wormhole_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/wormhole_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/wormhole_ynh/tree/testing --debug
of
sudo yunohost app upgrade wormhole -u https://github.com/YunoHost-Apps/wormhole_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
