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
TMB gives you two ways to power your wallet. Whether you already have crypto or want to use your credit card, we’ve made the process seamless.

#### 1. Deposit with Google Pay / Apple Pay (MoonPay)

Perfect for those who don't own crypto or want a frictionless top-up using their credit card.

* How it works: We’ve integrated MoonPay to bridge the gap between your bank and the blockchain.
* Credit Card Bonus: Use your favorite credit card via MoonPay to rack up your standard card rewards, points, or cashback on your deposit.
* Speed: Near-instant delivery once the payment is approved.

#### The Steps:

1. Navigate to the Profile tab and tap Add Funds.
2. Select the Google Pay / Apple Pay option.
3. Enter the amount you wish to deposit.
4. Verify your identity (first-time users only) and confirm your purchase.
5. Delivery: Your USDC.e will appear in your TMB balance automatically.

***

#### 2. Deposit with Crypto (On-Chain)

If you already have USDC in another wallet (like MetaMask, Coinbase Wallet, or Phantom), you can move it to TMB directly.

* Supported Networks: Polygon (Direct), Base, and Arbitrum.
* The Bridge Experience: Sending from Base or Arbitrum? Don't sweat the technicals. TMB's integrated Relay Bridge automatically converts your funds into USDC.e on Polygon so they are ready for immediate trading.
* Speed: Polygon is near-instant; Base and Arbitrum typically take 1–5 minutes.

#### The Steps:

1. Tap the Plus (+) icon on the Home screen header or go to the Profile tab.
2. Tap Deposit.
3. Select your Source Chain (where your funds are currently sitting).
4. Enter the amount and confirm the transaction in your external wallet.

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
