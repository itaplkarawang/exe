# ⚡ Bulk App Installer

Install banyak aplikasi `.exe` / `.msi` sekaligus secara otomatis — tanpa klik satu per satu.

![Platform](https://img.shields.io/badge/Platform-Windows-blue)
![Python](https://img.shields.io/badge/Built%20with-PyInstaller-green)

---

## 📥 Download

Pergi ke tab **[Releases](../../releases)** → download `BulkInstaller.exe` terbaru.

> Tidak perlu install Python atau software apapun.

---

## ✨ Fitur

- 📂 **Scan folder / USB** — temukan semua `.exe` dan `.msi` otomatis
- ✅ **Pilih sesuka hati** — centang/uncentang aplikasi yang mau diinstall
- 🚀 **Silent install** — install otomatis tanpa popup / klik manual
- 🔍 **Auto-detect tipe** — Inno Setup, NSIS, MSI dikenali otomatis
- 📊 **Status real-time** — lihat progress tiap installer
- 📋 **Log detail** — catat hasil setiap proses install
- ⛔ **Bisa dibatalkan** — stop kapan saja di tengah proses

---

## 🚀 Cara Pakai

1. Download `BulkInstaller.exe` dari tab Releases
2. Klik kanan → **Run as Administrator**
3. Klik **📂 Pilih Folder** → arahkan ke folder/USB berisi installer
4. Centang aplikasi yang mau diinstall
5. Klik **🚀 Mulai Install** → selesai!

---

## 🔨 Build Sendiri

Repo ini sudah dilengkapi GitHub Actions. Setiap push ke `main` akan otomatis build ulang `.exe` dan upload ke Releases.

```
git clone https://github.com/USERNAME/bulk-installer
cd bulk-installer
git add .
git commit -m "update"
git push
```

Tunggu ~2 menit → cek tab **Actions** → setelah hijau, `.exe` tersedia di tab **Releases**.

---

## ⚠️ Catatan

- Jalankan sebagai **Administrator** agar silent install bisa berjalan
- Beberapa installer mungkin tidak support silent mode → akan dibuka manual
- Exit code `3010` = sukses tapi perlu restart PC
