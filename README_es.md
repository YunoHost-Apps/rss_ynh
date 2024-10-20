<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# RSS para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/rss.svg)](https://ci-apps.yunohost.org/ci/apps/rss/) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/rss.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/rss.maintain.svg)

[![Instalar RSS con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=rss)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarRSS rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

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

**Versión actual:** 1.5.3~ynh1

## Capturas

![Captura de RSS](./doc/screenshots/card-view.png)

## Documentaciones y recursos

- Repositorio del código fuente oficial de la aplicación : <https://codeberg.org/danb/rss/>
- Catálogo YunoHost: <https://apps.yunohost.org/app/rss>
- Reportar un error: <https://github.com/YunoHost-Apps/rss_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/rss_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/rss_ynh/tree/testing --debug
o
sudo yunohost app upgrade rss -u https://github.com/YunoHost-Apps/rss_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
