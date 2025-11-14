# 🧠 **MindFlash Chatbot – Open Source Frontend Chat UI**

MindFlash adalah antarmuka chatbot modern yang terinspirasi dari desain aplikasi messaging, dengan fitur lengkap seperti tema gelap/terang, upload file, auto-scroll, dan formatting teks ala WhatsApp.  
Proyek ini menggunakan **HTML, CSS, dan JavaScript murni** serta terhubung langsung dengan **Google Generative Language API (Gemini)**.

---

## 🚀 **Fitur Utama**

### 💬 *Chat Interface Modern*
- Desain elegan dengan animasi halus  
- Sistem pesan user & bot  
- Avatar untuk user dan bot

### 🎨 *Dark & Light Theme*
- Tombol switch tema  
- Tersimpan otomatis via `localStorage`

### 📎 *Upload File*
- Mendukung image, PDF, TXT, CSV  
- Preview otomatis di chat

### 🧵 *Formatting Text*
- **Bold** → `*teks*`  
- _Italic_ → `_teks_`  
- ~~Strikethrough~~ → `~teks~`  

### 🧩 *Syntax Highlighting untuk Kode*
- Menggunakan **highlight.js**  
- Tombol copy otomatis pada blok kode

### 🔄 *Auto Scroll & Anti Skip*
- Auto scroll saat ada pesan baru  
- Auto-scroll indicator saat user scroll manual

### 💾 *Save Chat*
- Riwayat chat otomatis disimpan di `localStorage`

---

## 📦 **Instalasi & Penggunaan**

### 1. Clone repository
```bash
git clone https://github.com/USERNAME/REPO.git
cd REPO
```

> Ganti `USERNAME/REPO` menjadi repo Anda.

---

### 2. Atur API Key
Masukkan API key Gemini Anda pada bagian berikut di `index.html`:

```javascript
const API_KEY = "MASUKKAN_API_KEY_ANDA_DI_SINI";
```

Letaknya di:

```javascript
const API_KEY = "...";
const API_URL = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=${API_KEY}`;
```

---

### 3. Jalankan secara lokal
Tidak memerlukan server — cukup buka:

```
index.html
```

---

## 🖥️ **Struktur Proyek**

```
/
├── index.html     # File utama berisi HTML, CSS, dan JS
├── mindflash.png  # Avatar bot
├── user.png       # Avatar user
└── README.md      # Dokumentasi
```

---

## 🧩 **Cara Kerja Chatbot**

1. User mengirim pesan  
2. UI membuat bubble chat  
3. Pesan dikirim ke Gemini API  
4. Respons bot ditampilkan + diformat + highlight  
5. Chat disimpan ke localStorage

---

## 🌍 **Deploy ke Hosting**

### GitHub Pages
1. Settings → Pages  
2. Pilih branch `main`  
3. Pilih folder root  
4. Done!

### Vercel

### Netlify

---

## 🤝 **Kontribusi**

1. Fork repo  
2. Buat branch baru  
3. Commit perubahan  
4. Lakukan pull request  

---

## 📜 **Lisensi**

Dirilis di bawah **MIT License**.

---

## ❤️ **Credits**

Dibuat oleh: **Arsyadin Awwal**  
Bebas digunakan untuk keperluan personal maupun komersial.

