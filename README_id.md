<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# RSS untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/rss.svg)](https://ci-apps.yunohost.org/ci/apps/rss/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/rss.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/rss.maintain.svg)

[![Pasang RSS dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=rss)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang RSS secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

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

**Versi terkirim:** 1.5.3~ynh1

## Tangkapan Layar

![Tangkapan Layar pada RSS](./doc/screenshots/card-view.png)

## Dokumentasi dan sumber daya

- Depot kode aplikasi hulu: <https://codeberg.org/danb/rss/>
- Gudang YunoHost: <https://apps.yunohost.org/app/rss>
- Laporkan bug: <https://github.com/YunoHost-Apps/rss_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/rss_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/rss_ynh/tree/testing --debug
atau
sudo yunohost app upgrade rss -u https://github.com/YunoHost-Apps/rss_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
