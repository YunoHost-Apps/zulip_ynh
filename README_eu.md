<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Zulip YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/zulip)](https://ci-apps.yunohost.org/ci/apps/zulip/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/zulip)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/zulip)

[![Instalatu Zulip YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zulip)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Zulip YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Zulip is an open-source team collaboration tool with unique topic-based threading that combines the best of email and chat to make remote work productive and delightful. Zulip is the only modern team chat app that is designed for both live and asynchronous conversations.

**Paketatutako bertsioa:** 9.4~ynh1

## Pantaila-argazkiak

![Zulip(r)en pantaila-argazkia](./doc/screenshots/screenshot.webp)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://zulip.com/>
- Administratzaileen dokumentazio ofiziala: <https://zulip.readthedocs.io/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/zulip/zulip>
- YunoHost Denda: <https://apps.yunohost.org/app/zulip>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/zulip_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/zulip_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zulip_ynh/tree/testing --debug
edo
sudo yunohost app upgrade zulip -u https://github.com/YunoHost-Apps/zulip_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
