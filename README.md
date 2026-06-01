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
*(Tip: You can upload one of those golden flowchart images you made here!)*

## 🛠️ Technology Stack
* **Languages:** Python / MQL5 / Pine Script
* **Architecture Style:** Event-driven, Modular System Design
* **Integrations:** TradingView Webhooks / MetaTrader 5 API / Bybit Secure Connection

## ⚠️ Repository Notice
*This repository contains the abstract system architecture, core routing logic, and framework documentation. The proprietary execution source code and high-frequency live strategies remain protected for confidentiality.*
