# Tonal — палитра из фотографии / Photo Palette

Инструмент извлекает несколько ведущих цветов из фотографии в браузере. Исходное изображение остаётся на устройстве.

![Tonal photo palette](screenshots/tonal-photo-palette.png)

## Возможности

- Загрузить изображение или перетащить его в рабочую область.
- Выбрать от 3 до 8 цветов и увидеть их долю в кадре.
- Скопировать отдельный HEX, все цвета как CSS-переменные или скачать JSON.
- Применить ведущий цвет к палитре интерфейса.
- Переключить русский и английский язык, автоматическую, светлую или тёмную тему.
- Встроенный снимок леса для первого знакомства с инструментом.

Изображение уменьшается до небольшого превью и анализируется через Canvas. Цвета группируются простым взвешенным алгоритмом кластеризации; внешние сервисы и модели не используются.

## Запуск

Откройте `index.html` или запустите сервер из папки проекта:

```sh
python -m http.server 8000
```

Перейдите на <http://localhost:8000>. Сборка и зависимости не нужны.

## SEO и география

Страница содержит description, Open Graph и структурированные данные `WebApplication`. Метаданные региона указывают место создания проекта — Уфу, Республика Башкортостан; сам инструмент работает в браузере без привязки к местоположению пользователя.

---

# Tonal — Photo Palette

Tonal extracts a small set of leading colors from a photograph in your browser. The source image stays on your device.

## Features

- Choose an image or drop it into the workspace.
- Select 3 to 8 colors and inspect their share in the photograph.
- Copy one HEX value, copy all colors as CSS variables, or download JSON.
- Apply the leading color to the interface palette.
- Switch between Russian and English, automatic, light and dark themes.
- Start with the bundled forest photograph.

The image is reduced to a small preview and analyzed with Canvas. A weighted clustering algorithm groups colors locally; no external service or model is used.

## Run locally

Open `index.html`, or start a server from the project folder:

```sh
python -m http.server 8000
```

Visit <http://localhost:8000>. No build step or dependencies are required.

## SEO and geography

The page includes a description, Open Graph metadata and `WebApplication` structured data. Regional metadata identifies Ufa, Bashkortostan as the project's place of creation; the browser tool itself works independently of the user's location.
