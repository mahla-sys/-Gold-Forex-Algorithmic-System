
# XAUUSD & Forex Modular Algorithmic Trading Framework 📈
### Event-Driven Execution Engine, Pine Script Converter & Quantitative Suite in MQL5 / MT5

A scalable, institutional-grade algorithmic trading ecosystem engineered to analyze, backtest, and execute quantitative strategies on Gold (XAUUSD) and major Forex pairs. Built with a strict focus on decoupled software architecture, this framework utilizes a proprietary **central Radio (Pub/Sub) messaging bus** rather than brittle, monolithic script execution.

> ⚡ **Development Track Record:**  
> **50+ Iterative Expert Advisors (EAs) Engineered** | **Pine Script to MQL5 Algorithmic Conversion** | **4 Decoupled Execution Managers** | **22-Field Machine Learning Telemetry Logging**

---

## 📊 Core System Capabilities & Quantitative Scope

- **50+ Custom EAs Built & Backtested:** Extensive field experience engineering diverse algorithmic models across multiple asset classes:
  - **Scalping & High-Frequency Momentum:** Fast execution models tuned to capture micro-structure volatility.
  - **Trend-Following & Multi-Timeframe (MTF):** Dynamic trend filters using multi-period moving averages, ADX strength confirmation, and market structure breaks.
  - **Volatility & Breakout Systems:** Session opens, ATR range expansions, and liquidity sweep detections.
- **TradingView (Pine Script) to MetaTrader 5 (MQL5) Conversion:**
  - High-fidelity algorithmic translation ensuring exact mathematical parity between TradingView indicators and MT5 execution.
  - Optimization of non-repainting signals, multi-indicator sync, and zero-latency execution loops.
- **Decoupled Radio Messaging Core (Pub/Sub):** Eliminates race conditions and order freeze by routing all state changes through a central event bus (`CRadio`).
- **Mathematical Risk & Capital Preservation:** Dynamic fractional position sizing calculated in real-time via ATR volatility, accompanied by hard-coded global equity drawdown caps.
- **Broker Anomaly & Slippage Defense:** Built-in safeguards against spread expansions during high-impact macroeconomic news releases, execution latency spikes, and slippage.

---

## 📐 System Architecture Blueprint

The block diagram below illustrates the decoupled topological design of the framework. Independent managers (Filter Validation, Risk Sizing, Position Lifecycle, and Exit Execution) communicate asynchronously via event broadcasts without tight coupling.

![System Architecture Blueprint](https://github.com/mahla-sys/-Gold-Forex-Algorithmic-System/blob/main/InShot_20260601_200956260.jpg?raw=true)

---

## 🔍 Core Component Walkthrough

### 📡 1. Event-Driven Messaging Layer (CRadio)
The low-level infrastructure backbone managing system listeners and asynchronous event dispatching across subsystems. This guarantees that risk management and order tracking never lag behind price updates.

![CRadio Code Structure](https://github.com/mahla-sys/-Gold-Forex-Algorithmic-System/blob/main/Screenshot%202026-06-01%20194031.png?raw=true)

---

### 🗂️ 2. Modular File Structure & Component Separation
Component structure under MetaEditor demonstrating strict encapsulation. Each module represents a dedicated domain (Filter management, lifecycle monitoring, math libraries), facilitating rapid strategy iteration without code regression.

![Modular File Structure](https://github.com/mahla-sys/-Gold-Forex-Algorithmic-System/blob/main/Screenshot%202026-06-01%20193915.png?raw=true)

---

### 📜 3. Live Execution & Dynamic Indicator Filtering Logs
Live terminal logs executing inside the MetaTrader 5 Strategy Tester. Demonstrates the framework dynamically evaluating mathematical thresholds (e.g., ADX strength, RSI momentum) and filtering out low-probability trades in real time.

![Real-Time Execution Logs](https://github.com/mahla-sys/-Gold-Forex-Algorithmic-System/blob/main/Screenshot%202026-06-01%20194527.png?raw=true)

---

## 🏗️ The 4 Decoupled Execution Managers

1. **Filter Manager:** Evaluates 20+ dynamic technical rules, spread spikes, volatility bands, and news event evasion.
2. **Entry Manager:** Computes lot sizing, dynamic fractional risk, and broadcasts open orders via the Radio bus.
3. **Trade Lifecycle Manager:** Continually logs 22 operational telemetry fields, executing dynamic trailing stops and multi-stage breakeven logic.
4. **Exit Manager:** Executes mathematical liquidations isolated from signal generation logic.
5. **Telemetry Logger:** Streams trade metrics directly to structured datasets for downstream Machine Learning analysis (Random Forest / Scikit-Learn).

---

## 💼 Custom Algorithmic Development & Conversion Services

I provide quantitative development and algorithmic engineering services for traders, prop firm participants, and funds:

- **Custom EA Architecture:** Turning discretionary setups, technical indicator rules, or price action strategies into automated, tested MetaTrader 5 Expert Advisors.
- **Pine Script to MQL5 Migration:** Direct, clean translation of your custom TradingView strategies into high-performance MT5 robots.
- **Risk & Account Protection Integration:** Adding news filters, trailing stops, daily drawdown limits, and broker latency shields to existing scripts.
- **Strategy Optimization & Stress-Testing:** Running deep parameter sweeps and multi-year backtesting across changing market conditions.

---

## 🛠️ Technology Stack
- **Execution & Scripting:** MQL5, MetaTrader 5, Pine Script (TradingView v5)
- **Analytics & Prototyping:** Python (Scikit-Learn, Pandas for backtest data modeling)
- **Design Paradigm:** Event-Driven Architecture, Pub/Sub Messaging, Low-Coupling OOP

---

## 📬 Contact & Consultation
Have an indicator, trading setup, or Pine Script strategy you want automated or converted?

- **Telegram:** [@mahla_systems](https://t.me/mahla_systems)
- **Email:** [mahla.systems@proton.me](mailto:mahla.systems@proton.me)
- **GitHub:** [github.com/mahla-sys](https://github.com/mahla-sys)

---
*Notice: This repository showcases the architectural patterns, routing logic, and core component designs. Proprietary execution code and private trading algorithms are protected under confidentiality.* haryo47 بفرست:


این کار دقیقاً همان «صفحه فرود متمرکز» است که می‌خواستیم، بدون اینکه به بقیه
رزومه و اعتبارت دست بزنیم!
