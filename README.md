# code-craft
Lightweight, multi-language web-based generator for promo codes, passwords, serial keys, and UUIDs with built-in export &amp; QR tools.
# ⚡ Code Craft — Universal Code & Password Generator

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![JavaScript](https://img.shields.io/badge/javascript-vanilla-yellow.svg)
![HTML5/CSS3](https://img.shields.io/badge/frontend-HTML5%2FCSS3-orange.svg)

**Code Craft** — это веб-приложение для мгновенной генерации промокодов, стойких паролей, серийных ключей, HEX-значений и криптографически стойких UUID v4.

---

## ✨ Особенности

* 🔒 **Высокая безопасность:** Используется системный `Web Crypto API` (`crypto.getRandomValues`) вместо `Math.random()`.
* 🌍 **Мультиязычность (i18n):** Поддержка **Русского**, **English** и **Української** языков.
* 🎯 **Гибкие типы кодов:**
  * **Промокоды:** Без визуально схожих символов (`O/0`, `I/1`).
  * **Серийники:** С автоматическим разбиением на блоки дефисами.
  * **Пароли:** С поддержкой спецсимволов.
  * **PIN-коды:** Только цифры.
  * **HEX / UUID v4:** Для разработчиков и системных интеграций.
* 🛠️ **Гибкая настройка:** Префиксы, суффиксы, регулировка длины, свой набор символов, защита от дубликатов (уникальность).
* 📤 **Удобный экспорт:**
  * Копирование списка в один клик.
  * Скачивание результата в `.txt`.
  * Быстрая генерация **QR-кода** для первого элемента.

---

## 🚀 Быстрый запуск

Приложение является **Single File Web App** и не требует установки Node.js или сборщиков:

1. Склонируйте репозиторий:
   ```bash
   git clone [https://github.com/your-username/code-craft.git](https://github.com/your-username/code-craft.git)
