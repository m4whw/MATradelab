# MA TradeLab — Getting Started Guide

[English](getting-started.md) | [العربية](../ar/getting-started.md)

---

## Welcome to MA TradeLab

**MA TradeLab** is engineered from the ground up to streamline professional trade journaling, prop firm risk compliance, pre-trade quantitative gating, and real-time news intelligence in a unified, 100% local Windows desktop workstation.

This guide walks you through initial configuration, account creation, seamless MT5 historical report imports, and live platform connector setups.

---

## 1. First Launch & Interface Localization

Upon starting MA TradeLab for the first time, you are greeted with the main command center.

### Real-Time Bilingual Toggle
In the top-left corner of the title bar, toggle between **English (EN GB)** and **Arabic (SA العربية)** at any time:
- The entire application interface immediately adapts in real time.
- All forms, tooltips, chart indicators, analytical summaries, and news feeds reflect the chosen language with proper Left-to-Right (LTR) or Right-to-Left (RTL) typography.

---

## 2. Managing Trading & Prop Firm Accounts

Before logging or importing trades, ensure you have set up your trading account profiles:

1. Navigate to **Prop Firms / Accounts** from the left navigation drawer.
2. Click **Create New Account**.
3. Configure the account properties:
   - **Account Identifier / Name**: e.g., `Topstep 50k Express`, `FTMO Swing Master`, or `Interactive Brokers Main`.
   - **Market Type**: Select between **Futures**, **Forex**, **Equities**, or **Crypto**.
   - **Account Category**: Select **Prop Firm Evaluation**, **Prop Firm Funded / Performance**, **Personal Cash**, or **Personal Margin**.
   - **Starting Capital & Currency**: Specify initial balance (e.g., `$50,000 USD`).
   - **Prop Rules Configuration**: Set the Daily Loss Limit (DLL), Maximum Trailing Drawdown, High-Water Mark trailing type (EOD or Intra-day), and Maximum Contract Allocation.
4. Save the profile. MA TradeLab's **Prop Firm Intelligence Engine (PFIE)** will continuously monitor all trade executions against these parameters.

---

## 3. MT5 1-Click Historical Report Import (New in v2.5.4)

MA TradeLab v2.5.4 introduces an automatic MT5 trade-import engine that does not require an active MT5 connection, EA, or WebRequest. You can import years of historical trades directly from an MT5 report in seconds.

### Step-by-Step Export from MetaTrader 5:
1. Open your **MetaTrader 5** terminal.
2. In the bottom **Toolbox** window, switch to the **History** tab.
3. Right-click anywhere in the trade history area.
4. Set the desired date range (e.g., **All History** or **Last 3 Months**).
5. Right-click again, hover over **Report**, and select **HTML (Internet Explorer)** or **Open XML (MS Office Excel)**.
6. Save the file to your desktop (e.g., `ReportHistory-12345678.html`).

### Step-by-Step Import into MA TradeLab:
1. In MA TradeLab, open the left navigation menu and select **Import / Export → MT5 Synchronization**.
2. Click the prominent gold button: **Import MT5 History** (`استيراد سجل MT5`).
3. Select your saved MT5 HTML or CSV report file.
4. **Automated Processing**:
   - **Account Auto-Provisioning**: The parser extracts the Account Login, Broker Name, Server, and Currency from the header. If the account does not exist in your database, MA TradeLab automatically provisions it for you.
   - **Incremental Import & Duplicate Prevention**: The engine inspects every Position ID, Order ID, and Deal Ticket against existing records in SQLite. Only genuinely new trades are imported, while existing trades are safely preserved without duplication.
   - **Comprehensive Field Extraction**: Accurately imports entry/exit timestamps, ticket numbers, volumes, prices, stop loss, take profit, gross profit, commissions, swaps, and net P&L.
5. A detailed summary dialog will display the total trades found, newly imported count, and skipped duplicates.

---

## 4. Live MetaTrader 5 (MT5) Real-Time Connector

For live real-time sync of executions, open positions, and account balances:

1. Navigate to **Import / Export → MT5 Synchronization**.
2. Click **Install Connector** (`تثبيت الموصل`):
   - MA TradeLab automatically scans all MetaTrader 5 installations on your computer and copies the pre-compiled `MATradeLabConnector.mq5` into each terminal's `MQL5\Experts\` directory.
3. In **MetaTrader 5**:
   - Go to **Tools** → **Options** (`Ctrl + O`) → **Expert Advisors** tab.
   - Check **Allow algorithmic trading**.
   - Check **Allow WebRequest for listed URL** and add the local loopback URL:
     ```text
     http://127.0.0.1:18082
     ```
   - Click **OK**.
4. Open the **Navigator** panel in MT5 (`Ctrl + N`), expand **Expert Advisors**, and drag `MATradeLabConnector` onto any open chart. Ensure **Allow Algo Trading** is checked in the EA inputs.
5. In MA TradeLab, click **Start Connection / Connect** (`اتصال / قطع الاتصال`). The status indicator will turn vibrant green (**Connected**), showing real-time balance and incoming trade executions with zero latency.

---

## 5. NinjaTrader 8 & ATAS Connectors

### NinjaTrader 8 Integration
- In the top-left account selector or Import/Export module, select **NinjaTrader 8**.
- MA TradeLab monitors NinjaTrader execution feeds and exported execution logs in real time, synchronizing contract sizes (NQ, ES, YM, GC, CL), commissions, and execution timestamps.

### ATAS Integration
- Select **ATAS** from the connector list.
- Connect directly to the local ATAS platform instance to capture high-precision futures executions with order flow context.

---

## Next Steps

- Explore [Features & Capabilities](features.md) to learn how to master the Pre-Trade Gate and statistical analytics.
- Review [Changelog & Version History](changelog.md) for full release notes.
