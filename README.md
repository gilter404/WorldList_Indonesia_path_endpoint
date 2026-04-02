# 🇮🇩 Indonesian Endpoint & Path Wordlist

Kumpulan wordlist endpoint/path yang sering digunakan pada website di Indonesia.  
Cocok untuk keperluan **pentesting**, **bug bounty**, dan **recon automation**.

---

## 📌 Deskripsi

Wordlist ini berisi endpoint umum yang sering ditemukan pada:

- Website pemerintah (go.id)
- Website kampus (ac.id)
- Website perusahaan lokal
- Aplikasi berbasis Indonesia

---

---

## 🚀 Cara Penggunaan

### Dengan `ffuf`
```bash
ffuf -u https://target.com/FUZZ -w indonesia-endpoints.txt
```

### Dengan `dirsearch`
```bash
dirsearch -u https://target.com -w indonesia-endpoints.txt
```

### Dengan `gobuster`
```bash
gobuster dir -u https://target.com -w indonesia-endpoints.txt
```

⚠️ Disclaimer
Wordlist ini hanya untuk:
Edukasi
Penelitian keamanan
Pengujian legal dengan izin
Dilarang digunakan untuk aktivitas ilegal.
🤝 Kontribusi
Pull request sangat diterima!
Tambahkan endpoint khas Indonesia lainnya 🔥
⭐ Support
Kalau bermanfaat:
⭐ Star repo ini
🔁 Share ke teman pentester
