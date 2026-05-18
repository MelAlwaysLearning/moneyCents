# moneyCents 💰

A free, privacy-first budget and expense tracker that runs entirely in your browser — no account, no server, no subscription.

---

## What it does

| Tab | What you can do |
|-----|----------------|
| 📊 Dashboard | See your monthly income, expenses, net savings, and savings rate at a glance |
| 💳 Transactions | Log income and expenses by category |
| 📋 Budget | Set monthly spending limits per category with visual progress bars |
| 🎯 Goals | Track savings goals (vacation, emergency fund, new car, etc.) |
| 🧾 Bill Splitter | Split a bill equally or by custom amounts among any number of people |
| 📚 Financial Literacy | 50/30/20 snapshot, compound interest / debt / savings calculators, and key money concepts |

---

## How your data is saved

moneyCents has **no backend**. All your data is saved automatically in your browser's **localStorage** — a private storage area built into every modern browser.

### What this means for you

✅ Your data is saved automatically every time you add a transaction, set a budget limit, or update a goal.  
✅ It stays private — no data ever leaves your device.  
⚠️ If you clear your browser history or browser data, your moneyCents data will be erased.  
⚠️ Data does not sync between different browsers or devices automatically.

---

## Saving your data to your desktop (backup)

Because the data lives in your browser, you should **export a backup file regularly** — especially before clearing your browser, switching browsers, or getting a new computer.

### How to export (save a backup to your Desktop) — step by step

1. Open `index.html` in your browser (double-click the file)
2. Click the **🚀 Start Here** tab at the top of the app
3. Click the green **⬇️ Export Data (Download)** button
4. Your browser will download a file named `moneycents-backup-2024-01-15.json` (today's date will be in the name)
5. Open your **Downloads** folder
6. Drag the file to your **Desktop** (or any folder you'd like to keep it in)

> **Pro tip:** Set your browser's default download location to your Desktop so the file saves there automatically. In Chrome: Settings → Downloads → change Location to Desktop. In Safari: Preferences → General → File download location → Desktop.

### How to restore a backup — step by step

1. Open `index.html` in your browser
2. Click the **🚀 Start Here** tab
3. Click **📂 Import Data (Restore)**
4. A file picker will open — find and select your `moneycents-backup.json` file
5. Click **Confirm** when asked
6. The app will switch to your Dashboard with all your data restored

---

## Saving your backup to Google Drive

You can store your backup file on Google Drive for extra safety:

1. Export your backup file using the steps above
2. Go to [drive.google.com](https://drive.google.com) and sign in
3. Drag and drop the `.json` file into your Drive (or click **+ New → File upload**)
4. To restore later, download the file from Drive and use the Import step above

> **Tip:** Create a folder called `moneyCents Backups` in your Drive to keep them organized.

---

## Running the app

moneyCents is a single HTML file — no installation or server needed.

1. Download or clone this repository
2. Double-click `index.html` to open it in your browser
3. Bookmark the page for easy access

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/moneyCents.git

# Open the app
open moneyCents/index.html
```

---

## Tips

- **Back up regularly** — once a week or after any big data entry session
- **Name your backup files by date** — the export does this automatically
- **Keep a copy on Google Drive and one on your desktop** for double safety
- Your dark mode preference is also saved in localStorage

---

## Tech stack

Plain HTML, CSS, and vanilla JavaScript. No frameworks, no dependencies, no build step.

---

*Built with love. Track it. Save it. Own it. 💰*
