# 🌐 Forex Ai Analyst

[![Platform](https://img.shields.io/badge/Platform-Windows%20x64%20(Desktop%20EXE)-0078D6?style=flat-square&logo=windows&logoColor=white)](https://github.com/SamDesantos/)
[![Status](https://img.shields.io/badge/Release-v1.0.0%20Stable-10B981?style=flat-square)](https://github.com/SamDesantos/)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

An institutional-grade desktop due diligence terminal built for discretionary currency traders, macro fund managers, and prop firm desks. 

Instead of relying on retail indicators and surface-level noise, **Forex Ai Analyst** executes a structured **5-Layer Due Diligence Framework** that synthesizes central bank policy, sovereign yields, institutional CFTC COT positioning, retail sentiment crowd traps, and Smart Money order blocks into actionable execution plans.

---

## 🏛️ What Makes It Different?

Retail software typically focuses on lagging oscillators and single-timeframe charts. This terminal approaches currency and asset pricing from an **intermarket macro perspective**:

* **Top-Down Macro Discipline:** Evaluates rate differentials, sovereign 10-year yield spreads, and US Dollar Index (DXY) tailwinds.
* **Smart Money vs. Retail Crowds:** Contrasts commercial institutional positioning from the CFTC COT report against retail trader positioning to identify liquidity pool targets and squeeze risks.
* **Tri-Modal Scenario Playbooks:** Automatically formats every trade setup into probabilistic *Bullish Extension*, *Consolidation Chop*, and *Bearish Breakdown* regimes with strict invalidation levels.
---

## ⚡ Core Capabilities

### 1. 5-Layer Institutional Analytical Framework
Every asset profile undergoes a comprehensive 5-phase research evaluation:

* **Layer 1: Central Bank Policy & Macro Wind:** Federal Reserve vs. global central bank policy divergence, real vs. nominal rate spreads, and DXY macro pressure.
* **Layer 2: Asset Fundamentals & Session Liquidity:** Session overlaps (London/NY/Tokyo), ATR expectancy, terms-of-trade commodity exposure, and overnight swap yield dynamics.
* **Layer 3: Market Microstructure & Positioning:**
  * **CFTC Commitment of Traders (COT):** Non-commercial speculative positioning vs. institutional commercial hedger shifts.
  * **Contrarian Retail Sentiment:** Live long/short crowd sentiment gauge to locate liquidity hunts.
* **Layer 4: Technical Structure & Key Order Blocks:**
  * Automated detection of **Immediate Support**, **Major Floor**, **Primary Resistance**, and **Breakout Targets**.
  * Fair Value Gaps (FVG) and premium/discount valuation zones.
* **Layer 5: Intermarket & Cross-Asset Alignment:** Cross-asset matrix evaluating correlation strengths across DXY, S&P 500, US 10Y Yields, and Crude Oil.

---

### 2. Multi-Market Asset Universe
* **G10 & FX Crosses:** EUR/USD, GBP/USD, USD/JPY, AUD/USD, USD/CAD, USD/CHF, NZD/USD, EUR/GBP, GBP/JPY, EUR/JPY, and more.
* **Precious Metals & Energy:** Gold (XAU/USD), Silver (XAG/USD), WTI Crude Oil, and Brent.
* **Equities & Sovereign Benchmarks:** S&P 500, Nasdaq 100, Dow Jones, DAX 40, FTSE 100, Nikkei 225, and US 10Y Treasury Yield.
* **Digital Liquidity Bellwethers:** Bitcoin (BTC/USD), Ethereum (ETH/USD), and major crypto crosses.

---

### 3. Integrated Price-Level Alert System
* **Directional Threshold Monitoring:** Arm instant *Crosses Above* ($\ge$) or *Drops Below* ($\le$) threshold alerts on any pair.
* **Institutional Level Snapping:** Snap target price alerts directly to institutional support blocks, weekly liquidity floors, or primary resistance levels.
* **Synthesized Dual-Tone Audio Chime:** Low-latency acoustic chime generated on-the-fly via the Web Audio API without external audio file dependencies.
* **Floating Real-Time Visual Toasts:** Real-time alert notifications displaying exact pip breach distance, with immediate 1-click **Re-Arm** and **Inspect Asset** actions.
* **Persistent Alerts Drawer:** Manage, mute, re-arm, and clear active and historical triggers.

---

### 4. Institutional PDF Research Dossier Generator
* One-click export of complete multi-layer due diligence dossiers into high-resolution, print-ready formal PDF research reports.
* Includes executive summaries, directional conviction ratings, probability matrices, and concrete invalidation guidelines.

---

## 🎯 Target Audience

* **Discretionary Macro & FX Traders:** Building multi-day swing positions with fundamental and structural confluence.
* **Prop Firm Traders:** Requiring structured trade rationales, calculated invalidation levels, and strict risk parameters.
* **Asset Allocators & Analysts:** Generating institutional research briefings on currency pairs, commodities, and rate differentials.

---

## 📸 Screenshots

### Dashboard

![Dashboard](screenshots/dashboard.png)

### Reports

![Reports](screenshots/reports.png)

---

## 🔒 Privacy & Local State

* **No Mandatory Cloud Accounts:** Your custom alerts, saved reports, and watchlists are stored directly in your local desktop environment.
* **High Performance & Low Resource Footprint:** Native Rust runtime ensures instant startup, low memory usage, and smooth rendering.

---

## ⚖️ Disclaimer

*Forex Analyst Desk is a market research and analytical workstation intended for educational, informational, and analytical purposes only. Foreign exchange, futures, and leveraged CFD trading involve substantial risk of loss and are not suitable for every investor. Nothing contained in this terminal constitutes financial, investment, or trading advice.*
