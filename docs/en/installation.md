# MA TradeLab — Installation & Setup Guide

[English](installation.md) | [العربية](../ar/installation.md)

---

## Overview

**MA TradeLab** is distributed in two official delivery formats for 64-bit Windows systems:
1. **Windows Setup Installer (`MATradeLab_Setup.exe`)** — Automated installer with desktop shortcuts, Start Menu integration, and clean uninstaller support.
2. **Portable Edition (`MA_TradeLab_v2.5.4_Portable.zip`)** — Self-contained standalone archive requiring zero administrative privileges; ideal for USB drives or dedicated trading rigs.

Both editions are 100% self-contained and run completely offline with zero external cloud dependencies.

---

## System Requirements

| Specification | Minimum Requirement | Recommended Specification |
| :--- | :--- | :--- |
| **Operating System** | Windows 10 64-bit (Build 1903+) | Windows 11 64-bit |
| **Processor** | Intel Core i3 / AMD Ryzen 3 (2.0 GHz+) | Intel Core i5 / AMD Ryzen 5 or higher |
| **Memory (RAM)** | 4 GB | 8 GB – 16 GB |
| **Disk Storage** | 500 MB free space | NVMe SSD storage |
| **Display Resolution**| 1366 × 768 | 1920 × 1080 (Full HD) or 4K with High-DPI scaling |
| **Runtime** | Microsoft .NET 8.0 Desktop Runtime (x64) | Included / Self-contained |

---

## Official Release Packages (v2.5.4)

Always verify package integrity using the official SHA-256 hashes prior to execution:

| Package | Filename | Size | SHA-256 Checksum |
| :--- | :--- | :--- | :--- |
| **Setup Installer** | `MATradeLab_Setup.exe` | 161.3 MB | `a2355f7b6a8cff0faefc1ad33ee087d9f82bf79d8001631cf5bcff6638057e19` |
| **Portable Package** | `MA_TradeLab_v2.5.4_Portable.zip` | 90.6 MB | `5cc3df2c9aa9919c198a5f6b1b9f1911d1eedf1d0d41b6d55e178d6a8830318e` |

Official release assets can be downloaded directly from the [GitHub Releases Page](https://github.com/m4whw/MATradelab/releases/tag/v2.5.4).

### Hash Verification Command
To verify the SHA-256 hash in PowerShell:
```powershell
Get-FileHash -Algorithm SHA256 "MATradeLab_Setup.exe"
Get-FileHash -Algorithm SHA256 "MA_TradeLab_v2.5.4_Portable.zip"
```

---

## Method 1: Setup Installer Installation

1. Download `MATradeLab_Setup.exe` from the official repository release.
2. Run the executable installer.
3. Select the destination folder (default: `%LocalAppData%\Programs\MATradeLab` for single-user mode).
4. Choose whether to create a Desktop Shortcut and Start Menu entry.
5. Click **Install**. Once finished, launch MA TradeLab immediately.

### Silent / Enterprise Unattended Installation
For automated setup scripts or trading desk deployment:
```cmd
MATradeLab_Setup.exe /VERYSILENT /SUPPRESSMSGBOXES /NORESTART
```

---

## Method 2: Portable Edition Installation

1. Download `MA_TradeLab_v2.5.4_Portable.zip`.
2. Right-click the `.zip` archive, select **Extract All...**, and extract to your desired directory (e.g., `D:\TradingTools\MATradeLab` or an encrypted external SSD).
3. Open the extracted folder and double-click `MATradeLab.exe`.
4. No system registry modifications or administrator rights are required.

---

## Data Storage & DPAPI Security

MA TradeLab operates under a zero-telemetry, offline-first security model:

- **Local Database**: All trading accounts, journal records, executions, strategies, and notes are stored locally in an embedded SQLite database (`matradelab.db`) with Write-Ahead Logging (WAL) enabled for concurrency and crash-resilience.
- **Data Location**:
  - Installer Edition: `%LocalAppData%\MATradeLab\`
  - Portable Edition: Stored in the application folder or `%LocalAppData%\MATradeLab\` depending on configuration.
- **Hardware-Level Encryption**: Sensitive configuration elements (such as local connector tokens or broker identifiers) are protected via the Windows **Data Protection API (DPAPI)** using `DataProtectionScope.CurrentUser`. No plaintext passwords or keys are ever exported or transmitted.

---

## Backup, Restore & Uninstallation

### Backing Up Your Trading Data
To make a complete backup of all your journals, settings, and screenshots:
1. Close MA TradeLab.
2. Navigate to `%LocalAppData%\MATradeLab\`.
3. Copy the following files/folders to your secure backup storage:
   - `matradelab.db` (Primary SQLite database)
   - `matradelab.db-wal` (Write-ahead log if present)
   - `Screenshots/` (Attached chart images)

### Restoring Your Data
1. Install or extract MA TradeLab on the new workstation.
2. Copy your backed up `matradelab.db` and `Screenshots/` into `%LocalAppData%\MATradeLab\`.
3. Launch the application; all accounts, trades, and historical statistics will load immediately.

### Clean Uninstallation
1. Open Windows **Settings** → **Apps** → **Installed Apps**.
2. Locate **MA TradeLab** and click **Uninstall**.
3. (Optional) To remove historical journal records and configuration, manually delete the folder `%LocalAppData%\MATradeLab\`.
