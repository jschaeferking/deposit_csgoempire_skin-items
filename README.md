# 🖥️ CSGOEmpire Inventory & Deposit Tool (.exe)

Een krachtige en gebruiksvriendelijke desktoptool om je CSGOEmpire-inventaris te bekijken, te filteren en automatisch te **depositeren** via de officiële API — met live prijzen van csgo.market.

---

## 🧾 Over deze tool

Deze Windows desktop-app helpt je bij:
- Het laden van je volledige **CSGOEmpire-inventaris**
- Het vergelijken van prijzen met csgo.market (Instant Sell of Post Auction)
- Het selecteren en **depositeren van meerdere items**
- En dit alles via een overzichtelijke **grafische interface (GUI)**

> ⚙️ Geen installatie nodig. Geen codeerkennis vereist.

---

## 🔧 Functies

✅ Volledige inventory viewer via CSGOEmpire API  
✅ Live prijsvergelijking met csgo.market  
✅ Sorteren en filteren op prijs, coinwaarde, asset ID, enz.  
✅ Multi-item selectie & automatisch depositen  
✅ % aanpassing op prijzen (instelbaar via spinbox)  
✅ API-token wordt veilig opgeslagen in `config.txt`  

---

## 🚀 Hoe gebruiken

1. **Download & start** het `.exe` bestand  
2. **Voer je CSGOEmpire API-token** in bij eerste gebruik  
   - Wordt opgeslagen in `config.txt` (verborgen & beschermd)  
3. **Selecteer een prijsbron** via het dropdownmenu  
   - `Instant Sell (USD)` of `Post Auction (USD)`  
4. Klik op `Fetch prices & show valid items`  
5. Selecteer één of meerdere items  
6. Klik op `Deposit selected` om te verzenden naar CSGOEmpire

---

## 📁 Output bestanden

| Bestand                 | Inhoud                                               |
|------------------------|------------------------------------------------------|
| `prices_*.txt`           | Marktprijzen (snapshot) van csgo.market per bron     |

---

## 🛠 Vereisten

- 🪟 Windows 10 of 11  
- 🌐 Internetverbinding  
- 📦 Geen installatie nodig (standalone `.exe`)

---

## 🔐 API-token

Je vindt je persoonlijke API-token hier:  
👉 [[https://csgoempire.com/settings](https://csgoempire.com/trading/apikey)]([https://csgoempire.com/settings](https://csgoempire.com/trading/apikey))

Deze wordt automatisch gevraagd & opgeslagen bij eerste opstart.

---

## 🧪 Problemen oplossen

### 🟡 Ik heb al een `config.txt`  
✔️ Geen probleem. De tool hergebruikt die automatisch.

### 🔴 Deposit mislukt?

Controleer of:
- Het item **niet** in een actieve deposit zit  
- Je een stabiele **internetverbinding** hebt  
- De **coinwaarde** correct berekend werd (> 0)

---

## 🧊 Tip

Gebruik het **“Options”**-menu in de app om kolommen te verbergen zoals:
- Asset IDs  
- Originele prijs  
- Suggested price  
- Coinwaarde  

---

## 📸 Screenshot

*(Voeg hier een screenshot toe van de GUI in actie als je wil)*

---

## 🧑‍💻 Developer

Gemaakt met ❤️ door [jouw naam of GitHub profiel]

---
