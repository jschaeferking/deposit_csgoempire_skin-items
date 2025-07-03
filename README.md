# 🖥️ CSGOEmpire Inventory & Deposit Tool

A powerful and user-friendly desktop tool to **view**, **filter**, and automatically **deposit** your CSGOEmpire inventory via the official API — with live prices from csgo.market.

---

## 🧾 About this tool

This Windows desktop app helps you to:
- Load your full **CSGOEmpire inventory**
- Compare prices with csgo.market (Instant Sell or Post Auction)
- Select and **deposit multiple items**
- All through a clean and simple **graphical interface (GUI)**

> ⚙️ No installation required. No coding knowledge needed.

---

## 🔧 Features

✅ Full inventory viewer via CSGOEmpire API  
✅ Live price comparison with csgo.market  
✅ Sort and filter by price, coin value, asset ID, etc.  
✅ Multi-item selection & automatic deposit  
✅ Adjustable % markup on prices (via spinbox)  
✅ API token securely saved in `config.txt`  

---

## 🚀 How to use

1. **Download & launch** the `.exe` file  
2. **Enter your CSGOEmpire API token** on first use  
   - Saved in `config.txt` (hidden & protected)  
3. **Select a price source** from the dropdown  
   - `Instant Sell (USD)` or `Post Auction (USD)`  
4. Click `Fetch prices & show valid items`  
5. Select one or more items  
6. Click `Deposit selected` to send them to CSGOEmpire

---

## 📁 Output files

| File            | Contents                                        |
|-----------------|------------------------------------------------|
| `prices_*.txt`  | Market price snapshots from csgo.market by source |

---

## 🛠 Requirements

- 🪟 Windows 10 or 11  
- 🌐 Internet connection  
- 📦 No installation needed (standalone `.exe`)

---

## 🔐 API token

You can find your personal API token here:  
👉 https://csgoempire.com/trading/apikey

It will be requested & saved automatically on first launch.

---

## 🧪 Troubleshooting

### 🟡 I already have a `config.txt`  
✔️ No problem. The tool will use it automatically.

### 🔴 Deposit failed?

Check that:
- The item is **not** in an active deposit  
- You have a stable **internet connection**  
- The **coin value** was calculated correctly (> 0)

---

## 🧊 Tip

Use the app’s **“Options”** menu to hide columns like:
- Asset IDs  
- Original price  
- Suggested price  
- Coin value  

---

## 📸 Screenshot



---

## 🧑‍💻 Developer

Made with ❤️

---
