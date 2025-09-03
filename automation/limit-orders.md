# Smart Limit Orders

Smart Limit Orders go beyond simple price triggers. They monitor 30+ different metrics about your tokens and automatically execute trades when your conditions are met. Think of them as your personal trading assistant that never sleeps.

## What Makes Them Smart?

Unlike traditional limit orders that only watch price, MEME AI's Smart Limit Orders can trigger on:
- 🎯 **Security scores** - Exit if token becomes risky
- 📊 **Market metrics** - React to volume spikes or crashes
- 🐋 **Whale movements** - Detect accumulation or dumps
- 👥 **Community health** - Monitor adoption trends
- 📈 **Momentum indicators** - Ride trends automatically

## Quick Start

### Creating Your First Order

1. Go to **Wallet** tab
2. Find your token
3. Click **"Set Limit Order"**
4. Choose order type:
   - **Take Profit** - Sell when things look good
   - **Stop Loss** - Sell when risks appear
5. Select what to monitor
6. Set your target value
7. Click **"Create Order"**

### Simple Example
**"Sell my BONK if it doubles in price"**
- Type: Take Profit
- Trigger: Price
- Condition: Above
- Value: (2x current price)

## Order Types Explained

### 🎯 Take Profit (TP)
Automatically sells when favorable conditions are met:
- Token reaches target price
- Momentum peaks
- Whale accumulation detected
- Community milestones hit

**Use when:** You want to lock in gains automatically

### 🛡️ Stop Loss (SL)
Automatically sells when risk conditions appear:
- Price drops below support
- Security score deteriorates
- Whales start dumping
- Liquidity disappears

**Use when:** You want to protect against losses

## Common Strategies

### 🛡️ "Protect Me From Rug Pulls"

Create these stop losses:
1. **Security Score** < 40 (contract risks)
2. **Top 10 Holders** > 70% (concentration risk)
3. **Liquidity Score** < 30 (can't exit)
4. **Price** -25% (maximum loss)

*Any trigger = automatic exit*

### 💰 "Take Profits Like a Pro"

Set multiple take profits:
1. Sell 25% at **+50%** gain
2. Sell 25% at **+100%** gain
3. Sell 25% at **+200%** gain
4. Keep 25% for moon potential

### 🐋 "Follow the Whales"

Monitor whale behavior:
1. **Buy** when whale count increases
2. **Sell** if Top 10 hold >60%
3. **Alert** on sudden whale exits

### 📈 "Ride the Momentum"

Momentum-based trading:
1. **Take Profit** when Momentum Score > 80
2. **Stop Loss** when Momentum Score < 30
3. **Alert** on volume spikes > $5M

## Understanding Metrics

### 🎯 Score Metrics (0-100)

Think of scores like grades in school:

| Score | Grade | What it Means |
|-------|-------|---------------|
| 90-100 | A+ | Excellent |
| 70-89 | B | Good |
| 50-69 | C | Average |
| 30-49 | D | Poor |
| 0-29 | F | Failing |

#### Key Scores Explained

**Security Score** - How safe is this token?
- 70+: Verified contract, safe to trade
- 40-70: Some risks, be cautious
- <40: High risk, consider exiting

**Liquidity Score** - Can I trade without issues?
- 70+: Excellent liquidity, low slippage
- 40-70: Moderate liquidity
- <40: Poor liquidity, high slippage risk

**Community Score** - How strong is the community?
- 70+: Active, growing community
- 40-70: Developing community
- <40: Weak or declining community

**Momentum Score** - Is it trending?
- 70+: Strong upward momentum
- 30-70: Neutral momentum
- <30: Losing steam, consider exit

**Quality Score** - Overall token quality
- 70+: High quality project
- 50-70: Moderate quality
- <50: Low quality, high risk

### 📊 Market Metrics

**Market Cap** - Total value of all tokens
- Use for milestone alerts ($1M, $10M, $100M)
- Set floors to exit if it drops too low

**24h Volume** - Daily trading activity
- High = lots of interest
- Low = dying momentum
- Spike = something happening

**Liquidity** - Available for trading
- >$1M: Excellent
- $100K-$1M: Good
- <$100K: Poor, expect slippage

**Holders** - Number of unique wallets
- Growing = adoption
- Stable = maturity
- Declining = losing interest

### 🐋 Whale Metrics

**Whale Holders** - Wallets with >1% of supply
- Increasing = smart money accumulating
- Decreasing = distribution phase

**Top 10 Holders %** - Concentration risk
- >70%: Extreme risk
- 50-70%: High concentration
- 30-50%: Moderate
- <30%: Well distributed

**Buy Ratio** - Buyers vs Sellers (24h)
- >70%: Strong buying (bullish)
- 30-70%: Mixed sentiment
- <30%: Heavy selling (bearish)

## Setting Smart Triggers

### For Price Targets

**Percentage-based (Recommended):**
- Take Profit: +50%, +100%, +200%
- Stop Loss: -10%, -20%, -30%

**Fixed price:**
- Use for psychological levels
- Round numbers often act as resistance

### For Score Triggers

**Safety thresholds:**
- Stop Loss: Current score -15 points
- Take Profit: Current score +15 points

**Example:**
- Current Security Score: 65
- Stop Loss trigger: 50 (exit if risky)
- Take Profit trigger: 80 (sell on improvement)

### For Market Metrics

**Volume triggers:**
- Take Profit: 3x average volume (hype)
- Stop Loss: <$50K daily (death)

**Holder triggers:**
- Take Profit: >10,000 holders
- Stop Loss: <1,000 holders

## Advanced Examples

### The Safety Net Setup
Comprehensive protection with multiple triggers:

```
Order 1: Stop Loss - Price below -20%
Order 2: Stop Loss - Security Score below 45
Order 3: Stop Loss - Top 10 Holders above 65%
Order 4: Stop Loss - Liquidity below $50K
Order 5: Take Profit - Price above +100%
```

### The Trend Follower
Ride momentum intelligently:

```
Order 1: Take Profit - Momentum Score above 85
Order 2: Take Profit - Volume above $5M
Order 3: Take Profit - Buy Ratio above 80%
Order 4: Stop Loss - Momentum Score below 30
```

### The Quality Filter
Only hold quality tokens:

```
Order 1: Stop Loss - Quality Score below 50
Order 2: Stop Loss - Security Score below 60
Order 3: Stop Loss - Community Score below 40
```

## Best Practices

### ✅ DO's
- **Start with small amounts** to test
- **Use multiple trigger types** for coverage
- **Set realistic targets** based on volatility
- **Review orders weekly** and adjust
- **Keep some SOL** for fees

### ❌ DON'Ts
- **Don't set triggers too tight** (allow for volatility)
- **Don't ignore security scores** (always set safety stops)
- **Don't use same settings** for all tokens
- **Don't forget expiration** dates (default 30 days)
- **Don't rely on one metric** alone

## Tips & Tricks

### Setting Trigger Values

**For volatile tokens:**
- Wider ranges (price ±30%)
- Lower score thresholds
- Higher volume requirements

**For stable tokens:**
- Tighter ranges (price ±15%)
- Higher score requirements
- Normal volume levels

### Common Mistakes to Avoid

1. **Setting triggers too close**
   - Tokens move 5-10% daily normally
   - Scores fluctuate 5-10 points
   - Give room for normal movement

2. **Ignoring liquidity**
   - Always check liquidity score
   - Low liquidity = high slippage
   - May not execute at expected price

3. **Forgetting about orders**
   - Orders expire (default 30 days)
   - Market changes require adjustments
   - Review active orders weekly

## Managing Orders

### Viewing Active Orders
1. Go to **Wallet** → **Limit Orders**
2. See all active orders
3. Shows current vs trigger values
4. Time until expiration

### Editing Orders
- Cannot edit active orders
- Cancel and create new one
- Instant cancellation
- No fees for cancelling

### Order Execution
When triggered:
1. System detects condition met
2. Automatically swaps to SOL/USDC
3. Notification sent
4. Shows in trade history
5. Order marked complete

## FAQs

**Q: How quickly do orders execute?**
Orders are checked every minute and execute immediately when triggered.

**Q: What are the fees?**
Only standard network fees (~$0.02) and swap fees (1%). No extra charges for limit orders.

**Q: Can I set buy orders?**
Currently only sell orders. Buy orders coming soon!

**Q: Do orders work offline?**
Yes! Orders run 24/7 on our servers even when you're not logged in.

**Q: How many orders can I have?**
Up to 20 active orders per token, 100 total.

**Q: What if multiple orders trigger?**
Each executes independently in order of trigger time.

**Q: Can I get notifications?**
Yes! Enable notifications in settings for email/telegram alerts.

**Q: What's the minimum order?**
$10 minimum to cover fees and ensure execution.

## Troubleshooting

### Order Not Triggering?
- Check token balance still available
- Verify trigger condition is correct
- Ensure order hasn't expired
- Confirm trigger value is realistic

### High Slippage on Execution?
- Increase slippage tolerance (default 1%)
- Check liquidity before setting orders
- Consider smaller amounts
- Avoid low liquidity tokens

### Can't Create Order?
- Verify you own the token
- Check minimum balance ($10)
- Ensure values are valid
- Try refreshing the page

## Pro Strategies

### The Accumulator's Exit
For long-term holds with smart exits:
- Stop Loss: Security Score < 40
- Take Profit 1: Price +300%
- Take Profit 2: Market Cap > $100M
- Emergency Exit: Liquidity < $25K

### The Scalper's Setup
For quick in-and-out trades:
- Take Profit: Price +15%
- Stop Loss: Price -5%
- Momentum Exit: Score < 40
- Volume Exit: < $100K daily

### The Safety-First Approach
Maximum protection priority:
- Stop Loss 1: Price -15%
- Stop Loss 2: Any score < 45
- Stop Loss 3: Whale concentration > 60%
- Only Take Profit: +100% minimum

---

🎯 **Ready to Set Smart Orders?** Head to your wallet and create your first limit order. Start with simple price triggers, then explore advanced metrics as you learn!