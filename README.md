# n8n – Sistem Permohonan Izin Karyawan

Repository ini berisi dokumentasi dan workflow n8n untuk sistem
**Permohonan Izin Karyawan** yang terintegrasi dengan Google Sheets,
Email, dan Telegram.

Sistem ini dirancang untuk mengelola proses perizinan karyawan secara
otomatis mulai dari pengajuan, persetujuan atasan, verifikasi HR,
hingga realisasi izin.

---

## 🎯 Tujuan Project

- Mengotomatisasi proses perizinan karyawan
- Mengurangi proses manual dan kesalahan input
- Mempercepat alur persetujuan
- Menyediakan dokumentasi dan jejak proses (audit trail)
- Mengirim notifikasi otomatis ke pihak terkait

---

## 🧩 Gambaran Umum Sistem

Alur utama sistem terdiri dari 4 tahap:

1. Pengajuan izin oleh karyawan
2. Persetujuan oleh atasan
3. Verifikasi akhir oleh HR
4. Realisasi izin oleh karyawan

Google Sheets digunakan sebagai database utama,
sedangkan n8n berperan sebagai pengatur logika dan automasi.

---

## 🛠 Teknologi yang Digunakan

- **n8n** – Workflow Automation
- **Google Form** – Input data karyawan
- **Google Sheets** – Database
- **Google Apps Script** – Tombol persetujuan (Setujui / Tolak)
- **Gmail API** – Notifikasi email
- **Telegram Bot API** – Notifikasi cepat

---

## 📁 Struktur Repository

