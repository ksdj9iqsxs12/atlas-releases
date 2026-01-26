# Installation Guide

## System Requirements

### Minimum
- Windows 10 (64-bit)
- 8GB RAM
- 2GB free disk space
- Internet connection
- MetaTrader 5

### Recommended
- Windows 11 (64-bit)
- 16GB RAM
- SSD storage
- Stable internet (10+ Mbps)
- MetaTrader 5 with VPS (for 24/7 operation)

## Download

1. Go to the [Releases page](https://github.com/ksdj9iqsxs12/overlay-releases/releases)
2. Choose your version:
   - **Stable** (v1.x.x) - Recommended for live trading
   - **Beta** (v2.x.x-beta) - Latest features, may have bugs
3. Download the `.exe` installer

## Installation Steps

### Standard Installation

1. Run the downloaded installer
2. Accept the license agreement
3. Choose installation directory (default: `C:\Program Files\Overlay`)
4. Select components:
   - Overlay Core (required)
   - Desktop shortcut (recommended)
   - Start menu shortcut (optional)
5. Click "Install"
6. Wait for installation to complete
7. Click "Finish" to launch Overlay

### Portable Installation

For USB drive or non-admin installation:

1. Download the portable `.zip` version
2. Extract to your preferred location
3. Run `Overlay.exe` directly

## First-Time Setup

### AI Provider Configuration

Overlay requires at least one AI provider:

#### Option 1: Groq (Recommended for Beginners)
1. Sign up at [console.groq.com](https://console.groq.com)
2. Create an API key
3. Enter the key in Overlay Settings > AI Providers > Groq

#### Option 2: OpenAI
1. Sign up at [platform.openai.com](https://platform.openai.com)
2. Add credits to your account
3. Create an API key
4. Enter the key in Overlay Settings > AI Providers > OpenAI

#### Option 3: Google Gemini
1. Sign up at [aistudio.google.com](https://aistudio.google.com)
2. Create an API key
3. Enter the key in Overlay Settings > AI Providers > Gemini

#### Option 4: Ollama (Local Models)
1. Install Ollama from [ollama.ai](https://ollama.ai)
2. Pull a model: `ollama pull llama3`
3. Ensure Ollama is running
4. Overlay will auto-detect local Ollama

### MetaTrader 5 Connection

1. Install MetaTrader 5 from your broker
2. Log into your trading account
3. Keep MT5 running
4. Launch Overlay - it will auto-connect

**Note:** Overlay uses the MT5 Python API. No additional MT5 configuration is required.

## Updating

### Automatic Updates

Overlay checks for updates on launch:
1. If an update is available, you'll see a notification
2. Click "Update Now" to download and install
3. Overlay will restart with the new version

### Manual Updates

1. Download the new version from Releases
2. Close Overlay if running
3. Run the installer (it will update in place)
4. Your settings and data are preserved

## Uninstallation

1. Go to Windows Settings > Apps
2. Find "Overlay AI Trading"
3. Click "Uninstall"
4. Follow the prompts

**Note:** User data (settings, memories) is preserved by default. To remove all data, delete the `%APPDATA%\Overlay` folder.

## Troubleshooting

### "Windows protected your PC" warning

This appears because the installer isn't code-signed yet:
1. Click "More info"
2. Click "Run anyway"

### Overlay won't start

1. Ensure you have the Visual C++ Redistributable installed
2. Download from [Microsoft](https://aka.ms/vs/17/release/vc_redist.x64.exe)
3. Install and try again

### Can't connect to MetaTrader 5

1. Ensure MT5 is running and logged in
2. Restart MT5
3. Restart Overlay
4. Check Windows Firewall isn't blocking the connection

### AI not responding

1. Verify your API key in Settings
2. Check your internet connection
3. Ensure you have API credits (for paid providers)
4. Try a different AI provider
