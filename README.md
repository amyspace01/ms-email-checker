# Microsoft Email Availability Checker

⚠️ **Educational / research purposes only**

A Python tool that checks whether Microsoft email addresses
(`@hotmail.com`, `@outlook.com`) are **AVAILABLE** or **TAKEN**
using real browser automation.

The script uses **Playwright (Chromium)** and behaves like a real user,
with optional proxy support.

---

## ✨ Features

- ✅ Checks Hotmail / Outlook email availability
- ✅ Real browser automation (Chromium, non-headless)
- ✅ Manual input **or** CSV file input
- ✅ Proxy support (HTTP / authenticated)
- ✅ IP check page opens in a secondary tab
- ✅ Timestamped CSV results
- ✅ Multiple runs without restarting
- ✅ Works on multiple PCs via `git clone`

---

## 🖥️ Supported Systems

- Linux (Ubuntu / Debian / Linux Mint)
- Python **3.10+**

> ⚠️ Windows and macOS are not officially tested.

---

## 📦 Project Files

```text
ms-email-checker/
├── mscheck.py      # Main script
├── install.sh      # One-command installer
├── README.md       # This file
