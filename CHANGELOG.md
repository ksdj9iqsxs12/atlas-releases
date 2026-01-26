# Changelog

All notable changes to Overlay AI Trading will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [Unreleased]

### Coming Soon
- Strategy marketplace
- AI character customization
- Trade signal sharing

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
- Multi-provider AI support (Ollama, Groq, OpenAI, Gemini, OpenRouter)
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

[Unreleased]: https://github.com/ksdj9iqsxs12/overlay-releases/compare/v2.0.0-beta.1...HEAD
[2.0.0-beta.1]: https://github.com/ksdj9iqsxs12/overlay-releases/compare/v1.0.0...v2.0.0-beta.1
[1.0.0]: https://github.com/ksdj9iqsxs12/overlay-releases/compare/v0.9.0...v1.0.0
[0.9.0]: https://github.com/ksdj9iqsxs12/overlay-releases/releases/tag/v0.9.0
