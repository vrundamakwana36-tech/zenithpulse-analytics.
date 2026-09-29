# ZenithPulse Analytics™ 📈⚡
### Institutional-Grade Big Screen Technical Analysis & Interactive Trading Terminal

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Compliance: SEBI Aligned](https://img.shields.io/badge/Compliance-SEBI%20Compliant-green.svg)](https://sebi.gov.in)
[![Data Protection: DPDP Act 2023](https://img.shields.io/badge/Privacy-DPDP%20Act%202023-blue.svg)](https://meity.gov.in)
[![Technology: Vanilla JS & TradingView](https://img.shields.io/badge/Tech-Vanilla%20JS%20%7C%20TradingView%20LWC-orange.svg)](https://tradingview.github.io/lightweight-charts/)

> **Live Platform URL**: Hosted on GitHub Pages (Access instantly in any web browser with zero installation).

---

## 🌟 What's New in this Version

### 1. 🖥️ Permanent Big Screen Candlestick Chart on Main Page
- The main viewport is **permanently dedicated to the Big Screen Candlestick Chart**.
- It is never hidden or replaced when accessing other tools.
- Supports Fullscreen view (`[ ⛶ ]`), zoom controls (`+`, `-`, `⟲ Reset`), and style switching (`Candles`, `Line`, `Area`).

### 2. 🗂️ Closable Left Side Tool Drawer (Screener & Study Journal)
- **Automated Technical Market Screener** and **Trade Observation & Study Journal** are now docked in a sleek **slide-out Left Drawer Panel** directly next to the left sidebar icons:
  - **Open with 1-Click**: Click the Screener or Journal icon on the left to slide open the panel.
  - **Easy `✕ Close Panel` Button**: Prominent close button in the drawer header (or press `ESC` on your keyboard, or click the icon again) to slide it away immediately.
  - **Live Multi-Tasking**: While the screener or journal is open on the left, the **Big Screen Chart remains 100% visible and interactive**! Clicking any stock row in the screener loads that chart instantly without losing your screener place!

### 3. 🇮🇳 45+ Official Indian Shares & MCX Commodities
Expanded the symbol universe to match top traded instruments on official Indian broker platforms (Zerodha Kite, Angel One, Groww, Upstox, NSE):
- **45+ Indian Bluechips & Momentum Shares**:
  - `RELIANCE`, `TCS`, `HDFCBANK`, `BHARTIARTL`, `ICICIBANK`, `INFY`, `SBIN`, `HINDUNILVR`, `ITC`, `LT`
  - `BAJFINANCE`, `TATAMOTORS`, `KOTAKBANK`, `AXISBANK`, `ADANIENT`, `ADANIPORTS`, `MARUTI`, `SUNPHARMA`
  - `TITAN`, `TATASTEEL`, `POWERGRID`, `NTPC`, `WIPRO`, `COALINDIA`, `ONGC`, `ASIANPAINT`, `JSWSTEEL`
  - `HCLTECH`, `TECHM`, `ZOMATO`, `JIOFIN`, `HAL`, `BEL`, `VEDL`, `IRFC`, `SUZLON`, `TRENT`, `NESTLEIND`
  - `HEROMOTOCO`, `EICHERMOT`, `BAJAJ-AUTO`, `ULTRACEMCO`, `GRASIM`, `INDUSINDBK`, `CIPLA`
- **MCX Commodities**:
  - `NATURALGAS` (Natural Gas Futures - base ₹228.40)
  - `CRUDEOIL` (Crude Oil Futures - base ₹6,180.00)
  - `GOLD` (Gold 10g Futures - base ₹75,450.00)
  - `SILVER` (Silver 1kg Futures - base ₹91,200.00)
  - `COPPER` (Copper 1kg Futures - base ₹835.50)
- **Benchmark Indices**:
  - `NIFTY 50`, `BANK NIFTY`, `FINNIFTY`, `MIDCPNIFTY`, `SENSEX`
- **Forex (FX) & Crypto**:
  - `USD/INR`, `EUR/INR`, `GBP/INR`, `EUR/USD`, `GBP/USD`, `USD/JPY`
  - `BTC/USDT`, `ETH/USDT`, `SOL/USDT`, `BNB/USDT`, `XRP/USDT`, `DOGE/USDT`

### 4. 🎮 Interactive Trading Terminal (Trade on this Website)
- **Simulated Paper Trading**:
  - **₹10,00,000.00** starting virtual cash.
  - Buy (Long) / Sell (Short) order ticket with Market/Limit, Stop-Loss, Target, and auto Risk:Reward.
  - Live Unrealized P&L updates dynamically on every 3-second price tick!
  - 1-Click "Close Position" to lock in realized profits into account capital.
  - Synthesized Web Audio API sound chimes on order execution.
- **1-Click Direct Broker Order Launchers**:
  - Quick order pads for **Zerodha Kite**, **Angel One**, **Upstox Pro**, **Dhan Web**, and **Groww**.

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

1. Open your repository on **[github.com](https://github.com/)** in your web browser:
   `https://github.com/<your-username>/<your-repo-name>`
2. Click **Add file** ➔ **Upload files**.
3. Drag and drop the updated files from your computer:
   - [`c:\vrunda\trading\index.html`](./index.html)
   - [`c:\vrunda\trading\README.md`](./README.md)
4. Click the green **Commit changes** button.
5. In 1–2 minutes, your live GitHub Pages link will automatically show the updated big screen chart with the closable left drawer and all 45+ Indian shares!

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
