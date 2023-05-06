<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# rss for YunoHost

[![Integration level](https://dash.yunohost.org/integration/rss.svg)](https://dash.yunohost.org/appci/app/rss) ![Working status](https://ci-apps.yunohost.org/ci/badges/rss.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/rss.maintain.svg)

[![Install rss with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=rss)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install rss quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

A simple, opinionated, RSS feed aggregator

### Features

The following features are built into the application:

- Supports RSS and ATOM formats.
- Regular auto-fetching of RSS feeds.
        Every hour by default, configurable down to 5 mins.
- Custom feed names and colors.
- Feed-based tags for categorization.
- 3 different post layout modes (card, list, compact).
- Fetching of page open-graph images.
- Feeds managed via a single plaintext file.
- System-based dark/light theme.
- Post title/description search.
- Mobile screen compatible.
- Built-in support to prune old post data.

**Shipped version:** 1.3.0~ynh1

**Demo:** https://demo.example.com

## Screenshots

![Screenshot of rss](./doc/screenshots/card-view.png)

## Documentation and resources

* Official app website: <https://github.com/ssddanbrown/rss>
* Official admin documentation: <https://yunohost.org/packaging_apps>
* Upstream app code repository: <https://github.com/ssddanbrown/rss>
* YunoHost documentation for this app: <https://yunohost.org/app_rss>
* Report a bug: <https://github.com/YunoHost-Apps/rss_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/rss_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/rss_ynh/tree/testing --debug
or
sudo yunohost app upgrade rss -u https://github.com/YunoHost-Apps/rss_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
