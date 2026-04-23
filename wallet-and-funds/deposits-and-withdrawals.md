---
description: >-
  TMB makes it easy to move funds in and out. Whether you’re coming from
  Polygon, Base, or Arbitrum, we handle the technical heavy lifting so your USDC
  is ready when the market moves.
icon: coin-vertical
---

# Deposits & Withdrawals

#### How to Fund Your Wallet

{% tabs %}
{% tab title="Deposits" %}
We support the most popular L2s to ensure you can fund your account from wherever you keep your liquidity.

1. Navigate to the Profile tab or click the plus icon on header on home page.
2. Tap Deposit.
3. Select your source chain (Polygon, Base, or Arbitrum).
4. Enter the amount and confirm the transaction.

> The Bridge Experience: If you're depositing from Base or Arbitrum, our integrated Relay bridge automatically converts your funds into the correct format on Polygon. This usually takes few minutes. If you're on Polygon, it’s near-instant.

***

#### Understanding USDC.e

On Polygon, there are two versions of USDC. TMB (and Polymarket) uses USDC.e (the bridged version).

Don't sweat the details-when you deposit via TMB, we automatically ensure your funds arrive as USDC.e so they are ready for immediate trading.

| Token         | Polygon Contract Address                     |
| ------------- | -------------------------------------------- |
| USDC.e        | `0x2791Bca1f2de4661ED88A30C99A7a9449Aa84174` |
| USDC (Native) | `0x3c499c542cef5e3811e1192ce70d8cc03d5c3359` |

**💡 Pro-Tips for Smooth Funding**

* The 1% Rule: Your balance needs to cover your preset trade amount plus a 1% platform fee. If you want to place a $10 prediction, make sure you have at least $10.10 in your wallet.
* The One-Time Setup: You must complete the one-time wallet setup (triggered by your first trade attempt) before you can withdraw.
* Patience is a Virtue: Bridging from other chains can take a few minutes. If your balance doesn't update immediately, grab a coffee-it’s on the way.
* Redeeming Wins: When you win a prediction, those funds are added to your Safe wallet balance. They stay there until you choose to withdraw them to an external address.
{% endtab %}

{% tab title="Withdrawals" %}
You can withdraw your USDC.e balance to any Polygon-compatible wallet address at any time.

**How to Withdraw**

1. Go to the Profile tab.
2. In the stats row, find the Winnings card and tap Withdraw.
3. Enter the recipient address (Double-check this! On-chain transactions are final).
4. Enter the amount (or tap Max) and hit Confirm.

***

**The Withdrawal Lifecycle**

* Confirming: Your wallet is signing the request.
* Pending: The Polygon network is processing the move.
* Completed: Funds have landed. You’ll see a link to PolygonScan for proof.
{% endtab %}
{% endtabs %}
