# MA TradeLab — Features & Architectural Capabilities

[English](features.md) | [العربية](../ar/features.md)

---

## Technical Architecture Overview

**MA TradeLab** combines quantitative financial analytics, algorithmic prop risk compliance, and desktop execution ergonomics into a unified workstation. Built on **.NET 8 WPF** with hardware-accelerated rendering and a local **SQLite** database, MA TradeLab provides microsecond data retrieval with complete privacy and offline resilience.

---

## 1. Smart Trading Journal & Statistical Analytics

A world-class analytical journal engineered to eliminate cognitive bias and highlight your true mathematical edge.

### Core Analytical Capabilities:
- **Comprehensive Multi-Asset Coverage**: Native calculation models for CME/NYMEX Futures (NQ, ES, YM, RTY, GC, CL), Spot Forex pairs, Global Equities, and Cryptocurrencies.
- **Mathematical Expectancy & Edge Factor**:
  - Automatically calculates Expectancy:
    $$\text{Expectancy} = (\text{Win Rate} \times \text{Avg Win}) - (\text{Loss Rate} \times \text{Avg Loss})$$
  - Computes Expectancy Ratio and Profit Factor in real time.
- **R-Multiple & Normalized Risk Tracking**: Evaluate trades based on risk taken ($1R, 2R, 3R$) rather than raw dollars, ensuring consistent performance measurement across account sizes.
- **Trade Execution Attributes**:
  - Detailed tracking of entry/exit timestamps, ticket numbers, slippage, gross profit, commissions, swaps, and net realized P&L.
- **Visual Chart Archiving**:
  - Attach multiple high-resolution chart screenshots (higher timeframe context, execution timeframe, and post-trade outcome).
  - Categorize by setup type, strategy, session (London, New York AM/PM, Asia), and execution mistake tags (e.g., FOMO, early exit, revenge trading).

---

## 2. Prop Firm Intelligence Engine (PFIE)

Designed specifically for traders working with proprietary trading firms (Topstep, Apex Trader Funding, Tradeify, MyFundedFutures, FTMO, Fast Track Trading).

### Risk Guard Features:
- **Dynamic Trailing Drawdown Engine**:
  - Supports both **Intra-Day Trailing** (tick-by-tick peak balance) and **End-of-Day (EOD) Trailing** rules.
  - Automatically freezes the trailing threshold when the account reaches its designated funded lock-in level.
- **Daily Loss Limit (DLL) Guardian**:
  - Tracks open unrealized and closed realized losses against the firm's strict daily thresholds.
  - Visual color-coded warning banners when within 20% of the daily limit.
- **Contract Scaling & Consistency Evaluator**:
  - Calculates maximum allowed contracts based on current account equity tiers.
  - Validates consistency percentages (e.g., no single day exceeding 30% of total profits).
- **Buffer & Payout Planner**:
  - Computes the exact risk buffer available before a drawdown breach.
  - Calculates eligible payout amounts based on firm profit-split terms and minimum trading day requirements.

---

## 3. Pre-Trade Decision Engine & Risk Gatekeeper

Trading discipline cannot rely on emotional willpower alone. The Pre-Trade Gate acts as a rigorous cognitive firewall between your trading idea and order execution.

### Cognitive & Quantitative Gates:
- **Mandatory Pre-Flight Checklist**:
  - Validates technical setup criteria, market condition alignment, and emotional discipline rating before allowing trade clearance.
- **Automated Position Sizing Calculator**:
  - Calculates exact contract / lot sizing based on account balance, stop-loss distance in ticks/pips, and defined dollar risk budget.
- **Risk-to-Reward (R:R) Enforcement**:
  - Automatically verifies whether the anticipated reward meets your minimum defined threshold (e.g., minimum 2.0 R:R). Sub-par risk setups are flagged immediately.
- **Economic News Blackout Interlock**:
  - Automatically alerts and locks trade clearance within customizable buffer windows (e.g., 5 or 10 minutes) before and after High-Impact macro events.

---

## 4. Personal & Trading Financial Management

A complete personal finance and capital allocation system built directly inside your trading terminal.

### Key Financial Tools:
- **Unified Net Worth Dashboard**: Aggregate trading account balances, prop firm funded accounts, bank reserves, and investment portfolios in a single consolidated view.
- **Monthly Profit & Loss Ledger**: Comprehensive historical calendar showing daily, weekly, and monthly net trading returns alongside personal income and living expenses.
- **Prop Firm Payout Ledger**: Track evaluation fees paid, reset expenses, and gross/net payouts received, calculating your true Lifetime Prop ROI.
- **Tax Reserve & Capital Withdrawal Planner**: Automatically calculate recommended tax withholdings based on trading profits and schedule regular personal dividend distributions.

---

## 5. Economic Calendar & Studio Audio Alerts

Never get caught in an unexpected macroeconomic volatility spike.

### Features:
- **Live Macroeconomic Feed**: Tracks Tier-1 global economic releases (CPI, Core PCE, Non-Farm Payrolls, FOMC Decisions, GDP, PMI, Treasury Auctions) across the US, Eurozone, UK, Japan, Australia, and Canada.
- **Studio-Quality Voice Alerts**: Crisp, human-recorded voice announcements alerting you 15 minutes, 5 minutes, and 1 minute before high-impact economic releases.
- **Impact Filtering & Country Selector**: Filter by currency and volatility tier (High, Medium, Low) to keep focus only on relevant market movers.
- **Audio Focus Modes**: One-click mute or auto-suppress audio during active execution windows.

---

## 6. DeepCharts & MenthorQ Gamma Converter

Quantitative options market makers' positioning dictates liquidity levels and pin points in index futures (NQ, ES).

### Gamma Architecture:
- **Options Gamma Exposure Parsing**: Import and parse market maker gamma levels (Call Resistance, Put Support, High Gamma Strike, Net Zero Gamma).
- **Automated Price Level Mapping**: Converts complex option positioning matrices into clean price levels ready for charting and execution levels.

---

## 7. Live Trading Radio & Ambient Focus Station

Psychological composure and flow state are essential for high-performance execution.

### Station Highlights:
- **Curated Ambient & Lo-Fi Soundscapes**: Integrated desktop audio player delivering high-fidelity lo-fi beats, synthwave, and alpha-wave ambient frequencies engineered to reduce cortisol and sustain focus during long trading sessions.
- **Zero Resource Footprint**: Background audio streaming with zero impact on CPU or order execution performance.
- **Quick Controls**: Convenient volume controls and track playback toggles integrated directly into the top application bar.
