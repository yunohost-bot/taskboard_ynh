<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# TaskBoard YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/taskboard.svg)](https://dash.yunohost.org/appci/app/taskboard) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/taskboard.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/taskboard.maintain.svg)

[![Instalatu TaskBoard YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=taskboard)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek TaskBoard YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

A Kanban-inspired app for keeping track of things that need to get done.
The goal of TaskBoard is to provide a simple and clean interface to a functional and minimal application for keeping track of tasks. It's not trying to be the next Trello or LeanKit.

**Paketatutako bertsioa:** 1.0.2~ynh3

**Demoa:** <https://taskboard.matthewross.me/demo>

## Pantaila-argazkiak

![TaskBoard(r)en pantaila-argazkia](./doc/screenshots/screenshots.png)

## :red_circle: Ezaugarri zalantzagarriak

- **Jatorrizko garapena utzita**: Software honek ez du arduradunik. Denborak aurrera egin ahala funtzionatzeari utziko dio, konpondu gabeko segurtasun arazoak izango ditu, etab.
- **Mantendu gabeko paketea**: YunoHost pakete honek ez du mantenduko duenik, bere gain hartuko duen norbaiten beharra dauka. Honek esan nahi duena da mantentze-lanak minimoak izango direla eta aplikazioa erabiltzen ez duten boluntarioek egingo dituztela lanok; denborak aurrera egin ahala fidagarri izateari utziko dio. [Aplikazioak nola paketatu](https://yunohost.org/packaging_apps_intro) ikas dezakezu, zure gain hartu nahi baduzu.

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <http://taskboard.matthewross.me/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/kiswa/TaskBoard>
- YunoHost Denda: <https://apps.yunohost.org/app/taskboard>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/taskboard_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/taskboard_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/taskboard_ynh/tree/testing --debug
edo
sudo yunohost app upgrade taskboard -u https://github.com/YunoHost-Apps/taskboard_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
