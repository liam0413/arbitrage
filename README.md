# **🚀 Solana Arbitrage Bot** 🐧

A **Solana Arbitrage Bot** designed to scan for profitable arbitrage opportunities across multiple decentralized exchanges (DEXes) and liquidity pools (LPs). The bot works by analyzing token pair addresses, fetching liquidity pools, and executing profitable trades. 💡

---

## **✨ Features** ✨

### 1. **DEX Support** 💎
Scan for profitable arbitrage opportunities on the following DEXes:
- 🌊 **Orca**
- 🌌 **Meteora**
- 💸 **Raydium**

### 2. **Pool Addresses** 🔄
Support for scanning liquidity pools, including:
- ⚡ **CLP** (Concentrated Liquidity Pools)
- 💧 **LP** (Liquidity Pools)
- 🛠️ **AMM** (Automated Market Makers)
- 🏦 **CLMM** (Concentrated Liquidity Market Makers)

### 3. **Token Pair Address Input** 🔑
- Enter approximately **1100 token pair addresses** into the bot. 📥

### 4. **Pool Address Input** 🔄
- Enter approximately **9 pool addresses per token pair** into the bot. 🔢 (for each token pair, you will input the relevant pool addresses).

### 5. **Arbitrage Execution** 💥
- The bot scans all combinations of your input (token pairs and pools) across the specified DEXes and liquidity pools.
- **Only executes trades if profitable**, using a predefined formula to calculate profitability and find the most optimal combination.

### 6. **Trade Logging** 📂
- All successful trades are logged and saved to a `.txt` file for record-keeping and analysis.

### 7. **Continuous Scanning** 👀
- The bot continuously scans for arbitrage opportunities and updates the console with real-time data about its scanning process.

---

## **🔧 Configuration** ⚙️

### **Environment File (`.env`) Settings** 📝
To configure the bot, you'll need to set the following values in the `.env` file:

```env
GAS_FEE=0.0005          # ⛽ Gas fee for transactions
SLIPPAGE=0.1            # 🔄 Slippage tolerance (in percentage)
JITO_FEES=0.01          # 💰 JITO fees (in percentage)
SWAP_AMOUNT=1000        # 💵 The amount of tokens to swap (adjustable)
