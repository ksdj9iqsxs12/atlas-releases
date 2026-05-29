# Frequently Asked Questions

## General

### What is ATLAS Desktop App?

ATLAS Desktop App is an AI-powered desktop trading workstation for Windows. It connects to MetaTrader 5 and gives traders a premium interface for chart analysis, AI chat, strategy research, risk workflows, bookmarks, DOM context, and agent-assisted market preparation.

### Why did the name change?

The product is now called **ATLAS Desktop App** because it has grown beyond a simple desktop layer. Version 1.5 is a full trading command center with AI tools, workflow utilities, model routing, agent features, and a redesigned interface for active traders.

### Is ATLAS Desktop App free?

ATLAS Desktop App is primarily a paid product because premium model access, infrastructure, ongoing research, updates, and support have real operating costs. Some users may receive free ATLAS AI access to test features, evaluate preview tools, or provide feedback. Some users may also receive free limited access with caps on usage, models, or features. Free access is not guaranteed, can change at any time, and does not replace paid plans.

### Which brokers are supported?

Any broker that offers MetaTrader 5 can be used, subject to your broker's rules, account type, market access, and execution conditions. ATLAS Desktop App connects to MetaTrader 5 rather than directly to brokers.

### Can I use ATLAS Desktop App on Mac or Linux?

ATLAS Desktop App is currently Windows-only. Mac and Linux support may be considered for a future release.

---

## Trading and Risk

### Will ATLAS Desktop App trade for me automatically?

ATLAS Desktop App can support Full Auto workflows when configured by the user, but we strongly recommend starting with Manual or Semi-Auto mode. You should understand the analysis, risk settings, strategy rules, and broker behavior before allowing any automation.

### Is my money safe?

No software can make trading risk-free. ATLAS Desktop App includes risk controls such as maximum position limits, daily loss limits, per-trade risk settings, minimum confidence thresholds, manual confirmations, and emergency stop controls. However, markets can move quickly, AI can be wrong, broker execution can vary, and losses can exceed expectations. Only trade with capital you can afford to lose.

### Is ATLAS Desktop App financial advice?

No. ATLAS Desktop App is educational, analytical, and workflow software. It does not provide financial, investment, legal, tax, brokerage, or fiduciary advice. AI outputs are informational only. You are solely responsible for deciding whether to trade, how much to risk, and whether any strategy is suitable for your account.

### What trading styles does ATLAS Desktop App support?

ATLAS Desktop App can assist with scalping, day trading, swing trading, position trading, discretionary analysis, and strategy research. Its memory and workflow tools help adapt the interface and analysis format to your preferred style.

### Can I trade forex, stocks, indices, gold, and crypto?

ATLAS Desktop App can analyze and work with instruments available through MetaTrader 5, including forex pairs, XAUUSD gold, NASDAQ-style index symbols such as NAS100 or US100 where supported, US30, crypto CFDs, and other broker-provided instruments.

### Do the XAUUSD or NASDAQ models guarantee 60%+ accuracy?

No. ATLAS strategy-lab workflows may use 60%+ historical accuracy as an internal promotion target for certain XAUUSD or NASDAQ research configurations, but this is not a live-trading guarantee. Accuracy depends on market regime, spread, slippage, broker execution, position sizing, news, liquidity, user settings, and whether the strategy remains valid.

---

## AI, Models, and Analysis

### Which AI models does ATLAS Desktop App support?

ATLAS Desktop App is designed for multi-provider model routing. Depending on provider availability, plan eligibility, and user configuration, it may work with newer frontier model families such as GPT 5.5, GPT 5.4, GPT 4.7, GPT 4.6, GPT 4.5, Claude Opus-class models, Claude Sonnet 4.6, Claude Sonnet 4.5, Codex-class models, and other supported models.

### What is ATLAS AI?

ATLAS AI is the app's integrated AI access layer for users who do not want to manage every provider manually or who are testing ATLAS-hosted features. Access can be paid, trial-based, free for selected testers, or free with strict limits. Availability, limits, and included models can change as we test features and manage provider costs.

### How does chart analysis work?

ATLAS Desktop App can capture chart context from MetaTrader 5 and send relevant information to vision-capable or reasoning-capable AI models. The AI may analyze trend, support and resistance, liquidity zones, market structure, volatility, order blocks, invalidation levels, and possible trade plans.

### What are strategy-focused models?

Strategy-focused models are ATLAS workflows tuned for market research and strategy refinement. They help identify rule gaps, test assumptions, generate new strategy ideas, improve entry and exit logic, add risk constraints, and find potential inefficiencies. They are research tools, not guaranteed profit engines.

### Can AI replace my trading judgment?

No. AI should be treated as a research assistant, not an authority. You must verify all outputs, consider current news and market conditions, review risk, and decide whether a trade makes sense for you.

### Does ATLAS Desktop App learn from my trades?

ATLAS Desktop App includes memory-assisted workflows that can remember preferences, trading rules, session focus, risk limits, and feedback. Where enabled, it can help adapt future analysis to your style. You should still review what is stored and avoid relying blindly on historical preferences.

### Can I use ATLAS Desktop App without an internet connection?

Some local workflows may be possible with local models, but cloud AI providers, ATLAS AI, updates, and many model-routing features require an internet connection.

---

## Desktop App 1.5

### What is new in version 1.5?

Version 1.5 introduces a redesigned desktop interface, new trader tools, agent capabilities, easier navigation, DOM and bookmark integration, improved AI chat workflows, strategy-research improvements, and better support for frontier model routing.

### What are agent capabilities?

Agent capabilities allow ATLAS to help with multi-step workflows such as preparing a market brief, comparing instruments, refining a strategy, generating a checklist, reviewing a chart, or organizing trade notes. Agents are assistants and must not be treated as autonomous financial advisers.

### What are bookmarks used for?

Bookmarks help you save important instruments, levels, trade ideas, chart states, research notes, and setups so you can return to them quickly instead of losing context during active sessions.

---

## Technical

### Does ATLAS Desktop App slow down my computer?

ATLAS Desktop App is designed to be lightweight for normal use. Resource usage depends on enabled tools, chart capture frequency, model calls, and local versus cloud inference.

### Can I run ATLAS Desktop App on a VPS?

Yes, ATLAS Desktop App can be used on a Windows VPS for longer-running workflows, subject to your VPS resources, broker permissions, and internet stability.

### Is my data secure?

ATLAS Desktop App is designed to keep sensitive configuration local where possible, encrypt API keys, and use your selected providers for model requests. Any data sent to external AI providers is subject to those providers' policies, so avoid sending secrets or information you do not want processed by a third party.

### How do I update ATLAS Desktop App?

ATLAS Desktop App checks for updates automatically when supported. You can also download newer builds from the Releases page and install them manually.

---

## Troubleshooting

### ATLAS Desktop App can't connect to MetaTrader 5

1. Ensure MetaTrader 5 is running and logged in.
2. Restart both MetaTrader 5 and ATLAS Desktop App.
3. Check Windows Firewall settings.
4. Verify that the required MetaTrader 5 integration is enabled and available.

### AI responses are slow

1. Try a faster model or provider.
2. Check your internet connection.
3. Reduce prompt size or chart context.
4. Use a smaller model for quick tasks and reserve frontier models for deeper analysis.

### Charts are not being analyzed correctly

1. Make sure the chart is visible and not covered by other windows.
2. Use a clean chart template.
3. Confirm that your selected model supports the needed vision or reasoning mode.
4. Add explicit context such as symbol, timeframe, session, and what you want analyzed.

---

## Support

### Where can I get help?

- [GitHub Issues](https://github.com/ksdj9iqsxs12/atlas-releases/issues) for bugs and features
- Documentation in this repository
- Community channels when available

### How do I report a bug?

Use our [bug report template](https://github.com/ksdj9iqsxs12/atlas-releases/issues/new?template=bug_report.md) on GitHub.

### How do I request a feature?

Use our [feature request template](https://github.com/ksdj9iqsxs12/atlas-releases/issues/new?template=feature_request.md) on GitHub.
