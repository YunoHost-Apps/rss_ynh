<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# RSS для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/rss.svg)](https://ci-apps.yunohost.org/ci/apps/rss/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/rss.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/rss.maintain.svg)

[![Установите RSS с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=rss)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить RSS быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

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

**Поставляемая версия:** 1.5.3~ynh1

## Снимки экрана

![Снимок экрана RSS](./doc/screenshots/card-view.png)

## Документация и ресурсы

- Репозиторий кода главной ветки приложения: <https://github.com/ssddanbrown/rss>
- Магазин YunoHost: <https://apps.yunohost.org/app/rss>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/rss_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/rss_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/rss_ynh/tree/testing --debug
или
sudo yunohost app upgrade rss -u https://github.com/YunoHost-Apps/rss_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
