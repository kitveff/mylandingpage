# Артём Китаев — Personal Landing Page

Лендинг-визитка для SRE-инженера, DevOps и Python-разработчика.

**Live:** [kitveff.github.io/mylandingportfolio](https://kitveff.github.io/mylandingpage) *(после включения GitHub Pages)*

---

## Стек

Чистый HTML + CSS + Vanilla JS — никаких фреймворков, никаких зависимостей.

- Google Fonts (JetBrains Mono + Manrope) — единственный внешний ресурс
- Canvas API — анимированный фон в Hero
- IntersectionObserver — scroll reveal анимации
- localStorage — сохранение выбранной темы

## Фичи

- **Dark / Light тема** с плавным переходом, запоминается в localStorage
- **Typewriter эффект** — смена ролей в Hero (SRE → DevOps → Vibe-coder → Python)
- **Анимированная сетка** на canvas, реагирующая на движение мыши
- **Кастомный курсор** — точка + отстающее кольцо
- **Scroll reveal** — staggered появление секций через IntersectionObserver
- **Форма заявки** — открывает Telegram с pre-filled сообщением
- Полностью **адаптивная** вёрстка (375 / 768 / 1280 / 1920px)
- Фиксированный nav с **backdrop-blur** при скролле

## Структура

```
mylandingportfolio/
├── index.html   # весь проект в одном файле
├── .gitignore
└── README.md
```

## Запуск

Просто открыть `index.html` в браузере — никаких сборок, серверов и зависимостей.

```bash
open index.html
```

Или через любой статический сервер:

```bash
npx serve .
# или
python3 -m http.server 8080
```

## Деплой на GitHub Pages

1. Залить репо на GitHub
2. Settings → Pages → Source: `Deploy from a branch` → `main` / `(root)`
3. Сайт будет доступен по `https://kitveff.github.io/mylandingpage`

---

**Контакты:** [@kitveff](https://t.me/kitveff) · [kitveff@gmail.com](mailto:kitveff@gmail.com)
