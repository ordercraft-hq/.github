<div align="center">
  <h1>⚡ OrderCraft</h1>
  <p><strong>High-performance, local-first, 100% open-source financial charting & technical analysis terminal.</strong></p>

  <p>
    <a href="https://github.com/ordercraft-hq/terminal/releases/latest">
      <img src="https://img.shields.io/github/v/release/ordercraft-hq/terminal?style=flat-square&color=2962FF&label=Latest%20Release" alt="Latest Release" />
    </a>
    <a href="https://github.com/ordercraft-hq/terminal/blob/main/LICENSE">
      <img src="https://img.shields.io/badge/License-MIT-26a69a?style=flat-square" alt="MIT License" />
    </a>
    <a href="https://github.com/ordercraft-hq/terminal">
      <img src="https://img.shields.io/badge/Stack-Go%20%2B%20React%20%2B%20TypeScript-00ADD8?style=flat-square" alt="Tech Stack" />
    </a>
  </p>

  <p>
    <a href="https://github.com/ordercraft-hq/terminal"><strong>Explore the Terminal Repo →</strong></a>
    ·
    <a href="https://github.com/ordercraft-hq/terminal/releases/latest"><strong>Download v0.1.0 Binaries</strong></a>
    ·
    <a href="https://github.com/ordercraft-hq/terminal/discussions"><strong>Join Discussions</strong></a>
  </p>
</div>

---

<img width="1680" height="984" alt="image" src="https://github.com/user-attachments/assets/3111b68c-1158-4f48-a2c8-5e79d2252362" />


## 🚀 Why OrderCraft?

Modern financial charting platforms lock basic technical analysis behind expensive monthly subscriptions—restricting how many indicators you can place on a chart, limiting multi-pane layouts, and forcing your market workflows into the cloud.

**OrderCraft** is built for traders, quantitative developers, and self-hosters who want institutional-grade charting speed on their own machine:

* **📦 Single-Binary Zero-Config Execution:** Compiled into a standalone ~14MB Go binary (`windows`, `macos`, `linux`) with an embedded React UI. Double-click and stream live market data in under 2 seconds.
* **🛡️ 100% Local-First & Private (BYOK):** Zero telemetry, zero accounts, and zero cloud lock-in. Connect free public feeds (Binance, Yahoo Finance) out of the box or bring your own API keys (OANDA, Alpaca) stored strictly on your local disk.
* **📐 Custom Interactive Drawing Engine:** Trendlines, Ray/Extended lines, Horizontal/Vertical levels, Fibonacci Retracements, Parallel Channels, Rectangles, and Long/Short Risk-Reward Position calculators.
* **🖥️ Multi-Chart Synchronized Workspaces:** Split your screen into `1x1`, `2V`, `2H`, `3`, or `4`-pane grids with synchronized crosshairs, symbols, and timeframes.

---

## ⚡ Quick Start (v0.1.0)

Grab the prebuilt standalone executable for your OS from our **[Latest Releases](https://github.com/ordercraft-hq/terminal/releases/latest)** page:

| Platform | Architecture | Download |
| :--- | :--- | :--- |
| **Windows** | `x64` | [`ordercraft-windows-amd64.exe`](https://github.com/ordercraft-hq/terminal/releases/latest/download/ordercraft-windows-amd64.exe) |
| **macOS** | `Apple Silicon (M1-M4)` | [`ordercraft-darwin-arm64`](https://github.com/ordercraft-hq/terminal/releases/latest/download/ordercraft-darwin-arm64) |
| **macOS** | `Intel (x64)` | [`ordercraft-darwin-amd64`](https://github.com/ordercraft-hq/terminal/releases/latest/download/ordercraft-darwin-amd64) |
| **Linux** | `x64` / `ARM64` | [`ordercraft-linux-amd64`](https://github.com/ordercraft-hq/terminal/releases/latest/download/ordercraft-linux-amd64) / [`arm64`](https://github.com/ordercraft-hq/terminal/releases/latest/download/ordercraft-linux-arm64) |

```bash
# Launch in standalone frameless desktop window mode:
./ordercraft --app-mode
