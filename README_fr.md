<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Hotglue pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/hotglue.svg)](https://ci-apps.yunohost.org/ci/apps/hotglue/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/hotglue.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/hotglue.maintain.svg)

[![Installer Hotglue avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hotglue)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Hotglue rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Hotglue est un logiciel de manipulation de contenu qui permet une cohérence visuelle entre l'édition et la visualisation.
Pour commencer l'édition, vous devez ajouter `__DOMAIN____PATH__/edit` à la fin de l'URL, par exemple https://hotglue.me/demo/edit

Consultez d'autres sites Hotglue : https://hotglue.me/latest

**Version incluse :** 1.04~ynh1

**Démo :** <https://hotglue.me/demo/>

## Captures d’écran

![Capture d’écran de Hotglue](./doc/screenshots/example.jpg)

## Documentations et ressources

- Site officiel de l’app : <https://hotglue.me>
- Documentation officielle utilisateur : <https://discourse.superglue.it/c/hotglue>
- Documentation officielle de l’admin : <https://discourse.superglue.it/c/hotglue>
- Dépôt de code officiel de l’app : <https://github.com/k0a1a/hotglue2>
- YunoHost Store : <https://apps.yunohost.org/app/hotglue>
- Signaler un bug : <https://github.com/YunoHost-Apps/hotglue_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/hotglue_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hotglue_ynh/tree/testing --debug
ou
sudo yunohost app upgrade hotglue -u https://github.com/YunoHost-Apps/hotglue_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
