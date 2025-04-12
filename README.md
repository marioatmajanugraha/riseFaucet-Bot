# 🚀 RiseFaucet-Bot

Script ini mengotomatiskan klaim token di faucet **Rise Testnet** dengan efisien dan rapi!

![Rise Faucet](https://github.com/user-attachments/assets/0e8d8783-6281-4262-88a0-5ea0b229b0bb)
---

## 📌 Fitur
- ✅ Auto claim untuk semua token yang tersedia (`ETH`, `MOG`, `PEPE`, `RISE`, `USDC`, `USDT`, `WBTC`)
- 🔒 Dukungan **proxy** (`proxy.txt`) untuk koneksi aman
- 🔐 Integrasi **Anti-Captcha** untuk bypass CAPTCHA otomatis
- 📊 Tampilan status token dalam **tabel rapi** (Claimed/Failed + detail)
- ⏱️ Delay antar klaim untuk menghindari **rate limit**
- 🎯 **Mode sederhana**: proses semua wallet dan token secara otomatis

---

## 🚀 Cara Penggunaan

### 1. Clone repository
```
git clone https://github.com/marioatmajanugraha/riseFaucet-Bot.git
cd riseFaucet-Bot
```

### 2. Install Dependencies
```
npm install axios chalk@4.1.2 cfonts http-proxy-agent socks-proxy-agent
```

### 3. Siapkan file konfigurasi
wallets.json
```
[
  {
    "address": "GANTI WALLET ADDRESS KALIAN",
    "privateKey": "GANTI PRIVATEKEY WALLET ADDRESS KALIAN"
  }
]
```

proxy.txt (opsional)
```
http://username:password@host:port
socks5://username:password@host:port
```

### 4. Jalankan Script
```
node faucet.obf.js
```

### 5. Ikuti Instruksi
Pilih apakah ingin menggunakan proxy (y/n)

Masukkan Anti-Captcha API Key

Script akan otomatis memproses semua wallet dan token

## ⚠️ Disclaimer
Gunakan script ini dengan bijak dan sesuai aturan Rise Testnet.

Developer tidak bertanggung jawab atas penyalahgunaan atau masalah akun.

## 🤝 Kontribusi
Ingin menambahkan fitur atau perbaikan?

Fork repo ini dan ajukan pull request – kolaborasi sangat kami hargai!

## 📞 Kontak
Pertanyaan? Hubungi: [@balveerxyz](https://t.me/balveerxyz)

Join channel Telegram gratis: [Airdrop 888](https://t.me/airdroplocked)
