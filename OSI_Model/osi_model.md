# 🌐 OSI Model - Open Systems Interconnection Model

OSI modeli (Open Systems Interconnection) bu — **kompyuter tarmoqlaridagi muloqotni 7 qatlamga ajratadigan nazariy model**. Har bir qatlam o‘zining vazifasiga ega va ular bir-birining ustida ishlaydi.

---

## 🧱 OSI Model Qatlamlari (Yuqoridan pastga):

| Qatlam raqami | Nomi                  | Vazifasi                                              | Real hayotiy misol                     |
|---------------|------------------------|--------------------------------------------------------|----------------------------------------|
| 7             | Application Layer       | Foydalanuvchiga yaqin xizmatlar (veb brauzer, email)   | Gmail, Google Chrome, WhatsApp         |
| 6             | Presentation Layer      | Ma’lumotni formatlash (shifrlash, siqish, kodlash)     | SSL/TLS, JPEG, MP4                     |
| 5             | Session Layer           | Sessiyani boshqarish (aloqani boshlash/yopish)        | Zoom, Skype sessiyasi                  |
| 4             | Transport Layer         | Ma’lumotlarni ishonchli uzatish, segmentatsiya         | TCP, UDP                               |
| 3             | Network Layer           | IP manzillash va marshrutlash                          | IP, Routers, Ping                      |
| 2             | Data Link Layer         | Fizik aloqani boshqarish, MAC manzil, freym            | Switch, MAC address                    |
| 1             | Physical Layer          | Elektr signallar, kabellar, bitlar uzatilishi          | Ethernet kabel, Wi-Fi, USB             |

---

## 🔢 7-Qatlam: Application Layer
### 🎯 Vazifa:
- Foydalanuvchiga eng yaqin qatlam
- Tarmoq orqali xizmat ko‘rsatuvchi ilovalar shu qatlamda ishlaydi

### 📌 Misollar:
- Web brauzer: `Google Chrome`, `Firefox`
- Email mijozlari: `Outlook`, `Gmail`
- Chat dasturlari: `Telegram`, `WhatsApp`

---

## 🔠 6-Qatlam: Presentation Layer
### 🎯 Vazifa:
- Ma’lumotlarni formatlash (shifrlash, dekodlash, siqish)

### 📌 Misollar:
- HTTPS (SSL/TLS orqali)
- Rasm formatlari: `.jpg`, `.png`
- Video formatlar: `.mp4`, `.avi`

---

## 🔐 5-Qatlam: Session Layer
### 🎯 Vazifa:
- Tarmoqdagi ilovalar o‘rtasidagi sessiyani boshqarish (boshlash, davom ettirish, tugatish)

### 📌 Misollar:
- Video qo‘ng‘iroqlar (Zoom sessiyasi)
- SSH sessiya orqali masofaviy boshqaruv
- Multiplayer o‘yinlarda o‘yinchi sessiyasi

---

## 📦 4-Qatlam: Transport Layer
### 🎯 Vazifa:
- Ma’lumotni segmentlarga bo‘lib uzatish
- Xatolikni aniqlash va ishonchli yetkazish

### 📌 Protokollar:
- **TCP** – ishonchli (YouTube, Gmail)
- **UDP** – tez, lekin noaniq (online o‘yinlar, VoIP)

---

## 🌍 3-Qatlam: Network Layer
### 🎯 Vazifa:
- IP-manzillarni boshqarish va ma’lumotni manzilga yetkazish

### 📌 Misollar:
- **IP protokoli**: 192.168.1.1
- **Routers** ishlaydi shu qatlamda
- `ping`, `traceroute` komandalar

---

## 🖧 2-Qatlam: Data Link Layer
### 🎯 Vazifa:
- Fizik uzatish qurilmalari o‘rtasida ishonchli uzatish
- MAC manzillar, freymlar bilan ishlaydi

### 📌 Misollar:
- **Switch** qurilmalari shu qatlamda ishlaydi
- MAC Address: `00:0a:95:9d:68:16`

---

## ⚡ 1-Qatlam: Physical Layer
### 🎯 Vazifa:
- Haqiqiy fizika: kabel, signal, nurlar
- Bitlar qanday qilib fizik ko‘rinishda uzatiladi

### 📌 Misollar:
- Ethernet kabellari
- Wi-Fi, USB, Bluetooth, fiber-optik aloqa

---

## 🧠 Qo‘shimcha eslatma
OSI modeli **amaliyotda bevosita ishlatilmaydi**, lekin **TCP/IP modeli** bilan birgalikda **tarmoqni o‘rganish va muammolarni aniqlashda** asosiy nazariy poydevor hisoblanadi.

---

## 🔗 Real hayotdagi taqqoslash:
Aloqani quyidagicha tasavvur qiling:
- Siz telefon orqali do‘stingizga rasm yubormoqchisiz.
- Har bir qatlam rasmni tayyorlash, kodlash, uzatish, yo‘llash, qabul qilish va ko‘rsatish jarayonida ishtirok etadi.
- Bu aynan OSI modelining qatlamlariga to‘g‘ri keladi!

---

## ✅ Yakuniy xulosa:
OSI modeli — bu tarmoqni tushunish uchun **asosiy nazariy model** bo‘lib, har bir qatlam ma’lumotlarni yuqoridan pastga (yoki aksincha) uzatadi va uni boshqaradi.

