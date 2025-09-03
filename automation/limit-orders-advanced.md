# Advanced Limit Orders Guide

This guide covers advanced strategies and technical details for power users of MEME AI's Smart Limit Orders system.

## Complete Trigger Reference

### Quick Reference Table

| Trigger Type | Range | Update Frequency | Best For |
|-------------|-------|------------------|----------|
| **Price** | Variable | Real-time | Classic TP/SL |
| **Security Score** | 0-100 | 5 minutes | Safety monitoring |
| **Liquidity Score** | 0-100 | 5 minutes | Exit liquidity |
| **Activity Score** | 0-100 | 10 minutes | Trading activity |
| **Community Score** | 0-100 | 30 minutes | Social sentiment |
| **Momentum Score** | 0-100 | 5 minutes | Trend following |
| **Quality Score** | 0-100 | 15 minutes | Overall health |
| **Market Cap** | >$0 | Real-time | Milestones |
| **Volume 24h** | >$0 | 5 minutes | Activity spikes |
| **Liquidity** | >$0 | 5 minutes | Pool depth |
| **Holders** | >0 | 10 minutes | Adoption |
| **Whale Holders** | 0-1000 | 30 minutes | Smart money |
| **Top 10 Supply %** | 0-100% | 30 minutes | Concentration |
| **Buy Ratio** | 0-100% | 5 minutes | Sentiment |

## Understanding Score Calculations

### Security Score Components
- **40%** - Contract verification status
- **20%** - Mint/freeze authority
- **20%** - LP burn/lock status
- **10%** - Audit status
- **10%** - Known vulnerabilities

### Liquidity Score Formula
```
Liquidity Score = (
  (Liquidity/MarketCap × 40) +
  (Number of LPs × 20) +
  (LP Lock % × 20) +
  (DEX Diversity × 20)
)
```

### Momentum Score Factors
- Price change velocity (30%)
- Volume momentum (25%)
- Holder growth rate (20%)
- Social mentions (15%)
- Buy/sell pressure (10%)

## Multi-Trigger Strategies

### The Quadruple Protection System

**Strategy Goal:** Maximum downside protection

```
Order 1: Price Stop Loss
- Trigger: Price
- Condition: Below
- Value: Entry Price × 0.80 (-20%)
- Amount: 100%

Order 2: Security Stop Loss
- Trigger: Security Score
- Condition: Below
- Value: 45
- Amount: 100%

Order 3: Liquidity Stop Loss
- Trigger: Liquidity
- Condition: Below
- Value: $50,000
- Amount: 100%

Order 4: Whale Dump Protection
- Trigger: Top 10 Supply %
- Condition: Above
- Value: 70%
- Amount: 100%
```

### The Profit Ladder System

**Strategy Goal:** Systematic profit taking

```
Order 1: First Target
- Trigger: Price
- Value: Entry × 1.5 (+50%)
- Amount: 25%

Order 2: Second Target
- Trigger: Price
- Value: Entry × 2.0 (+100%)
- Amount: 25%

Order 3: Third Target
- Trigger: Price
- Value: Entry × 3.0 (+200%)
- Amount: 25%

Order 4: Moon Bag Exit
- Trigger: Momentum Score
- Condition: Below
- Value: 25
- Amount: 25% (remaining)
```

### The Smart Entry System

**Strategy Goal:** Optimal entry timing

```
Monitor these before manual entry:
- Security Score > 60
- Liquidity Score > 50
- Community Score > 40
- Top 10 Supply % < 50%
- Buy Ratio > 60%

Then set protective orders immediately after entry.
```

## Whale Behavior Patterns

### Accumulation Signals
- Whale holders increasing (+2-3 per day)
- Top 10 % stable or slightly increasing
- Large buys with no immediate sells
- Shark holders also increasing

**Strategy:** Follow the accumulation
```
Take Profit Order:
- Trigger: Whale Holders
- Condition: Below
- Value: Current - 3
(Exit when whales start leaving)
```

### Distribution Signals
- Whale holders decreasing
- Top 10 % decreasing
- Multiple small sells
- Increased wallet dispersion

**Strategy:** Exit before dump
```
Stop Loss Order:
- Trigger: Whale Holders
- Condition: Below  
- Value: Current - 2
(Quick exit on distribution)
```

## Volume Analysis Strategies

### Volume Breakout Trading

**Identify Breakouts:**
- Normal daily volume × 3 = Breakout
- Sustained for 2+ hours = Valid
- With price increase = Bullish
- Without price increase = Caution

```
Take Profit Order:
- Trigger: Volume 24h
- Condition: Above
- Value: Average × 3
- Note: Combine with price target
```

### Volume Death Spiral

**Identify Death:**
- Volume < $50K for 3 days
- Declining holder count
- No social activity
- Widening spreads

```
Stop Loss Order:
- Trigger: Volume 24h
- Condition: Below
- Value: $50,000
- Action: Full exit
```

## Score Correlation Patterns

### High Correlation Pairs
These scores often move together:

**Security + Liquidity**
- Both drop = Major red flag
- Immediate exit recommended

**Momentum + Activity**
- Both rise = Strong trend
- Good entry signal

**Community + Holders**
- Both growing = Healthy adoption
- Long-term hold signal

### Divergence Patterns

**Price Up, Scores Down**
- Artificial pump likely
- Set tight stop losses

**Price Down, Scores Up**
- Accumulation opportunity
- Consider adding position

**Volume Up, Holders Flat**
- Wash trading possible
- Avoid or exit

## Time-Based Considerations

### Best Times for Order Execution

**High Liquidity Hours:**
- 9 AM - 12 PM EST
- 2 PM - 6 PM EST
- Weekend mornings

**Low Liquidity Hours:**
- 2 AM - 6 AM EST
- Weekend late nights
- Major holidays

### Order Duration Strategy

**Short-term Trades:** 7-day expiry
- Momentum plays
- Quick scalps
- News trades

**Medium-term:** 30-day expiry
- Standard positions
- Trend following
- Most strategies

**Long-term:** 90-day expiry
- Major milestones
- Security monitoring
- HODL protection

## Risk Management Framework

### Position Sizing with Orders

**Conservative Approach:**
- 5% of portfolio per token
- Stop loss at -10%
- Maximum risk: 0.5% of portfolio

**Moderate Approach:**
- 10% of portfolio per token
- Stop loss at -20%
- Maximum risk: 2% of portfolio

**Aggressive Approach:**
- 20% of portfolio per token
- Stop loss at -30%
- Maximum risk: 6% of portfolio

### Order Ladder Example

For a $10,000 position:

```
Stop Losses (Protection):
- $2,000 at Security Score < 40
- $3,000 at Price -15%
- $5,000 at Price -25%

Take Profits (Gains):
- $2,500 at +50%
- $2,500 at +100%
- $2,500 at +200%
- $2,500 at momentum peak
```

## Metric Threshold Guidelines

### By Token Age

**New Tokens (< 7 days):**
- Wide price ranges (±50%)
- Low score thresholds (>30)
- Focus on security metrics
- Quick profit taking

**Developing (7-30 days):**
- Moderate ranges (±30%)
- Medium thresholds (>50)
- Balance all metrics
- Gradual profit taking

**Established (> 30 days):**
- Tight ranges (±20%)
- High thresholds (>60)
- Focus on momentum
- Strategic holds

### By Market Cap

**Micro Cap (<$1M):**
- Expect 50%+ swings
- Security Score > 40 minimum
- Take profits aggressively
- Multiple stop losses

**Small Cap ($1M-$10M):**
- 30% swings normal
- Security Score > 50 preferred
- Balanced profit taking
- Standard protection

**Mid Cap ($10M-$100M):**
- 20% swings expected
- Security Score > 60 required
- Patient profit taking
- Focus on trends

## Troubleshooting Complex Orders

### Orders Not Executing

**Check in order:**
1. Token balance sufficient
2. SOL for fees (0.1 minimum)
3. Trigger actually reached
4. Order not expired
5. No conflicting orders

### Partial Fills

**Common causes:**
- Insufficient liquidity
- Slippage exceeded
- Multiple orders triggered
- Network congestion

**Solutions:**
- Increase slippage to 3-5%
- Reduce order size
- Space out triggers
- Avoid low liquidity tokens

### Cascading Orders

**Preventing cascades:**
- Don't set similar triggers
- Space price levels 10%+ apart
- Use different metrics
- Stagger amounts

## API Integration (Advanced)

### Webhook Notifications

Set up custom alerts:
```javascript
{
  "webhook_url": "your-server.com/webhook",
  "events": ["order_triggered", "order_filled"],
  "include_data": true
}
```

### Bulk Order Creation

Create multiple orders efficiently:
```javascript
const orders = [
  { type: 'stop_loss', trigger: 'price', value: price * 0.8 },
  { type: 'stop_loss', trigger: 'security_score', value: 40 },
  { type: 'take_profit', trigger: 'price', value: price * 1.5 }
];
```

## Performance Optimization

### Reduce Check Frequency
For less critical orders:
- Use daily checks for long-term
- Hourly for medium-term
- Minute checks only for active trading

### Order Priority System
1. Stop losses (highest)
2. Security triggers
3. Take profits
4. Monitoring orders (lowest)

---

🚀 **Master Tip:** The best traders use 5-7 orders per position covering different risk scenarios. Start simple and add complexity as you learn your token's behavior.