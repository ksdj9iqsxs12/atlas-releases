# Getting Started with Overlay

This guide will help you get up and running with Overlay AI Trading in minutes.

## Prerequisites

Before installing Overlay, ensure you have:

1. **Windows 10/11** (64-bit)
2. **MetaTrader 5** installed and logged into your broker account
3. **Internet connection** for AI model access
4. **API key** from at least one AI provider (Groq, OpenAI, or Google Gemini)

## Installation

1. Download the latest version from the [Releases page](https://github.com/ksdj9iqsxs12/overlay-releases/releases)
2. Run the installer (`AtlasOverlay-*.exe`)
3. Follow the installation wizard
4. Launch Overlay from your desktop shortcut

See [Installation Guide](installation.md) for detailed instructions.

## First Launch

### 1. Configure AI Provider

On first launch, Overlay will prompt you to configure an AI provider:

- **Groq** (Recommended) - Fast, free tier available
- **OpenAI** - GPT-4 quality, paid
- **Google Gemini** - Good balance of speed and quality
- **Ollama** - Run models locally (requires setup)

Enter your API key and select your preferred models.

### 2. Connect to MetaTrader 5

1. Ensure MetaTrader 5 is running
2. Overlay will auto-detect MT5 and connect
3. You'll see a green "Connected" indicator in the overlay

### 3. Choose Your Trading Mode

| Mode | Best For |
|------|----------|
| **Manual** | Learning, discretionary trading |
| **Semi-Auto** | Active traders wanting AI assistance |
| **Full Auto** | Passive income, tested strategies |
| **Sleep** | Away from keyboard, protecting positions |

Start with **Manual** mode to familiarize yourself with Overlay's capabilities.

## Your First Trade

### Manual Mode Example

1. Open a chart in MetaTrader 5 (e.g., EURUSD H1)
2. In Overlay, type: "Analyze this chart"
3. Overlay will screenshot and analyze the chart
4. Review the AI's analysis and suggestions
5. If you agree, execute the trade manually in MT5

### Semi-Auto Example

1. Enable Semi-Auto mode in Overlay
2. Type: "Look for buy setups on XAUUSD"
3. When AI finds a setup, it will ask for confirmation
4. Review the entry, SL, and TP
5. Click "Confirm" to execute, or "Reject" to skip

## Key Concepts

### Memory System

Overlay remembers your trading preferences:
- "I prefer tight stop losses" - AI will suggest smaller SLs
- "I like to trade the London session" - AI focuses on London hours
- "My max risk is 1% per trade" - AI respects your limits

### Risk Guard

Built-in protection features:
- Maximum positions limit
- Daily loss limit (default 5%)
- Per-trade risk limit (default 1%)
- Minimum confidence threshold

### Strategy Generation

Create custom strategies:
1. Type: "Create a strategy that buys when RSI is oversold and price is at support"
2. Review the generated Python code
3. Backtest the strategy
4. Deploy in Semi-Auto or Full Auto mode

## Next Steps

- Read the [FAQ](faq.md) for common questions
- Explore the different trading modes
- Create your first AI-generated strategy
- Join our community for tips and discussions

## Troubleshooting

If you encounter issues:
1. Check that MetaTrader 5 is running and logged in
2. Verify your API key is correct
3. Check your internet connection
4. Review logs in the Settings menu
5. [Report a bug](https://github.com/ksdj9iqsxs12/overlay-releases/issues/new?template=bug_report.md)
