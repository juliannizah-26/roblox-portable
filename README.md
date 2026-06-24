<p align="center">
  <img src="https://github.com/user-attachments/assets/a6dcb2d8-73a8-4ce2-bec0-ad452f27c997" width="100" alt="Bloxstrap Loader"/>
</p>

# <p align="center"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=28&pause=500&color=2DEB8C&center=true&width=500&height=60&lines=ROBLOX;BLOXSTRAP" alt="Typing" /></p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows-blue?style=for-the-badge" alt="Windows" />
  <img src="https://img.shields.io/badge/Environment-Server%20%26%20Client-orange?style=for-the-badge" alt="Environment" />
</p>

---

## 🚀 Cara Pakai

### Prasyarat
- **Microsoft .NET 6 Desktop Runtime** — Installer tersedia di folder `_CommonRedist`
- Wajib diinstall di **Server** dan **Client**

### Langkah-langkah
1. Download Bloxstrap dari [bloxstraplabs.com](https://bloxstraplabs.com/)
2. Jalankan **Bloxstrap Loader.exe** (Untuk Membuat Folder Otomatis)
3. Install Bloxstrap, arahkan lokasi instalasi ke folder **Bloxstrap**
4. Jalankan kembali **Bloxstrap Loader.exe** (Administrator jika diperlukan)
   - Pertama kali jalan di **Server** — registry akan di-export ke `_AppRegistry/`

### Konfigurasi
Buka `config.ini` untuk mengatur sesi login:

```ini
[Settings]
AutoLogout=true
```

| Nilai | Keterangan |
|-------|-----------|
| `true` | akun logout otomatis |
| `false` | akun tetap login |

## Struktur Folder

```
Bloxstrap Loader/
├── Bloxstrap Loader.exe      # Launcher utama
├── Bloxstrap/                # Folder instalasi Bloxstrap
├── _AppRegistry/             # Hasil export registry (server)
├── _CommonRedist/            # .NET Runtime installer
├── config.ini                # Pengaturan AutoLogout
├── z_Settings.bat            # Buka settings
└── z_Uninstall.bat           # Hapus semua
```
