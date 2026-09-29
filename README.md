# ZenithPulse Analytics™ 📈
### Institutional-Grade Technical Analysis & Market Research Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Compliance: SEBI Aligned](https://img.shields.io/badge/Compliance-SEBI%20Compliant-green.svg)](https://sebi.gov.in)
[![Data Protection: DPDP Act 2023](https://img.shields.io/badge/Privacy-DPDP%20Act%202023-blue.svg)](https://meity.gov.in)
[![Technology: Vanilla JS & TradingView](https://img.shields.io/badge/Tech-Vanilla%20JS%20%7C%20TradingView%20LWC-orange.svg)](https://tradingview.github.io/lightweight-charts/)

> **Live Platform URL**: Hosted on GitHub Pages (Access instantly in any web browser with zero installation).

---

## 🌟 Overview

**ZenithPulse Analytics™** is a institutional-grade, single-page algorithmic technical analysis web application built using HTML5, CSS3, and vanilla JavaScript without any external build tools or bundlers. 

It provides retail and institutional market researchers with real-time candlestick pattern recognition, multi-timeframe synchronization, strategy backtesting, and quantitative risk calculators, while strictly adhering to **SEBI (Securities and Exchange Board of India)** regulations and India's **Digital Personal Data Protection (DPDP) Act 2023**.

---

## ⚖️ Regulatory Compliance & Operational Modes

ZenithPulse features a built-in compliance architecture driven by a top-level configuration:

```javascript
let COMPLIANCE_MODE = "EDUCATIONAL"; // Options: "EDUCATIONAL" (Default) | "SEBI_REGISTERED"
```

### 1. `EDUCATIONAL` Mode (Default)
- **Header Badge**: `[EDUCATIONAL MODE] Non-Advisory Research Platform`
- **Signal Markers**: Labeled strictly as **"Bullish Setup"** / **"Bearish Setup"** (Never "BUY" or "SELL").
- **Statutory Footnote**: Clearly discloses that all tools are for educational/informational purposes and the platform is not registered as an Investment Adviser or Research Analyst with SEBI.
- **Signal Strength Panel**: Multi-segment visual meter (-10 to +10) with indicator checklist. Strictly does **not** show any "confidence %" or "accuracy %" that implies certainty or guaranteed returns.
- **Illustrative Technical Levels**: Labeled *"Illustrative technical levels, not a recommendation. For educational chart reading only."*

### 2. `SEBI_REGISTERED` Mode
- Displays verified SEBI Intermediary details in the top header and statutory footer:
  - **Category**: Research Analyst
  - **SEBI Reg. No.**: `INH000012345`
  - **Validity**: `15-Mar-2024 to 14-Mar-2029`
- Includes the mandatory statutory disclaimer:
  > *"Registration granted by SEBI and certification from NISM in no way guarantee performance of the intermediary or provide any assurance of returns to investors."*

---

## 📊 Core Features

1. **Interactive Candlestick Chart**:
   - Powered by **TradingView Lightweight Charts v4.1.1** via CDN.
   - Smooth pan, zoom, crosshair tracking, and timeframes: `1m`, `5m`, `15m`, `1h`, `4h`, `1D`, `1W`.
2. **Multi-Asset Symbol Universe**:
   - **NSE / BSE Equities**: RELIANCE, TCS, INFY, HDFCBANK, TATAMOTORS, SBIN, ITC, LT.
   - **Indian Indices**: NIFTY 50, BANK NIFTY, FIN NIFTY, SENSEX.
   - **Cryptocurrencies**: BTC/USDT, ETH/USDT, SOL/USDT.
   - **Forex**: USD/INR, EUR/USD, GBP/INR.
   - Public feeds & synthetic tick generator without scraping exchange websites.
3. **Candlestick Pattern Recognition Engine**:
   - Automated mathematical detection for **Doji, Hammer, Shooting Star, Bullish Engulfing, Bearish Engulfing, Morning Star, Evening Star, Three White Soldiers, and Three Black Crows**.
4. **Technical Indicators**:
   - Exponential Moving Averages (EMA 9, 21, 50, 200)
   - Wilder's Relative Strength Index (RSI 14) with 30/70 boundary zones
   - MACD (12, 26, 9) with momentum histogram
   - Bollinger Bands (20, 2)
   - Supertrend (10, 3.0) ATR-based trailing trend stops
   - Session Volume Weighted Average Price (VWAP)
   - Auto-detected Support & Resistance horizontal price lines ($R_2, R_1, \text{Pivot}, S_1, S_2$)

---

## ⚡ Institutional Pro Suite

- **Multi-Timeframe Analysis**: Tri-chart matrix (1D Macro, 1H Intermediate, 15m Micro) for cross-timeframe alignment.
- **Strategy Backtesting Engine**:
  - Quantitative models: EMA 9/21 Trend, Supertrend Following, RSI Reversion.
  - Metrics: Win Rate %, Hypothetical P/L (₹ and %), Max Drawdown %, Profit Factor.
  - Interactive Canvas Equity Curve and CSV trade log export.
  - **Statutory Notice**: *"Backtested and past performance is hypothetical, does not reflect real trading, and is not indicative of future results. Assumptions: Zero slippage, zero brokerage."*
- **Mathematical Position Size Calculator**: Computes risk amount, risk per share, permissible quantity, and exposure without financial advice.
- **Technical Market Screener**: Live filtering of 14+ assets across asset classes.
- **Trade Study Journal**: 100% private client-side study log with CSV export.
- **High-Res PNG Export**: Instant chart capture via native canvas renderer.

---

## 🔒 India DPDP Act 2023 & SEBI Compliance

- **Zero Data Harvesting**: No collection of user broker portfolio holdings, bank accounts, or financial credentials.
- **Client-Side Privacy**: Watchlists, journals, and theme settings remain 100% in local browser storage (`localStorage`).
- **Right to Erasure**: Includes an instant "Erase All Local Data" button under Section 12 of the DPDP Act.
- **Grievance Redressal**: Includes Designated Compliance Officer details, Bandra Kurla Complex (BKC) Mumbai registered address, 48-hour acknowledgment SLA, and direct links to the official **SEBI SCORES** portal (`scores.sebi.gov.in`).

---

## 🚀 How to Run Locally

Since this is a zero-dependency single-page application, no Node.js or build tools are required:

1. **Direct Browser**:
   Double click [`index.html`](./index.html) or open:
   ```text
   file:///path/to/index.html
   ```

2. **PowerShell**:
   ```powershell
   Start-Process "index.html"
   ```

3. **Live Server / Python HTTP**:
   ```bash
   python -m http.server 8080
   ```

---

## 💳 Pro Software Subscriptions & Contact
To activate **ZenithPulse Pro™** software tools or inquire about institutional licensing:
* **Monthly Access**: ₹199 / month
* **Annual Pro (Best Value)**: ₹1,499 / year *(equivalent to ₹125/month)*
* **Lifetime License**: ₹3,499 one-time
* **WhatsApp / Phone Support**: [+91 9769179580](https://wa.me/919769179580)
* **Direct UPI ID**: `9769179580@upi`
* **Email**: `compliance@zenithpulse.example`
* **Compliance Officer**: Vrunda Mehta (Head of Regulatory Compliance)

---

## 📜 License
Distributed under the MIT License. Copyright © 2026 Zenith Capital Research & Analytics LLP.
