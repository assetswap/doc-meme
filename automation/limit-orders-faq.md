# Limit Orders FAQ

Quick answers to common questions.

## General Questions

### How fast do orders execute?
Orders check every minute. Execute within 60 seconds of trigger.

### What are the fees?
* Network fee: ~$0.02
* Swap fee: 1%
* No extra charges for limit orders

### Do orders work when I'm offline?
Yes! Orders run 24/7 on our servers.

### How many orders can I have?
* 20 per token
* 100 total across all tokens

### Can I set buy orders?
Not yet. Only sell orders. Buy orders coming soon!

### What happens when triggered?
1. Order executes automatically
2. Swaps to SOL or USDC
3. You get a notification
4. Shows in trade history

## Setup Issues

### "Insufficient Balance" Error
You need:
* The token you're trying to sell
* Minimum $10 worth
* Some SOL for fees (~$0.10)

### Can't Create Order
Check:
* You own the token
* Values are valid numbers
* Not at order limit (20 per token)

Try:
* Refresh page
* Clear browser cache
* Re-connect wallet

### Order Not Showing Up
* Check "Limit Orders" tab in wallet
* May take 30 seconds to appear
* Refresh if needed

## Execution Problems

### Order Didn't Trigger
Check if:
* Order expired (30 days default)
* Token still in wallet
* Trigger value was reached
* Enough liquidity exists

### High Slippage Warning
Your order executed but at worse price.

Fix:
* Set higher slippage tolerance
* Use smaller amounts
* Avoid low liquidity tokens

### Partial Execution
Only part of order filled.

Why:
* Not enough liquidity
* Price moved too fast
* Slippage limits hit

## Strategy Questions

### What Values Should I Use?

**For volatile tokens:**
* Wider stops (-30%)
* Higher profits (+100%)

**For stable tokens:**
* Tighter stops (-15%)
* Lower profits (+30%)

### Should I Use Multiple Orders?
Yes! Better to have:
* Multiple take profits
* Multiple stop losses
* Different metrics

### Which Metrics Matter Most?

**For safety:**
* Security Score
* Liquidity Score
* Top 10 Holders %

**For profits:**
* Price
* Momentum Score
* Volume

## Technical Issues

### Orders Disappearing
Orders expire after 30 days (default).
Set longer expiry when creating.

### Getting Notifications
1. Go to Settings
2. Enable notifications
3. Add email or Telegram
4. Test notification

### Wallet Not Connecting
Try:
* Different browser
* Update wallet extension
* Clear cache
* Use wallet connect

## Understanding Metrics

### What's a Good Security Score?
* 70+ = Safe
* 40-70 = Caution
* Below 40 = Risky

### What's Slippage?
Difference between expected and actual price.
* 1% = Normal
* 3% = High
* 5%+ = Very high

### What Are Whale Holders?
Wallets owning >1% of total supply.
More whales = more concentrated = more risk.

## Best Practices

### How Often Should I Check Orders?
* Active trading: Daily
* Long term: Weekly
* After major events: Always

### Should I Cancel Old Orders?
Yes if:
* Market changed significantly
* Strategy changed
* Token fundamentals changed

### Can I Copy Someone's Orders?
You can copy strategies but adjust for:
* Your risk tolerance
* Token specifics
* Account size

## Troubleshooting Steps

### Order Not Working?

1. **Check Balance**
   * Token still there?
   * Enough SOL for fees?

2. **Check Order Details**
   * Not expired?
   * Values make sense?
   * Right token?

3. **Check Market**
   * Enough liquidity?
   * Token still trading?
   * Price actually hit trigger?

4. **Contact Support**
   * Screenshot order
   * Note token and time
   * Describe issue

## Special Cases

### Token Renamed/Migrated
Orders won't transfer. Cancel and recreate.

### Network Congestion
Orders may delay during high traffic.
Still execute, just slower.

### Multiple Triggers at Once
Each executes independently.
Order depends on trigger time.

## Getting Help

### Quick Help
* In-app chat (bottom right)
* Hover over (?) icons

### Community Help
* [Discord](https://discord.gg/memeai)
* [Telegram](https://t.me/memeai)

### Support Ticket
* Email: support@meme.ai
* Include order ID
* Screenshot helpful

## Pro Tips

💡 **Start small** - Test with $20 orders first

💡 **Use percentages** - Better than fixed prices

💡 **Set and forget** - Don't watch constantly

💡 **Multiple exits** - Never all-or-nothing

💡 **Review weekly** - Markets change

Still have questions? Join our [Discord](https://discord.gg/memeai) and ask!