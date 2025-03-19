# 🚀 Crypto Trading Automation with n8n & AI

## 📌 Overview
This project is a fully automated **crypto trading assistant** that integrates **real-time market analysis** with **AI-driven insights**, all triggered by a simple **Telegram message**. It leverages **n8n**, **Binance API**, **NewsAPI**, and AI models like **GPT-4o, Google Gemini, Deepseek, or Ollama** to provide detailed trading recommendations.

## 🔧 Features
- 📩 **Telegram Integration**: Send a crypto symbol (e.g., `BTC`) to initiate the workflow.
- 📊 **Market Data Fetching**: Retrieves candlestick data (15m, 1h, 1d intervals) from **Binance API**.
- 📰 **News Sentiment Analysis**: Pulls recent crypto news using **NewsAPI** and applies **AI-based sentiment analysis**.
- 🤖 **AI-Driven Trading Insights**:
  - Analyzes **technical indicators** (price action, volatility, support/resistance levels).
  - Evaluates **market sentiment** (short-term & long-term analysis).
  - Provides **spot and leveraged trading recommendations** with **entry prices, stop-loss, and take-profit levels**.
- 📲 **Automated Telegram Response**: The final analysis is formatted and sent back to Telegram for quick execution.

## 🛠️ Tech Stack
- **n8n** (Low-code automation platform)
- **Binance API** (Market data retrieval)
- **NewsAPI** (Crypto news aggregation)
- **GPT-4o / Google Gemini / Deepseek / Ollama** (AI-driven sentiment and trade analysis)
- **Telegram Bot API** (User interaction and response handling)

## 🚀 How It Works
1. **User sends a crypto symbol** via Telegram.
2. **n8n triggers the workflow**, fetching market data and recent news.
3. **Sentiment analysis** is performed using AI.
4. **AI processes** technical & sentiment data to generate a **trading recommendation**.
5. **Telegram bot sends the final decision** back to the user.

## 📌 Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/crypto-trading-automation.git
   cd crypto-trading-automation
   ```
2. Install **n8n** (if not already installed):
   ```bash
   npm install -g n8n
   ```
3. Set up API credentials:
   - **Binance API Key & Secret**
   - **NewsAPI Key**
   - **OpenAI API Key (or other AI model credentials)**
   - **Telegram Bot Token**
4. Import the **n8n workflow JSON file** into your n8n instance.
5. Start n8n:
   ```bash
   n8n start
   ```
6. Connect your **Telegram bot** and start sending crypto symbols!

## 📜 License
This project is licensed under the **MIT License**.

## 📬 Feedback & Contributions
💡 Have ideas for improvement? Found a bug? Open an **issue** or submit a **pull request**! Let's make crypto trading smarter together. 🚀

