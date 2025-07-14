# 📜 Surat Ini Disimpan Dalam Diam

Sebuah proyek HTML statis — bukan sekadar halaman web,  
tapi arsip kenangan yang dikunci oleh waktu dan kata sandi.

---

## 💡 Tentang Proyek Ini

**"Surat Untuk Wita"** adalah file `index.html` interaktif yang berisi 20 halaman surat terenkripsi.  
Surat-surat ini hanya bisa dibuka dengan satu kata yang punya arti,  
dan satu lagu yang mengiringi perjalanan membacanya.

Tidak ada sistem login akun.  
Tidak ada cloud, tidak ada database.  
Hanya satu file... dan seseorang yang dipilih untuk membukanya.

---

## 🔐 Keamanan

- Seluruh isi surat disimpan dalam bentuk terenkripsi (AES).
- Password tidak disimpan langsung, hanya diverifikasi melalui hash SHA-256.
- Isi surat hanya bisa dibaca **jika** pembaca tahu kata kuncinya —  
  bukan karena dia menebak, tapi karena dia mengingatnya.

---

## 🎵 Fitur

- 🎧 *Media Player* dengan kontrol Play, Pause, dan progress bar.
- 🔐 *Halaman Login* dengan password tersembunyi.
- 📖 *20 Halaman Surat* yang akan terbuka satu per satu.
- 🕰️ *Counter* waktu sejak surat pertama kali dibuat.
- 🧭 *Navigasi Halaman*: tombol Kembali, Lanjut, dan Dashboard.
- 💌 Surat bisa terus ditambah di halaman berikutnya — tinggal tempel.

---

## 📁 Struktur File

- `index.html` – Halaman utama surat yang bisa dijalankan offline.
- `cardigan.mp3` – Lagu utama sebagai latar suasana.
- **Tidak ada dependensi eksternal yang berat** — ringan dan pribadi.

---

## 📌 Catatan

Surat ini bukan untuk dibuka oleh siapa pun.  
Tapi kalau kamu membaca ini, dan kamu tahu kata kuncinya,  
maka... mungkin surat ini memang ditulis untuk kamu.

---

> Tidak semua isi hati bisa diucapkan langsung.  
> Tapi kadang... HTML dan musik cukup untuk menyampaikan semuanya.
