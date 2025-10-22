# 💳 AI Credits Usage Guide

## What are AI Credits?

AI Credits are the currency used to interact with AssetSwap's AI assistant. Every message you send consumes credits based on the complexity of your request and the tools used.

## How Credits Are Calculated

Your credit consumption is based on two factors:

### 1. Message Complexity (Token-based)
The length and complexity of your conversation determines the base credit cost:

| Complexity | Token Range | Credits | Example |
|------------|------------|---------|---------|
| **Quick Chat** | < 500 tokens | 1 credit | "Hi", "Thanks", "What's the price of BTC?" |
| **Simple** | 500-2,000 tokens | 2 credits | Basic questions, simple explanations |
| **Moderate** | 2,000-5,000 tokens | 3 credits | Detailed queries, short analysis |
| **Complex** | 5,000-10,000 tokens | 5 credits | In-depth analysis, multiple questions |
| **Very Complex** | 10,000-20,000 tokens | 8 credits | Comprehensive research, detailed strategies |
| **Extended** | 20,000-30,000 tokens | 25 credits | Large document analysis |
| **Large** | 30,000-40,000 tokens | 30 credits | Extensive reports |
| **Very Large** | 40,000-80,000 tokens | 60 credits | Multiple document processing |
| **Huge** | 80,000-100,000 tokens | 70 credits | Maximum context analysis |
| **Maximum** | > 100,000 tokens | 100 credits | Extreme processing tasks |

### 2. Tool Usage
Each tool the AI uses adds 1 credit to your cost:

| Tool Type | Credits | Examples |
|-----------|---------|----------|
| **Price Check** | +1 credit | Getting current token prices |
| **Balance Check** | +1 credit | Checking wallet balances |
| **Trade Execution** | +1 credit | Buying/selling tokens |
| **Market Analysis** | +1 credit | Analyzing market trends |
| **Portfolio Review** | +1 credit | Reviewing holdings |
| **Risk Assessment** | +1 credit | Calculating risks |

## Real-World Examples

### Quick Interactions (1-2 credits)
```
You: "What's the price of SOL?"
AI: [uses get_price tool] "SOL is currently $145.23"
Cost: 1 credit (tokens) + 1 credit (tool) = 2 credits
```

### Trading Operations (5-8 credits)
```
You: "Buy $100 worth of SOL"
AI: [uses get_price, check_balance, execute_trade tools]
Cost: 2 credits (tokens) + 3 credits (tools) = 5 credits
```

### Portfolio Analysis (10-15 credits)
```
You: "Analyze my portfolio performance this week"
AI: [uses multiple tools for comprehensive analysis]
Cost: 5 credits (tokens) + 8 credits (tools) = 13 credits
```

### Complex Research (25-50 credits)
```
You: "Write a detailed trading strategy for meme coins"
AI: [extensive response with market analysis tools]
Cost: 25 credits (tokens) + 10 credits (tools) = 35 credits
```

## A7X Token Rewards 🪙

You earn A7X tokens for every interaction:

| Credits Used | A7X Earned | Rate |
|--------------|------------|------|
| 1-9 credits | 1 A7X | Minimum reward |
| 10-19 credits | 1 A7X | 10% |
| 20-29 credits | 2 A7X | 10% |
| 30-39 credits | 3 A7X | 10% |
| 50 credits | 5 A7X | 10% |
| 100 credits | 10 A7X | 10% |

**Formula**: A7X = floor(credits ÷ 10) with minimum of 1

## Credit Management

### New User Bonus
- New users receive **100 free credits** upon signup
- This allows approximately:
  - 100 quick questions
  - 50 simple trades
  - 20 complex analyses
  - 10 comprehensive reports

### Low Credit Warning
- ⚠️ You'll see a warning when your balance drops below **20 credits**
- 🚫 You cannot send messages when you have **0 credits**

### Negative Balance
- If your last message costs more than your remaining credits, your balance can go negative
- Example: You have 5 credits, use a complex query costing 15 credits → Balance: -10
- You must add credits before sending another message

### Adding Credits
Visit [assetswap.ai/billing](https://assetswap.ai/billing) to:
- Purchase credit packages
- Set up pay-as-you-go billing
- View your usage history

## Tips to Save Credits

### 1. Be Concise
- ✅ "Buy $50 SOL" (2 credits)
- ❌ "I would like you to help me purchase fifty dollars worth of Solana tokens please" (3-4 credits)

### 2. Batch Questions
Instead of multiple messages, combine related questions:
- ✅ "What's the price of BTC, ETH, and SOL?" (single message, 3 tools = 4 credits)
- ❌ Three separate messages (3 messages × 2 credits = 6 credits)

### 3. Avoid Unnecessary Conversation
- ✅ Get straight to the point
- ❌ Excessive pleasantries or repeated questions

### 4. Use Simple Queries When Possible
- ✅ "BTC price" (1-2 credits)
- ❌ "Can you provide me with a detailed analysis of Bitcoin's current market price including historical context" (5-10 credits)

## Understanding Your Usage

### Check Your Balance
Your current credit balance is displayed in:
- Top navigation bar
- After each interaction
- Profile/settings page

### Usage Breakdown
After each message, you'll see:
- Credits consumed for this message
- Tool calls made
- Remaining balance
- Low balance warning (if < 20 credits)

## FAQ

**Q: Why do some simple questions cost more credits?**
A: If the AI needs to use tools (like checking prices or balances), each tool adds 1 credit.

**Q: Can I get free credits?**
A: New users get 100 free credits. Additional credits must be purchased.

**Q: What happens if I run out mid-conversation?**
A: Your last message will be processed (even if it makes your balance negative), but you'll need to add credits for the next message.

**Q: Do credits expire?**
A: No, purchased credits never expire.

**Q: How accurate is credit calculation?**
A: Very accurate - we count exact tokens used plus tools executed.

## Need Help?

- 📧 Email: support@assetswap.ai
- 💬 Discord: [Join our community](https://discord.gg/assetswap)
- 📖 More docs: [docs.assetswap.ai](https://docs.assetswap.ai)