# Installation Guide

Use this guide to install ATLAS Desktop App on Windows and prepare it for AI-assisted trading workflows.

## System Requirements

### Minimum

- Windows 10 (64-bit)
- 8GB RAM
- 2GB free disk space
- Internet connection for cloud AI models
- MetaTrader 5

### Recommended

- Windows 11 (64-bit)
- 16GB RAM or higher
- SSD storage
- Stable internet connection (10+ Mbps)
- MetaTrader 5 with a reliable broker connection or VPS for longer sessions
- Paid or eligible ATLAS AI/model-provider access for frontier models

## Download

1. Go to the [Releases page](https://github.com/ksdj9iqsxs12/atlas-releases/releases).
2. Choose the newest ATLAS Desktop App build available for your channel.
3. Download the `.exe` installer or portable archive if offered.

## Installation Steps

### Standard Installation

1. Run the downloaded installer.
2. Accept the license agreement and risk disclosures.
3. Choose an installation directory, such as `C:\Program Files\ATLAS Desktop App`.
4. Select components:
   - ATLAS Desktop App Core (required)
   - Desktop shortcut (recommended)
   - Start menu shortcut (optional)
   - Model/provider integration helpers (optional, when offered)
5. Click **Install**.
6. Wait for installation to complete.
7. Click **Finish** to launch ATLAS Desktop App.

### Portable Installation

For USB drive or non-admin use:

1. Download the portable `.zip` version if available.
2. Extract it to your preferred folder.
3. Run `ATLAS-Desktop-App.exe` directly.

## First-Time Setup

### AI Provider Configuration

ATLAS Desktop App needs at least one AI access route for cloud model features:

#### Option 1: ATLAS AI

1. Sign in with your ATLAS account if prompted.
2. Confirm your plan, trial, tester status, or limited free access.
3. Select the model tier available to your account.

Some users may receive free ATLAS AI access for testing, feedback, or limited previews. Most ongoing usage is paid because premium AI models and infrastructure have operating costs.

#### Option 2: OpenAI-Compatible Providers

1. Create an API key with your provider.
2. Add credits or billing where required.
3. Enter the key in **Settings > AI Providers**.
4. Select available GPT-class or compatible models, such as GPT 5.5, GPT 5.4, GPT 4.7, GPT 4.6, or GPT 4.5 where supported by your provider.

#### Option 3: Anthropic/OpenRouter-Style Providers

1. Create an API key with a supported provider.
2. Enter the key in **Settings > AI Providers**.
3. Select supported Opus-class, Sonnet 4.6, Sonnet 4.5, Codex-class, or other frontier models where available.

#### Option 4: Local Models

1. Install the supported local model runtime.
2. Pull or configure your preferred model.
3. Ensure the runtime is active.
4. Let ATLAS Desktop App detect the local endpoint or enter it manually.

### MetaTrader 5 Connection

1. Install MetaTrader 5 from your broker.
2. Log in to your trading account.
3. Keep MetaTrader 5 running.
4. Launch ATLAS Desktop App and verify the connection status.

## Updating

### Automatic Updates

ATLAS Desktop App checks for updates when supported:

1. If an update is available, you will see a notification.
2. Click **Update Now** to download and install.
3. Restart the app if prompted.

### Manual Updates

1. Download the new version from Releases.
2. Close ATLAS Desktop App if it is running.
3. Run the installer.
4. Keep existing settings unless you intentionally want a clean install.

## Uninstallation

1. Go to **Windows Settings > Apps**.
2. Find **ATLAS Desktop App**.
3. Click **Uninstall**.
4. Follow the prompts.

User data, settings, memories, and logs may be preserved by default. Delete the relevant ATLAS application data folder only if you want a full reset.

## Legal and Trading Safety Setup

Before trading with ATLAS Desktop App:

- Read the license agreement and risk disclosures.
- Use a demo account first.
- Configure daily loss limits and per-trade risk limits.
- Require manual confirmation until you fully understand the workflow.
- Never treat AI output as guaranteed, personalized financial advice, or a substitute for your own judgment.

## Troubleshooting

### "Windows protected your PC" warning

This can appear when an installer is new or not yet recognized by Windows SmartScreen:

1. Verify that you downloaded the file from the official Releases page.
2. Click **More info**.
3. Click **Run anyway** only if you trust the source.

### ATLAS Desktop App won't start

1. Ensure you have the Visual C++ Redistributable installed.
2. Download it from [Microsoft](https://aka.ms/vs/17/release/vc_redist.x64.exe).
3. Install and try again.

### Can't connect to MetaTrader 5

1. Ensure MetaTrader 5 is running and logged in.
2. Restart MetaTrader 5.
3. Restart ATLAS Desktop App.
4. Check that Windows Firewall is not blocking the connection.

### AI not responding

1. Verify your ATLAS AI access or API key in Settings.
2. Check your internet connection.
3. Ensure you have credits or an active plan for paid providers.
4. Try a different model or provider.
