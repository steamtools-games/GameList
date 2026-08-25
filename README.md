# 🎮 SteamTools GameList & Manifest Generator

[![SteamTools](https://img.shields.io/badge/SteamTools.games-Live%20Generator-0ea5e9?style=for-the-badge&logo=steam&logoColor=white)](https://steamtools.games/)
[![Games Indexed](https://img.shields.io/badge/Games%20Indexed-99%2B%20Popular%20Titles-10b981?style=for-the-badge)](https://steamtools.games/games)
[![OpenAPI 3.1](https://img.shields.io/badge/REST%20API-OpenAPI%203.1-8b5cf6?style=for-the-badge)](https://steamtools.games/developers)
[![License](https://img.shields.io/badge/License-MIT-amber?style=for-the-badge)](LICENSE)
[![Discord](https://img.shields.io/badge/Community-Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/invite/FDKpJu5zgT)

An open-source directory and automated manifest generator for **SteamTools (Watt Toolkit)**. Generate clean `.lua` scripts, `key.vdf` depot keys, and application manifests for any Steam game.

[English](#english) | [中文说明](#中文说明)

---

<a name="english"></a>
## 🌟 Quick Links

* 🌐 **Web Generator**: [https://steamtools.games/](https://steamtools.games/)
* 🎮 **Curated Games Catalog**: [https://steamtools.games/games](https://steamtools.games/games)
* 💻 **Client Setup (Windows / macOS / Linux)**: [https://steamtools.games/install](https://steamtools.games/install)
* 📖 **How It Works**: [https://steamtools.games/how-it-works](https://steamtools.games/how-it-works)
* 🔌 **Developer REST API**: [https://steamtools.games/developers](https://steamtools.games/developers)
* 💬 **Discord Community**: [https://discord.com/invite/FDKpJu5zgT](https://discord.com/invite/FDKpJu5zgT)

---

## 🚀 How to Use SteamTools

1. **Find your Game**: Search by game name or Steam App ID on [SteamTools.games](https://steamtools.games/).
2. **Download Package**: Click **Download ZIP** to receive `{appId}_public.lua`, `key.vdf`, and setup guide.
3. **Place Files**: Copy `.lua` and `key.vdf` into your SteamTools install directory.
4. **Restart Client**: Launch SteamTools / Steam — the game will appear in your library ready for synchronization.

---

## 🔥 Featured Popular Games (Quick Downloads)

| App ID | Game Name | Direct Manifest Link |
| :--- | :--- | :--- |
| `2358720` | **Black Myth: Wukong (黑神话：悟空)** | [Download Manifest & Lua](https://steamtools.games/app/2358720) |
| `1245620` | **ELDEN RING (艾尔登法环)** | [Download Manifest & Lua](https://steamtools.games/app/1245620) |
| `271590` | **Grand Theft Auto V (GTA 5)** | [Download Manifest & Lua](https://steamtools.games/app/271590) |
| `730` | **Counter-Strike 2 (CS2)** | [Download Manifest & Lua](https://steamtools.games/app/730) |
| `1623730` | **Palworld (幻兽帕鲁)** | [Download Manifest & Lua](https://steamtools.games/app/1623730) |
| `1091500` | **Cyberpunk 2077 (赛博朋克 2077)** | [Download Manifest & Lua](https://steamtools.games/app/1091500) |
| `1174180` | **Red Dead Redemption 2 (荒野大镖客 2)** | [Download Manifest & Lua](https://steamtools.games/app/1174180) |
| `105600` | **Terraria (泰拉瑞亚)** | [Download Manifest & Lua](https://steamtools.games/app/105600) |
| `413150` | **Stardew Valley (星露谷物语)** | [Download Manifest & Lua](https://steamtools.games/app/413150) |
| `892970` | **Valheim (英灵神殿)** | [Download Manifest & Lua](https://steamtools.games/app/892970) |
| `400` | **Portal (传送门)** | [Download Manifest & Lua](https://steamtools.games/app/400) |

👉 **[Browse Full 99+ Games Catalog on SteamTools.games →](https://steamtools.games/games)**

---

## 🔌 Free REST API & Automation

You can query metadata and generate manifests programmatically using our public API endpoints (no API key required).

### 1. Search Games
```bash
curl -s "https://steamtools.games/api/search?query=wukong" | jq
```

### 2. Generate Manifest Package
```bash
curl -s -X POST "https://steamtools.games/api/generate" \
  -H "Content-Type: application/json" \
  -d '{"appId": "2358720", "branch": "public"}' | jq
```

Full OpenAPI 3.1 specification available at [https://steamtools.games/developers](https://steamtools.games/developers).

---

<a name="中文说明"></a>
## 🇨🇳 中文说明

本仓库提供 **SteamTools (Watt Toolkit)** 所需的热门游戏清单数据与全自动化 Manifest / Lua 生成器支持。

### 🌟 核心导航
* 🌐 **在线生成器官网**：[https://steamtools.games/zh](https://steamtools.games/zh)
* 🎮 **99 款热门游戏库大厅**：[https://steamtools.games/zh/games](https://steamtools.games/zh/games)
* 💻 **客户端多平台安装指南 (Win/Mac/Linux)**：[https://steamtools.games/zh/install](https://steamtools.games/zh/install)
* 📖 **工作原理与排错教程**：[https://steamtools.games/zh/how-it-works](https://steamtools.games/zh/how-it-works)
* 🔌 **开发者 OpenAPI / REST 接口**：[https://steamtools.games/zh/developers](https://steamtools.games/zh/developers)

### 快速使用三步法
1. 打开 [SteamTools.games](https://steamtools.games/zh)，输入任意 Steam 游戏名称或 App ID；
2. 点击 **下载 ZIP**，获取包含 `{appId}_public.lua`、`key.vdf` 与使用说明的完整包；
3. 将解压出来的 `.lua` 和 `key.vdf` 放入 SteamTools 安装目录，重启客户端即可。

---

## 📄 License

MIT License © 2026 [SteamTools.games](https://steamtools.games/)
