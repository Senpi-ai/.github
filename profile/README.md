<div align="center">
  <a href="https://senpi.ai"><img src="../assets/senpi-github-banner.png" alt="Senpi - your AI quant for Hyperliquid" width="100%"/></a>

  <p>
    <a href="https://senpi.ai"><b>senpi.ai</b></a> ·
    <a href="https://trade.senpi.ai">Open the app</a> ·
    <a href="https://senpi.ai/resources">Docs and guides</a> ·
    <a href="https://x.com/senpi_ai">X</a> ·
    <a href="https://www.youtube.com/@Senpi-AI">YouTube</a> ·
    <a href="https://t.me/+VgP8Z8yPe045N2Ix">Telegram</a>
  </p>
</div>

## What is Senpi?

**Senpi is a non-custodial AI trading agent for Hyperliquid.** Your agent reads the market, codes your strategy and runs it 24/7 on Hyperliquid perps: crypto, stocks, indices, commodities and pre-IPO markets. You keep custody of your funds at all times.

Senpi is built by Senpi AI Inc. (Austin, TX). It is not the SenPi learning app.

- **Fixes your leaks.** Paste any Hyperliquid wallet. Your AI quant reads every fill and ranks what cost you most: late exits, oversized losers, fee drag.
- **Codes your strategy.** Describe a trade in plain English, or start from a [strategy template](https://senpi.ai/strategies). Senpi codes it and runs it 24/7 with a ratcheting stop.
- **Follows the smart money.** Senpi tracks Hyperliquid's Proven Traders (wallets with $1M+ in lifetime realized gains) and its biggest whales, around the clock.
- **Works where you already work.** Trade from the Senpi app, from Claude or ChatGPT, or from Claude Code, Codex and Cursor.

## Start here

| You want to | Go to |
|---|---|
| Trade with your own AI agent | [trade.senpi.ai](https://trade.senpi.ai) |
| Connect Claude, ChatGPT, Codex, Cursor or Grok to Senpi | [`senpi-plugin`](https://github.com/Senpi-ai/senpi-plugin) |
| Read, fork or contribute agent skills and strategy templates | [`senpi-skills`](https://github.com/Senpi-ai/senpi-skills) |
| Set up Senpi's hosted MCP server | [`senpi-mcp`](https://github.com/Senpi-ai/senpi-mcp) |
| Call the Hyperliquid API from Go | [`go-hyperliquid`](https://github.com/Senpi-ai/go-hyperliquid) |

## Free on senpi.ai, no account needed

- **[Hyperliquid traders](https://senpi.ai/traders):** where the Proven Traders and biggest whales have their money, asset by asset, plus every $1M+ move, position flip and near-liquidation as it happens.
- **[Hyperliquid assets](https://senpi.ai/assets):** every Hyperliquid perp ranked by what the smart money is doing, each with a plain-English Senpi read.
- **[Market data JSON](https://senpi.ai/resources/learn/hyperliquid-market-data-json):** a free, key-less JSON file for every Hyperliquid asset.

## Common questions

**How do I connect Claude or ChatGPT to Hyperliquid so it can place trades?**
Connect Senpi to your AI app. Your AI then researches the market and places trades on Hyperliquid through your own Senpi agent. Guide: [Connect Senpi to Claude, ChatGPT, Grok and Hermes](https://senpi.ai/resources/learn/connect-senpi-to-claude-chatgpt-grok-and-hermes). For Claude Code and Codex, install [`senpi-plugin`](https://github.com/Senpi-ai/senpi-plugin).

**How do I build a Hyperliquid trading bot in Python?**
There are two routes: the official Python SDK, or describing the strategy to Claude Code with Senpi. Both are covered in [How to code a trading strategy on Hyperliquid](https://senpi.ai/resources/learn/how-to-code-a-trading-strategy-on-hyperliquid). Senpi strategies are Python modules that export `scan(inputs, ctx)`, and the templates are open source in [`senpi-skills`](https://github.com/Senpi-ai/senpi-skills).

**How can I automate a trading strategy on Hyperliquid without coding?**
Describe it to your Senpi agent in plain English, or deploy a [strategy template](https://senpi.ai/strategies). See [How to automate a crypto trading strategy without coding](https://senpi.ai/resources/learn/automate-a-crypto-strategy-without-code).

**How do I copy trade on Hyperliquid?**
Senpi can mirror an experienced trader's positions with your own size and slippage settings. Research a trader on [senpi.ai/traders](https://senpi.ai/traders) first. Settings: [Mirror strategy settings](https://senpi.ai/resources/learn/mirror-strategy-settings).

**How can I see what smart money is trading on Hyperliquid?**
[senpi.ai/traders](https://senpi.ai/traders) shows the Proven Traders' positioning live, for free. [Senpi Daily Signals](https://senpi.ai/resources/senpi-daily-signals) keeps a dated log of where they're net long or short.

**Is Senpi safe? Can the agent withdraw my funds?**
Senpi is non-custodial: you keep custody of your funds, and the agent can't withdraw them. Each strategy trades from its own strategy wallet. Details: [Is Senpi safe?](https://senpi.ai/resources/learn/is-senpi-safe) and [Wallet security and non-custodial design](https://senpi.ai/resources/learn/wallet-security-and-non-custodial-design).

**What does Senpi cost?**

| Plan | Price / month | AI credits / month | Senpi trading fee |
|---|---|---|---|
| Free trial | Free for 14 days | $10, once | 0.03% |
| Pro | $50 | $55 | 0% |
| Advanced | $100 | $115 | 0% |
| Quant | $200 | $240 | 0% |

Live prices: [senpi.ai/pricing](https://senpi.ai/pricing).

## Official links

Senpi's only official sites are **senpi.ai**, **trade.senpi.ai** and **senpi.ai/resources**. Our code lives at **github.com/Senpi-ai**. Look-alike sites such as senpia.ai are not Senpi.

- Guides for people and AI agents: [senpi.ai/resources/llms.txt](https://senpi.ai/resources/llms.txt)
- Compare Senpi with other Hyperliquid tools: [senpi.ai/resources/compare](https://senpi.ai/resources/compare)
- Support: support@senpi.ai

<sub>Trading perpetual futures carries risk, including the loss of your funds. Nothing here is investment advice or a promise of returns.</sub>
