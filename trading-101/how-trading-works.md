---
description: >-
  TMB isn’t a casino-it’s a gateway to highly accurate prediction data. Trade on
  a global peer-to-peer exchange powered by Polygon blockchain and Polymarket
  liquidity.
icon: chart-column
---

# How Trading Works

### The Engine: Outcome Shares

Everything you trade on TMB is technically an Outcome Share. These are specialized tokens (ERC-1155) that represent a specific result of a future event.

The core logic is simple:

* Winning Shares are worth exactly $1.00.
* Losing Shares are worth exactly $0.00.

Because everyone knows a winning share will be worth $1.00 eventually, the current price represents the market’s collective "bet" on the probability of that event happening.

***

### Anatomy of a Trade

#### 1. Shares Calculation

TMB abstracts the "share" math so you can focus on the payout. However, behind the scenes, your Preset Bet determines how many tokens you buy:

\$$shares = \frac{bet\\\_amount}{share\\\_price}\$$

Example: You have a $10 Preset and you hold YES at a price of $0.62.

* TMB buys 16.13 shares for you ($10 / $0.62).

#### 2. Risk vs. Reward

The price of a share is the Market Odds. The lower the odds, the higher the payout (and the higher the risk).

| Market Odds (Price) | TextImplied Probability | TextPayout per $1 Bet |
| ------------------- | ----------------------- | --------------------- |
| \*\*$0.10\*\*       | 10% (Long Shot)         | $10.00                |
| $0.50               | 50% (Coin Flip)         | $2.00                 |
| $0.90               | 90% (Near Certainty)    | $1.11                 |

***

### Order Execution: No Latency, No Friction

#### The Order Type

All trades on TMB are Fill-or-Kill (FOK) Market Orders.

* Instant: Executes immediately at the best available price.
* All-or-Nothing: If the market is moving too fast and the full order can’t be filled at your price, the trade is cancelled so you don't get a "bad fill."

#### The Execution Flow

1. The Hold: You trigger an Action Block.
2. The Fetch: TMB grabs the best real-time price from the Polymarket CLOB (Central Limit Order Book).
3. The Fee: A transparent 1% platform fee is collected.
4. The Mint: Your Safe Smart Account signs the order and receives the Outcome Tokens.
5. The Flip: Your card flips to show your live position.

***

### The "Exit" Strategy: Selling Early

You don't have to wait for the clock to hit zero to get paid. Because TMB uses a live order book, you can trade your positions while the market is still active.

* Lock in Profit: If you bought YES at $0.50 and the price climbs to $0.80, you can sell early to bank that 30% gain.
* Cut Losses: If the market is moving against you, sell your shares back to the market to preserve your remaining capital.

> How to Sell: Tap any active position in your Profile or on the Flipped Card and hit Sell. The proceeds land back in your Safe wallet instantly.

***

### Market Resolution & Truth

How do we know who actually won? TMB relies on the UMA Optimistic Oracle.

UMA is a decentralized "truth machine." Once an event ends, a result is proposed. If no one disputes it during the challenge period, the outcome is finalized on-chain.

* Trustless: No human at TMB or Polymarket can "decide" who won to avoid paying out.
* Redeemable: Once UMA finalizes the result, your winning shares move to the Redeem tab in your Profile, ready to be converted into USDC.e.
