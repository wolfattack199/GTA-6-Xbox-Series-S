<div align="center">

# 🌴 GTA 6 · How the Xbox Download Works 🌴

### *What an Xbox Series X|S actually downloads when you install GTA 6, seen from the network*

![Size](https://img.shields.io/badge/package-209.9%20GB-ff2d95?style=for-the-badge)
![Version](https://img.shields.io/badge/version-1.0.2.1-7b2dff?style=for-the-badge)
![Platform](https://img.shields.io/badge/platform-Xbox%20Series%20X%7CS-107c10?style=for-the-badge)
![Format](https://img.shields.io/badge/format-encrypted%20XVC-555555?style=for-the-badge)

</div>

---

## 👀 What this is

I watched my own Xbox install **GTA 6 (Ultimate Edition)** through a Wi-Fi hotspot I made on my PC, and logged what it downloaded.
These are my notes on how a big Xbox game gets delivered.

> [!NOTE]
> This repo contains **no game files** and **no tools to unlock or modify them**.
> To play GTA 6 you need to buy it for Xbox or PlayStation, or wait for Rockstar's official PC version.

---

## 📦 The game package

| | |
|---|---|
| 🎮 **Game** | Grand Theft Auto VI (Rockstar Games) |
| 📁 **Package name** | `RockstarGamesInc.28872443D20A7_1.0.2.1_neutral_ANZ_k2ss7vbb13xte_xs.xvc` |
| 📏 **Size** | **225,335,779,328 bytes** (Windows shows ≈ **209.9 GB**) |
| 🏷️ **Version** | 1.0.2.1 (updated Nov 14, 2026) |
| 🌐 **Served from** | Microsoft's Xbox download network (`assets1.xboxlive.com`) |
| ✨ **Ultimate add-on** | A separate package, about **2 GB** |
| 💾 **Space needed on the Xbox** | ≈ 212 GB for the game and the add-on |

---

## 🔍 What I learned

- **The whole game is one file.** The Xbox downloads it in thousands of small pieces (HTTP "range requests") and puts them back together.
- **It comes from Microsoft's servers**, cached close to you (mine came from Dallas). Partway through, the Xbox can switch to a different server.
- **Before you can play, the Xbox checks your license** with `licensing.mp.microsoft.com`.
- **The package is encrypted (XVC).** Only an Xbox with a valid license for your account can open it. The key stays inside the console's security chip.
- **That's why the Xbox file can't run on a PC**, even with a strong GPU. The code inside is built for the Xbox's own system and graphics chip.

---

## 🎮 Want to play GTA 6 on a PC screen?

- 🖥️ **Remote Play:** stream from your own Xbox using the Xbox app, or at **xbox.com/play** in Chrome or Edge.
- ✨ **Sharper picture:** with an NVIDIA RTX card, turn on **RTX Video Super Resolution** in the NVIDIA Control Panel while you stream in the browser.
- ⏳ **Real PC graphics (ray tracing, DLSS):** wait for Rockstar's official PC release.

---

<div align="center">

*Network notes from my own Xbox and my own home network · Nov 2026*
*Not affiliated with Rockstar Games, Take-Two, or Microsoft.*

</div>
