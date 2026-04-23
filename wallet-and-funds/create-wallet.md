---
description: >-
  TMB is built to get you straight into the action. We use Privy for
  authentication, which means no seed phrases, no browser extensions, and no
  private keys to lose in a desk drawer.
icon: credit-card
---

# Create Wallet

### Sign-Up Methods

<table><thead><tr><th width="374">Method</th><th>The Experience</th></tr></thead><tbody><tr><td>Email</td><td>Enter your address, grab the 6-digit code from your inbox, and you're in.</td></tr><tr><td>Google</td><td>One-tap OAuth. Fast, familiar, and secure.</td></tr><tr><td>X (Twitter)</td><td>Tap "Continue with Twitter" and authorize with your Twitter account via OAuth.</td></tr></tbody></table>

***

### The Lifecycle of Your Account

When you join TMB, a few things happen behind the scenes to make your experience frictionless:

1. Instant Embedded Wallet: Privy creates a non-custodial wallet on the Polygon blockchain the moment you sign up. This acts as your digital ID.
2. Home Screen Access: You’re immediately dropped into the Home feed to browse trending markets and live scores.
3. Smart Account Deployment: The first time you trade, we deploy your Safe Smart Account. Think of this as your "Trading Engine"-it’s the secure vault that holds your USDC and handles your trades.

#### Account Details

You can find these in your Profile tab at any time:

* Safe Address: Your dedicated trading address where funds are settled , visible on the Profile screen and on sidebar menu.

***

### The Tech Stack (For the Curious)

If you want to look under the hood, here is how we handle your security:

#### 🔐 Authentication Flow

1. User logs in via Privy (Social/Email).
2. TMB backend provides a nonce (a unique, one-time number).
3. Your embedded wallet signs a Sign-In with Ethereum (SIWE) message.
4. Our backend verifies the signature and issues a JWT.
5. You’re authorized to trade across the entire TMB ecosystem.

#### 🛡️ Security First

* Non-Custodial: TMB _never_ sees your private keys. They are managed in a secure enclave, meaning you-and only you-control your funds.
* No Seed Phrases: By tying your wallet to your social login, we eliminate the risk of losing a piece of paper. If you can get into your Gmail or X account, you can get into TMB.
* Session-Based: We use secure, expiring tokens to ensure that even if you leave your browser open, your account remains protected.

***

