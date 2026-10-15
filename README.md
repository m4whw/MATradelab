<div align="center">

# 📊 MA TradeLab (v2.5.2)

[![Release](https://img.shields.io/badge/Release-v2.5.2-gold?style=for-the-badge&logo=github&logoColor=white)](https://github.com/m4whw/MATradelab/releases/tag/v2.5.2)
[![Platform](https://img.shields.io/badge/Platform-Windows_10%2B_%7C_64--bit-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/m4whw/MATradelab/releases/tag/v2.5.2)
[![Framework](https://img.shields.io/badge/.NET-8.0_WPF-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/)
[![Security](https://img.shields.io/badge/Privacy-100%25_Offline_Local_Storage-2ea44f?style=for-the-badge&logo=sqlite&logoColor=white)](#-security--data-privacy)

### 🌐 Select Language / اختر لغة القراءة:
[**🇺🇸 English Documentation (Skip to English)**](#-english-documentation) &nbsp;•&nbsp; [**🇸🇦 الوثائق باللغة العربية (الانتقال للقسم العربي)**](#-الوثائق-باللغة-العربية)

</div>

---

# 🇺🇸 English Documentation

## 📑 Table of Contents
- [🌟 Overview](#-overview)
- [💎 Core Capabilities](#-core-capabilities)
  - [1. Smart Trading Journal & Statistical Analytics](#1-smart-trading-journal--statistical-analytics)
  - [2. Prop Firm Intelligence Engine (PFIE)](#2-prop-firm-intelligence-engine-pfie)
  - [3. Pre-Trade Decision Engine & Risk Management](#3-pre-trade-decision-engine--risk-management)
  - [4. Personal & Trading Financial Management](#4-personal--trading-financial-management)
  - [5. Economic Calendar & Studio Audio Alerts](#5-economic-calendar--studio-audio-alerts)
  - [6. Direct Platform Connectors (MT5, NinjaTrader 8, ATAS)](#6-direct-platform-connectors)
  - [7. DeepCharts & MenthorQ Gamma Converter](#7-deepcharts--menthorq-gamma-converter)
  - [8. Live Trading Radio & Ambient Focus Station](#8-live-trading-radio--ambient-focus-station)
- [🛠️ Technical Specifications](#️-technical-specifications)
- [📦 Download & Installation](#-download--installation)
- [🔒 Security & Data Privacy](#-security--data-privacy)
- [👨‍💻 Author & Developer](#-author--developer)

---

## 🌟 Overview

**MA TradeLab** is an ultra-high performance Windows desktop workstation engineered specifically for professional futures, forex, and equities traders, as well as proprietary firm (Prop Firm) traders (Topstep, Apex Trader Funding, Tradeify, MyFundedFutures, FTMO).

It unifies an **advanced trade journaling engine**, a **real-time prop compliance risk guardian**, a **pre-trade quantitative execution gatekeeper**, a **live economic calendar with studio human voice alerts**, a **comprehensive personal & trading financial ledger**, and **zero-latency local platform connectors**—all running 100% offline with zero external cloud dependencies.

---

## 💎 Core Capabilities

### 1. Smart Trading Journal & Statistical Analytics
- **Multi-Asset Trade Journaling**: Log trades across CME/NYMEX Futures (NQ, ES, YM, RTY, GC, CL), Spot Forex, and Equities with contract sizing, exact tick calculations, commissions, and gross/net realized P&L.
- **Advanced Mathematical Performance Metrics**:
  - **Expectancy & Expectancy Ratio**: Calculate the true statistical edge per dollar risked.
  - **Win Rate & Profit Factor**: Real-time evaluation of execution quality.
  - **Average Win / Loss and R-multiple tracking**.
  - **Consecutive Wins / Losses Tracker**.
- **Visual Trade Archiving**: Attach before & after multi-timeframe chart screenshots, entry trigger reasoning, trade behavioral ratings, and emotional discipline notes.
- **Multi-Dimensional Filtering**: Instantly filter trades by Account, Trading Strategy, Session (New York AM/PM, London, Asia), Symbol, Direction (Long/Short), and Custom Date Ranges.

### 2. Prop Firm Intelligence Engine (PFIE)
- **Built-in Catalog for 50+ Global Prop Firms**: Pre-configured rule parameters for Topstep, Apex Trader Funding, Tradeify, MyFundedFutures, Fast Track Funder, FTMO, FundedNext, and custom accounts.
- **Automated Rule Guardrails & Threshold Alerts**:
  - **Daily Loss Limit (DLL)**: Dynamic real-time calculation with warning buffers before breaching accounts.
  - **Trailing Drawdown & Static Drawdown**: Exact tracking against high-water marks and peak balances.
  - **Maximum Loss Limit (MLL)**: Strict risk ceiling visualization.
  - **Profit Target & Consistency Tracking**: Live progress bar toward evaluation completion and payout eligibility.
- **Multi-Account Matrix**: Seamlessly manage and isolate multiple Evaluation challenges, Funded accounts, and Personal broker accounts simultaneously with zero database cross-contamination.

### 3. Pre-Trade Decision Engine & Risk Management
- **Objective Pre-Trade Checklist**: Protect your capital against FOMO, revenge trading, and emotional impulse entries by executing an objective, multi-variable criteria check before opening a position.
- **Weighted Rule Checklist**: Build customized strategy rules with percentage weights (0-100%) and non-negotiable mandatory conditions.
- **Automated Contract Sizing & Dollar Risk Calculation**: Enter your stop-loss in points/pips/ticks and account risk percentage; the engine calculates the exact number of contracts/lots to risk.
- **Strict Execution Verdict**: Clear deterministic recommendation (**EXECUTE** or **DO NOT EXECUTE**) based on meeting the minimum required strategy score.

### 4. Personal & Trading Financial Management
- **Multi-Account Ledger**: Track Bank Accounts, Physical Cash Reserves, Broker Capital, and Crypto Wallets with full balance synchronization.
- **Strict Double-Entry Accounting Integrity**: Internal transfers between accounts (e.g. Bank to Broker) are isolated and never falsely categorized as income or expenses.
- **Dedicated Trading Cost & Subscription Tracker**:
  - Track live market data fees (CME Level 1 / Level 2), charting platform licenses (TradingView, Bookmap, Sierra Chart), VPS servers, and prop firm fees.
  - Monitor trading education, courses, hardware upgrades (PCs, Monitors, UPS), and equipment maintenance.
- **Subscription Expiry & Renewal Reminders**: Dynamic alert window (1 to 30 days before renewal) with color-coded status badges (`DUE SOON`, `Due Today!`, `Overdue`).
- **Assets & Liabilities Ledger**: Track physical and digital assets vs debts, credit cards, and loans with live Net Worth and Debt-to-Asset ratio calculations.
- **Executive Financial Analytics & 5 Native Vector Charts**:
  1. **Monthly Cash Flow**: Income vs Expense column comparison.
  2. **Net Worth Growth Trajectory**: Cumulative wealth progression polygon.
  3. **Expense Allocation**: Proportional categorical breakdown.
  4. **Trading Performance Ratios**: Trading revenue vs operating trading expenses.
  5. **Savings Progress**: Monthly saved capital vs target goals.
- **Full Editing & Cascade Deletion**: Easily edit account details and safely delete accounts with automated cascade cleanup, preventing database constraint errors.

### 5. Economic Calendar & Studio Audio Alerts
- **Real-Time Macroeconomic Event Feed**: High-impact news tracking for CPI, Core CPI, NFP (Non-Farm Payrolls), FOMC Rate Decisions, PPI, GDP, Retail Sales, and Unemployment Claims.
- **High-Fidelity Studio Human Voice Alerts**:
  - Real human voice countdown reminders: 15 minutes, 5 minutes, 1 minute before high-impact news releases.
  - Second-of-release warning chime to protect open trades from extreme slippage and volatility spikes.
  - Actual outcome notifications when the actual figure is published by the feed.
- **T1 News Calendar & Pre-Trade News Gate**: Official BLS, Federal Reserve and EIA release dates shown in New York and Brussels time; the Pre-Trade engine blocks new entries inside the high-impact window (±2 min prop rule plus a ±5 min safety buffer).
- **Customizable Audio & Language Controls**: Bilingual Arabic & English studio voices with individual event toggles, volume sliders, and sound testing.

### 6. Direct Platform Connectors
- **Localhost Zero-Latency IPC**: Connects directly to desktop trading platforms without cloud intermediaries:
  - **MetaTrader 5 (MT5)**: MQL5 Expert Advisor (`MATradeLabConnector.mq5`) listening on port 18082 for instant trade sync.
  - **NinjaTrader 8 (NT8)**: Native C# add-on on port 18080 for live futures trade journaling.
  - **ATAS Platform**: Integrated strategy connector (`MATradeLabAtasConnector.cs`) on port 18081 for order-flow trade logging.

### 7. DeepCharts & MenthorQ Gamma Converter
- **Institutional Option Gamma Integration**: Parse and convert raw options positioning, Call/Put Walls, 0DTE Volatility Triggers, and Gamma Flips from MenthorQ into standardized symbol formats (`$NQ1!`, `$ES1!`, `$QQQ`, `$SPY`).
- **One-Click DeepCharts Export**: Generate optimized JSON data ready for direct import into DeepCharts for institutional market structure analysis.

### 8. Live Trading Radio & Ambient Focus Station
- **Integrated Background Audio**: Multi-channel streaming including market news feeds, economic radio, and ambient focus streams (Chill, Lo-Fi, Ambient, Groove Salad) designed to sustain focus and emotional discipline during intense market sessions.

---

## 🛠️ Technical Specifications

| Specification | Technical Details |
|---|---|
| **Software Name** | **MA TradeLab** |
| **Version** | **v2.5.2 (Official Stable Release)** |
| **Target OS** | Windows 10 / Windows 11 (64-bit Architecture) |
| **Runtime** | .NET 8.0 Desktop Runtime (Self-Contained / Mapped x64) |
| **Language & Architecture** | C# 12 / WPF with MVVM Clean Architecture |
| **Database Engine** | Embedded SQLite with EF Core & ACID Compliant Transactions |
| **Packaging** | Setup Installer (~161 MB) & Portable ZIP (~91 MB), SHA-256 checksums on the release page |
| **User Interface** | Dual Native Interface (English and Arabic with dynamic RTL/LTR switch) |
| **Visual Theme** | High-Contrast Dark Gold Cyberpunk Workstation |
| **Data Privacy** | **100% Offline Local Storage** (Zero Telemetry, Zero Cloud Sync) |

---

## 📦 Download & Installation

### Available Packages for Version 2.5.2:

| Package | Size | Description | Download Link |
|---|---|---|---|
| **`MATradeLab_Setup.exe`** | **~161 MB** | **Official Setup Installer (Recommended)**: Self-contained installer that automatically configures shortcuts and desktop links. | [📥 Download Setup](https://github.com/m4whw/MATradelab/releases/download/v2.5.2/MATradeLab_Setup.exe) |
| **`MA_TradeLab_v2.5.2_Portable.zip`** | **~91 MB** | **Portable Archive**: Extract to any directory or external USB drive and launch directly. | [📥 Download Portable ZIP](https://github.com/m4whw/MATradelab/releases/download/v2.5.2/MA_TradeLab_v2.5.2_Portable.zip) |

### Installation Instructions:
1. Download `MATradeLab_Setup.exe` from the table above.
2. Run the installer and choose your preferred destination directory.
3. Launch MA TradeLab, select your preferred interface language, and start logging trades immediately.

> **Note**: MA TradeLab is completely self-contained. It does not require prior installation of .NET Runtime or any external dependencies.

---

## 🔒 Security & Data Privacy

- **Zero Cloud Storage**: All trade data, account numbers, strategy parameters, screenshots, and financial records reside strictly on your local computer.
- **Credential Protection**: API keys and sensitive settings are encrypted with the Windows Data Protection API (DPAPI).
- **Local-Only Connectors**: The MT5, NinjaTrader 8 and ATAS connector ports accept connections from your own computer only and reject browser and network requests.

---

## 👨‍💻 Author & Developer

**Mohamed Abdelaziz**  
*Software Engineer & Quantitative Systematic Trader*  
- **Official Website**: [https://mohamed-abdelaziz.com](https://mohamed-abdelaziz.com)  
- **GitHub**: [@m4whw](https://github.com/m4whw)  
- **Project Repository**: [https://github.com/m4whw/MATradelab](https://github.com/m4whw/MATradelab)


---

# 🇸🇦 الوثائق باللغة العربية

## 📑 فهرس المحتويات
- [🌟 نظرة عامة على المنصة](#-نظرة-عامة-على-المنصة)
- [💎 الأركان والقدرات الأساسية](#-الأركان-والقدرات-الأساسية)
  - [1. سجل الصفقات الذكي والتحليل الإحصائي المتقدم](#1-سجل-الصفقات-الذكي-والتحليل-الإحصائي-المتقدم)
  - [2. محرك ذكاء وإدارة حسابات شركات التمويل](#2-محرك-ذكاء-وإدارة-حسابات-شركات-التمويل)
  - [3. محرك القرار الكمي وإدارة المخاطر قبل التنفيذ](#3-محرك-القرار-الكمي-وإدارة-المخاطر-قبل-التنفيذ)
  - [4. الإدارة المالية الشاملة للتداول والمصاريف الشخصية](#4-الإدارة-المالية-الشاملة-للتداول-والمصاريف-الشخصية)
  - [5. المفكرة الاقتصادية الحية والتنبيهات الصوتية الاستوديو](#5-المفكرة-الاقتصادية-الحية-والتنبيهات-الصوتية-الاستوديو)
  - [6. الربط المباشر مع منصات التداول](#6-الربط-المباشر-مع-منصات-التداول)
  - [7. محول مستويات الجاما المؤسسية](#7-محول-مستويات-الجاما-المؤسسية)
  - [8. راديو المتداول المباشر ومحطة التركيز الذهني](#8-راديو-المتداول-المباشر-ومحطة-التركيز-الذهني)
- [🛠️ المواصفات الفنية للبرنامج](#️-المواصفات-الفنية-للبرنامج)
- [📦 روابط التحميل والتثبيت السريع](#-روابط-التحميل-والتثبيت-السريع)
- [🔒 الأمان وحماية الخصوصية](#-الأمان-وحماية-الخصوصية)
- [👨‍💻 المطور ومعلومات التواصل](#-المطور-ومعلومات-التواصل)

---

## 🌟 نظرة عامة على المنصة

برنامج **MA TradeLab** هو محطة عمل مكتبية فائقة الأداء لنظام تشغيل ويندوز، صُممت خصيصاً للمتداولين المحترفين ومتداولي حسابات التقييم في شركات التمويل لأسواق العقود الآجلة (الفيوتشرز)، الفوركس، والأسهم.

تجمع المنصة بين **سجل صفقات كمي متطور**، **محرك ذكي لمراقبة التوافق التام مع شروط شركات التمويل لحظياً**، **بوابة قرار صارمة لتقييم الفرص قبل دخول السوق**، **مفكرة اقتصادية فورية مع تنبيهات صوتية مسجلة باستوديو احترافي للعد التنازلي**، **نظام محاسبي متكامل لإدارة أموال التداول والمصاريف الشخصية وصافي الثروة**، و**موصلات محلية مباشرة لربط المنصات بدون وسطاء**—وكل ذلك يعمل محلياً بنسبة 100% بدون أي حاجة للاتصال بسيرفرات سحابية خارجية.

---

## 💎 الأركان والقدرات الأساسية

### 1. سجل الصفقات الذكي والتحليل الإحصائي المتقدم
- **تدوين متعدد الأصول والأسواق**: تسجيل صفقات العقود الآجلة في بورصات CME و NYMEX (عقود NQ, ES, YM, RTY, GC, CL)، وتداول العملات الأجنبية (الفوركس)، والأسهم، مع حساب دقيق لقيمة النقاط، العمولات، والأرباح والخسائر الإجمالية والصافية.
- **مقاييس إحصائية ورياضية متقدمة**:
  - **التوقع الرياضي ونسبة التوقع (Expectancy & Expectancy Ratio)**: لقياس الميزة التنافسية الحقيقية لكل دولار يتم المخاطرة به.
  - **عامل الربح ومعدل الصفقات الرابحة (Profit Factor & Win Rate)**: لتقييم جودة الأداء الفعلي.
  - **متوسط الربح والخسارة وتتبع مضاعف المخاطرة (R-Multiple)**.
  - **تتبع عدد الصفقات الرابحة والخاسرة المتتالية**.
- **أرشفة بصرية متكاملة للشارتات**: إمكانية إرفاق لقطات الشاشة للشارت قبل وبعد الدخول، مع توثيق أسباب الدخول، وتقييم الحالة النفسية والانضباط الذهني.
- **فلترة متقدمة متعددة الأبعاد**: تصفية فورية للصفقات حسب الحساب، الاستراتيجية، جلسة التداول (نيويورك صباحاً ومساءً، لندن، آسيا)، الرمز المالي، الاتجاه (شراء/بيع)، أو النطاق الزمني.

### 2. محرك ذكاء وإدارة حسابات شركات التمويل
- **كتالوج مدمج لأكثر من 50 شركة تمويل عالمية**: إعدادات مسبقة ومحدثة لقواعد شركات التمويل الرائدة مثل Topstep و Apex Trader Funding و Tradeify و MyFundedFutures و FTMO وغيرها.
- **حواجز أمان ومراقبة حية للحدود الحرجة**:
  - **حد الخسارة اليومي (Daily Loss Limit)**: حساب حي وتفاعلي يوضح هامش الأمان المتبقي قبل الوصول للحد الخطر لتفادي فقدان الحساب.
  - **التراجع المتحرك والثابت (Trailing & Static Drawdown)**: تتبع فوري ودقيق بالنسبة لقمة الرصيد المحققة.
  - **حد الخسارة الكلي (Maximum Loss Limit)**: خط أمان بصري واضح لا يمكن تجاوزه.
  - **تتبع الهدف الربحي والاتساق**: شريط تقدم حي نحو إكمال متطلبات التقييم والأهلية للسحب.
- **عزل تام وشامل بين الحسابات**: إدارة حسابات التحديات المتعددة، الحسابات الممولة، والحسابات الحقيقية الشخصية في آن واحد دون أي تداخل في السجلات على مستوى قاعدة البيانات.

### 3. محرك القرار الكمي وإدارة المخاطر قبل التنفيذ
- **قائمة تدقيق موضوعية قبل فتح أي صفقة**: حماية رأس المال من مشاعر الخوف من فوات الفرص (FOMO)، والتداول الانتقامي، والقرارات العاطفية، من خلال إلزام المتداول بفحص شروط الاستراتيجية خطوة بخطوة.
- **شروط مرجحة بأوزان مئوية**: تخصيص شروط استراتيجيتك بأوزان محددة (0 إلى 100%) وتحديد شروط إلزامية قاطعة يمنع التنفيذ تماماً عند فشلها.
- **حساب آلي لحجم العقود والمخاطرة بالدولار**: ما عليك سوى تحديد وقف الخسارة بالنقاط ونسبة المخاطرة المسموحة من الحساب، ليقوم المحرك بحساب حجم العقود المناسب بدقة تامة.
- **توصية نهائية حاسمة**: حكم قاطع ومباشر (**نفّذ / EXECUTE** أو **لا تنفّذ / DO NOT EXECUTE**) بناءً على تجاوز الحد الأدنى للدرجة المطلوبة.

### 4. الإدارة المالية الشاملة للتداول والمصاريف الشخصية
- **دفتر أستاذ متعدد الحسابات المالية**: متابعة الحسابات المصرفية، النقد السائل (الكاش)، رؤوس أموال التداول لدى الوسطاء، ومحافظ العملات المشفرة.
- **نزاهة محاسبية بدفتر القيود المزدوج**: التحويلات الداخلية بين حساباتك (مثل التحويل من البنك إلى حساب الوسيط) معزولة تماماً ولا تحتسب كإيرادات أو مصروفات لتفادي تشويه الأرقام الحقيقية.
- **متتبع اشتراكات وتكاليف التداول المتخصصة**:
  - رصد رسوم بيانات السوق المباشرة (بيانات CME Level 1 / Level 2)، تراخيص برامج التحليل (TradingView, Bookmap, Sierra Chart)، وسيرفرات VPS، ورسوم تحديات التمويل.
  - متابعة استثمارات التعليم، الكورسات، ترقيات أجهزة الكمبيوتر، الشاشات، ووحدات الطاقة البديلة.
- **تنبيهات استباقية لمواعيد تجديد الاشتراكات**: نافذة تنبيه مرنة من 1 إلى 30 يوماً قبل موعد التجديد مع شارات ملونة توضح حالة الاشتراك (مستحق قريباً، مستحق اليوم، متأخر).
- **سجل الأصول والالتزامات**: تتبع الأصول الثابتة والرقمية مقابل الديون والقروض مع حساب فوري لصافي الثروة (Net Worth) ونسبة الالتزامات إلى الأصول.
- **لوحة تحليلات مالية تنفيذية و 5 رسوم بيانية متجهة**:
  1. **التدفق النقدي الشهري**: مقارنة أعمدة الإيرادات مقابل المصروفات.
  2. **مسار نمو صافي الثروة**: منحنى بياني تراكمي لتطور الثروة عبر الزمن.
  3. **توزيع المصروفات**: مخطط نسبي لتصنيفات الإنفاق.
  4. **مؤشرات أداء التداول المالي**: مقارنة أرباح التداول بالتكاليف التشغيلية.
  5. **التقدم في أهداف الادخار**: رصد المبالغ المدخرة شهرياً مقارنة بالأهداف المحددة.
- **تعديل كامل وحذف آمن متسلسل**: إمكانية تعديل كافة تفاصيل الحسابات المالية، وحذف الحسابات بأمان تام مع معالجة متسلسلة للبيانات المرتبطة لتفادي أخطاء قيود قاعدة البيانات.

### 5. المفكرة الاقتصادية الحية والتنبيهات الصوتية الاستوديو
- **تغذية مباشرة للأخبار الاقتصادية الكبرى**: متابعة حية لبيانات التضخم (CPI)، تقارير التوظيف (NFP)، قرارات الفائدة للفيدرالي الأمريكي (FOMC)، الناتج المحلي (GDP)، وإعانات البطالة.
- **تنبيهات صوتية مسجلة باستوديو احترافي**:
  - عد تنازلي بأصوات بشرية حقيقية: قبل 15 دقيقة، 5 دقائق، ودقيقة واحدة من صدور الخبر عالي التأثير.
  - جرس تحذيري عند ثانية صدور الخبر لحماية الصفقات المفتوحة من الانزلاقات السعرية العنيفة.
  - إعلانات صوتية فورية بنتائج الصدور عند نشر الرقم الفعلي في مصدر البيانات.
- **تقويم أخبار T1 وبوابة الأخبار قبل التنفيذ**: مواعيد رسمية من BLS والفيدرالي الأمريكي وEIA بتوقيت نيويورك وبروكسل، ومحرك القرار يمنع الدخول داخل نافذة الخبر عالي التأثير (±2 دقيقة قاعدة شركة التمويل و±5 دقائق هامش أمان).
- **تحكم صوتي كامل وثنائي اللغة**: مسارات صوتية مستقلة بالعربية والإنجليزية مع إمكانية تفعيل أو كتم التنبيه لكل حدث، والتحكم بمستوى الصوت واختبار الأصوات مباشرة.

### 6. الربط المباشر مع منصات التداول
- **ربط فائق السرعة بدون تأخير عبر Localhost**: تواصل مباشر مع المنصات بدون الحاجة لأي وسيط خارجي:
  - **MetaTrader 5 (MT5)**: إكسبيرت بلغة MQL5 على منفذ 18082 لمزامنة الصفقات فورياً.
  - **NinjaTrader 8 (NT8)**: إضافة أصلية بلغة C# على منفذ 18080 لتدوين صفقات العقود الآجلة لحظياً.
  - **منصة ATAS**: موصل استراتيجي مدمج على منفذ 18081 لتدوين صفقات تدفق الأوامر (Order Flow).

### 7. محول مستويات الجاما المؤسسية
- **تكامل متقدم مع مستويات الجاما لعقود الخيارات**: قراءة وتحويل تمركزات الجاما وحوائط الشراء والبيع (Call/Put Walls) من MenthorQ إلى صيغ قياسية مثل (`$NQ1!`, `$ES1!`, `$QQQ`, `$SPY`).
- **تصدير فوري لمنصة DeepCharts**: إنشاء ملفات JSON مهيكلة وجاهزة للاستيراد المباشر في منصة DeepCharts لدراسة هياكل السوق المؤسسية.

### 8. راديو المتداول المباشر ومحطة التركيز الذهني
- **صوتيات مدمجة للحفاظ على الهدوء والتركيز**: قنوات بث مباشر للأخبار الاقتصادية، تلاوة القرآن الكريم، ومحطات صوتية مخصصة للتركيز الذهني (Lo-Fi, Ambient, Chillout) للحفاظ على التوازن النفسي أثناء الجلسات الحساسة.

---

## 🛠️ المواصفات الفنية للبرنامج

| البند الفني | التفاصيل التقنية |
|---|---|
| **اسم البرنامج** | **MA TradeLab** |
| **الإصدار الحالي** | **v2.5.2 (الإصدار الرسمي المستقر)** |
| **نظام التشغيل المدعوم** | Windows 10 / Windows 11 (معمارية 64-bit) |
| **بيئة التشغيل** | .NET 8.0 Desktop Runtime (مدمجة بالكامل Self-Contained) |
| **لغة البرمجة والمعمارية** | C# 12 / WPF بمعمارية Clean Architecture ونمط MVVM |
| **محرك قاعدة البيانات** | SQLite مدمجة مع EF Core ومعاملات ACID الآمنة |
| **خيارات الحزم** | مثبت برامجي مستقل (~161 ميجابايت) وحزمة محمولة Portable (~91 ميجابايت)، مع بصمات SHA-256 في صفحة الإصدار |
| **واجهة المستخدم** | واجهة ثنائية اللغة بالكامل (عربي وإنجليزي مع تبديل فوري لاتجاه الواجهة RTL / LTR) |
| **التصميم والسمة البصرية** | نمط Cyberpunk داكن عالي التباين بلمسات ذهبية احترافية |
| **حماية البيانات** | **تخزين محلي 100%** (خالٍ تماماً من التتبع أو التزامن السحابي) |

---

## 📦 روابط التحميل والتثبيت السريع

### الحزم الرسمية المتاحة للإصدار v2.5.2:

| اسم الحزمة | الحجم التقريبي | الوصف وطريقة الاستخدام | رابط التحميل المباشر |
|---|---|---|---|
| **`MATradeLab_Setup.exe`** | **~161 ميجابايت** | **المثبت الرسمي الموصى به**: مثبت تلقائي مستقل بالكامل، يقوم بإعداد البرنامج وإنشاء أيقونات سطح المكتب وقائمة البداية. | [📥 تحميل مثبت الإعداد (Setup)](https://github.com/m4whw/MATradelab/releases/download/v2.5.2/MATradeLab_Setup.exe) |
| **`MA_TradeLab_v2.5.2_Portable.zip`** | **~91 ميجابايت** | **الحزمة المحمولة (Portable)**: قم بفك الضغط في أي مجلد أو فلاشة USB وشغّل البرنامج مباشرة مع حفظ بياناتك محلياً. | [📥 تحميل الحزمة المحمولة (ZIP)](https://github.com/m4whw/MATradelab/releases/download/v2.5.2/MA_TradeLab_v2.5.2_Portable.zip) |

### خطوات التثبيت:
1. حمّل ملف `MATradeLab_Setup.exe` من الجدول أعلاه.
2. شغّل برنامج التثبيت واختر مسار التثبيت المطلوب على جهازك.
3. افتح البرنامج، واختر لغتك المفضلة (العربية أو الإنجليزية)، وابدأ في تدوين صفقاتك وإدارة حساباتك فوراً.

> **ملاحظة هامة**: البرنامج مستقل بذاته بالكامل، ولا يحتاج إلى تثبيت مسبق لحزمة .NET Runtime أو أي برمجيات إضافية على جهازك.

---

## 🔒 الأمان وحماية الخصوصية

- **غياب تام للخوادم السحابية**: جميع صفقاتك، وأرقام حساباتك، وبيانات استراتيجياتك، وصور شارتاتك، وأرصدتك المالية مخزنة حصرياً على القرص الصلب لجهازك الخاص.
- **حماية بيانات الدخول**: تشفير مفاتيح API والإعدادات الحساسة باستخدام Windows Data Protection API (DPAPI).
- **موصلات محلية فقط**: منافذ موصلات MT5 وNinjaTrader 8 وATAS تقبل الاتصال من جهازك فقط وترفض أي طلب من المتصفح أو الشبكة.

---

## 👨‍💻 المطور ومعلومات التواصل

**محمد عبد العزيز (Mohamed Abdelaziz)**  
*مهندس برمجيات ومتداول كمي منهجي*  
- **الموقع الرسمي**: [https://mohamed-abdelaziz.com](https://mohamed-abdelaziz.com)  
- **حساب جيت هب**: [@m4whw](https://github.com/m4whw)  
- **صفحة المشروع**: [https://github.com/m4whw/MATradelab](https://github.com/m4whw/MATradelab)

