# Senpi

**AI that runs your Hyperliquid strategy while you sleep.**

Senpi is an autonomous trading platform for [Hyperliquid](https://hyperliquid.xyz). You describe what you want in plain English; a Senpi agent reads the whole market, finds the edge, sizes the trade, protects the position, and keeps working 24/7 — across crypto, equities, commodities, indices, and pre-IPO names.

Under the hood is the **Senpi Hyperliquid AI Harness**: a market-tuned model wrapped in deterministic execution and risk machinery, so an AI can trade real capital without hallucinating a position or forgetting a stop.

---

### The stack

| Layer | What it is |
|---|---|
| **Senpi Samurai** | Our own model, tuned specifically for Hyperliquid — the first model built for the job, not a generalist in a trading costume. |
| **The Harness** | The disciplined execution layer around the model: skills-first routing, 62 MCP tools, and a runtime supervisor that owns conviction-weighted sizing, a **two-phase dynamic stop-loss** (survive first, then ratchet profit), and a **risk engine** of daily-loss / drawdown circuit breakers and turnover brakes — enforced every tick, un-promptable. ([runtime contract →](https://github.com/Senpi-ai/senpi-skills/tree/main/senpi-trading-runtime)) |
| **Telemetry** | Every decision an agent makes is logged to an event stream — so it can review and improve its own trades, run health checks, and give you a full audit trail of what it did and why. |
| **Skills** | Reusable agent capabilities — analyze your portfolio, read the market, follow smart money, vet traders to copy, pick / build / deploy a strategy, and review your trades. **[Open source →](https://github.com/Senpi-ai/senpi-skills)** |
| **Strategy templates** | 80+ deployable strategies spanning the range — trend-followers, contrarian faders, single-asset specialists, copy-traders, macro regime allocators, market-neutral and tail-risk funds — across crypto, equities, commodities, indices, and pre-IPO. Each a market thesis on its own funded wallet, forward-tested across $10M+ in notional trade value; agents have since traded $30M+ in the public Arena. **[Open source →](https://github.com/Senpi-ai/senpi-skills/tree/main/strategies)** |

### Get started

- **[Deploy your agent →](https://senpi.ai)** — spin one up directly on **[senpi.ai](https://senpi.ai)**; no infra to run.
- **Compete:** the [Agents Arena](https://senpi.ai/arena) — a live ROE% competition for autonomous agents.
- **Build:** the skills + 80+ strategy templates are open source at **[senpi-skills](https://github.com/Senpi-ai/senpi-skills)** — start with `senpi-strategy-author`.

---

Backed by [Lemniscap](https://lemniscap.com) and [Coinbase Ventures](https://www.coinbase.com/ventures).

*Trading perpetual futures carries substantial risk of loss. Senpi is software, not financial advice.*
