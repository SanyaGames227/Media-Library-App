🌐 [English](README.md) · [Русский](README_RU.md) · [Українська](README_UA.md)

# 🎬 Media Library App

A powerful desktop media tracker and catalog manager built with Python and PyQt5. Organize your movies, shows, games, books — or anything else — in a clean, fast, offline-first interface.
> Idea & Design: **sanyagames227** · Development: **Claude AI (Anthropic)**

<img width="1402" height="832" src="https://github.com/user-attachments/assets/15bb5999-83d2-4ef8-9c36-150c9dca3e62" />

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
<img width="1402" height="832" src="https://github.com/user-attachments/assets/a6c336f6-04ab-4138-a5ac-aaa18040f4ff" />


### 🏷️ Custom Fields
Create your own data fields for each category — any combination of:
- Text, Number, Date, Checkbox, Marks (multi-checkbox), Dropdown, Slider
- Show fields in the item list, compact mode (emoji/icon), or context menu
- Use field variables in text exports as `{variable}`
<img width="402" height="651" src="https://github.com/user-attachments/assets/70fcc0c4-bf2f-41b1-a443-1f2ffc0071a8" />


### 🎖️ Tier Lists
- Built-in tier list system with fully customizable tier sets
<img width="1402" height="832" src="https://github.com/user-attachments/assets/1fcb6c59-6650-4c23-b87c-bdd3037f71b8" />

### 👥 Multi-User Support
- Track viewing history by user — who you watched with

### 📊 Statistics
- Monthly and yearly activity charts
- Average ratings, total watch time, solo vs. group views
- Release year distribution
- Rewatch tracking
<img width="902" height="532" src="https://github.com/user-attachments/assets/7407e8bb-a763-4542-a77f-e8ea7ad57935" />


### 🖼️ Cover Art
- Upload covers from file or paste image/URL directly
- Online cover search built in
- Configurable JPEG quality for storage efficiency
- Unused image cleanup tool
<img width="502" height="974" src="https://github.com/user-attachments/assets/dcadd0cf-b537-4cf2-884f-01c8821e0dba" />


### 📤 Export & Import
- **HTML export** — with the option to embed images as base64 (single file) or export them to a folder
- **CSV/ZIP export** — full data export with covers, icons, and custom fields
- **ZIP import** — restore from exported archives with a diff preview (see exactly what will be added)
- Text export with fully customizable templates using field variables
- Multi-category batch export
<img width="1251" height="805" src="https://github.com/user-attachments/assets/76cfa1f1-892d-4891-bee6-98d9ce9667b7" />


### 🗒️ Notes
- Per-item rich notes editor
<img width="962" height="712" src="https://github.com/user-attachments/assets/809c63ec-2763-43d0-bc5d-70898d906abb" />


### ⚙️ Settings & Customization
- **Language support** — English, Русский, Українська (and custom `.json` language files)
- **HiDPI scaling** for QHD and 4K monitors
- **Automatic weekly backup** on launch
- **Backup on delete** — configurable auto-backup when deleting items, categories, fields, tiers, or users
- **Database maintenance** — VACUUM optimization with auto-backup
- Custom date format
- Desktop shortcut creator
<img width="462" height="614" src="https://github.com/user-attachments/assets/6423cf26-2951-453d-a35e-e651e3cb9443" />


---

## 🛠️ Used Library

| Component | Version |
|-----------|---------|
| Python | 3.x |
| PyQt5 | 5.x |
| Pillow | 10.x |
| SQLite3 | 3.x |

---

## 🚀 Getting Started

### Requirements

**Option 1 — Python**

```bash
pip install PyQt5 Pillow
python media-library-app.pyw
```

**Option 2 — Portable**

Extract the archive of portable version and run the `.exe` file.

---

## 📂 Data Storage

All data is stored locally — no accounts, no cloud, no telemetry. The database and settings live in the app's data directory on your machine.

---

## About

<img width="462" height="614" src="https://github.com/user-attachments/assets/e56abb59-5192-492c-8364-e3d960abe4af" />

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
