<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Magic-Wormhole for YunoHost

[![Integration level](https://apps.yunohost.org/badge/integration/wormhole)](https://ci-apps.yunohost.org/ci/apps/wormhole/)
![Working status](https://apps.yunohost.org/badge/state/wormhole)
![Maintenance status](https://apps.yunohost.org/badge/maintained/wormhole)

[![Install Magic-Wormhole with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wormhole)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Magic-Wormhole quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

This repository implements the Magic-Wormhole "Transit Relay", a server that helps clients establish bulk-data transit connections even when both are behind NAT boxes. Each side makes a TCP connection to this server and presents a handshake. Two connections with identical handshakes are glued together, allowing them to pretend they have a direct connection.

**Shipped version:** 0.4.0~ynh1

**Demo:** <https://demo.example.com>
## Documentation and resources

- Official app website: <https://example.com>
- Upstream app code repository: <https://github.com/magic-wormhole/magic-wormhole-transit-relay>
- YunoHost Store: <https://apps.yunohost.org/app/wormhole>
- Report a bug: <https://github.com/YunoHost-Apps/wormhole_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/wormhole_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/wormhole_ynh/tree/testing --debug
or
sudo yunohost app upgrade wormhole -u https://github.com/YunoHost-Apps/wormhole_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
