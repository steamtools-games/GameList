# 🎮 SteamTools 游戏目录与 Manifest 生成器

[![SteamTools](https://img.shields.io/badge/SteamTools.games-在线生成器-0ea5e9?style=for-the-badge&logo=steam&logoColor=white)](https://steamtools.games/zh)
[![Games Indexed](https://img.shields.io/badge/收录游戏-99%2B%20热门大作-10b981?style=for-the-badge)](https://steamtools.games/zh/games)
[![OpenAPI 3.1](https://img.shields.io/badge/开放接口-OpenAPI%203.1-8b5cf6?style=for-the-badge)](https://steamtools.games/zh/developers)
[![License](https://img.shields.io/badge/开源协议-MIT-amber?style=for-the-badge)](LICENSE)
[![Discord](https://img.shields.io/badge/官方社区-Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/invite/FDKpJu5zgT)

本开源仓库为 **SteamTools (Watt Toolkit)** 提供最新热门游戏清单数据与自动化 Manifest / Lua 生成器支持。支持一键生成纯净的 `.lua` 脚本、`key.vdf` 密钥与游戏清单文件。

---

### 🌐 多语言版本 / Read this in your language:
**[English](README.md)** | **[简体中文](README_zh.md)** | **[Русский](README_ru.md)** | **[Türkçe](README_tr.md)** | **[Español](README_es.md)** | **[Français](README_fr.md)** | **[Português (Brasil)](README_pt-BR.md)**

---

## 🌟 核心直达链接

* 🌐 **官网在线生成器**：[https://steamtools.games/zh](https://steamtools.games/zh)
* 🎮 **99 款精选热门游戏库大厅**：[https://steamtools.games/zh/games](https://steamtools.games/zh/games)
* 💻 **客户端多平台安装指南 (Win/Mac/Linux)**：[https://steamtools.games/zh/install](https://steamtools.games/zh/install)
* 📖 **工作原理与常见问题排错**：[https://steamtools.games/zh/how-it-works](https://steamtools.games/zh/how-it-works)
* 🔌 **开发者 REST 接口与 OpenAPI 3.1**：[https://steamtools.games/zh/developers](https://steamtools.games/zh/developers)
* 💬 **官方 Discord 交流社区**：[https://discord.com/invite/FDKpJu5zgT](https://discord.com/invite/FDKpJu5zgT)

---

## 🚀 极速使用三步法

1. **查找游戏**：在 [SteamTools.games](https://steamtools.games/zh) 搜索游戏名称或粘贴 Steam App ID；
2. **下载文件包**：点击 **下载 ZIP**，获取包含 `{appId}_public.lua`、`key.vdf` 及说明文档的完整包；
3. **放置文件**：将 `.lua` 与 `key.vdf` 放入 SteamTools 根目录；
4. **重启客户端**：重启 SteamTools 与 Steam，游戏即可在库中加载。

---

## 🔥 精选热门大作（直接下载入口）

| App ID | 游戏名称 | 专属 Manifest & Lua 下载页 |
| :--- | :--- | :--- |
| `2358720` | **黑神话：悟空 (Black Myth: Wukong)** | [获取清单与 Lua 脚本](https://steamtools.games/zh/app/2358720) |
| `1245620` | **艾尔登法环 (ELDEN RING)** | [获取清单与 Lua 脚本](https://steamtools.games/zh/app/1245620) |
| `271590` | **侠盗猎车手 5 (GTA V)** | [获取清单与 Lua 脚本](https://steamtools.games/zh/app/271590) |
| `730` | **反恐精英 2 (Counter-Strike 2)** | [获取清单与 Lua 脚本](https://steamtools.games/zh/app/730) |
| `1623730` | **幻兽帕鲁 (Palworld)** | [获取清单与 Lua 脚本](https://steamtools.games/zh/app/1623730) |
| `1091500` | **赛博朋克 2077 (Cyberpunk 2077)** | [获取清单与 Lua 脚本](https://steamtools.games/zh/app/1091500) |
| `1174180` | **荒野大镖客：救赎 2 (RDR2)** | [获取清单与 Lua 脚本](https://steamtools.games/zh/app/1174180) |
| `105600` | **泰拉瑞亚 (Terraria)** | [获取清单与 Lua 脚本](https://steamtools.games/zh/app/105600) |
| `413150` | **星露谷物语 (Stardew Valley)** | [获取清单与 Lua 脚本](https://steamtools.games/zh/app/413150) |
| `892970` | **英灵神殿 (Valheim)** | [获取清单与 Lua 脚本](https://steamtools.games/zh/app/892970) |
| `400` | **传送门 (Portal)** | [获取清单与 Lua 脚本](https://steamtools.games/zh/app/400) |

👉 **[查看全部 99 款热门游戏完整列表 →](https://steamtools.games/zh/games)**

---

## 🔌 开发者公共 API 接口

无需 API Key 即可直接调用公共端点进行自动化查询与生成：

### 1. 搜索 Steam 游戏
```bash
curl -s "https://steamtools.games/api/search?query=wukong" | jq
```

### 2. 生成 Manifest 清单包数据
```bash
curl -s -X POST "https://steamtools.games/api/generate" \
  -H "Content-Type: application/json" \
  -d '{"appId": "2358720", "branch": "public"}' | jq
```

完整 OpenAPI 3.1 规范文档请访问：[https://steamtools.games/zh/developers](https://steamtools.games/zh/developers)。

---

## 📄 开源协议

MIT License © 2026 [SteamTools.games](https://steamtools.games/)
