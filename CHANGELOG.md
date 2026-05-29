# Changelog

All notable changes to ATLAS Desktop App will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [Unreleased]

### Coming Soon

- Expanded strategy marketplace concepts
- More AI character and workspace customization
- Trade signal sharing experiments with stronger risk disclosures

---

## [1.5.0] - 2026-05-29

### Added

- **ATLAS Desktop App rebrand** - Updated product language from legacy product wording to ATLAS Desktop App.
- **New desktop interface** - Cleaner navigation, premium trader workspace layout, and easier access to tools, chat, notes, and market context.
- **Agent capabilities** - AI-assisted workflows for market prep, chart review, strategy critique, checklist creation, and research organization.
- **DOM and bookmark integrations** - Save key levels, trade ideas, instruments, and workflow context for faster session review.
- **Frontier model routing language** - Documentation now references newer model families such as GPT 5.5, GPT 5.4, GPT 4.7, GPT 4.6, GPT 4.5, Opus-class models, Sonnet 4.6, Sonnet 4.5, Codex-class models, and other supported providers.
- **XAUUSD and NASDAQ research workflows** - Added documentation for gold and NASDAQ-focused strategy research, including internal 60%+ historical accuracy targets with clear live-performance disclaimers.
- **Strategy-focused model workflows** - Added strategy-generation and refinement positioning for market inefficiency research, rule critique, and system improvement.
- **ATLAS AI access clarification** - Added FAQ language explaining paid access, selected free tester access, and free limited access.
- **Trading risk and legal notices** - Added stronger disclaimers that AI trading is at the user's own risk and is not financial advice.

### Changed

- Refreshed README, installation, getting-started, FAQ, and security language for the ATLAS Desktop App brand.
- Reframed the product as a desktop trading command center rather than a simple companion window.

---

## [2.0.0-beta.1] - 2026-01-26

### Added

- **Self-Improving AI** - System learns from your trading patterns
- **A/B Testing Framework** - Test prompt variations automatically
- **Market Regime Detection** - AI adapts to trending vs ranging markets
- **Auto Trigger System** - Fine-grained control over automation
- **Enhanced Memory System** - Multi-tier memory with semantic search

### Changed

- Improved tool execution loop (fixes max iterations bug)
- Better duplicate tool call prevention
- Enhanced logging infrastructure

### Fixed

- Max iterations reached error during normal chat
- Duplicate Price Data tool calls
- Memory extraction edge cases

---

## [1.0.0] - 2026-01-15

### Added

- Initial stable release
- Manual, Semi-Auto, Full Auto, and Sleep trading modes
- Neural Vision chart analysis
- LLM Strategy Forge for strategy generation
- Risk Guard Protocol with drawdown protection
- Multi-provider AI support
- Conversational trading interface
- MetaTrader 5 integration
- Memory system with RAG-based recall
- Backtesting engine with Monte Carlo simulation

### Security

- SQL injection prevention via ORM
- API key encryption
- Input sanitization for all user inputs

---

## [0.9.0] - 2025-12-01

### Added

- Beta testing release
- Core trading functionality
- Basic AI analysis

---

[Unreleased]: https://github.com/ksdj9iqsxs12/atlas-releases/compare/v1.5.0...HEAD
[1.5.0]: https://github.com/ksdj9iqsxs12/atlas-releases/compare/v2.0.0-beta.1...v1.5.0
[2.0.0-beta.1]: https://github.com/ksdj9iqsxs12/atlas-releases/compare/v1.0.0...v2.0.0-beta.1
[1.0.0]: https://github.com/ksdj9iqsxs12/atlas-releases/compare/v0.9.0...v1.0.0
[0.9.0]: https://github.com/ksdj9iqsxs12/atlas-releases/releases/tag/v0.9.0
