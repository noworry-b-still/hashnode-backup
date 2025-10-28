---
title: "The Plan: My Rust Journey Through Markets and Web3 Systems"
seoDescription: "Discover how I embarked on a month-long journey to learn Rust and explore market infrastructure and blockchain systems"
datePublished: Mon Oct 13 2025 07:00:00 GMT+0000 (Coordinated Universal Time)
cuid: cmhb651ke000602la2nzl7rbn
slug: the-plan-my-rust-journey-through-markets-and-web3-systems
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/RP6Ba_6U154/upload/09b75c677cbd399a477ffe1b97f4fbc8.jpeg
tags: systems-programming, rust-programming

---

> *Disclaimer: This post is for educational purposes only. I’m exploring how programming languages like Rust are used in trading infrastructure and Web3 systems. This is* ***not*** *financial advice.*

I’ve always been intimidated by C and C++. My first impressions were shaped by poor guidance when I was introduced to them, and during my bachelor’s, I absorbed the belief that high-level languages like Python and Java were inherently “better” because they abstracted away complexity.

So I avoided anything that made me think about memory, pointers, or allocation.

That belief stood firm—until my internship at **Bose Professional** shattered it.

At Bose, we used **Elixir**, a functional language I’ll write about later. One day, during a conversation about language design, **Nick Cahill**, a senior Elixir engineer on my team, casually mentioned **Rust**. That chat changed everything.

But discovery wasn’t enough. I needed *purpose*—a reason to push through fear.

I want to build a career where programming meets high-performance computing and real-world systems. I’ve realized that the intersection of **systems programming** and **financial infrastructure** is one of the most exciting and technically challenging areas in software.

The finance world has long been dominated by **C++** for speed and control. But recently, there’s been a quiet revolution—teams are adopting **Rust** for performance-critical systems, trading backends, and blockchain layers.

That’s the world I want to enter.

I’m giving myself one focused month—from **October 13th, 2025, to November 12th, 2025**—to learn both the fundamentals of market systems and deepen my Rust expertise. I’ll document my progress every week.

This isn’t just about learning; it’s about proving to myself that **discipline can be built** and **growth can be engineered**.

I’m deeply grateful to Nick and the team at Bose for nudging me toward Rust. I genuinely love it. My goal is to master systems programming and eventually work on high-performance trading or blockchain infrastructure.

And as always, I start this journey with **Shiva’s blessings**.

If you’ve ever felt lost or behind—this is for you.

---

## Week 1: Market Foundations + Rust Market Data

**Day 1 – Order Books, Bid/Ask, Liquidity**

* *Resources:* Investopedia – Order Book Basics, Binance Academy – Liquidity & Order Types
    
* *Journal Idea:* “Order books felt like the heartbeat of markets—the rhythm of supply and demand.”
    

**Day 2 – Market vs Limit Orders, Slippage**

* *Resources:* BabyPips – Order Types, Coinbase Learn – What is Slippage
    
* *Journal Idea:* “Market orders = speed. Limit orders = patience. Execution always has trade-offs.”
    

**Day 3 – Moving Averages (MA)**

* *Resources:* TradingView – Moving Averages Explained, [TA-Lib Rust Example](https://github.com/TA-Lib/ta-lib-rust)
    
* *Journal Idea:* “Moving averages smooth the chaos. I wrote my first SMA in Rust today.”
    

**Day 4 – RSI & MACD**

* *Resources:* Investopedia – RSI, MACD Basics
    
* *Journal Idea:* “RSI shows market fatigue; MACD reveals momentum. Perfect duo.”
    

**Day 5 – Risk Management**

* *Resources:* BabyPips – Risk Management, Binance Academy – Risk in Trading
    
* *Journal Idea:* “Good risk management feels like engineering safety nets before jumping.”
    

**Day 6 – Rust: Fetch BTC Price (REST API)**

* *Resources:* Binance REST API, Reqwest crate
    
* *Journal Idea:* “Fetching live BTC prices felt like touching the market’s pulse through code.”
    

**Day 7 – Build a CLI Price Fetcher**

* *Resources:* Rust CLI Guide, Serde JSON crate
    
* *Journal Idea:* “I built a CLI tool that prints BTC/ETH prices. Small step toward real-time systems.”
    

---

## Week 2: Web3 & Blockchain Basics

**Day 8 – Blockchain Fundamentals**

* *Resources:* [Ethereum.org](http://Ethereum.org) – Blockchain Basics, Binance Academy – Blockchain Explained
    
* *Journal Idea:* “A blockchain is math and trust woven together.”
    

**Day 9 – Ethereum & Gas**

* *Resources:* [Ethereum.org](http://Ethereum.org) – Gas & Transactions, Solidity by Example – Transactions
    
* *Journal Idea:* “Gas is fuel. Every action costs something—like in life.”
    

**Day 10 – Wallets & Keys**

* *Resources:* [Ethereum.org](http://Ethereum.org) – Wallets, Etherscan tutorial
    
* *Journal Idea:* “Your private key = identity. Wallets are self-sovereign bank accounts.”
    

**Day 11 – Rust: Generate Ethereum Wallet**

* *Resources:* [ethers-rs crate](https://github.com/gakonst/ethers-rs)
    
* *Journal Idea:* “Generated my first ETH wallet in Rust. Digital identity feels tangible now.”
    

**Day 12 – Query ETH Balance**

* *Resources:* Infura, Alchemy free tier
    
* *Journal Idea:* “Queried my wallet balance on Sepolia testnet—small thrill of transparency.”
    

**Day 13 – Send a Testnet Transaction**

* *Resources:* Sepolia Faucet, [ethers-rs send example](https://github.com/gakonst/ethers-rs/blob/master/examples/send_transaction.rs)
    
* *Journal Idea:* “Watching a transaction confirm felt like magic—math ensuring truth.”
    

**Day 14 – Week Wrap-Up**

* *Resources:* Buildspace Intro to Web3, CryptoZombies Solidity basics
    
* *Journal Idea:* “Week 2 complete: from zero to sending ETH. The plumbing of Web3 finally makes sense.”
    

---

## Week 3: Trading + Web3 Integration

**Day 15 – Trading Bots Overview**

* *Resources:* Binance Academy – Trading Bots, [Rust Bot Example](https://github.com/fede1024/rust-crypto-trading-bot)
    
* *Journal Idea:* “Bots aren’t magic—they’re disciplined, rule-following coders.”
    

**Day 16 – Strategy: Moving Average Crossover**

* *Resources:* Crossover Strategy Explained, TA-Lib Rust bindings
    
* *Journal Idea:* “Crossovers mark transitions—like shifting tides in code and markets.”
    

**Day 17 – Rust: Implement Crossover Bot**

* *Resources:* Tokio Async, Binance WebSocket API
    
* *Journal Idea:* “My bot listens to BTC prices and signals changes. Feels alive.”
    

**Day 18 – AMMs (Uniswap)**

* *Resources:* Uniswap v2 Whitepaper, Docs
    
* *Journal Idea:* “Uniswap’s xy=k blew my mind—markets as equations.”
    

**Day 19 – Rust: Fetch Uniswap Reserves**

* *Resources:* [ethers-rs examples](https://github.com/gakonst/ethers-rs/tree/master/examples)
    
* *Journal Idea:* “Queried Uniswap pools via Rust. Data feels like on-chain telemetry.”
    

**Day 20 – Compare CEX vs DEX Prices**

* *Resources:* CoinMarketCap – Price Differences, Binance + Uniswap endpoints
    
* *Journal Idea:* “Centralized vs decentralized—two mirrors of the same market.”
    

**Day 21 – Log Market Gaps**

* *Resources:* Rust logging crate, Tokio tasks
    
* *Journal Idea:* “My script logs small price gaps now. Learning where systems meet strategy.”
    

---

## Week 4: Final Project

**Day 22–30 → Build + Refine a Rust-based Market Simulator**

A simulated Rust trading system that:

* Pulls data from Binance and Uniswap test endpoints
    
* Identifies simple market inefficiencies
    
* Logs opportunities instead of executing real trades
    
* *Resources:* Rust Async Book, ethers-rs full guide
    
* *Journal Idea (Day 30):* “Finished my Rust-based trading simulator. It’s not about profit—it’s about understanding.”
    

---

**Namaste.**