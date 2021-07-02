# Платформа Доки

[![Статус Netlify](https://github.com/doka-guide/platform/workflows/Netlify%20Deploy/badge.svg)](https://github.com/doka-guide/platform/actions?query=workflow%3ANetlify%20Deploy)

[![Статус Docker](https://github.com/doka-guide/platform/workflows/Docker%20Deploy/badge.svg)](https://github.com/doka-guide/platform/actions?query=workflow%3ADocker%20Deploy)

Дока — это добрая энциклопедия для веб-разработчиков. Наша цель — сделать документацию по веб-разработке практичной, понятной и не унылой.

Этот репозиторий содержит платформу для сайта «[Дока](https://doka.guide/)». Платформа собирает статьи из [отдельного репозитория](https://github.com/doka-guide/content).

## Как устроен сайт

Сайт «Доки» работает на базе [Eleventy](https://www.11ty.dev). При помощи Nunjucks-темплейтов Eleventy превращает статьи в формате Markdown в HTML-страницы.

Проект собирается с помощью GitHub Actions и хостится в Netlfiy, читайте [подробнее про деплой](./docs/deploy.md).

## Как работать

Для работы с платформой вам потребуется [Node.js v14](https://nodejs.org/en/) и npm v6.

Чтобы запустить Доку локально, нужно:

1. Скачать репозиторий.
1. Установить зависимости командой `npm i`.
1. Запустить локальный веб-сервер командой `npm start`.

Больше вариантов локального запуска Доки — [в руководстве по запуску](docs/how-to-run.md)
