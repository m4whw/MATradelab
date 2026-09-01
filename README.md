# 📊 MA TradeLab
### المنصة المتقدمة لتدوين الصفقات، إدارة مخاطر شركات التمويل، والتحليل الاستراتيجي الذكي
**Advanced Desktop Trading Journal, Prop Firm Engine & Strategy Analytics**

<div align="center">

[![Platform](https://img.shields.io/badge/Platform-Windows_10%2B_%7C_64--bit-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#)
[![Framework](https://img.shields.io/badge/.NET-8.0_WPF-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)](#)
[![Security](https://img.shields.io/badge/Privacy-100%25_Offline_Local_Storage-2ea44f?style=for-the-badge&logo=sqlite&logoColor=white)](#)
[![License](https://img.shields.io/badge/License-Proprietary-D4AF37?style=for-the-badge)](#)

</div>

---

## 🌟 Overview / نبذة عن البرنامج

**MA TradeLab** is an ultra-high performance desktop application engineered for professional traders and proprietary firm (Prop Firm) traders across Futures, Forex, and Equities. It combines an **Advanced Trading Journal**, a **Prop Firm Intelligence Engine (PFIE)**, an **Economic Calendar with Studio Voice Alerts**, and **Direct Local Platform Connectors**—all while guaranteeing 100% offline data privacy on your local machine.

**MA TradeLab** هو برنامج مكتبي فائق الأداء مصمم للمتداولين المحترفين ومتداولي شركات التمويل (Prop Firms) في أسواق الفيوتشرز (Futures)، الفوركس (Forex)، والأسهم. يجمع البرنامج بين **سجل صفقات ذكي ومفصل (Trading Journal)**، **محرك حماية ومتابعة شروط شركات التمويل (Prop Firm Engine)**، **منظومة تنبيهات صوتية وإخبارية متقدمة (Economic Calendar & Audio Alerts)**، بالإضافة إلى **الربط المباشر مع أشهر منصات التداول** دون الحاجة لوسطاء خارجيين مع الحفاظ على خصوصية بياناتك 100% داخل جهازك.

---

## 💎 Key Features & Technical Capabilities / أهم المميزات الفنية

### 1. 📓 Smart Trading Journal & Statistical Analytics (سجل الصفقات والتحليل الإحصائي)
- **Precision Logging**: Track entries, exits, commissions, Realized PnL, and R-Multiples.
- **Real-Time Performance Metrics**: Expectancy, Win Rate, Profit Factor, Equity Curve, and Drawdown.
- **Visual Trade Archiving**: Attach before & after chart screenshots with behavioral grading and detailed notes.
- **Advanced Filtering**: Filter trades by strategy, trading session (New York, London, Asian), symbol, or time horizon.

### 2. 🛡️ Prop Firm Intelligence Engine (PFIE) (محرك ذكاء شركات التمويل)
- **Built-in Database for 50+ Global Prop Firms**: (Topstep, Tradeify, Apex Trader Funding, MyFundedFutures, FTMO, FundedNext, and more).
- **Automated Rule Enforcement**: Real-time tracking of Trailing Drawdown, Static Drawdown, Daily Loss Limit, Max Loss Limit, and profit target progression.
- **Multi-Account Matrix**: Seamlessly switch between Evaluation challenges and Funded / Master accounts.

### 3. ⏰ Economic Calendar & Studio Audio Alerts (المفكرة الاقتصادية والتنبيهات الصوتية)
- **Real-Time Macro Events**: Live calendar for high-impact events (CPI, NFP, FOMC, GDP, Interest Rates).
- **Ultra-Clear Studio Human Voice Alerts**: Customizable countdown alerts (1-30 minutes), release-second chimes, actual number update notifications, and extreme volatility safeguards.
- **Audio Customization**: Toggle individual sound types, test sounds, or import custom WAV/MP3 files.

### 4. 🔄 Direct Platform Connectors (المزامنة الفورية مع منصات التداول)
- **MetaTrader 5 (MT5)**: Native MQL5 connector (`MATradeLabConnector.mq5`) on port 18082 for 1-click sync.
- **NinjaTrader 8**: Native C# add-on (`MATradeLabConnector.cs`) on port 18080 for instant futures sync.
- **ATAS Platform**: Integrated strategy connector (`MATradeLabAtasConnector.cs`) on port 18081.
- **100% Localhost IPC**: Zero third-party API dependencies or cloud middlemen.

### 5. 🎯 DeepCharts Gamma Levels Converter (محول مستويات الجاما)
- Convert raw institutional Gamma & Option levels from **MenthorQ** into standard symbols (`$NQ1!`, `$ES1!`, `$QQQ`, `$SPY`, etc.).
- One-click JSON export ready for instant import into **DeepCharts**.

### 6. 🧠 AI Research Hub & Strategy Builder (مركز الذكاء الاصطناعي وبناء الاستراتيجيات)
- **Local & Cloud AI**: 100% offline privacy via **Ollama** (Local LLMs) and cloud integrations (**OpenAI ChatGPT, Google Gemini, Anthropic Claude**).
- **Weighted Strategy Checklist**: Build custom weighted entry rules and psychological discipline checklists.

### 7. 🔒 Military-Grade Privacy & Encryption (الخصوصية والأمان الفائق)
- **Zero Data Leakage**: All trade logs, account balances, and notes remain stored locally in an encrypted SQLite database.
- **Windows DPAPI**: Hardware-level encryption for AI API credentials.

---

## 🛠️ Technical Specifications / المواصفات التقنية

| Specification / البند | Details / المواصفات |
|---|---|
| **Operating System / نظام التشغيل** | Windows 10 / Windows 11 (64-bit) |
| **Runtime / بيئة التشغيل** | .NET 8.0 Desktop Runtime (x64) |
| **Architecture / لغة البرمجة** | C# 12 / WPF (MVVM Clean Architecture) |
| **Database / قاعدة البيانات** | SQLite (Offline-First / Embedded) |
| **Installer / المثبت** | Standalone Single-File Setup (~42 MB) |
| **Languages / اللغات** | العربية والإنجليزية (Dual Native UI) |
| **Theme / المظهر** | Dark Theme فاخر بتدرجات ذهبية |

---

## 📦 Quick Installation / التثبيت والتشغيل السريع
1. Download `MATradeLab_Setup.exe` from [Official Website](https://mohamed-abdelaziz.com/ar/learning/tools/matradelab) or [Releases](https://github.com/m4whw/MATradelab/releases).
2. Run the setup wizard, choose your directory, and click **Install**.
3. Launch the application, select your preferred language (العربية / English), and start journaling and syncing!

---

<div align="center">

**Developed by: Mohamed Abdelaziz / تطوير وإشراف: محمد عبد العزيز**  
Official Website: [mohamed-abdelaziz.com](https://mohamed-abdelaziz.com)  
All Rights Reserved © 2026

</div>