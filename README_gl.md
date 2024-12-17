<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Magic-Wormhole para YunoHost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/wormhole)](https://ci-apps.yunohost.org/ci/apps/wormhole/)
![Estado de funcionamento](https://apps.yunohost.org/badge/state/wormhole)
![Estado de mantemento](https://apps.yunohost.org/badge/maintained/wormhole)

[![Instalar Magic-Wormhole con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wormhole)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Magic-Wormhole de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

This repository implements the Magic-Wormhole "Transit Relay", a server that helps clients establish bulk-data transit connections even when both are behind NAT boxes. Each side makes a TCP connection to this server and presents a handshake. Two connections with identical handshakes are glued together, allowing them to pretend they have a direct connection.

**Versión proporcionada:** 0.4.0~ynh1
## Documentación e recursos

- Repositorio de orixe do código: <https://github.com/magic-wormhole/magic-wormhole-transit-relay>
- Tenda YunoHost: <https://apps.yunohost.org/app/wormhole>
- Informar dun problema: <https://github.com/YunoHost-Apps/wormhole_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/wormhole_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/wormhole_ynh/tree/testing --debug
ou
sudo yunohost app upgrade wormhole -u https://github.com/YunoHost-Apps/wormhole_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
