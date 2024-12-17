<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Magic-Wormhole dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/wormhole)](https://ci-apps.yunohost.org/ci/apps/wormhole/)
![Status działania](https://apps.yunohost.org/badge/state/wormhole)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/wormhole)

[![Zainstaluj Magic-Wormhole z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wormhole)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Magic-Wormhole na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

This repository implements the Magic-Wormhole "Transit Relay", a server that helps clients establish bulk-data transit connections even when both are behind NAT boxes. Each side makes a TCP connection to this server and presents a handshake. Two connections with identical handshakes are glued together, allowing them to pretend they have a direct connection.

**Dostarczona wersja:** 0.4.0~ynh1

**Demo:** <https://demo.example.com>
## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://example.com>
- Repozytorium z kodem źródłowym: <https://github.com/magic-wormhole/magic-wormhole-transit-relay>
- Sklep YunoHost: <https://apps.yunohost.org/app/wormhole>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/wormhole_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/wormhole_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/wormhole_ynh/tree/testing --debug
lub
sudo yunohost app upgrade wormhole -u https://github.com/YunoHost-Apps/wormhole_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
