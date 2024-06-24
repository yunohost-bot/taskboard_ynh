<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# TaskBoard pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/taskboard.svg)](https://dash.yunohost.org/appci/app/taskboard) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/taskboard.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/taskboard.maintain.svg)

[![Installer TaskBoard avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=taskboard)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer TaskBoard rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

A Kanban-inspired app for keeping track of things that need to get done.
The goal of TaskBoard is to provide a simple and clean interface to a functional and minimal application for keeping track of tasks. It's not trying to be the next Trello or LeanKit.

**Version incluse :** 1.0.2~ynh4

**Démo :** <https://taskboard.matthewross.me/demo>

## Captures d’écran

![Capture d’écran de TaskBoard](./doc/screenshots/screenshots.png)

## :red_circle: Anti-fonctionnalités

- **Application non maintenue **: Ce logiciel n'est plus maintenu. Attendez-vous à ce qu'il ne fonctionne plus avec le temps, et que l'on découvre des failles de sécurité qui ne seront pas corrigées, etc.
- **Package non maintenu **: Ce package YunoHost n'est pas activement maintenu et a besoin d'être adopté. Cela veut dire que la maintenance minimale est réalisée par des bénévoles qui n'utilisent pas l'application, il faut donc s'attendre à ce que l'app perde en fiabilité avec le temps. Vous pouvez [apprendre comment packager](https://yunohost.org/packaging_apps_intro) si vous voulez l'adopter.

## Documentations et ressources

- Site officiel de l’app : <http://taskboard.matthewross.me/>
- Dépôt de code officiel de l’app : <https://github.com/kiswa/TaskBoard>
- YunoHost Store : <https://apps.yunohost.org/app/taskboard>
- Signaler un bug : <https://github.com/YunoHost-Apps/taskboard_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/taskboard_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/taskboard_ynh/tree/testing --debug
ou
sudo yunohost app upgrade taskboard -u https://github.com/YunoHost-Apps/taskboard_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
