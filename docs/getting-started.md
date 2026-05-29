# Getting Started with ATLAS Desktop App

This guide helps you set up ATLAS Desktop App and start using the new AI-powered trading workspace safely.

## Before You Begin

Make sure you have:

1. **Windows 10/11** (64-bit).
2. **MetaTrader 5** installed and logged in to your broker account.
3. **Internet access** for ATLAS AI or external AI providers.
4. **AI access** through ATLAS AI, your own API keys, or local models where supported.
5. **A risk plan** that defines your max daily loss, max position size, and when you stop trading.

> **Risk reminder:** ATLAS Desktop App can help analyze markets, organize workflows, and generate strategy ideas, but it cannot remove trading risk. AI may be wrong. You are responsible for every trade.

## Installation

1. Download the latest version from the [Releases page](https://github.com/ksdj9iqsxs12/atlas-releases/releases).
2. Run the installer.
3. Accept the license agreement and complete the wizard.
4. Launch ATLAS Desktop App from your desktop shortcut.

See the [Installation Guide](installation.md) for detailed instructions.

## First Launch

### 1. Configure AI Access

On first launch, choose how ATLAS Desktop App should access AI models:

- **ATLAS AI** - Integrated access for eligible paid users, testers, and limited-access users.
- **OpenAI-compatible providers** - Use your own key for GPT-class models when supported.
- **Anthropic/OpenRouter-style providers** - Use your own key for Opus-class, Sonnet-class, and other frontier models when supported.
- **Local models** - Use local inference where available for privacy-focused or offline-adjacent workflows.

New model-routing workflows are designed for frontier families such as GPT 5.5, GPT 5.4, GPT 4.7, GPT 4.6, GPT 4.5, Claude Opus-class models, Claude Sonnet 4.6, Claude Sonnet 4.5, Codex-class models, and other supported models as they become available through connected providers.

### 2. Connect to MetaTrader 5

1. Start MetaTrader 5.
2. Log in to your broker account.
3. Launch ATLAS Desktop App.
4. Confirm that the connection indicator shows MetaTrader 5 is available.

### 3. Set Risk Controls First

Before asking ATLAS for setups, configure:

- Max daily loss.
- Max risk per trade.
- Max open positions.
- Allowed symbols.
- Whether orders require manual confirmation.
- Emergency stop behavior.

### 4. Choose Your Trading Mode

| Mode | Best For |
|------|----------|
| **Manual** | Learning the app, discretionary trading, and reviewing AI analysis before acting. |
| **Semi-Auto** | Traders who want help with planning, stop loss, take profit, and setup review while keeping confirmation control. |
| **Full Auto** | Advanced users with tested strategies, strict limits, and a clear understanding of automation risk. |
| **Sleep** | Monitoring existing positions without opening new trades. |

Start with **Manual** mode until you understand how ATLAS Desktop App reads your charts and structures its analysis.

## Your First AI Workflow

### Manual Chart Review

1. Open a chart in MetaTrader 5, such as XAUUSD H1 or NAS100 M15.
2. In ATLAS Desktop App, ask: `Analyze this chart and explain the bullish and bearish cases.`
3. Review the response for market structure, key levels, invalidation, risk, and confidence.
4. Compare the response with your own plan before taking any action.

### Strategy Research Workflow

1. Ask ATLAS: `Build a strategy idea for XAUUSD that avoids low-liquidity periods and uses clear invalidation.`
2. Ask follow-ups: `What are the weaknesses?`, `What filters would reduce bad trades?`, and `How should this be backtested?`
3. Save promising ideas with bookmarks or notes.
4. Backtest and forward-test before considering live use.

### Agent-Assisted Session Prep

Use agents to create a trading brief:

1. Ask for a session watchlist.
2. Request key risk events to consider.
3. Compare XAUUSD, NASDAQ, and major FX pairs.
4. Save the important levels or assumptions as bookmarks.

## Key Concepts

### New Desktop Interface

Version 1.5 is built around a cleaner desktop workflow: AI chat, market context, bookmarks, strategy notes, tools, and agent actions are easier to reach from one workspace.

### Frontier AI Chat

ATLAS Desktop App can route different tasks to different models. A fast model may summarize notes, while a deeper model may review a complex strategy or chart. Availability depends on your plan, provider access, and connected keys.

### XAUUSD and NASDAQ Research Models

ATLAS includes workflows focused on gold and NASDAQ-style instruments. These workflows can target high-quality historical research thresholds such as 60%+ accuracy during internal testing, but live performance is never guaranteed.

### Strategy-Focused Models

Strategy-focused workflows help generate, critique, and refine trading systems. They are useful for finding missing filters, improving invalidation rules, reducing overfitting, and turning vague ideas into testable rules.

### Risk Guard

Built-in protections include max positions, daily loss controls, per-trade risk limits, confirmation settings, and emergency stops. Use them every time.

## Next Steps

- Read the [FAQ](faq.md).
- Configure risk limits before live trading.
- Try Manual mode with a demo account.
- Create your first AI-assisted strategy note.
- Test every strategy before using real capital.

## Troubleshooting

If you encounter issues:

1. Confirm that MetaTrader 5 is running and logged in.
2. Verify your ATLAS AI access or API key.
3. Check your internet connection.
4. Try a smaller or faster model.
5. Review logs in the Settings menu.
6. [Report a bug](https://github.com/ksdj9iqsxs12/atlas-releases/issues/new?template=bug_report.md).
