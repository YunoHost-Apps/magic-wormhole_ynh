<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Magic-Wormhole pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/wormhole)](https://ci-apps.yunohost.org/ci/apps/wormhole/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/wormhole)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/wormhole)

[![Installer Magic-Wormhole avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wormhole)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Magic-Wormhole rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Ce référentiel implémente le « relais de transit » Magic-Wormhole, un serveur qui aide les clients à établir des connexions de transit de données en masse même lorsque les deux se trouvent derrière des boîtes NAT. Chaque côté établit une connexion TCP avec ce serveur et présente une poignée de main. Deux connexions avec des poignées de main identiques sont collées ensemble, ce qui leur permet de prétendre qu'elles ont une connexion directe.


**Version incluse :** 0.4.0~ynh1
## Documentations et ressources

- Dépôt de code officiel de l’app : <https://github.com/magic-wormhole/magic-wormhole-transit-relay>
- YunoHost Store : <https://apps.yunohost.org/app/wormhole>
- Signaler un bug : <https://github.com/YunoHost-Apps/wormhole_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/wormhole_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/wormhole_ynh/tree/testing --debug
ou
sudo yunohost app upgrade wormhole -u https://github.com/YunoHost-Apps/wormhole_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
