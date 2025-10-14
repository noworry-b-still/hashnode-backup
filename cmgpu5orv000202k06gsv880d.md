---
title: "The $1M Plan: Why I'm Betting Everything on Rust and Trading"
datePublished: Tue Oct 14 2025 00:40:35 GMT+0000 (Coordinated Universal Time)
cuid: cmgpu5orv000202k06gsv880d
slug: why-im-betting-everything-on-rust-and-trading
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/RP6Ba_6U154/upload/de0bec33d0caaf992f15ab769e124bfa.jpeg
tags: web3, systems-programming, rust-programming

---

I've always been intimidated by C and C++. My first impressions were tainted by poor guidance when I was introduced to them, and as time passed, I was fed a narrative during my bachelor's degree that high-level languages like Python and Java were *inherently superior* to low-level languages. Since then, I've shied away from anything that forced me to think about memory allocation, pointers, and manual memory management.

This mental model remained unchallenged—until my internship at Bose Professional shattered it completely.

At Bose, we worked primarily with Elixir—a functional programming language I'll write about in another blog—at least during my first few months. It was there that Nick Cahill, a senior Elixir engineer on my team, casually introduced me to Rust during one of our conversations about programming languages. That conversation changed everything. *That's how I discovered Rust.*

But discovery alone wasn't enough. I needed direction, purpose—a reason to push through the fear.

I want to make money from programming—not just money, but the kind of money that could help me retire early, return to my parents, and live peacefully in my village in Bharat. While entry-level engineering salaries in the United States are fairly good compared to other countries, I want *more*. I want to rapidly upskill myself and become an expert in a domain that pays even better than traditional tech companies.

The answer is obvious: **trading and finance**.

This domain has long been dominated by one language—**C++**—the very language I've been avoiding. Companies in this space still use it extensively for its performance and low-level control. But there's a shift happening: Web3 has been embracing Rust, and some companies are rewriting critical systems in Rust too.

I have a goal. I have the means. But one thing is missing besides my learning and discipline: **opportunity**.

And here's the brutal truth—getting a job at these firms is *ruthlessly* competitive. Brilliant minds from Ivy League schools fail to secure spots. I'm an international student from Bharat, and I have ADHD—something no one knows about, not even my family or friends. *Only Shiva knows.*

I feel like I lack discipline. I feel guilty, like I'm a loser destined for mediocrity. I'm tired of waiting for opportunities and endlessly preparing for the same DSA problems, watching others move forward while I remain stuck.

**Enough.**

So I'm giving myself one month—from **October 13th, 2025, to November 12th, 2025**—to learn core concepts in the finance domain and get comfortable with Rust. I know LLMs can be a huge support in learning new skills and planning the process. ChatGPT gave me a plan, and I will follow it *no matter what*. I'll write a blog every week about what I learned and created.

This isn't just about learning anymore. It's about proving to myself that I'm not mediocre, that I'm not destined to fail, that discipline can be built, and that opportunity can be *created*.

I'm deeply grateful to Nick Cahill and the team at Bose for inspiring me to explore Rust. I truly love Rust, and I've fallen in love with systems programming. I want to become an expert in Rust and the trading software domain. I want to land a job at a firm in this space, solve high-impact problems, and **make $1 million within four years of getting that job**.

*Shiva is my savior.* I begin this journey with his blessings.

I hope everyone who feels like me—lost, doubting, struggling—finds hope, guidance, and love.

---

## **Week 1: Trading Foundations + Rust Market Data**

**Day 1 – Order books, bid/ask, liquidity**

* Resources:
    
    * Investopedia – Order Book Basics
        
    * Binance Academy – Liquidity & Order Types
        
* Journal Idea: *“Today I learned how order books actually work. The bid/ask spread felt like the heartbeat of trading.”*
    

**Day 2 – Market vs limit orders, slippage**

* Resources:
    
    * BabyPips – Types of Orders
        
    * Coinbase Learn – What is Slippage
        
* Journal Idea: *“Market orders = speed, limit orders = patience. Slippage showed me that even execution has hidden costs.”*
    

**Day 3 – Moving Averages (MA)**

* Resources:
    
    * TradingView – Moving Averages Explained
        
    * [Rust code – SMA example](https://github.com/TA-Lib/ta-lib-rust)
        
* Journal Idea: *“Moving averages are like smoothing out the noise. I coded my first SMA in Rust today.”*
    

**Day 4 – RSI & MACD**

* Resources:
    
    * Investopedia – RSI
        
    * MACD basics
        
* Journal Idea: *“RSI is the trader’s fatigue meter; MACD is the momentum whisper. I like how they complement each other.”*
    

**Day 5 – Risk management**

* Resources:
    
    * BabyPips – Risk Management
        
    * Binance Academy – Risk in Trading
        
* Journal Idea: *“If you can’t manage risk, you can’t survive. Today I realized trading is more defense than offense.”*
    

**Day 6 – Rust: fetch BTC price (REST API)**

* Resources:
    
    * Binance REST API Docs
        
    * Reqwest crate docs
        
* Journal Idea: *“Fetching live BTC prices felt like tapping into the market’s pulse with Rust as my stethoscope.”*
    

**Day 7 – Build a CLI price fetcher**

* Resources:
    
    * Rust CLI Guide
        
    * Serde JSON crate
        
* Journal Idea: *“I built a tiny Rust CLI that prints BTC/ETH prices. First baby step toward algo trading bots.”*
    

---

## **Week 2: Web3 & Blockchain Basics**

**Day 8 – Blockchain basics**

* Resources:
    
    * Ethereum.org – Blockchain basics
        
    * Binance Academy – Blockchain Explained
        
* Journal Idea: *“A blockchain is just a chain of promises verified by math. Simple, but powerful.”*
    

**Day 9 – Ethereum & gas**

* Resources:
    
    * Ethereum.org – Gas & Transactions
        
    * Solidity by Example – Transactions
        
* Journal Idea: *“Gas is the fuel for Ethereum. Today I realized every action has a cost, just like in real life.”*
    

**Day 10 – Wallets & keys**

* Resources:
    
    * Ethereum.org – Wallets
        
    * Etherscan tutorial
        
* Journal Idea: *“Your private key = your identity. Wallets are like bank accounts without a bank.”*
    

**Day 11 – Rust: generate Ethereum wallet**

* Resources:
    
    * ethers-rs crate
        
    * [ethers-rs examples](https://github.com/gakonst/ethers-rs)
        
* Journal Idea: *“Generated my first ETH wallet in Rust. The address felt like my new digital passport.”*
    

**Day 12 – Query ETH balance**

* Resources:
    
    * Infura RPC (free endpoint)
        
    * Alchemy free tier
        
* Journal Idea: *“Queried my wallet’s balance on Sepolia testnet. Feels like peeking into my Web3 bank account.”*
    

**Day 13 – Send a testnet transaction**

* Resources:
    
    * Sepolia faucet
        
    * [ethers-rs tx example](https://github.com/gakonst/ethers-rs/blob/master/examples/send_transaction.rs)
        
* Journal Idea: *“I sent my first ETH on Sepolia. Watching it confirm was like magic—math and money fused.”*
    

**Day 14 – Wrap-up**

* Resources:
    
    * Buildspace Free Web3 Intro
        
    * CryptoZombies Solidity basics
        
* Journal Idea: *“Week 2 complete: from zero to sending ETH. I now understand the ‘plumbing’ of Web3.”*
    

---

## **Week 3: Trading + Web3 Integration**

**Day 15 – Trading bots overview**

* Resources:
    
    * Binance Academy – Trading Bots
        
    * [GitHub Rust trading bot example](https://github.com/fede1024/rust-crypto-trading-bot)
        
* Journal Idea: *“Bots aren’t magic—they’re disciplined, automated traders. Humans code the greed.”*
    

**Day 16 – Strategy: moving average crossover**

* Resources:
    
    * Moving Average Crossover explained
        
    * TA-Lib Rust bindings
        
* Journal Idea: *“Moving averages crossing = signal of change. Like watching traffic lights in markets.”*
    

**Day 17 – Rust: implement crossover bot**

* Resources:
    
    * Tokio async
        
    * Binance WebSocket API
        
* Journal Idea: *“My bot now listens live to BTC prices and prints trade signals. First glimpse of automation.”*
    

**Day 18 – AMMs (Uniswap)**

* Resources:
    
    * Uniswap v2 Whitepaper
        
    * Uniswap Docs
        
* Journal Idea: *“Uniswap = math-powered market maker. x*y=k blew my mind.”\*
    

**Day 19 – Rust: fetch Uniswap reserves**

* Resources:
    
    * Etherscan Uniswap contracts
        
    * [ethers-rs contract call example](https://github.com/gakonst/ethers-rs/tree/master/examples)
        
* Journal Idea: *“Queried Uniswap pool reserves. It’s like pulling liquidity secrets straight from the blockchain.”*
    

**Day 20 – Compare CEX vs DEX prices**

* Resources:
    
    * CoinMarketCap Arbitrage Article
        
    * \[Binance + Uniswap price endpoints\]
        
* Journal Idea: *“CEX and DEX don’t always agree. Found small price gaps = tiny arbitrage windows.”*
    

**Day 21 – Log arbitrage opportunities**

* Resources:
    
    * Rust logging crate
        
    * Tokio tasks for periodic checks
        
* Journal Idea: *“Coded my first arbitrage logger. My bot now whispers: ‘here’s a profit chance.’”*
    

---

## **Week 4: Final Project**

**Day 22–30** → Build + refine a Rust **CEX/DEX Arbitrage Bot** (as outlined earlier).

* Resources each day:
    
    * Rust async book
        
    * ethers-rs full guide
        
* Journal Idea (example for Day 30): *“Finished my first Rust Web3 trading bot. It only simulates, but it taught me markets, wallets, and coding discipline.”*
    

---

Namaste.