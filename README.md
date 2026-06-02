# XAUUSD & Forex Modular Algorithmic Trading System

A scalable, high-performance algorithmic trading framework developed to analyze, backtest, and execute trades on Gold (XAUUSD) and major Forex pairs. Built with a strict focus on modularity and system architecture, this ecosystem utilizes a dedicated Radio messaging system rather than unstructured script execution.

## 📊 Core System Features
* **Modular Infrastructure:** Separated into independent core modules: Data Ingestion, Signal Generation, Risk Management, and Execution.
* **Radio Messaging System:** Implements a decoupled communication framework where distinct sub-systems pass real-time event messages safely, preventing race conditions.
* **Technical Analytics Engine:** Built-in calculation layers for core mathematical indicators:
  * Trend & Strength: SMA, ADX
  * Momentum & Volatility: RSI, ATR
* **Risk & Drawdown Control:** Dynamic position sizing based on real-time ATR, maintaining hard-coded global drawdown safety thresholds.

## 📐 System Architecture
This comprehensive block diagram illustrates the decoupled architecture of the ecosystem. It shows how independent core handlers (Indicator Filters, Risk Calculators, and Position Managers) communicate dynamically without monolithic dependencies.

![System Architecture Blueprint](https://github.com/mahla-sys/-Gold-Forex-Algorithmic-System/blob/main/InShot_20260601_200956260.jpg?raw=true)

---

## 🔍 Core Component Previews

### 📡 Event-Driven Messaging Layer (CRadio)
A sneak peek into the low-level infrastructure showcasing the `CRadio` core class. This module manages listeners and orchestrates asynchronous communication across sub-systems to maintain high-speed execution stability.

![CRadio Code Structure](https://github.com/mahla-sys/-Gold-Forex-Algorithmic-System/blob/main/Screenshot%202026-06-01%20194031.png?raw=true)

### 🗂️ Modular File Structure & Lifecycle Evolution
The component structure under MetaEditor highlights strict modular versioning. Each sub-script represents a focused iteration of algorithmic filters and optimized execution parameters, proving a long-term development lifecycle.

![Modular File Structure](https://github.com/mahla-sys/-Gold-Forex-Algorithmic-System/blob/main/Screenshot%202026-06-01%20193915.png?raw=true)

### 📜 Real-Time Logic & Dynamic Filtering Logs
Live terminal logs executing inside the strategy tester. This confirms the production readiness of the environment, specifically demonstrating the system dynamically blocking low-probability trades using mathematical threshold filters (e.g., ADX indicators).

![Real-Time Execution Logs](https://github.com/mahla-sys/-Gold-Forex-Algorithmic-System/blob/main/Screenshot%202026-06-01%20194527.png?raw=true)

---

## 🛠️ Technology Stack
* **Languages:** Python / MQL5 / Pine Script
* **Architecture Style:** Event-Driven, Modular System Design
* **Integrations:** TradingView Webhooks / MetaTrader 5 API / Bybit Secure Connection

## ⚠️ Repository Notice
*This repository contains the abstract system architecture, core routing logic, and framework documentation. The proprietary execution source code and high-frequency live strategies remain protected for confidentiality.*
