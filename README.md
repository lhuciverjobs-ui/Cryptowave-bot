# 🚀 CryptoWave Account Creator v1.0
### 🤖 Bot Pintar Auto Bikin Akun Mining CryptoWave Massal - Gak Ribet, Cepat, Auto!
> **Buat ratusan akun mining dalam sekejap!** Email temp + referral auto + verifikasi otomatis 🔥

<div align="center">
  <img src="https://img.shields.io/badge/Version-1.0-brightgreen?style=for-the-badge">
  <img src="https://img.shields.io/badge/Node.js-18+-blue?style=for-the-badge&logo=node.js">
  <img src="https://img.shields.io/badge/Status-Stable-success?style=for-the-badge">
  <br>
  <img src="https://img.shields.io/badge/License-MIT-red?style=flat-square">
  <img src="https://img.shields.io/badge/Crypto-Mining-blue?style=flat-square">
  <img src="https://img.shields.io/badge/Referral-EARNB8A993-yellow?style=flat-square">
</div>

## 🔥 Kenapa Pake Tool Ini?

**Buat akun CryptoWave mining secara otomatis massal!** Gak perlu ribet manual satu-satu. Support temporary email + auto verifikasi kode. Siap mining langsung setelah register!

## ⚡ Fitur Keren Tool Ini

### 🤖 **Auto Registration System**
- 📧 **Email Otomatis**: Generate email sementara dari generator.email
- 👤 **Nama Random**: Display name unik buat tiap akun
- 🔑 **Password Tetap**: Semua akun pake password "masuk123"
- 🎯 **Referral Auto**: Otomatis isi kode referral EARNB8A993
- ✉️ **Auto Verifikasi**: Deteksi otomatis kode email verifikasi

### 🎨 **User Experience Mantap**
- 🎭 **UI Keren**: Banner ASCII art yang eye-catching
- 📈 **Progress Real-time**: Lihat progress bikin akun live
- ⏰ **Anti-Rate Limit**: Delay cerdas biar gak kena block
- 🎪 **Animasi Smooth**: Loading animation yang cool
- 📱 **Output Bersih**: Log yang rapi dan mudah dibaca

### 🚀 **Siap Mining Crypto**
- 📦 **Mass Create**: Bikin banyak akun sekaligus
- 🛡️ **Secure Banget**: Protected pake proxy DataImpulse
- 💰 **Bonus Referral**: Auto dapat bonus dari referral
- ⚡ **Ready Mining**: Akun langsung siap mining setelah register

## 🛠️ Install & Setup Cepat

### 📋 Kebutuhan Sistem
```bash
Node.js v18+
Windows/Linux/MacOS
Internet connection
```

### ⚡ Quick Start (3 Langkah)
```bash
# 1. Clone & masuk folder
git clone https://github.com/lhuciver/cryptowave-account-creator.git
cd cryptowave-account-creator

# 2. Install dependencies
npm install

# 3. Jalankan tool
node index.js
```

### 🔧 Ganti Proxy (Opsional)
Tool ini udah pake proxy DataImpulse bawaan. Kalo mau ganti proxy sendiri:
```javascript
// Edit di index.js baris 15-20
const proxyConfig = {
  host: 'proxy-mu.com',
  port: 1234,
  username: 'username-mu',
  password: 'password-mu'
};
```

## 🎯 Cara Pakai (Super Gampang)

### 📍 Step 1: Jalankan Tool
```bash
node index.js
```

### 📍 Step 2: Masukin Jumlah Akun
```
📊 How many CryptoWave accounts to create? (Max 10 for safety): 5
```

### 📍 Step 3: Biarin Auto Kerja
Tool otomatis ngerjain semua:
- 👤 Generate nama display random
- 📧 Buat email temporary
- 🔐 Register ke CryptoWave pake referral EARNB8A993
- 🔑 Password semua: **masuk123**
- ✉️ Auto deteksi kode verifikasi email

### 📍 Step 4: Check Hasil
Akun langsung tersimpan di `cryptowave_accounts.txt`:
```
CryptoWave: CoolMiner1234|randomemail@domain.com|masuk123|Ref: EARNB8A993|Code: 123456
```

## 📱 Preview Tool

## ⚙️ Konfigurasi Penting

### 🔑 Ganti Password Default
```javascript
// Di index.js baris 623
const password = 'passwordbaru123'; // Ganti 'masuk123'
```

### 🎯 Ganti Referral Code
**📍 Lokasi:** `index.js` baris 624
```javascript
const referralCode = 'KODE_REF_BARU'; // Ganti 'EARNB8A993'
```

**🔥 Cara Ganti:**
1. Buka `index.js`
2. Cari baris 624: `const referralCode = 'EARNB8A993';`
3. Ganti `'EARNB8A993'` dengan kode referral kamu
4. Simpan dan jalankan ulang

**⚠️ Penting:** Pastikan referral code valid ya!

### 📊 Naikin Limit Akun
```javascript
// Di index.js baris 589
if (loopCount > 50) { // Ubah dari 10 ke 50
```

### 📧 Ganti Email Provider
```javascript
// Edit function getTempEmail() baris 102
// Ganti endpoint generator.email ke provider lain
```

## ⚠️ Catatan Penting

**Disclaimer:** Tool ini buat educational aja ya! Pastiin legal di negara kamu dan gak abuse. Gunakan sehat untuk mining crypto legit!

### 📏 Best Practices:
- 🎯 Maksimal 10 akun per jam (biar gak kena block)
- 🛡️ Pake proxy berbeda kalau bikin banyak akun
- ❌ Jangan pake buat spam atau aktivitas ilegal
- 📜 Respect CryptoWave terms of service
- ⚡ Gunakan untuk mining yang halal

### ⏱️ Anti-Rate Limit:
- Tool udah ada delay otomatis
- Gak usah force bikin terlalu banyak sekaligus
- Pake VPN/proxy rotation kalau batch besar

## 🐛 Ada Masalah? Fix Cepat

### ❌ "Failed to get temporary email"
- **Fix**: Cek koneksi internet kamu
- **Tips**: Generator.email lagi down, tunggu bentar atau ganti provider

### ❌ "Registration failed"
- **Fix**: CryptoWave lagi maintenance atau rate limit
- **Tips**: Kurangin jumlah akun (max 5 dulu) atau coba besok pagi

### ❌ "Verification code not found"
- **Fix**: Email verifikasi lama sampe
- **Tips**: Akun tetep bisa login manual lewat website nanti

### ❌ Proxy Error
- **Fix**: Cek username/password proxy
- **Tips**: Pastikan proxy support HTTPS dan gak expired

## 📞 Butuh Bantuan?

<div align="center">

### 👨‍💻 **lhuciver**
**GitHub**: [@lhuciver](https://github.com/lhuciverjobs-ui)  
**Telegram**: [@lhuciver](https://t.me/sdksdkr00t)  
**Discord**: lhuciver#1337

**⭐ Like tool ini? Kasih star di GitHub ya!**

</div>

---

<div align="center">
Made with ❤️ by <strong>lhuciver</strong> | CryptoWave Account Creator v1.0

**🚀 Siap mining crypto? Daftar di:**
**🔗 https://cryptowave.blog/auth?ref=EARNB8A993**
</div>
