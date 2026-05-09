# 🎬 Media Library App

A powerful desktop media tracker and catalog manager built with Python and PyQt5. Organize your movies, shows, games, books — or anything else — in a clean, fast, offline-first interface.

> Idea & Design: **sanyagames227** · Development: **Claude AI (Anthropic)**

---

## ✨ Features

### 📁 Flexible Organization
- **Folders and Categories** — group your media any way you want, with custom icons and background images per category
- **Unlimited items** per category with cover art, title, year, rating, notes, watch date, and more
- **Alternative titles** with sort key support — search by any alias, display the primary name
- **Favorites** — mark and filter items instantly

### 🔍 Powerful Search & Filtering
- **Real-time search** across titles and all custom fields (Ctrl+F)
- **Custom search prefixes** — define your own filter keywords (e.g. `tag:horror`, `yw:2024`)
- **Filter by date** — preset ranges or custom date range picker
- **Favorites-only** filter toggle
- **Sort** by title, year, rating, watch date, or manual drag-and-drop order
- Per-category sort memory — each category remembers its own sorting

### 🏷️ Custom Fields
Create your own data fields for each category — any combination of:
- Text, Number, Date, Checkbox, Marks (multi-checkbox), Dropdown, Slider
- Show fields in the item list, compact mode (emoji/icon), or context menu
- Use field variables in text exports as `{variable}`

### 🎖️ Tier Lists
- Built-in tier list system with fully customizable tier sets
- Multiple tier list sets per category
- Drag-and-drop tier assignment

### 👥 Multi-User Support
- Track watch history per user — who watched what, with whom, and how many times
- Per-user watch dates and view counts

### 📊 Statistics
- Monthly and yearly activity charts
- Average ratings, total watch time, solo vs. group views
- Release year distribution
- Rewatch tracking

### 🖼️ Cover Art
- Upload covers from file or paste image/URL directly
- Online cover search built in
- Configurable JPEG quality for storage efficiency
- Unused image cleanup tool

### 📤 Export & Import
- **HTML export** — embed images as base64 (single file) or export to folder
- **CSV/ZIP export** — full data export with covers, icons, and custom fields
- **ZIP import** — restore from exported archives with a diff preview (see exactly what will be added)
- Text export with fully customizable templates using field variables
- Multi-category batch export

### 🗒️ Notes
- Per-item rich notes editor with unsaved-changes protection

### ⚙️ Settings & Customization
- **Language support** — English, Русский, Українська (and custom `.json` language files)
- **HiDPI scaling** for QHD and 4K monitors
- **Automatic weekly backup** on launch (background, non-blocking)
- **Backup on delete** — configurable auto-backup when deleting items, categories, fields, tiers, or users
- **Database maintenance** — VACUUM optimization with auto-backup
- Custom date format (year / year+month / full date)
- Desktop shortcut creator

---

## 🛠️ Tech Stack

| Component | Version |
|-----------|---------|
| Python | 3.x |
| PyQt5 | 5.x |
| Pillow | 10.x |
| SQLite3 | 3.x |

---

## 🚀 Getting Started

### Requirements
```
pip install PyQt5 Pillow
```

### Run
```
python media-library-app.pyw
```

---

## 📂 Data Storage

All data is stored locally — no accounts, no cloud, no telemetry. The database and settings live in the app's data directory on your machine.

---

## 🩷 Support

If you enjoy this app, consider supporting its development:

| Method | Address |
|--------|---------|
| PayPal | sanyadisa1@gmail.com |
| USDT TON | `UQA3aY7KTAav4PzRkbIteKDAfpn9GWJDd7CIN_CUOYFunmAo` |
| USDT TRX | `TSLizuNc3rc2CBKvC4vEWGrDgNPupZvGPP` |
| TON | `UQA3aY7KTAav4PzRkbIteKDAfpn9GWJDd7CIN_CUOYFunmAo` |
| BTC | `1344AjbWQkLaenTNbHizPgdBxjMwGeaCes` |

---

## 📄 License

© 2026 sanyagames227. Built with ♥ and Claude AI.
