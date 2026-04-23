---
icon: book-open-cover
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
---

# Overview

### What is TMB?

TMB (Trust Me Bro) is a mobile-first prediction market app that wraps institutional-grade Polymarket liquidity into a dopamine-optimized experience.

While traditional decentralized finance (DeFi) often feels like a cockpit of complex charts and gas fees, TMB is built for the sports fans, the news junkies, and the casual observers who prioritize ease of use and social engagement. By combining a Progressive Web App (PWA) with frictionless action triggers, we’ve made predicting real-world outcomes intuitive and fun.

***

## The Friction Problem

Traditional prediction markets are built for power users. The barrier to entry is high: you have to manage gas fees, sign every single transaction, and navigate desktop interfaces that look like Bloomberg Terminals. For most people, the technical overhead of placing a simple prediction is a dealbreaker.

***

## The TMB Approach

We’ve abstracted the "crypto" out of the experience so you can focus on the "market." TMB hides the complexity of on-chain trading behind a mobile-native layer:

* Hold to Trade: Every trade is a single, tactile gesture. No messy "Confirm" pop-ups. Just press and hold to lock in your position.
* Embedded Wallets: Powered by Privy. No seed phrases or browser extensions-your wallet is created instantly when you log in via Google or X.
* Smart Accounts (Safe): We use proxy wallets to handle the heavy lifting. You don’t need to manually approve every trade or worry about holding MATIC for gas.
* Preset Frictionless Predictions: Set your default trade amount once and trade in milliseconds.
* Real-time Data:Live price charts, sports scores, and market updates are streamed directly to your device.

***

### Core Concepts

#### 1. Prediction Markets 101

At its heart, a prediction market is a way to trade on the probability of future events. Prices fluctuate between $0.00 and $1.00, serving as a real-time "likelihood" meter.

* Price as Probability: If a "Yes" share for a match is trading at $0.60, the market sees a 60% chance of that outcome.
* The Payout: If you’re right, your share matures to $1.00. If you’re wrong, it goes to $0.00.

#### 2. The Engine: Polymarket Liquidity

TMB doesn’t reinvent the wheel-we just make it more aerodynamic. We connect directly to Polymarket’s Central Limit Order Book (CLOB).

When you trigger a trade on a TMB card, our backend executes a market order on Polymarket on your behalf. You get the deepest liquidity in the world with the simplest UI on the market. All positions and balances are settled transparently on the Polygon blockchain.
