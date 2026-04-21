# Claude Limit Indicator – Chrome

A Chrome extension that shows your Claude.ai usage limits directly in the sidebar.

![screenshot](sidebar_on.png)

## Features
- Session (5-hour) and weekly (7-day) usage bars
- Color coded: 🟢 green → 🟡 yellow at 60% → 🔴 red at 80%
- Reset countdown timers
- Token count + cache timer per conversation
- Hides automatically when sidebar is collapsed
- No data stored, no external requests

## Installation

> No developer account needed. Works in Chrome, Brave, Arc, and any Chromium browser.

1. Clone or download this repo
```bash
git clone https://github.com/YOUR_USERNAME/claude-counter-chrome.git
```

2. Open Chrome and go to `chrome://extensions`

3. Enable **Developer mode** (toggle in the top right)

4. Click **Load unpacked** and select the `claude-counter-chrome` folder

5. Open [claude.ai](https://claude.ai) — the usage bars will appear in the sidebar

## Usage

- Open the sidebar on claude.ai to see your usage
- Click the usage panel to manually refresh
- Bars update automatically after every message and every 60 seconds

## Also available for Safari

👉 [claude-counter-safari](https://github.com/YOUR_USERNAME/claude-counter-safari)
