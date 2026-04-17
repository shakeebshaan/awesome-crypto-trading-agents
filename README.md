# Awesome Crypto Trading Agents [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of open-source AI-powered crypto trading agents, quant frameworks, and algorithmic trading bots — with a focus on BTC, hedging strategies, and agentic workflows for 2026.

[![Stars](https://img.shields.io/github/stars/shakeebshaan/awesome-crypto-trading-agents?style=flat-square&color=yellow)](https://github.com/shakeebshaan/awesome-crypto-trading-agents/stargazers)
[![Forks](https://img.shields.io/github/forks/shakeebshaan/awesome-crypto-trading-agents?style=flat-square&color=blue)](https://github.com/shakeebshaan/awesome-crypto-trading-agents/network/members)
[![Last Commit](https://img.shields.io/github/last-commit/shakeebshaan/awesome-crypto-trading-agents?style=flat-square&color=green)](https://github.com/shakeebshaan/awesome-crypto-trading-agents/commits/main)
[![License: CC0](https://img.shields.io/badge/License-CC0-orange.svg?style=flat-square)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](#contributing)

**Maintained by [@shakeebshaan](https://github.com/shakeebshaan)** · [Contributing](#contributing) · [License: CC0](#license)

### Related projects by the same author

- **[btc-hedge-lab](https://github.com/shakeebshaan/btc-hedge-lab)** — OSS playground for BTC hedging strategies (delta, basis, funding, collars)
- **[claude-code-quant-skills](https://github.com/shakeebshaan/claude-code-quant-skills)** — Claude Code skills tuned for quant research & backtesting

---

## Contents

- [AI Agent Frameworks](#ai-agent-frameworks)
- [Classical Trading Bots](#classical-trading-bots)
- [Backtesting Engines](#backtesting-engines)
- [Strategy Libraries](#strategy-libraries)
- [Data & Market Feeds](#data--market-feeds)
- [Reinforcement Learning](#reinforcement-learning)
- [Execution & Broker Abstraction](#execution--broker-abstraction)
- [Risk & Hedging](#risk--hedging)
- [Monitoring & Observability](#monitoring--observability)
- [LLM + Trading](#llm--trading)
- [Research & Papers](#research--papers)

---

## AI Agent Frameworks

Trading bots powered by autonomous AI agents — multi-step reasoning, tool use, and market-context awareness.

- **[jesse-ai/jesse](https://github.com/jesse-ai/jesse)** — Advanced crypto trading bot in Python; "personal AI quant" with Monte Carlo mode.
- **[freqtrade/freqtrade](https://github.com/freqtrade/freqtrade)** — Free OSS crypto bot, 40k+ stars; supports ML via FreqAI (adaptive prediction modeling).
- **[asavinov/intelligent-trading-bot](https://github.com/asavinov/intelligent-trading-bot)** — Feature engineering + ML signals.
- **[tensortrade-org/tensortrade](https://github.com/tensortrade-org/tensortrade)** — Reinforcement learning framework for trading agents.

## Classical Trading Bots

- **[hummingbot/hummingbot](https://github.com/hummingbot/hummingbot)** — Market-making and arbitrage bot, multi-exchange.
- **[StephanAkkerman/fintwit-bot](https://github.com/StephanAkkerman/fintwit-bot)** — Social-signal Discord bot.
- **[CyberPunkMetalHead/Binance-volatility-trading-bot](https://github.com/CyberPunkMetalHead/Binance-volatility-trading-bot)** — Binance volatility hunter.

## Backtesting Engines

- **[kernc/backtesting.py](https://github.com/kernc/backtesting.py)** — Lightweight, fast Python backtesting.
- **[mementum/backtrader](https://github.com/mementum/backtrader)** — Feature-rich OSS backtester.
- **[polakowo/vectorbt](https://github.com/polakowo/vectorbt)** — Vectorized NumPy-based backtesting at scale.
- **[nautechsystems/nautilus_trader](https://github.com/nautechsystems/nautilus_trader)** — High-performance event-driven system (Rust + Python).

## Strategy Libraries

- **[twopirllc/pandas-ta](https://github.com/twopirllc/pandas-ta)** — 130+ indicators for pandas.
- **[mrjbq7/ta-lib](https://github.com/mrjbq7/ta-lib)** — Technical analysis library.
- **[bukosabino/ta](https://github.com/bukosabino/ta)** — Pure-Python TA lib, easy install.

## Data & Market Feeds

- **[ccxt/ccxt](https://github.com/ccxt/ccxt)** — Unified crypto exchange API (100+ exchanges).
- **[binance/binance-connector-python](https://github.com/binance/binance-connector-python)** — Official Binance client.
- **[ranaroussi/yfinance](https://github.com/ranaroussi/yfinance)** — Yahoo finance data scraper.

## Reinforcement Learning

- **[AI4Finance-Foundation/FinRL](https://github.com/AI4Finance-Foundation/FinRL)** — RL for quantitative finance.
- **[AI4Finance-Foundation/ElegantRL](https://github.com/AI4Finance-Foundation/ElegantRL)** — Cloud-native DRL library.

## Execution & Broker Abstraction

- **[ccxt/ccxt](https://github.com/ccxt/ccxt)** — Unified order execution across 100+ exchanges.
- **[Hummingbot Gateway](https://github.com/hummingbot/gateway)** — DEX protocol gateway.

## Risk & Hedging

- **[microprediction/precise](https://github.com/microprediction/precise)** — Covariance-based portfolio tooling.
- **[quantopian/pyfolio](https://github.com/quantopian/pyfolio)** — Performance & risk analytics.
- **[shakeebshaan/btc-hedge-lab](https://github.com/shakeebshaan/btc-hedge-lab)** — Educational hedging strategies for BTC (active research).

## Monitoring & Observability

- **[grafana/grafana](https://github.com/grafana/grafana)** — Dashboards for PnL / metrics.
- **[prometheus/prometheus](https://github.com/prometheus/prometheus)** — Time-series metrics store.

## LLM + Trading

New category for 2026 — agents that combine LLMs with market data and order execution.

- **[shakeebshaan/claude-code-quant-skills](https://github.com/shakeebshaan/claude-code-quant-skills)** — Claude Code skills tuned for quant research, backtesting, strategy analysis.
- **[anthropics/anthropic-cookbook](https://github.com/anthropics/anthropic-cookbook)** — Claude API patterns including tool-use for finance workflows.

## Research & Papers

- [Deep Reinforcement Learning for Trading (arXiv)](https://arxiv.org/abs/1911.10107)
- [Advances in Financial Machine Learning — López de Prado](https://www.wiley.com/en-us/Advances+in+Financial+Machine+Learning-p-9781119482086)

---

## Contributing

PRs welcome. Add entries alphabetically within each category, format:

```
- **[owner/repo](link)** — one-line description focused on what makes it distinctive.
```

Entries must be:
1. Open source with an active commit history (last 6 months)
2. Specifically applicable to crypto or cross-asset algorithmic trading
3. Not a fork or derivative without meaningful additions

## License

[CC0 1.0 Universal](LICENSE) — public domain dedication. Use freely.
