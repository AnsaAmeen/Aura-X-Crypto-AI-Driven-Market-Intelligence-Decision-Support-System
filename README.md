# 🚀 Aura-X Crypto: AI-Driven Market Intelligence & Decision Support System

---

### An Autonomous AI-Powered Crypto Sentinel & Strategic Action Engine

The **Aura-X Crypto** is a high-performance, production-ready automation framework designed to navigate the volatility of digital assets. It transforms raw market telemetry (Price, Technical Indicators, Social Sentiment) into institutional-grade strategic action plans—enabling data-driven trading decisions and early trend detection through advanced AI orchestration.

---

## 📽️ Project Overview & Logic

The automation is implemented using **n8n** with a sophisticated 28-node modular architecture. Each stage of the workflow is clearly separated to improve readability, debugging, and future extensibility. 

The system bridges the gap between fragmented market data and execution strategy by utilizing **Retrieval-Augmented Generation (RAG)**—connecting a live data pipeline to a **Vector Database (Pinecone)** so the AI learns from historical market patterns.

---

### 🖼️ Workflow Architecture

* **Workflow Diagram:** `[Link to Image]`
* **Telegram Intelligence Report:** `[Link to Image]`
* **Pinecone Database Logs:** `[Link to Image]`

---

## 💎 Core Features

* 🤖 **AI Strategic Orchestration** Uses **OpenAI GPT-4o** to synthesize complex correlations between RSI, MACD, and real-time news to generate **BUY/SELL/HOLD** signals.

* 📡 **Multi-Stream Data Ingestion** Automated retrieval of spot prices via **CoinGecko**, OHLCV data via **Binance**, and market headlines via **CryptoPanic API**.

* 🧠 **RAG-Enabled Memory** Integrated with **Pinecone Vector Database** to store and query market history, providing the AI with long-term contextual awareness through **Text-Embedding-3**.

* 🌐 **Social Intelligence Scraper** Real-time monitoring of **Discord community chatter** to detect "Alpha" and narrative shifts before they hit mainstream news.

* 🚀 **Institutional-Grade Alerting** Multi-channel delivery system that dispatches high-priority **RSI Alerts** and **Sentiment Shifts** via **Telegram**.

* 📊 **Technical Analysis Engine** Custom-built JS engine that calculates real-time **RSI, MACD, and Bollinger Bands** to eliminate emotional trading bias.

---

## 🛠️ Infrastructure & Tech Stack

* **Automation Engine:** n8n (Hosted on AWS EC2 via Docker)
* **AI Model:** OpenAI GPT-4o & Text-Embedding-3
* **Vector Database:** Pinecone (for RAG & Market Memory)
* **Environment:** Ubuntu Linux & Docker Containerization
* **Data Sources:** CoinGecko API, Binance API, CryptoPanic API, Fear & Greed API
* **Languages:** JavaScript (Custom Function Nodes for TA Engine)
* **Integrations:** Telegram Bot API, Discord Webhooks

---

## 👤 Contributor

* **Ansa Ameen** — *AI Automation expert & Business developer*
