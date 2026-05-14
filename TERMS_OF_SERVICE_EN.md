# Jafar Pro — User Agreement and AI Assistant Terms of Service

**Last updated: 2026-05-15**

---

## PART I: USER AGREEMENT

### 1. Introduction

This document (hereinafter — the "Agreement") governs the relationship between the Author of the **Jafar Pro** software (hereinafter — the "Author") and the User (hereinafter — the "User", "You").

**ATTENTION:** Before using the Software, carefully read this Agreement. Beginning to use the Software constitutes your full and unconditional acceptance of all terms of this Agreement. If you disagree with any provision, you must immediately cease using the Software.

### 2. Broker

**This version of the Software works exclusively with Topstep (TopstepX) broker.**

- The Software is integrated only with the TopstepX API
- Connection to other brokers (Tradovate, NinjaTrader, Interactive Brokers, etc.) is not supported by this version
- The User independently registers accounts with Topstep broker and is responsible for compliance with broker rules (Daily Loss Limit, Consistency Rule, etc.)

### 3. Rental Model: Copy-Trade from Leader Account

The Software is provided to the User **for rent**. The rental fee is collected under the "Copy-Trade" model:

#### 3.1 Account Structure
- The User has **1 (one) main leader account** and up to **4 (four)** additional copy accounts
- All accounts are connected to the Software in copy-trade mode
- **One of the copy accounts is always the Author's account** (hereinafter — the "Author's Account")

#### 3.2 Copy-Trade Principle
- The leader account determines trading decisions; all copy accounts **mirror the leader account's trades**
- All entries, exits, stop-losses, and take-profits are identical across all accounts
- If the leader account earns $3,000 — each copy account (including the Author's Account) also earned $3,000
- The Author's Account cannot be disconnected from copy-trade while the Software connection is active

#### 3.3 Rental Fee
- **Profit earned on the Author's Account is the rental fee for using the Software**
- The User does NOT pay a fixed monthly fee
- The User does NOT compensate the Author's Account losses from their own funds
- If the Author's Account incurs a loss — the rental fee for that period is considered zero
- **Example:** Leader account earns $3,000. Each copy account (including the Author's Account) also earns $3,000. The Author receives $3,000 as rental fee. The User keeps the leader account profit ($3,000) + profit from their copy accounts (up to 3 × $3,000 = $9,000). Total User: up to $12,000, Author: $3,000.

#### 3.4 User Obligations
- The User undertakes to provide the Software with access to all accounts (including the Author's Account) throughout the entire period of Software use
- The User undertakes not to disconnect the Author's Account from copy-trade
- The User undertakes not to create separate instances of the Software to bypass the Author's Account
- The User undertakes not to modify the Software to exclude the Author's Account from copy-trade

#### 3.5 Liability for Violation
Violation of Section 3.4 terms entails:
- Immediate termination of access to the Software
- Obligation to compensate the Author for lost profit for the entire period of Software use
- Possible legal prosecution in accordance with applicable law

### 4. Service Description

**Jafar Pro** is a software suite for financial market analysis, including:

- **AI Assistant** — an analytical tool based on artificial intelligence (DeepSeek, Claude Opus, Gemini, Ollama), providing trading recommendations, market structure analysis (SMC/ICT), support/resistance levels, and volatility assessment
- **Trading Bots (Blade, Autobot)** — automated systems for analysis and execution of trading operations via TopstepX broker API
- **Coach** — an interactive AI mentor for preparation and post-analysis of trading sessions
- **Academy (Lesson)** — educational modules on SMC/ICT methodology
- **Market Scanner** — a tool for finding trading opportunities based on algorithmic analysis

### 5. User Status

- The User must be of legal age (18+)
- The User bears full responsibility for the accuracy of provided data (API keys, trading account data)
- The User undertakes to use the Software exclusively for lawful purposes
- One copy of the Software is intended for use by one User

### 6. Trading Risks

**CRITICALLY IMPORTANT:**

Trading CME futures involves a high level of risk and can result in complete loss of capital. You acknowledge and agree to the following:

- Past results do not guarantee future returns
- Any trading recommendations of the AI Assistant are informational in nature and do not constitute investment advice
- Automated trading through bots can lead to losses faster than manual trading
- You bear FULL and SOLE responsibility for all trades executed through your trading account
- Neither the Author nor the Software are licensed financial advisors or brokers

### 7. Limitation of Liability

To the maximum extent permitted by law:

- The Author is not liable for direct, indirect, incidental, or consequential damages, including lost profit, loss of data, or loss of trading capital
- The Author does not guarantee the accuracy, completeness, or timeliness of data obtained from external APIs (TopstepX, Yahoo Finance, Financial Modeling Prep, news sources)
- The Author is not liable for losses caused by: technical failures, API errors, data transmission delays, power outages, or actions of third parties
- All trading decisions are made by the User independently. The AI Assistant and bots provide only analytical information

### 8. API Keys and Security

- The User is independently responsible for the security of their API keys, tokens, and passwords
- The Software stores keys in environment variables and User configuration files
- The Author does not have access to the User's API keys
- The User undertakes to immediately notify their broker of any suspicious activity on the account

---

## PART II: AI ASSISTANT TERMS OF USE

### 9. Nature of AI Recommendations

The Jafar Pro AI Assistant uses large language models (LLMs) to generate analytical reports. You acknowledge and agree that:

- AI models may make errors, hallucinations, and inaccuracies
- Trading levels, forecasts, and recommendations are generated based on probabilistic models and **are not guaranteed**
- The AI Assistant does not possess consciousness, intuition, or understanding of context beyond the provided data
- The quality of the AI response depends on the quality and relevance of input data (market quotes, order book data, news background)

### 10. AI Providers

The Software may use the following AI models:

| Provider | Model | Flag |
|---|---|---|
| DeepSeek | deepseek-chat / deepseek-v4 | `--deepseek` (default) |
| Anthropic | Claude Opus 4.7 | `--claude` / `-c` |
| Google | Gemini 2.5 Pro | `--gemini` / `-g` |
| Ollama | Local models | `--ollama` |

- When using cloud AI providers, your request data is transmitted to the respective provider's servers
- The User agrees to the terms of use of the respective AI provider
- When using Ollama (locally), data does not leave the User's device
- The Author does not control and is not responsible for data processing by AI providers

### 11. Voice Assistant (Muxlisa)

- Voice output (`--voice`) is activated only upon explicit request of the User
- Only brief summaries are voiced — not the full AI analysis
- When using voice output, the Software uses the local TTS engine (macOS `say`)

---

## PART III: CONFIDENTIALITY AND DATA

### 12. Data Collection and Processing

**Data transmitted to external services:**
- Market requests → TopstepX API, Yahoo Finance, Financial Modeling Prep
- AI requests → DeepSeek API, Anthropic API, Google Gemini API (depending on selected provider)
- Telegram notifications → Telegram Bot API (trade numbers, balance, PnL)

**Data stored locally:**
- API keys and tokens → environment variables / `.env`
- Trading journal → `TRADING_JOURNAL.md`
- Configuration → Software configuration files

**The Author DOES NOT collect, DOES NOT store, and DOES NOT have access to:**
- User's trading history
- Trading account data
- User's API keys
- Content of User's AI requests

### 13. Telegram Notifications

The Software may send notifications to Telegram (startup, trading signals, Coach session results). Notifications include:
- Instrument and trading action
- Balance and PnL
- Trading levels
- Brief analytics

Telegram notifications are **not a replacement** for the Software interface and are provided "as is." Delay or absence of a notification does not constitute a violation of the terms of this Agreement.

---

## PART IV: FINAL PROVISIONS

### 14. Changes to Terms

The Author reserves the right to change the terms of this Agreement at any time. The new version takes effect from the moment of publication. Continued use of the Software after changes constitutes acceptance of the new terms.

### 15. Contact

For all matters related to this Agreement, contact the Author.

### 16. Acknowledgment

By starting to use Jafar Pro, you confirm that you:
- [ ] Have read and understood this Agreement
- [ ] Understand the risks of trading CME futures
- [ ] Understand the limitations of AI models and their recommendations
- [ ] Accept full responsibility for all trading decisions
- [ ] Agree to the data processing terms

---

**© 2024–2026 Jafar Pro. All rights reserved.**
