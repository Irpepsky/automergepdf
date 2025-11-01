# 🪶 AutomergePDF by FSN (29102025)

## 📦 Versi
**v1.0.0 (Final Release)**  
Tanggal Rilis: **29 Oktober 2025**  
Dibuat oleh: **FSN**

---

## 🚀 Deskripsi
**AutomergePDF by FSN** adalah aplikasi ringan berbasis **Python + Tkinter** yang berfungsi untuk **memantau folder secara otomatis dan menggabungkan file PDF** berdasarkan nama prefix.  
Dirancang agar berjalan **otomatis di background**, dengan tampilan GUI yang minimalis namun informatif.

---

## ✨ Fitur Utama
✅ **Auto Merge** — Menggabungkan file PDF dengan prefix sama.  
✅ **Auto Move Single File** — Memindah file tunggal ke output folder.  
✅ **Auto Start & Tray Mode** — Berjalan otomatis dan tetap aktif di tray.  
✅ **Auto Config Reload** — Reload config.ini tanpa restart.  
✅ **Activity Log** — Catatan aktivitas real-time di GUI dan file log.  
✅ **Compact GUI Mode** — Tombol + / - untuk sembunyikan tampilan log.  
✅ **Safety Lock** — Cegah aplikasi dijalankan ganda.

---

## ⚙️ Struktur Folder
```
📁 AutomergePDF/
│
├── AutoMergePDF.py        ← Main program
├── config.ini             ← Konfigurasi input/output folder & interval
├── log/                   ← Folder hasil log aktivitas
├── automergepdf.lock      ← Lock file otomatis (hapus sendiri saat close)
└── README.md              ← Dokumentasi ini
```

---

## 🧩 Isi `config.ini` Default
```ini
[settings]
input_folder = D:\PDF\Input
output_folder = D:\PDF\Output
scan_interval = 10
stable_delay = 5
```

---

## 🪄 Instalasi & Menjalankan Aplikasi

### 1️⃣ Install Python
Pastikan sudah menginstall **Python 3.9+**
```bash
python --version
```

### 2️⃣ Install Library yang Dibutuhkan
```bash
pip install PyPDF2 pystray pillow
```

### 3️⃣ Jalankan Aplikasi
```bash
python AutoMergePDF.py
```

---

## 🧠 Tips Penggunaan
💡 File PDF harus menggunakan format nama seperti:
```
INV_001.pdf
INV_002.pdf
```
➡️ Hasil merge otomatis menjadi:
```
INV.pdf
```

💡 Klik **📝 Config** untuk membuka dan mengedit `config.ini` langsung.  
💡 Klik **+ / -** untuk menampilkan atau menyembunyikan log.  
💡 Klik **X** hanya memindahkan aplikasi ke system tray.

---

## 📄 Changelog
### 🆕 v1.0.0 (Final Release)
- Penambahan auto start & tray icon  
- Compact GUI dengan tombol + / -  
- Log harian otomatis  
- Auto reload config.ini  
- Lock system untuk mencegah multi-instance  
- Perbaikan UI & spacing tombol  
- Exit aman dengan cleanup otomatis

---

## 🧑‍💻 Pengembang
**FSN Dev Team**  
📅 29 Oktober 2025  
🔖 Version: 1.0.0 — Stable Release

---

## 📄 License
This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

Developed with ❤️ by **FSN**
