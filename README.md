<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# TaskBoard for YunoHost

[![Integration level](https://dash.yunohost.org/integration/taskboard.svg)](https://dash.yunohost.org/appci/app/taskboard) ![Working status](https://ci-apps.yunohost.org/ci/badges/taskboard.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/taskboard.maintain.svg)

[![Install TaskBoard with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=taskboard)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install TaskBoard quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

A Kanban-inspired app for keeping track of things that need to get done.
The goal of TaskBoard is to provide a simple and clean interface to a functional and minimal application for keeping track of tasks. It's not trying to be the next Trello or LeanKit.

**Shipped version:** 1.0.2~ynh4

**Demo:** <https://taskboard.matthewross.me/demo>

## Screenshots

![Screenshot of TaskBoard](./doc/screenshots/screenshots.png)

## :red_circle: Antifeatures

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.
- **Package not maintained**: This YunoHost package is not actively maintained and needs adoption. This means that minimal maintenance is made by volunteers who don't use the app, so you should expect the app to lose reliability over time. You can [learn how to package](https://yunohost.org/packaging_apps_intro) if you'd like to adopt it.

## Documentation and resources

- Official app website: <http://taskboard.matthewross.me/>
- Upstream app code repository: <https://github.com/kiswa/TaskBoard>
- YunoHost Store: <https://apps.yunohost.org/app/taskboard>
- Report a bug: <https://github.com/YunoHost-Apps/taskboard_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/taskboard_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/taskboard_ynh/tree/testing --debug
or
sudo yunohost app upgrade taskboard -u https://github.com/YunoHost-Apps/taskboard_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
