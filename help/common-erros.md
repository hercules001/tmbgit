---
icon: message-exclamation
---

# Common Erros

### 📈 Trading & Market Errors

#### "Insufficient balance"

* The Cause: Your USDC.e balance is lower than your Preset trade amount + 1% fee.
* The Fix: Top up via the Profile tab. Remember: a $10 prediction requires $10.10 in your wallet.

#### "Fill-or-Kill order could not be filled"

* The Cause: The market moved too fast or liquidity is too thin for your trade size.
* The Fix: Try again immediately. If it keeps failing, try a slightly smaller trade amount or a more active market.

#### "Trading session expired"

* The Cause: Your secure connection to the market engine timed out.
* The Fix: Usually fixes itself. If not, refresh the app or toggle back to the Home screen.

***

### 🔐 Wallet & Setup Errors

#### "Safe deployment failed"

* The Cause: Your one-time trading wallet setup hit a snag on the Polygon network.
* The Fix: Wait 30 seconds and tap Continue again. Network congestion is the usual suspect.

#### "Invalid address" (Withdrawals)

* The Cause: The 0x address you entered is incorrect or formatted wrong.
* The Fix: Double-check the 42-character address. Note: TMB does not support ENS names (like name.eth) yet-use the full 0x address.

***

### 💸 Funding & Bridge Errors

#### "Bridge transaction failed"

* The Cause: The Relay bridge couldn't move your USDC from supported networks.
* The Fix: Ensure you have enough USDC _and_ gas (like ETH) on the source chain. Wait a few minutes and retry.

#### Balance not updating

* The Cause: Cross-chain moves take few minutes.
* The Fix: Grab a coffee. If it’s been over 10 minutes, check your Safe address on PolygonScan.

***

### 📱 App & Notification Errors

#### "Check browser permissions"

* The Cause: Your browser is blocking TMB from sending you win alerts.
* The Fix: Enable notifications in your browser settings. On iOS, you must add TMB to your Home Screen (PWA) to receive alerts.

💡 Pro-Tip: Having connectivity issues? If you are unable to connect to the app, get stuck in the authentication phase, or the interface feels laggy, switch your connection region and try again by refreshing the app.

***

### 💡 Still Stuck?

If these fixes don't get you back in the green, try a quick Log Out and Log In. This re-syncs your session and fixes 99% of persistent issues.

If the issue continues, reach out to us on [Telegram](https://t.me/tmbfun) for direct support.
