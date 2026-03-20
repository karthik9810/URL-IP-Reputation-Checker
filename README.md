# URL-IP-Reputation-Checker

python spam_checker.py

# 🛡️ Spam & Link Checker

> **Anyone can use this!** Paste any suspicious link or IP address and instantly find out if it's spam or safe — no account, no API key needed.

---

## 📋 Requirements

- Windows 10 or 11
- Python installed ([download here](https://www.python.org/downloads/))

---

## 🚀 Step-by-Step Setup (Windows)

### ✅ Step 1 — Download the file

Download `spam_checker.py` and save it somewhere easy, like your **Desktop** or **Downloads** folder.

---

### ✅ Step 2 — Open Terminal (PowerShell)

**Option A — Easiest:**
1. Go to the folder where `spam_checker.py` is saved
2. Click the **address bar** at the top of File Explorer
3. Type `powershell` and press **Enter**

**Option B — From Start Menu:**
1. Press `Windows key + R`
2. Type `powershell` → press **Enter**
3. Navigate to your file:
```powershell
cd Desktop
```
> Replace `Desktop` with wherever you saved the file (e.g. `cd Downloads`)

---

### ✅ Step 3 — Install the display library (one time only)

Copy and paste this into the terminal, then press **Enter**:

```powershell
pip install rich
```

Wait for it to finish. You only need to do this **once ever**.

---

### ✅ Step 4 — Run the tool

```powershell
python spam_checker.py
```

The tool will start and ask you to paste a link.

---

### ✅ Step 5 — Paste your link and check!

```
🔗 Paste link or IP: http://suspicious-login-verify.tk/paypal
```

Press **Enter** — you'll instantly see:

```
🚨 SPAM / DANGEROUS   Spam Risk: ████████████████████ 100%
```

or

```
✅ LOOKS SAFE          Spam Risk: ░░░░░░░░░░░░░░░░░░░░  0%
```

---

## ❓ Common Errors & Fixes

| Error | Fix |
|---|---|
| `python was not found` | Install Python from [python.org](https://www.python.org/downloads/) — check **"Add to PATH"** during install |
| `No such file or directory` | Make sure you're in the right folder. Use `cd Downloads` or `cd Desktop` |
| `No module named rich` | Run `pip install rich` first |
| `python3` not working | On Windows use `python` (not `python3`) |

---

## 💡 Tips

- You can check **multiple links** one after another — just keep pasting
- Works with URLs **and** IP addresses
- Type `exit` to quit the tool
- If unsure, also verify at 👉 [virustotal.com](https://virustotal.com) (free)

---

## 🔍 What It Checks

| Check | What it detects |
|---|---|
| 🔒 HTTPS | Is the connection secure? |
| 📛 Suspicious TLD | Spam domains like `.tk`, `.xyz`, `.click` |
| 🏷️ Brand Spoofing | Fake PayPal, Apple, bank links |
| 🔢 IP in URL | Hidden IP addresses in links |
| 📡 DNS Resolution | Can the domain even be reached? |
| 🛡️ Trusted Domain | Known safe sites (Google, GitHub, etc.) |
| 📜 URL Length | Very long URLs are often spam |
| 🧅 Tor/VPN Range | Anonymous/suspicious IP ranges |

---

## ⚠️ Disclaimer

This tool uses heuristic analysis for **educational purposes**. Always cross-reference with [VirusTotal](https://virustotal.com) for critical decisions.

---

Made with 🛡️ Python + Rich

