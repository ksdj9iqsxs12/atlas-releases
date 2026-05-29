# ATLAS Desktop App

<p align="center">
  <img src="https://raw.githubusercontent.com/ksdj9iqsxs12/atlas-releases/main/assets/logo.png" alt="ATLAS Logo" width="120">
</p>

<p align="center">
  <strong>The AI-powered desktop command center for traders who want sharper analysis, faster workflows, and better market structure awareness.</strong>
</p>

<p align="center">
  <a href="#downloads">Download</a> •
  <a href="#features">Features</a> •
  <a href="docs/getting-started.md">Get Started</a> •
  <a href="docs/faq.md">FAQ</a> •
  <a href="CHANGELOG.md">Changelog</a>
</p>

---

## What is ATLAS Desktop App?

ATLAS Desktop App is the next evolution of ATLAS: a premium AI trading workstation for Windows that connects to MetaTrader 5 and helps traders research, analyze, manage, and refine their market decisions from one polished desktop experience.

Version 1.5 focuses on making the desktop app feel faster, smarter, and more useful every day. It brings a redesigned interface, deeper agent capabilities, richer chart workflows, DOM and bookmark integrations, and a frontier-model chat experience built for serious traders. Instead of being just a chart assistant, ATLAS Desktop App acts like a full trading co-pilot: it can study XAUUSD, NASDAQ, forex, indices, crypto, and custom strategies while helping you organize the work behind each decision.

> **Important trading risk notice:** ATLAS Desktop App is educational, analytical, and workflow software. It is not financial, investment, legal, tax, or brokerage advice. AI-generated analysis can be wrong, incomplete, delayed, or unsuitable for your account. Trading involves substantial risk and can result in the loss of some or all of your capital. You are solely responsible for every trading decision, order, position size, strategy, broker connection, and outcome. Use AI in trading at your own risk.

---

## Downloads

| Version | Channel | Download | Notes |
|---------|---------|----------|-------|
| **v1.5.0** | Desktop Preview | [Releases](https://github.com/ksdj9iqsxs12/atlas-releases/releases) | Redesigned ATLAS Desktop App with new tools, agent capabilities, and model routing |
| **v1.0.0** | Stable | [Releases](https://github.com/ksdj9iqsxs12/atlas-releases/releases) | Legacy stable build |
| **v2.0.0-beta.1** | Beta | [Releases](https://github.com/ksdj9iqsxs12/atlas-releases/releases) | Experimental self-improving AI build |

**System Requirements:**
- Windows 10/11 (64-bit)
- MetaTrader 5 terminal
- 8GB RAM minimum, 16GB recommended
- Internet connection for cloud AI models
- Optional provider API keys for premium model access

---

## Features

### Desktop App 1.5 Improvements

- **New desktop interface** - A cleaner, more premium workspace built to reduce friction and keep analysis, chat, strategy notes, bookmarks, and tools close at hand.
- **Agent capabilities** - ATLAS agents can help break down market questions, inspect charts, compare setups, refine prompts, summarize plans, and assist with repeatable trading workflows.
- **Tool-rich trader workspace** - Built-in utilities for chart review, strategy notes, watchlist context, session preparation, risk reminders, and workflow organization.
- **DOM and bookmark integration** - Keep important market levels, trade ideas, setups, and decision points easier to revisit.
- **Ease-of-use upgrades** - Faster navigation, clearer controls, and a desktop-first layout designed for traders who need speed without clutter.

### Trading Modes

| Mode | Description |
|------|-------------|
| **Manual** | ATLAS suggests setups and context while you execute manually. |
| **Semi-Auto** | ATLAS helps manage SL/TP and trade planning while you confirm entries. |
| **Full Auto** | Strategy-driven execution with strict risk controls and user configuration. |
| **Sleep** | No new trades; ATLAS monitors existing positions and preserves risk limits. |

### AI and Model Capabilities

- **Frontier-model chat** - Route trading conversations through newer model families when available through your connected providers, including GPT 5.5, GPT 5.4, GPT 4.7, GPT 4.6, GPT 4.5, Claude Opus-class models, Claude Sonnet 4.6, Claude Sonnet 4.5, Codex-class models, and additional provider models.
- **Chart vision and reasoning** - Screenshots and chart context can be analyzed for trend, liquidity, support/resistance, order blocks, volatility, and invalidation zones.
- **Multi-provider flexibility** - Connect supported providers through your own keys or available ATLAS AI access, depending on your plan and eligibility.
- **Memory-assisted workflow** - ATLAS can remember preferences such as session focus, risk limits, strategy rules, and the way you like analysis structured.
- **AI-powered trading chat** - Ask ATLAS to explain a setup, challenge your bias, draft a plan, generate checklist questions, or compare multiple instruments.

### New Work Features for Strategy Research

- **XAUUSD and NASDAQ-focused model workflows** - New research flows help study gold and NASDAQ conditions, identify repeatable setups, and score opportunity quality. Internal strategy-lab runs may target 60%+ historical accuracy thresholds before a workflow is promoted, but no accuracy number is guaranteed in live markets.
- **Strategy-focused models** - Specialized strategy agents are designed to ingest market context, identify potential inefficiencies, find gaps in existing rules, generate new strategy ideas, and refine strategies with clearer entries, exits, invalidations, and risk constraints.
- **Market-knowledge synthesis** - ATLAS can combine chart context, user notes, historical observations, and strategy rules to help discover where a strategy may be overfitted, under-specified, or missing key market filters.

### Illustrative Model Benchmark Framework

These are positioning estimates for ATLAS routing and product planning, not audited third-party benchmarks and not promises of trading performance.

| Model family | Reasoning depth | Chart-analysis fit | Strategy-writing fit | Speed profile |
|--------------|-----------------|--------------------|----------------------|---------------|
| GPT 5.5 / GPT 5.4 class | Very high | Excellent | Excellent | Medium |
| GPT 4.7 / 4.6 / 4.5 class | High | Very good | Very good | Medium-fast |
| Claude Opus-class | Very high | Excellent for deep review | Excellent | Medium |
| Claude Sonnet 4.6 / 4.5 class | High | Very good | Very good | Fast-medium |
| Codex-class | High for code and tooling | Good with structured inputs | Excellent for strategy logic | Medium |

### Risk Management

- Maximum position limits
- Daily loss limits
- Per-trade risk percentage controls
- Minimum confidence thresholds
- Emergency stop controls
- Manual confirmation workflows
- Clear reminders that AI output is not a guarantee, signal service, or replacement for your own judgment

---

## Quick Start

1. **Download** the installer from [Releases](https://github.com/ksdj9iqsxs12/atlas-releases/releases).
2. **Run** the installer and accept the license agreement.
3. **Start** MetaTrader 5 and log in to your broker.
4. **Launch** ATLAS Desktop App from your desktop.
5. **Configure** your AI provider, ATLAS AI access, or API keys.
6. **Start in Manual mode** and use AI analysis only as one input in your decision process.

See the [Getting Started Guide](docs/getting-started.md) for detailed setup instructions.

---

## Legal and Safety Notice

By using ATLAS Desktop App, you acknowledge that:

- Trading is risky and past performance does not guarantee future results.
- AI models can hallucinate, misunderstand charts, miss news, misread market conditions, or generate unsuitable strategies.
- Any examples, benchmarks, strategy notes, accuracy references, or model comparisons are informational only.
- You are responsible for reviewing all outputs, setting risk controls, complying with laws and broker rules, and deciding whether to trade.
- ATLAS Desktop App does not guarantee profits, accuracy, uptime, execution quality, broker compatibility, or loss prevention.

---

## Documentation

- [Getting Started](docs/getting-started.md)
- [Installation Guide](docs/installation.md)
- [FAQ](docs/faq.md)
- [Changelog](CHANGELOG.md)

---

## Support

- **Bug Reports**: [Create an issue](https://github.com/ksdj9iqsxs12/atlas-releases/issues/new?template=bug_report.md)
- **Feature Requests**: [Request a feature](https://github.com/ksdj9iqsxs12/atlas-releases/issues/new?template=feature_request.md)
- **Security Issues**: See [SECURITY.md](SECURITY.md)

---

## License

ATLAS Desktop App is proprietary software. See the End User License Agreement included with the download.

---

<p align="center">
  <sub>Built for the next generation of AI-assisted traders.</sub>
</p>
