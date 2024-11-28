# Quick Edit to work with Nextcloud 30.0.2 sice the latest YunoHost-Version ist not working anymore.

<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Nextcloud for YunoHost

[![Integration level](https://dash.yunohost.org/integration/nextcloud.svg)](https://ci-apps.yunohost.org/ci/apps/nextcloud/) ![Working status](https://ci-apps.yunohost.org/ci/badges/nextcloud.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/nextcloud.maintain.svg)

[![Install Nextcloud with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=nextcloud)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Nextcloud quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Nextcloud lets you access and synchronize data, files, contacts and calendars between different devices (PCs or mobiles), or share them with other people (with or without accounts), and also offers advanced communication and collaborative working features. Nextcloud features its own application mechanism (see also [Nextcloud's app store](https://apps.nextcloud.com/)) for specific functionalities. 

In the context of YunoHost, Nextcloud integrates with the SSO/User Portal (YunoHost accounts are automatically connected to Nextcloud).

The `/.well-known` address will be automatically configured for CalDAV and CardDAV synchronization if no other service such as Baïkal is already using it.

The YunoHost catalog has two collaborative office suites, [OnlyOffice](https://github.com/YunoHost-Apps/onlyoffice_ynh) and [Collabora](https://github.com/YunoHost-Apps/collabora_ynh), which can be integrated with Nextcloud.

**Shipped version:** 29.0.9~ynh1

**Demo:** <https://demo.nextcloud.com/>

## Screenshots

![Screenshot of Nextcloud](./doc/screenshots/screenshot.png)

## Documentation and resources

- Official app website: <https://nextcloud.com>
- Official user documentation: <https://docs.nextcloud.com/server/latest/user_manual/en/>
- Official admin documentation: <https://docs.nextcloud.com/server/stable/admin_manual/>
- Upstream app code repository: <https://github.com/nextcloud/server>
- YunoHost Store: <https://apps.yunohost.org/app/nextcloud>
- Report a bug: <https://github.com/YunoHost-Apps/nextcloud_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/nextcloud_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/nextcloud_ynh/tree/testing --debug
or
sudo yunohost app upgrade nextcloud -u https://github.com/YunoHost-Apps/nextcloud_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
