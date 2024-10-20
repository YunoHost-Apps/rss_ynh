<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# RSS para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/rss.svg)](https://ci-apps.yunohost.org/ci/apps/rss/) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/rss.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/rss.maintain.svg)

[![Instalar RSS con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=rss)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar RSS de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

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

**Versión proporcionada:** 1.5.3~ynh1

## Capturas de pantalla

![Captura de pantalla de RSS](./doc/screenshots/card-view.png)

## Documentación e recursos

- Repositorio de orixe do código: <https://codeberg.org/danb/rss/>
- Tenda YunoHost: <https://apps.yunohost.org/app/rss>
- Informar dun problema: <https://github.com/YunoHost-Apps/rss_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/rss_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/rss_ynh/tree/testing --debug
ou
sudo yunohost app upgrade rss -u https://github.com/YunoHost-Apps/rss_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
