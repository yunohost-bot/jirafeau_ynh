<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Jirafeau for YunoHost

[![Integration level](https://dash.yunohost.org/integration/jirafeau.svg)](https://dash.yunohost.org/appci/app/jirafeau) ![](https://ci-apps.yunohost.org/ci/badges/jirafeau.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/jirafeau.maintain.svg)  
[![Install Jirafeau with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=jirafeau)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Jirafeau quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Jirafeau offers the possibility to host and share your files with ease. Choose a file, Jirafeau will provide you with a link with many options. It is possible to protect your links with a password as well as to choose how long the file will be kept on the server. The file and the link will self-destruct after this time. Downloads of transmitted files can be limited to a certain date, and each file can self-destruct after the first download. Jirafeau allows you to configure maximum retention times and maximum size per file. Encryption is available as an option.


**Shipped version:** 4.4.0~ynh1

**Demo:** https://demo.yunohost.org/jirafeau/

## Screenshots

![](./doc/screenshots/TPjh48P.png)

## Disclaimers / important information

## Configuration

### Changing the conditions of use of the service

The license text on the "Terms of Service" page, which is shipped with the default installation, is "based on the Open Source Initiative Terms of Service". To change this text simply copy the file `/lib/tos.original.txt`, rename it to `/lib/tos.local.txt` and adapt it to your own needs. If you update the installation, then only the `tos.original.txt` file may change eventually, not your `tos.local.txt file`.

## Administration

To administer the files within Jirafeau it is enough to go to the address `jirafeau.domaine.tld/admin.php`.
## Documentation and resources

* Official app website: https://gitlab.com/mojo42/Jirafeau
* Upstream app code repository: https://gitlab.com/mojo42/Jirafeau
* YunoHost documentation for this app: https://yunohost.org/app_jirafeau
* Report a bug: https://github.com/YunoHost-Apps/jirafeau_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/jirafeau_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/jirafeau_ynh/tree/testing --debug
or
sudo yunohost app upgrade jirafeau -u https://github.com/YunoHost-Apps/jirafeau_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps