# Frequently Asked Questions

## General

### What is Overlay?

Overlay is an AI-powered trading assistant that runs as a desktop overlay on Windows. It connects to MetaTrader 5 and uses Vision-Language Models to analyze charts, generate strategies, and execute trades.

### Is Overlay free?

Overlay has a free tier with limited features. Premium plans unlock advanced AI models, more trading modes, and higher limits.

### Which brokers are supported?

Any broker that offers MetaTrader 5 is supported. Overlay connects to MT5, not directly to brokers.

### Can I use Overlay on Mac or Linux?

Currently, Overlay is Windows-only. Mac and Linux support is planned for a future release.

---

## Trading

### Will Overlay trade for me automatically?

Yes, in Full Auto mode. However, we recommend starting with Manual or Semi-Auto mode until you're comfortable with how Overlay analyzes markets.

### Is my money safe?

Overlay includes multiple safety features:
- Maximum position limits
- Daily loss limits
- Per-trade risk limits
- Emergency stop controls

However, all trading involves risk. Only trade with money you can afford to lose.

### What trading styles does Overlay support?

- Scalping
- Day trading
- Swing trading
- Position trading

Overlay adapts to your preferred style through its memory system.

### Can I trade forex, stocks, and crypto?

Yes, Overlay can trade any instrument available in MetaTrader 5. Most commonly:
- Forex pairs (EURUSD, GBPUSD, etc.)
- Gold (XAUUSD)
- Indices (US30, NAS100)
- Crypto (BTCUSD on supported brokers)

---

## AI & Analysis

### Which AI models does Overlay use?

Overlay supports multiple AI providers:
- Ollama (local models)
- Groq (Llama, Mixtral)
- OpenAI (GPT-4)
- Google Gemini
- OpenRouter (access to many models)

### How does chart analysis work?

Overlay captures screenshots of your MT5 charts and sends them to vision-capable AI models. The AI analyzes patterns, support/resistance, and market structure.

### Does the AI learn from my trades?

Yes, Overlay has a memory system that:
- Remembers your trading preferences
- Learns from your winning and losing trades
- Adapts recommendations based on your history

### Can I use Overlay without an internet connection?

You can use Overlay with local AI models via Ollama. However, cloud AI providers require internet access.

---

## Technical

### Does Overlay slow down my computer?

Overlay is designed to be lightweight. Typical resource usage:
- RAM: 200-500 MB
- CPU: 1-5% (spikes during AI calls)
- GPU: Not required (all processing is server-side)

### Can I run Overlay on a VPS?

Yes, Overlay works great on Windows VPS for 24/7 operation. Recommended specs:
- Windows Server 2019/2022
- 4GB RAM minimum
- Stable internet connection

### Is my data secure?

- API keys are stored encrypted locally
- Chat logs stay on your machine
- No trading data is sent to our servers
- AI analysis uses your chosen provider (Groq, OpenAI, etc.)

### How do I update Overlay?

Overlay checks for updates automatically. When a new version is available, you'll see a notification and can update with one click.

---

## Troubleshooting

### Overlay can't connect to MetaTrader 5

1. Ensure MT5 is running and logged in
2. Restart both MT5 and Overlay
3. Check Windows Firewall settings
4. Verify MT5 has the Python API enabled

### AI responses are slow

1. Try a faster AI provider (Groq is fastest)
2. Check your internet connection
3. Reduce the complexity of your prompts
4. Consider using smaller AI models

### "Max iterations reached" error

This was a bug in early versions. Please update to the latest version where this has been fixed.

### Charts aren't being analyzed correctly

1. Ensure the chart is fully visible in MT5
2. Remove any overlapping windows
3. Try a clean chart template
4. Ensure you're using a vision-capable AI model

---

## Support

### Where can I get help?

- [GitHub Issues](https://github.com/ksdj9iqsxs12/atlas-releases/issues) for bugs and features
- Documentation in this repository
- Community Discord (coming soon)

### How do I report a bug?

Use our [bug report template](https://github.com/ksdj9iqsxs12/atlas-releases/issues/new?template=bug_report.md) on GitHub.

### How do I request a feature?

Use our [feature request template](https://github.com/ksdj9iqsxs12/atlas-releases/issues/new?template=feature_request.md) on GitHub.
