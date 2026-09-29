# ZenithPulse Analytics™ 📈⚡
### Institutional-Grade Technical Analysis & Interactive Trading Terminal

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Compliance: SEBI Aligned](https://img.shields.io/badge/Compliance-SEBI%20Compliant-green.svg)](https://sebi.gov.in)
[![Data Protection: DPDP Act 2023](https://img.shields.io/badge/Privacy-DPDP%20Act%202023-blue.svg)](https://meity.gov.in)
[![Technology: Vanilla JS & TradingView](https://img.shields.io/badge/Tech-Vanilla%20JS%20%7C%20TradingView%20LWC-orange.svg)](https://tradingview.github.io/lightweight-charts/)

> **Live Platform URL**: Hosted on GitHub Pages (Access instantly in any web browser with zero installation).

---

## 🌟 What's New in this Version

1. **One-Line Quick Market Rail (Side/Top Quick Switcher)**:
   - Category filters: `[🔥 All] [🇮🇳 Indian Stocks] [📊 Indices] [🛢️ Commodities] [💱 Forex] [🪙 Crypto]`.
   - Continuous one-line scrolling ticker rail with live prices and % change chips. Switch any market with a single click.

2. **Expanded Multi-Asset Universe & Commodities**:
   - **MCX Commodities**: **NATURAL GAS** (`NATURALGAS`), **CRUDE OIL** (`CRUDEOIL`), **GOLD 10g** (`GOLD`), **SILVER 1kg** (`SILVER`), **COPPER** (`COPPER`).
   - **Indian Equities (NSE)**: RELIANCE, TCS, INFY, HDFCBANK, ICICIBANK, TATAMOTORS, SBIN, BAJFINANCE, ADANIENT, ITC, LT.
   - **Indian Benchmark Indices**: NIFTY 50, BANK NIFTY, FINNIFTY, SENSEX.
   - **Forex (FX)**: USD/INR, EUR/INR, GBP/INR, EUR/USD, GBP/USD, USD/JPY.
   - **Cryptocurrencies**: BTC/USDT, ETH/USDT, SOL/USDT, BNB/USDT, XRP/USDT.

3. **Ultra-Clear High-Definition Charting View**:
   - Fullscreen mode toggle (`[ ⛶ ]`) for edge-to-edge monitor analysis.
   - Candlestick / Line / Mountain Area switcher.
   - Interactive Zoom In (`+`), Zoom Out (`-`), and Reset Scale (`⟲`).
   - Multi-indicator overlays: EMA 9, 21, 50, 200, Bollinger Bands, Supertrend, VWAP, Auto S/R, RSI (14), MACD.

4. **Direct Interactive Trading on Website**:
   - **🎮 Simulated Paper Trading Engine**:
     - Starting balance: **₹10,00,000.00** virtual capital.
     - Buy (Long) / Sell (Short) order ticket with Market/Limit, Stop-Loss (₹), Target (₹), and auto Risk:Reward calculator.
     - Real-time Unrealized P&L updates as simulated prices tick every 3 seconds!
     - 1-Click "Close Position" button to lock in realized profits/losses into account capital.
     - Completed trade log with historical return % and net P&L.
     - Web Audio API execution chimes on orders.
   - **🚀 1-Click Live Broker Execution Gateway**:
     - Direct pre-filled order pad launchers for **Zerodha Kite**, **Angel One**, **Upstox Pro**, **Dhan Web**, and **Groww**.

---

## ⚖️ Regulatory Compliance & Operational Modes

ZenithPulse features a built-in compliance architecture driven by a top-level configuration:

```javascript
let COMPLIANCE_MODE = "EDUCATIONAL"; // Options: "EDUCATIONAL" (Default) | "SEBI_REGISTERED"
```

### 1. `EDUCATIONAL` Mode (Default)
- **Header Badge**: `[EDUCATIONAL MODE] Non-Advisory Research Platform`
- **Signal Markers**: Labeled strictly as **"Bullish Setup"** / **"Bearish Setup"** (Never "BUY" or "SELL").
- **Statutory Footnote**: Discloses that all tools and simulated paper trading are for educational/informational purposes and the platform is not registered as an Investment Adviser or Research Analyst with SEBI.
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

## 🔒 India DPDP Act 2023 & Privacy Controls

- **Zero Data Harvesting**: No collection of user broker portfolio holdings, bank accounts, or financial credentials.
- **Client-Side Privacy**: Watchlists, journals, and simulated trading accounts remain 100% in local browser storage (`localStorage`).
- **Right to Erasure**: Includes an instant "Erase All Local Data" button under Section 12 of the DPDP Act.
- **Grievance Redressal**: Includes Designated Compliance Officer details, Bandra Kurla Complex (BKC) Mumbai registered address, and direct links to the official **SEBI SCORES** portal (`scores.sebi.gov.in`).

---

## 🔄 How to Update Your Live GitHub Website

To make these new changes live on your GitHub Pages website:

1. Open your repository on GitHub in your web browser:
   `https://github.com/<your-username>/<your-repo-name>`
2. Click **Add file** ➔ **Upload files**.
3. Drag and drop the updated [`index.html`](./index.html) and [`README.md`](./README.md) from `c:\vrunda\trading\`.
4. Click **Commit changes**.
5. Within 1–2 minutes, GitHub Pages will automatically refresh and your live site will feature the new clear charts, commodities, one-line market rail, and interactive trading terminal!

---

## 💳 Pro Software Subscriptions & Contact
To activate **ZenithPulse Pro™** software tools:
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
