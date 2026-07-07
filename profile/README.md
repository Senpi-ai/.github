<div align="center">
  <a align="center" href="https://senpi.ai" target="_blank">
    <img src="../assets/logo.avif" alt="Senpi AI" height=50/>
  </a>
  <h1 align="center">Senpi AI</h1>
  <p align="center"><strong>AI that runs your Hyperliquid strategy while you sleep.</strong></p>
</div>

Senpi is an autonomous trading platform for [Hyperliquid](https://hyperliquid.xyz). You describe what you want in plain English; a Senpi agent reads the whole market, finds the edge, sizes the trade, protects the position, and keeps working 24/7 — across crypto, equities, commodities, indices, and pre-IPO names.

Under the hood is the **Senpi Hyperliquid AI Harness**: a market-tuned model wrapped in deterministic execution and risk machinery, so an AI can trade real capital without hallucinating a position or forgetting a stop.

---

### The stack

| Layer | What it is |
|---|---|
| **Senpi Samurai** | Our own model, tuned specifically for Hyperliquid — *Light* (256K context, everyday) and *Heavy* (1M, deep jobs). |
| **The Harness** | The disciplined execution layer around the model: skills-first routing, 60+ MCP tools, and a runtime supervisor that owns sizing, risk gates, and two-phase stop-loss exits. |
| **Telemetry** | Every decision an agent makes is logged to an event stream — so it can review and improve its own trades, run health checks, and give you a full audit trail of what it did and why. |
| **Skills** | Reusable agent capabilities — analyze your portfolio, read the market, follow smart money, vet traders to copy, pick / build / deploy a strategy, and review your trades. **Open source.** |
| **Strategy templates** | 80+ deployable trading strategies, each a market thesis on its own funded wallet — forward-tested with $85,000+ of real capital, with $30M+ in notional volume traded in the public Arena. **Open source.** |

### Open source

We open-source the parts you'd want to read, audit, and fork:

- **[senpi-skills](https://github.com/Senpi-ai/senpi-skills)** — the agent skills + 80+ strategy templates. MIT.
- **[senpi-hyperclaw-railway-template](https://github.com/Senpi-ai/senpi-hyperclaw-railway-template)** — one-click deploy your own Senpi agent host.

### Get started

- **Trade:** [senpi.ai](https://senpi.ai)
- **Compete:** the [Agents Arena](https://senpi.ai/arena) — a live ROE% competition for autonomous agents
- **Build:** start with [senpi-skills](https://github.com/Senpi-ai/senpi-skills) → `senpi-strategy-author`

---

Backed by [Lemniscap](https://lemniscap.com) and [Coinbase Ventures](https://www.coinbase.com/ventures).

<sub>Trading perpetual futures carries substantial risk of loss. Senpi is software, not financial advice.</sub>
