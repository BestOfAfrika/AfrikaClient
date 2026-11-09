# 🌟 AfrikaClient

[![Discord](https://shields.io)](https://discord.gg)
[![Platform](https://shields.io)](https://github.com/BestOfAfrika/AfrikaClient/releases/)
[![Minecraft](https://shields.io)](https://fabricmc.net)

**AfrikaClient** is a free, high-performance, and feature-rich Minecraft Java Edition game utility environment made by **BestOfAfrika**. It consists of a sleek Windows-native launcher hub coupled with a powerful, modular optimization client designed to elevate your multiplayer and survival gameplay.

---

## 🛡️ Privacy & Security First
Unlike many third-party clients, AfrikaClient is designed with absolute transparency. We believe your gaming data and credentials belong solely to you.

* **Zero Telemetry:** No analytics, no tracking, and no background telemetry data collection.
* **Official Microsoft OAuth 2.0:** Account sign-ins go directly through official Xbox/Microsoft secure endpoints. The client never handles, intercepts, or views your account passwords.
* **Sandboxed Workspace:** The launcher only touches its own local application folder. It does not scan your PC directories or read unrelated application data.
* **Safe External Links:** Outbound URL actions strictly redirect to audited, trusted domains (Microsoft, Modrinth, Fabric, Spotify, Discord).
* **Opt-In Architecture:** Everything within the in-game modifications system is **disabled by default**. You choose exactly what you want to enable.
* **Clean Windows Integration:** Runs entirely without requiring administrator privileges and handles installations or uninstalls cleanly through default Windows App Settings.

---

## 🚀 Architectural Breakdown

### 1. AfrikaClient Launcher (v4.1.1)
A highly polished Windows desktop environment written in **Go**, utilizing a fast embedded web interface displayed within a native `WebView2` pipeline.
* **Smart Profile Manager:** Create separate instance folders with unique allocated RAM, dedicated mod configurations, and custom Java launch arguments.
* **Dynamic Multi-Account Switching:** Store and instantly toggle between multiple alternate accounts for seamless server deployment or multi-boxing configurations.
* **Granular FPS Booster:** Profile-specific optimization presets (**Off / Light / Balanced / Max FPS**) that dynamically tune game parameters without overwriting your standard global configurations.
* **Native Modrinth Integration:** Browse, discover, download, and update open-source modifications straight from the Modrinth API within the client interface. Includes anti-clash safeguards that manage overlapping mod classes.
* **Massive Cosmetic Customization:** Equips a 3D real-time rendering view displaying **86 unique cosmetics** (29 hats, 28 headbands, 29 animated wings) alongside native custom cape uploading.
* **Immersive Theme Engine:** Personalize your desktop client with **20 visual themes** (such as Galaxy, Sakura, Frost, Cosmic Christmas) and **14 distinct responsive layouts**. Supports live high-capacity background video elements exceeding 1 GB.
* **Media Integration:** An integrated Spotify companion dashboard that reads active track details and fetches metadata directly to your launcher home screen.

### 2. AfrikaClient In-Game Mod (v3.3.3)
A custom game engine optimization modification written in **Java** on top of **Fabric Loader 0.19.3** and Fabric API for Minecraft **1.21.11**. Accessible in-game via the **Right Shift** menu.
* **Comprehensive HUD Suite:** Fully positionable on-screen indicators tracking FPS graphs, CPS, precise server TPS, network ping, sub-coordinate systems (with Nether mapping), gear durability, health analytics, and entity trackers.
* **Interactive Spotify HUD:** Controls music playback dynamically from inside the game environment. Features draggable song progress timelines, track tracking, keybind mapping, and a real-time lyrics scrolling panel.
* **Custom Scoreboard UI:** Completely adjust transparency layouts, scaling profiles, and placement matrices for default multiplayer scoreboard panels across any target server.
* **Advanced Visual Diagnostics:** Includes optional motion blur mechanics, custom responsive crosshairs, Color Boost layers, item physics models, freelook perspectives, shulker box container previews, and low-health vignette markers.
* **Utility Engines:** Configurable ToggleSprint modules, Auto-GG chat broadcasts, chat timestamp matrices, breakdown notifications, and thorough horse biometric evaluation panels.
* **Performance Suite Expansion:** Instantly packages optimized, community-audited mod suites (including Sodium, Lithium, FerriteCore, Entity Culling, and ImmediatelyFast) at the click of a button.

---

## 📦 Installation Guide

1. Navigate to our official [GitHub Releases](https://github.com/BestOfAfrika/AfrikaClient/releases/) page.
2. Download the latest `AfrikaClient.exe` executable binary file.
3. *(Optional)* Verify your file integrity matching the provided `AfrikaClient.exe.sha256` checksum map.
4. Launch the application. The launcher will configure its dedicated runtime framework automatically.
5. Securely authenticate via your Microsoft Profile account, choose your performance tier, and press **Play**.
6. Once the runtime finishes loading, tap **Right Shift** inside your game instance to access your mod suite layout.

---

## 🛠️ Technical Details

* **Launcher Core:** Go (Golang) / Microsoft WebView2 / HTML5 Runtime
* **Mod Framework:** Java / Fabric Loader `0.19.3` / Fabric API `0.141.3+1.21.11`
* **Target Environment:** Windows 10 & Windows 11 (64-bit platforms)
* **Asset Endpoints:** Modrinth Core API Integration

---

## 👥 Community & Support

* **Official Discord Hub:** Join us on [Discord](https://discord.gg) for live support, feature requests, and updates.
* **Lead Developer Contact:** `bestofafrika` on Discord.

***Made with ♥ by BestOfAfrika***

*Disclaimer: AfrikaClient is an independent custom launcher utility framework and is not affiliated, authorized, associated, or endorsed by Mojang Studios or Microsoft Corporation.*
