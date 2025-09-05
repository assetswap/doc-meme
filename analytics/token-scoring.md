# How MEME AI Scores Tokens

MEME AI analyzes every token with a 100-point scoring system. Here's exactly how we calculate each score.

## Overall Token Score

Each token gets a score out of 100 points, like a grade in school. We look at 6 different things about each token and combine them for the final score:

| Metric | Weight | What It Measures |
|--------|--------|------------------|
| Liquidity | 25% | Can you buy and sell easily without affecting the price? |
| Activity | 20% | How many people are trading this token? |
| Momentum | 20% | Is the price going up or down? |
| Community | 15% | How many people support this token? |
| Security | 15% | Is it safe from scams or manipulation? |
| Maturity | 5% | How long has it been around and how stable is it? |

## Activity Score (100 points)

Evaluates trading engagement with a 100-point scale to measure real trading activity.

### 1. Multi-timeframe Trading (40% weight)
Analyzes trades across 1h, 4h, 24h periods:
- **100+ trades/period** = maximum points
- **Weighted distribution:**
  - 24h activity: 50%
  - 1h activity: 30%
  - 4h activity: 20%

### 2. Unique Wallet Engagement (35% weight)
| Unique Wallets | Points | Rating |
|----------------|--------|---------|
| 1000+ | 35 | Excellent |
| 500+ | 28 | Very Good |
| 100+ | 20 | Good |
| 50+ | 10 | Okay |
| <50 | 5 | Poor |

### 3. Buy/Sell Balance (25% weight)
We look at how many people are buying versus selling. A healthy token has both buyers and sellers:
- **40-60% buy ratio** = 25 points (perfect - almost equal buying and selling)
- **30-70% buy ratio** = 20 points (healthy balance)
- **20-80% buy ratio** = 15 points (acceptable but watch closely)
- **Extreme ratios** = Red flag (if everyone is only buying or only selling, something might be wrong)

### What Good Activity Looks Like
✅ Lots of trades throughout the day
✅ Many different wallets participating
✅ Balanced buying and selling
✅ Score above 70

### Red Flags
🚩 Only a few wallets trading
🚩 All buys or all sells
🚩 No recent activity
🚩 Score below 30

## Maturity Score (100 points)

Assesses market establishment with a 100-point scale to determine how stable and mature the token is.

### 1. Market Cap Tier (40% weight)
| Market Cap | Points | Classification |
|------------|--------|---------------|
| $100M+ | 40 | Established |
| $50M+ | 35 | Mature |
| $10M+ | 30 | Growing |
| $1M+ | 20 | Emerging |
| <$1M | 10 | Micro-cap |

### 2. Supply Distribution (30% weight)
**Top 10 Holders Concentration:**
- **<30%** = 15 points (excellent distribution)
- **30-50%** = 10 points (good)
- **50-70%** = 5 points (risky)
- **>70%** = 0 points (dangerous)

**Top 100 Holders Concentration:**
- **<80%** = 15 points (healthy)
- **>80%** = Lower score (concentration risk)

### 3. Token Supply in Circulation (20% weight)
This checks how many tokens are available now versus how many will ever exist (like checking if all the shares of a company are already sold or if more will be released later):
- **90%+ circulating** = 20 points (almost all tokens are already available - no surprises)
- **70-90%** = 15 points (most tokens are out there)
- **50-70%** = 10 points (more tokens might be released, which could lower the price)
- **<50%** = 5 points (lots more tokens coming - price might drop when released)

### 4. Holder Count (10% weight)
| Holders | Points | Community Size |
|---------|--------|---------------|
| 5000+ | 10 | Mature base |
| 1000+ | 8 | Good |
| 500+ | 6 | Growing |
| 100+ | 4 | Small |
| <100 | 2 | Tiny |

### What Good Maturity Looks Like
✅ Market cap over $10M
✅ Well distributed (top 10 < 50%)
✅ Thousands of holders
✅ Score above 60

### Red Flags
🚩 Top 10 hold over 70%
🚩 Very few holders
🚩 Low circulation percentage
🚩 Score below 30

## Other Important Scores

### Liquidity Score
Measures whether you can buy and sell the token without significant price impact. The score evaluates the pool size relative to market cap, checks available trading pairs, and estimates potential slippage for typical trade sizes.

### Momentum Score
Tracks whether the token is gaining or losing traction. The system analyzes price movements across multiple timeframes (1 hour, 24 hours, 7 days), monitors volume trends to spot increasing interest, and gauges social sentiment from community discussions.

### Community Score
Evaluates the strength and engagement of the token's community. This includes monitoring social media activity levels, tracking holder growth rates over time, and measuring engagement metrics like comments, shares, and active discussions.

### Security Score
Assesses the safety and trustworthiness of the token. The evaluation covers contract verification status, whether the token has been audited, any known security risks or vulnerabilities, and the reputation of the team behind the project.

## Reading the Scores

### Score Ranges
| Score | Grade | What It Means | Action |
|-------|-------|--------------|---------|
| 90-100 | A+ | Excellent | Strong buy signal |
| 70-89 | B | Good | Consider buying |
| 50-69 | C | Average | Research more |
| 30-49 | D | Poor | Be cautious |
| 0-29 | F | Failing | Avoid/Exit |

### For New Traders
Focus on tokens with:
* **Overall score 70+**
* **Security score 60+**
* **Activity score 50+**

### For Risk Takers
You might consider:
* **Lower scores (40-60)**
* **But NEVER below 30 security**
* **Check multiple metrics**

## How Autopilot Uses Scores

Autopilot leverages the scoring system to make intelligent trading decisions. It automatically filters out any tokens scoring below 50 overall to avoid poor investments. The system prioritizes tokens with scores above 70 for new positions. If any token's security score drops below 40, Autopilot will exit the position to protect your capital. Portfolio allocation is also balanced based on relative scores to optimize risk and reward.

## Quick Decision Guide

### Green Light (Buy)
✅ Overall score 70+
✅ Security score 60+
✅ Good activity (50+)
✅ Positive momentum

### Yellow Light (Caution)
⚠️ Overall score 50-70
⚠️ Check individual metrics
⚠️ Start small
⚠️ Set stop losses

### Red Light (Avoid)
🛑 Any score below 30
🛑 Security below 40
🛑 Top 10 hold >70%
🛑 No recent activity

## Pro Tips

Never ignore the Security Score as it serves as your primary safety net against scams and rug pulls. Activity matters because tokens with no trading activity are essentially dead investments. Always check multiple timeframes rather than just 24-hour data to understand true momentum. Distribution is critical - avoid tokens where whales control the majority of supply. Remember to combine all scores together since no single metric tells the complete story.

## Score Updates

The scoring system refreshes at different intervals to provide timely information. Activity scores update every hour to track trading patterns. Momentum scores refresh every 15 minutes to catch rapid price movements. Community metrics update every 4 hours to monitor social engagement. Security and Maturity scores update daily since these metrics change less frequently. Liquidity scores update in real-time to ensure accurate trading conditions.

Remember: Scores are guides, not guarantees. Always DYOR (Do Your Own Research)!