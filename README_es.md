<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Magic-Wormhole para Yunohost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/wormhole)](https://ci-apps.yunohost.org/ci/apps/wormhole/)
![Estado funcional](https://apps.yunohost.org/badge/state/wormhole)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/wormhole)

[![Instalar Magic-Wormhole con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wormhole)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarMagic-Wormhole rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

This repository implements the Magic-Wormhole "Transit Relay", a server that helps clients establish bulk-data transit connections even when both are behind NAT boxes. Each side makes a TCP connection to this server and presents a handshake. Two connections with identical handshakes are glued together, allowing them to pretend they have a direct connection.

**Versión actual:** 0.4.0~ynh1
## Documentaciones y recursos

- Repositorio del código fuente oficial de la aplicación : <https://github.com/magic-wormhole/magic-wormhole-transit-relay>
- Catálogo YunoHost: <https://apps.yunohost.org/app/wormhole>
- Reportar un error: <https://github.com/YunoHost-Apps/wormhole_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/wormhole_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/wormhole_ynh/tree/testing --debug
o
sudo yunohost app upgrade wormhole -u https://github.com/YunoHost-Apps/wormhole_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
