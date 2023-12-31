<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Zulip for YunoHost

[![Integration level](https://dash.yunohost.org/integration/zulip.svg)](https://dash.yunohost.org/appci/app/zulip) ![Working status](https://ci-apps.yunohost.org/ci/badges/zulip.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/zulip.maintain.svg)

[![Install Zulip with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zulip)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Zulip quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Zulip is an open-source team collaboration tool with unique topic-based threading that combines the best of email and chat to make remote work productive and delightful. Zulip is the only modern team chat app that is designed for both live and asynchronous conversations.

**Shipped version:** 7.4~ynh1

## Screenshots

![Screenshot of Zulip](./doc/screenshots/example.jpg)

## Documentation and resources

* Official app website: <https://zulip.com/>
* Official admin documentation: <https://zulip.readthedocs.io/>
* Upstream app code repository: <https://github.com/zulip/zulip>
* Report a bug: <https://github.com/YunoHost-Apps/zulip_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/zulip_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/zulip_ynh/tree/testing --debug
or
sudo yunohost app upgrade zulip -u https://github.com/YunoHost-Apps/zulip_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
