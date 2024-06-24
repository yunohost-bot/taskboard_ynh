<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# TaskBoard para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/taskboard.svg)](https://dash.yunohost.org/appci/app/taskboard) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/taskboard.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/taskboard.maintain.svg)

[![Instalar TaskBoard con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=taskboard)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarTaskBoard rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

A Kanban-inspired app for keeping track of things that need to get done.
The goal of TaskBoard is to provide a simple and clean interface to a functional and minimal application for keeping track of tasks. It's not trying to be the next Trello or LeanKit.

**Versión actual:** 1.0.2~ynh3

**Demo:** <https://taskboard.matthewross.me/demo>

## Capturas

![Captura de TaskBoard](./doc/screenshots/screenshots.png)

## :red_circle: Características no deseables

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.
- **Package not maintained**: This YunoHost package is not actively maintained and needs adoption. This means that minimal maintenance is made by volunteers who don't use the app, so you should expect the app to lose reliability over time. You can [learn how to package](https://yunohost.org/packaging_apps_intro) if you'd like to adopt it.

## Documentaciones y recursos

- Sitio web oficial: <http://taskboard.matthewross.me/>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/kiswa/TaskBoard>
- Catálogo YunoHost: <https://apps.yunohost.org/app/taskboard>
- Reportar un error: <https://github.com/YunoHost-Apps/taskboard_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/taskboard_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/taskboard_ynh/tree/testing --debug
o
sudo yunohost app upgrade taskboard -u https://github.com/YunoHost-Apps/taskboard_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
