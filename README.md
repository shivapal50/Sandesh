# 📨 Sandesh — Political Campaign WhatsApp Broadcaster

> **Sandesh** ek free, browser-based political campaign tool hai jo candidates aur campaign workers ko apne voters tak WhatsApp ke zariye personalized messages bhejne mein madad karta hai — bina kisi server ya paid service ke!

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)
![No Server](https://img.shields.io/badge/No%20Server-Required-brightgreen?style=for-the-badge)

---

## ✨ Features

- 📊 **Excel & CSV Import** — Ek click mein hazaaron voters upload karo
- 🗺️ **Ward Management** — Multiple wards/constituencies organize karo
- ✍️ **Smart Templates** — Diwali, Holi, Eid, Rally, Vote Appeal ke ready-made templates
- 👤 **Personalization** — `{name}` aur `{ward}` variables se har message personal banta hai
- 💬 **Live WhatsApp Preview** — Message bhejne se pehle bilkul WhatsApp jaisa preview dekho
- 📈 **Progress Tracking** — Real-time sent/pending stats dashboard
- 🌙 **Dark Mode** — System preference ke saath auto-sync + manual toggle
- 💾 **Offline Storage** — Saara data browser ke localStorage mein safe rehta hai
- ⬇️ **Export CSV** — Apna voter database kabhi bhi download karo
- 📱 **Mobile Friendly** — Phone se bhi perfectly kaam karta hai
- 🆓 **100% Free** — Koi subscription nahi, koi API key nahi, koi server nahi

---

## 🚀 Quick Start

### Option 1: Seedha Use Karo (No Installation)

1. `index.html` file download karo
2. Browser mein open karo — **bas itna hi!**
3. Koi server setup, koi internet connection (after load) ki zaroorat nahi

### Option 2: Clone karo

```bash
git clone https://github.com/your-username/sandesh.git
cd sandesh
# index.html ko browser mein open karo
```

---

## 📋 How to Use

### Step 1 — Voters Import Karo

**Excel se:**
- `.xlsx` file upload karo (drag & drop bhi kaam karta hai)
- Format: `Column A = Naam | Column B = Phone | Column C = Ward`
- Pehli row header ho sakti hai — automatically skip ho jaayegi

**CSV se:**
- `.csv` file upload karo
- Format: `Name, Phone, Ward`

**Manually:**
- Naam, phone number aur ward fill karo
- `+ Add Voter` dabao

### Step 2 — Message Likho

- Ready-made template choose karo **ya** apna message type karo
- `{name}` — automatically voter ka naam insert ho jaata hai
- `{ward}` — automatically ward ka naam insert ho jaata hai
- Live preview mein exactly WhatsApp jaisa dikhega

### Step 3 — Bhejo!

- Ward filter se select karo (sab ya specific ward)
- **"Send to All Contacts"** dabao
- Har voter ke liye WhatsApp automatically pre-filled message ke saath open hoga
- Bas **Send** dabao — done! ✅

---

## 📊 Excel/CSV Format

| Column A | Column B | Column C |
|----------|----------|----------|
| Ram Kumar | 9876543210 | Ward 12 |
| Sita Devi | 8765432109 | North Constituency |
| Mohan Lal | 07654321098 | Ward 5 |

> **Note:** Phone number 10 digit (India) ya full international format mein ho sakta hai. `91` prefix automatically add ho jaata hai.

---

## 🎨 Message Templates

| Template | Use Case |
|----------|----------|
| 🪔 Diwali | Deepavali shubhkamnayein |
| 🎨 Holi | Holi wishes |
| 🌙 Eid | Eid Mubarak |
| 🎆 New Year | Naya Saal |
| 🕉️ Navratri | Navratri wishes |
| 📢 Rally | Jaansabha announcement |
| 🗳️ Vote Appeal | Voting day appeal |

---

## 🏗️ Project Structure

```
sandesh/
└── index.html          # Poora app — single file!
```

Haan, poora app **ek hi HTML file** mein hai. Koi dependencies nahi (sivaaye XLSX.js CDN ke Excel import ke liye).

---

## 🔒 Privacy & Data

- ✅ Saara data **aapke browser mein** rehta hai (`localStorage`)
- ✅ Koi data kisi server par nahi jaata
- ✅ Koi account/login ki zaroorat nahi
- ✅ Voters ke numbers third-party ko nahi milte
- ⚠️ Browser cache clear karne par data delete ho sakta hai — **CSV Export** se backup zaroor rakho!

---

## 🤝 How WhatsApp Sending Works

Sandesh **WhatsApp Web API** (`wa.me` links) use karta hai jo completely free aur official hai:

```
https://wa.me/{phone}?text={encoded_message}
```

Har contact ke liye yeh link open hota hai — aapko sirf **Send** dabana hota hai WhatsApp mein. Koi WhatsApp Business API subscription nahi chahiye.

---

## 🛠️ Tech Stack

| Technology | Use |
|------------|-----|
| HTML5 / CSS3 / Vanilla JS | Core app |
| [SheetJS (XLSX)](https://sheetjs.com/) | Excel file parsing |
| Google Fonts (Playfair Display + Plus Jakarta Sans) | Typography |
| `localStorage` | Data persistence |
| `wa.me` links | WhatsApp integration |

---

## 📱 Browser Support

| Browser | Support |
|---------|---------|
| Chrome / Edge | ✅ Full |
| Firefox | ✅ Full |
| Safari (iOS) | ✅ Full |
| Mobile Chrome | ✅ Full |

---

## 🤲 Contributing

Pull requests welcome hain! Koi bug mila ya feature suggest karna hai?

1. Fork karo
2. Feature branch banao (`git checkout -b feature/naya-feature`)
3. Commit karo (`git commit -m 'Naya feature add kiya'`)
4. Push karo (`git push origin feature/naya-feature`)
5. Pull Request open karo

---

## 📄 License

MIT License — Free use karo, modify karo, distribute karo.

---

## 🙏 Acknowledgements

- [SheetJS](https://sheetjs.com/) — Excel parsing ke liye
- [WhatsApp](https://wa.me) — Free messaging API ke liye
- Google Fonts — Beautiful typography ke liye

---

<div align="center">

**Sandesh** — Apne voters tak pahuncho, seedha aur free mein. 🇮🇳

*Made with ❤️ for Indian democracy*

</div>
