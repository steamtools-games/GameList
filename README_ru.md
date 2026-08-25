# 🎮 Каталог игр SteamTools и генератор манифестов

[![SteamTools](https://img.shields.io/badge/SteamTools.games-Онлайн%20генератор-0ea5e9?style=for-the-badge&logo=steam&logoColor=white)](https://steamtools.games/ru)
[![Games Indexed](https://img.shields.io/badge/Игр%20в%20каталоге-99%2B%20популярных%20игр-10b981?style=for-the-badge)](https://steamtools.games/ru/games)
[![OpenAPI 3.1](https://img.shields.io/badge/REST%20API-OpenAPI%203.1-8b5cf6?style=for-the-badge)](https://steamtools.games/ru/developers)
[![License](https://img.shields.io/badge/Лицензия-MIT-amber?style=for-the-badge)](LICENSE)
[![Discord](https://img.shields.io/badge/Сообщество-Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/invite/FDKpJu5zgT)

Открытый каталог и автоматический генератор манифестов для **SteamTools (Watt Toolkit)**. Создавайте чистые скрипты `.lua`, ключи хранилищ `key.vdf` и манифесты приложений для любых игр Steam.

---

### 🌐 Выберите язык / Read this in your language:
**[English](README.md)** | **[简体中文](README_zh.md)** | **[Русский](README_ru.md)** | **[Türkçe](README_tr.md)** | **[Español](README_es.md)** | **[Français](README_fr.md)** | **[Português (Brasil)](README_pt-BR.md)**

---

## 🌟 Полезные ссылки

* 🌐 **Онлайн-генератор**: [https://steamtools.games/ru](https://steamtools.games/ru)
* 🎮 **Каталог 99+ популярных игр**: [https://steamtools.games/ru/games](https://steamtools.games/ru/games)
* 💻 **Установка клиента (Windows / macOS / Linux)**: [https://steamtools.games/ru/install](https://steamtools.games/ru/install)
* 📖 **Как это работает**: [https://steamtools.games/ru/how-it-works](https://steamtools.games/ru/how-it-works)
* 🔌 **REST API для разработчиков**: [https://steamtools.games/ru/developers](https://steamtools.games/ru/developers)
* 💬 **Сообщество Discord**: [https://discord.com/invite/FDKpJu5zgT](https://discord.com/invite/FDKpJu5zgT)

---

## 🚀 Как использовать SteamTools

1. **Найдите игру**: Введите название игры или Steam App ID на [SteamTools.games](https://steamtools.games/ru).
2. **Скачайте архив**: Нажмите **Скачать ZIP**, чтобы получить `{appId}_public.lua`, `key.vdf` и руководство.
3. **Разместите файлы**: Скопируйте `.lua` и `key.vdf` в корневую папку установки SteamTools.
4. **Перезапустите клиент**: Запустите SteamTools и Steam — игра появится в вашей библиотеке.

---

## 🔥 Популярные игры (прямые ссылки на скачивание)

| App ID | Название игры | Ссылка на манифест и Lua |
| :--- | :--- | :--- |
| `2358720` | **Black Myth: Wukong** | [Скачать манифест и Lua](https://steamtools.games/ru/app/2358720) |
| `1245620` | **ELDEN RING** | [Скачать манифест и Lua](https://steamtools.games/ru/app/1245620) |
| `271590` | **Grand Theft Auto V (GTA 5)** | [Скачать манифест и Lua](https://steamtools.games/ru/app/271590) |
| `730` | **Counter-Strike 2 (CS2)** | [Скачать манифест и Lua](https://steamtools.games/ru/app/730) |
| `1623730` | **Palworld** | [Скачать манифест и Lua](https://steamtools.games/ru/app/1623730) |
| `1091500` | **Cyberpunk 2077** | [Скачать манифест и Lua](https://steamtools.games/ru/app/1091500) |
| `1174180` | **Red Dead Redemption 2** | [Скачать манифест и Lua](https://steamtools.games/ru/app/1174180) |
| `105600` | **Terraria** | [Скачать манифест и Lua](https://steamtools.games/ru/app/105600) |
| `413150` | **Stardew Valley** | [Скачать манифест и Lua](https://steamtools.games/ru/app/413150) |
| `892970` | **Valheim** | [Скачать манифест и Lua](https://steamtools.games/ru/app/892970) |
| `400` | **Portal** | [Скачать манифест и Lua](https://steamtools.games/ru/app/400) |

👉 **[Посмотреть все 99+ игр в каталоге SteamTools.games →](https://steamtools.games/ru/games)**

---

## 🔌 Бесплатный REST API

Вы можете программно запрашивать метаданные и генерировать манифесты через наши публичные API-интерфейсы:

```bash
curl -s "https://steamtools.games/api/search?query=elden" | jq
```

Полная спецификация OpenAPI 3.1 доступна по адресу: [https://steamtools.games/ru/developers](https://steamtools.games/ru/developers).

---

## 📄 Лицензия

MIT License © 2026 [SteamTools.games](https://steamtools.games/)
