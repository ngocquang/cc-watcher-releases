<p align="center">
  <img src="https://img.shields.io/badge/100%25-Local-brightgreen?style=for-the-badge" alt="100% Local"/>
  <img src="https://img.shields.io/badge/No_Data_Sent-Privacy_First-blue?style=for-the-badge" alt="Privacy First"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/macOS-14%2B-blue?style=flat-square&logo=apple" alt="macOS 14+"/>
  <img src="https://img.shields.io/badge/Architecture-Universal-green?style=flat-square" alt="Universal"/>
  <img src="https://img.shields.io/badge/Version-0.9.4-purple?style=flat-square" alt="Version"/>
</p>

<h1 align="center">CC Watcher</h1>

<p align="center">
  <strong>Floating token-usage overlay for Claude Code</strong>
</p>

<p align="center">
  Monitor your Claude Code token consumption in real-time with a sleek, always-visible floating panel.<br/>
  <strong>Runs 100% locally — no data ever leaves your machine.</strong>
</p>

<p align="center">
  <a href="https://cc-watcher.com"><strong>Download →</strong></a>
</p>

---

## Features

| Feature | Description |
|---------|-------------|
| **📊 Live 5-Hour Chart** | Watch your token budget in real time — one bar per minute, colored per model |
| **🪟 Always Visible** | Non-activating floating panel across every Space and fullscreen app. Never steals focus |
| **⚡ Zero Config** | Installs its own Claude Code hook on first launch. No terminal or settings editing |
| **🔄 Auto-Updates** | Sparkle keeps you on the latest release. New versions land silently |

## Requirements

- **macOS 14.0** (Sonoma) or later
- **Claude Code** CLI installed
- Apple Silicon or Intel Mac (Universal binary)

## Installation

1. Visit [cc-watcher.com](https://cc-watcher.com)
2. Download the latest DMG
3. Open the DMG and drag `CCWatcher.app` to `/Applications`
4. First launch: right-click → **Open** to bypass Gatekeeper
5. Grant Claude Code hook access when prompted

## Usage

Once installed, CC Watcher runs as a floating overlay:

- **Launch**: Open `CCWatcher.app` from Applications
- **Position**: Drag the overlay to any corner of your screen
- **Visibility**: The panel stays visible across all Spaces and fullscreen apps
- **Updates**: Automatic updates via Sparkle — no manual intervention needed

## How It Works

CC Watcher integrates with Claude Code through a hook system:

1. On first launch, CC Watcher installs a Claude Code hook
2. The hook captures token usage data from Claude Code sessions
3. Data is visualized in real-time on the floating overlay
4. Usage history is displayed as a 5-hour rolling chart

## Auto-Update Feed

CC Watcher uses Sparkle for automatic updates. The appcast feed is available at:

```
https://cc-watcher.com/appcast.xml
```

## Troubleshooting

### App won't open (Gatekeeper)

Right-click the app → **Open** → Click **Open** in the dialog. This is required for unsigned apps on macOS.

### Hook not working

Ensure Claude Code is installed and accessible from your terminal:

```bash
claude --version
```

If the hook doesn't install automatically, check your Claude Code settings directory.

### Overlay not visible

- Check if CC Watcher is running in the menu bar
- Try repositioning the overlay by dragging it
- Restart the app if needed

## Privacy

CC Watcher runs **100% locally**:

- No data is sent to external servers
- Token usage data stays on your machine
- No analytics or telemetry
- No account required

---

<p align="center">
  <a href="https://cc-watcher.com"><strong>cc-watcher.com</strong></a>
</p>

<p align="center">
  Made with care for Claude Code users
</p>
