# MA TradeLab — Release Changelog & Version History

[English](changelog.md) | [العربية](../ar/changelog.md)

---

## [v2.5.4] — 2026-10-30 (Current Stable Release)

### Highlights
MA TradeLab v2.5.4 is a major maintenance and feature release introducing a complete offline MT5 historical trade report import system, comprehensive SQLite concurrency enhancements, and production-grade verified packaging.

### New Features & Improvements
- **1-Click MT5 Historical Report Import**:
  - Direct parsing of standard MetaTrader 5 HTML detailed reports and Open XML / CSV trade logs.
  - Eliminates the requirement for an active MT5 broker connection or EA WebRequest when back-filling trade history.
  - Extracts full trading execution metadata: position IDs, deal tickets, order numbers, entry/exit prices, gross profit, commissions, swaps, and net P&L.
- **Automated Trading Account Auto-Provisioning**:
  - The import engine automatically parses the report header for Account Login, Broker Name, Server, and Account Currency.
  - If the account does not exist in the database, it is automatically created and categorized under MetaTrader 5.
- **Incremental Import & Duplicate Detection**:
  - Compares every incoming deal/order against the local SQLite database.
  - Skips already imported records seamlessly without overwriting existing notes, screenshots, or psychological ratings.
- **Database Concurrency & SQLite Lock Resolution**:
  - Implemented SQLite Write-Ahead Logging (WAL) mode for simultaneous multi-threaded read/write resilience.
  - Configured 5,000ms busy timeout handlers to eliminate `SQLite Error 5: database is locked` exceptions during concurrent background updates.
- **Enhanced Setup & Connector Guides**:
  - Updated the in-app MT5 Setup Modal with clear bilingual instructions for WebRequest configuration and EA installation.

### Packaging & Integrity
- **Windows Setup Installer**: `MATradeLab_Setup.exe` (161.3 MB) — SHA-256: `a2355f7b6a8cff0faefc1ad33ee087d9f82bf79d8001631cf5bcff6638057e19`
- **Portable Edition**: `MA_TradeLab_v2.5.4_Portable.zip` (90.6 MB) — SHA-256: `5cc3df2c9aa9919c198a5f6b1b9f1911d1eedf1d0d41b6d55e178d6a8830318e`

---

## [v2.5.3] — 2026-10-15

### Highlights
Enhancements to the Economic News engine, high-impact speech synthesis announcements, and prop firm trailing drawdown edge cases.

### Improvements & Fixes
- **Audio News Engine**:
  - Added studio voice announcements 15 minutes, 5 minutes, and 1 minute prior to High-Impact macroeconomic events.
  - Improved speech queue prioritization when multiple economic events occur simultaneously.
- **Timezone Synchronization**:
  - Resolved UTC vs. local workstation timezone offset discrepancies in event countdown timers.
- **Prop Firm Intelligence Engine (PFIE)**:
  - Updated trailing threshold lock-in logic for accounts with fixed maximum drawdown stops.

---

## [v2.5.2] — 2026-09-30

### Highlights
Critical UI responsiveness fixes, multi-threaded worker isolation, and gamma level parser refinements.

### Improvements & Fixes
- **UI Thread Decoupling**:
  - Separated economic data background polling from the WPF UI dispatcher, resolving intermittent UI freezing during heavy market news feeds.
- **MenthorQ & DeepCharts Integration**:
  - Refined CSV parser to accommodate updated MenthorQ gamma exposure export column headers.
- **Memory Footprint Optimization**:
  - Reduced memory consumption during continuous long-running desktop sessions.

---

## [v2.5.1] — 2026-08-20

### Highlights
Expanded platform connector support and enhanced trade journaling visualization.

### Improvements & Fixes
- **Platform Connectors**:
  - Added support for NinjaTrader 8 execution log parsing.
  - Added experimental ATAS local connector integration.
- **Journal Visuals**:
  - Supported multiple screenshot attachments per trade (Higher Timeframe, Execution Timeframe, and Post-Trade Review).

---

## [v2.5.0] — 2026-07-01

### Highlights
Initial launch of the MA TradeLab unified desktop workstation on .NET 8.0 WPF.

### Initial Features
- Complete migration to .NET 8.0 WPF with hardware-accelerated dark theme UI.
- Native bilingual support (English & Arabic) with real-time UI switching.
- Offline-first SQLite database architecture with DPAPI credential encryption.
- Smart Trading Journal with Expectancy, Profit Factor, and R-Multiple analytics.
- Prop Firm Intelligence Engine (PFIE) supporting Topstep, Apex, and FTMO rules.
- Pre-Trade Gatekeeper with position sizing and mandatory pre-flight checklists.
- Integrated Live Trading Radio & Ambient Focus Station.
