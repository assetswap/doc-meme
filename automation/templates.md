# Task Templates

Pre-built automation strategies you can activate with one click and customize to your needs.

## Available Templates

### 1. Daily Best Token Buyer
**What it does:** Every day at midnight UTC, this task scans all available tokens, identifies the highest-scoring ones (score 80+), and automatically purchases them with your specified amount.

**Example:** Set it to buy $50 worth of tokens daily. If BONK scores 85 and WIF scores 82, it will split your $50 between them proportionally based on their scores.

**Best for:** Consistent portfolio growth, catching new opportunities daily

**Customizable settings:**
- Daily budget ($10 - $1000)
- Minimum token score (60-95)
- Time of execution
- Maximum tokens to buy per day

---

### 2. Portfolio Health Monitor
**What it does:** Continuously monitors your holdings every 30 minutes, checking for warning signs like liquidity drops, score declines, or unusual selling pressure. Automatically exits positions that become risky.

**Example:** You hold $500 of PEPE. If liquidity suddenly drops by $200K (potential rug pull sign), the task immediately sells your position to protect your capital.

**Best for:** Risk management, protecting gains, avoiding rug pulls

**Customizable settings:**
- Check frequency (5 min - 24 hours)
- Liquidity drop threshold
- Score decline trigger
- Minimum position size to monitor

---

### 3. Profit Taker
**What it does:** Automatically takes profits when your positions reach specified gains, either selling completely or partially to secure profits while keeping exposure.

**Example:** You buy MYRO at $0.10. When it reaches $0.15 (50% gain), the task sells 50% of your position, securing profits while keeping half for potential further gains.

**Best for:** Locking in gains, removing emotion from selling

**Customizable settings:**
- Profit threshold (10% - 500%)
- Sell percentage (25% - 100%)
- Trailing stop option
- Token-specific targets

---

### 4. Stop Loss Guardian
**What it does:** Places automatic stop losses on all positions to limit downside risk, selling tokens that drop below your loss tolerance.

**Example:** Any token that drops 25% from your entry price is automatically sold, preventing small losses from becoming large ones.

**Best for:** Risk management, capital preservation

**Customizable settings:**
- Stop loss percentage (5% - 50%)
- Trailing stop option
- Time-based stops
- Exclude specific tokens

---

### 5. DCA Accumulator
**What it does:** Dollar-cost averages into selected tokens over time, buying fixed amounts at regular intervals regardless of price.

**Example:** Buy $20 of SOL every Monday, Wednesday, and Friday, accumulating a position over time while averaging out price volatility.

**Best for:** Long-term accumulation, reducing timing risk

**Customizable settings:**
- Token selection
- Amount per purchase
- Frequency (hourly to monthly)
- Total accumulation target

---

### 6. Whale Copycat
**What it does:** Monitors successful wallet addresses and copies their trades automatically, following smart money movements.

**Example:** When a tracked profitable wallet buys $1000 of a new token, your task automatically buys $50 worth (5% of their position size).

**Best for:** Following smart money, learning from successful traders

**Customizable settings:**
- Wallets to follow
- Copy percentage (1% - 100%)
- Minimum/maximum trade size
- Delay before copying

---

### 7. Social Buzz Hunter
**What it does:** Scans social media for rapidly trending tokens and automatically buys small positions in tokens gaining viral attention.

**Example:** When a token gets 1000+ mentions per hour on crypto Twitter with positive sentiment, buy $25 worth immediately.

**Best for:** Catching viral trends early, social momentum trading

**Customizable settings:**
- Social velocity threshold
- Sentiment requirements
- Maximum position size
- Platforms to monitor

---

### 8. Rebalancer
**What it does:** Maintains your desired portfolio allocation, automatically buying and selling to keep target percentages.

**Example:** You want 40% SOL, 30% top memes, 30% cash. When memes pump to 45% of portfolio, it sells some and buys SOL to restore balance.

**Best for:** Portfolio management, systematic investing

**Customizable settings:**
- Target allocations
- Rebalance frequency
- Deviation threshold
- Asset categories

---

### 9. New Launch Scout
**What it does:** Identifies brand new token launches, analyzes them for safety, and takes small positions in promising ones within the first hour.

**Example:** When a new token launches with verified contract, locked liquidity, and good initial metrics, automatically buy $10-20 worth.

**Best for:** Early entry opportunities, high risk/reward plays

**Customizable settings:**
- Age threshold (1-24 hours)
- Safety requirements
- Position size
- Maximum daily purchases

---

### 10. Liquidity Exit Watcher
**What it does:** Monitors liquidity levels of your holdings and exits positions before potential rug pulls or liquidity crises.

**Example:** You hold WAGMI token. When its liquidity pool drops from $500K to $250K in an hour, the task immediately sells your entire position.

**Best for:** Rug pull protection, safety-first trading

**Customizable settings:**
- Liquidity drop percentage
- Time window
- Minimum liquidity threshold
- Action (sell all/partial)

---

### 11. Score Improvement Buyer
**What it does:** Watches tokens that are improving in score and buys them as they cross into higher score brackets.

**Example:** BODEN token improves from score 55 to 71 over 3 days. As it crosses 70, the task automatically buys $100 worth.

**Best for:** Momentum trading, quality improvement plays

**Customizable settings:**
- Score improvement rate
- Threshold scores
- Time period
- Purchase amount

---

### 12. Night Shift Trader
**What it does:** Executes trades during off-peak hours when you're sleeping, ensuring you don't miss opportunities in different time zones.

**Example:** While you sleep (11 PM - 7 AM your time), the task actively trades with a $200 budget, buying high-score tokens and taking profits.

**Best for:** 24/7 market coverage, global opportunity capture

**Customizable settings:**
- Active hours
- Night budget
- Risk parameters
- Allowed operations

## How to Use Templates

### Activation Steps
1. Go to **Automation** → **Templates**
2. Browse available templates
3. Click **"Use Template"**
4. Adjust settings to your preference
5. Click **"Activate"**

### Customization
Every template is fully customizable:
- Change any parameter
- Add additional conditions
- Combine multiple templates
- Create variations

### Template Stacking
You can run multiple templates simultaneously:
- Daily Buyer + Profit Taker
- Stop Loss + Whale Copycat
- Portfolio Monitor + Rebalancer

## Creating Custom Tasks

### From Scratch
1. Click **"New Task"**
2. Define trigger conditions
3. Set actions to take
4. Test in simulation
5. Activate when ready

### From Templates
1. Start with closest template
2. Modify parameters
3. Add custom logic
4. Save as new template

## Best Practices

### Starting Out
- Begin with 1-2 templates
- Use small amounts initially
- Monitor performance daily
- Adjust based on results

### Advanced Usage
- Combine complementary templates
- Create task chains
- Use conditional logic
- Build complex strategies

### Risk Management
- Always use stop losses
- Diversify task types
- Set maximum daily spend
- Keep manual override ready

## Performance Tracking

### Task Analytics
Each template shows:
- Success rate
- Average returns
- Total profit/loss
- Execution count
- Best/worst trades

### Optimization
- Review weekly performance
- Adjust underperformers
- Scale successful tasks
- Test new variations

## Common Combinations

### Conservative Setup
- Portfolio Health Monitor
- Stop Loss Guardian
- Profit Taker (30% gains)

### Balanced Setup
- Daily Best Token Buyer
- Portfolio Health Monitor
- Profit Taker (50% gains)
- Stop Loss Guardian (25% loss)

### Aggressive Setup
- New Launch Scout
- Whale Copycat
- Social Buzz Hunter
- Liquidity Exit Watcher

### Smart DCA Setup
- DCA Accumulator (SOL)
- Score Improvement Buyer
- Rebalancer
- Stop Loss Guardian

## Template Updates

Templates are regularly updated based on:
- Market conditions
- User feedback
- Performance data
- New strategies

Check monthly for:
- New templates
- Improved algorithms
- Better parameters
- Strategy insights

## Support

### Getting Help
- Click template info icon
- Read detailed descriptions
- Watch video tutorials
- Ask AI for guidance

### Troubleshooting
- Task not executing? Check balance
- Poor performance? Review settings
- Unexpected behavior? Check logs
- Still stuck? Contact support