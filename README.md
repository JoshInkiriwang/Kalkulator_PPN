# Kalkulator PPN 12% / VAT 12% Calculator 🇮🇩 🇬🇧

[![Aplikasi Web](https://img.shields.io/badge/Aplikasi_Web-Buka_Aplikasi-blue)](https://www.appsheet.com/start/c6b2645b-0d30-430a-ae0a-5956d68abd3c)

---

### 🇮🇩 Deskripsi Singkat
Aplikasi kalkulator PPN sederhana yang dibuat dengan `low-code` untuk membantu pengguna menghitung Pajak Pertambahan Nilai (PPN) sebesar 12%. Aplikasi ini menyimpan riwayat perhitungan secara personal dan aman, mengatasi tantangan umum dalam pengembangan `low-code`.

### 🇬🇧 Brief Description
A simple VAT calculator app built with `low-code` to help users compute 12% Value Added Tax (VAT). This application securely stores personal calculation history, addressing common challenges in `low-code` development.

---

### 🎯 Tujuan Proyek / Project Goals

* 🇮🇩 Membantu pengguna menghitung PPN secara mudah dan cepat, cocok untuk kebutuhan individu dan UMKM.
* 🇬🇧 Helping users quickly and easily calculate VAT, suitable for personal and small business use.

---

### 🛠️ Tools yang Digunakan / Tools Used

* **Figma** (mockup & prototype)
* **AppSheet** (platform pengembangan `low-code`)
* **Google Sheets** (sebagai `database` utama)
* **draw.io** (diagram tools)
* **Gemini** (AI assistant)

---

### ✨ Fitur Utama / Key Features

* **🔒 Keamanan Data Personal**: Setiap pengguna hanya dapat melihat data yang mereka buat sendiri melalui `Security Filters`.
  * 🇬🇧 **Personal Data Security**: Each user can only view their own data via `Security Filters`.
* **🖊️ Penomoran Item Otomatis**: Nama item dibuat secara otomatis untuk memudahkan pengisian formulir.
  * 🇬🇧 **Automatic Item Numbering**: Item names are automatically generated to simplify form-filling.
* **✅ Validasi Input**: Mencegah input nilai negatif atau nol pada kolom penting.
  * 🇬🇧 **Input Validation**: Prevents negative or zero values in key columns.
* **📈 Riwayat Perhitungan**: Menyimpan riwayat semua transaksi dengan kontrol `save` dan `cancel` yang jelas.
  * 🇬🇧 **Calculation History**: Stores transaction history with clear save and cancel controls.

---

### 🚶 User Flow (Versi Web)

* 🇮🇩 Pengguna mengisi data kalkulasi.
* 🇮🇩 **Simpan/Batal**: Tombol "Save" akan menyimpan data, sementara "Cancel" akan menghapus entri. Jika `form` sudah terisi, "Cancel" akan memunculkan verifikasi untuk mencegah penghapusan data tidak sengaja.
* 🇬🇧 **Save/Cancel**: The "Save" button saves the data, while "Cancel" discards the entry. If the form is filled, "Cancel" triggers a verification to prevent accidental data loss.

---

### 🧠 Pembelajaran & Tantangan / Challenges & Learnings

* **🇮🇩 Isu Autentikasi**: Aplikasi ini mewajibkan pengguna untuk `login` karena data disimpan secara personal dan perlu diakses secara aman. Ini berbeda dengan kalkulator web lainnya yang tidak menyimpan data.
  * 🇬🇧 **Authentication Issue**: This app requires users to log in because data is stored personally and needs secure access. This differs from other web calculators that do not store data.
* **🇮🇩 `Bug` Lokalisasi**: Mengatasi masalah format angka (misalnya, `xxx,xxx.xx` vs `xxx.xxx,xx`) di mana pengaturan `locale` tidak berfungsi secara konsisten.
  * 🇬🇧 **Localization Bug**: Overcoming number format issues (e.g., `xxx,xxx.xx` vs `xxx.xxx,xx`) where `locale` settings did not work consistently.
* **🇮🇩 Pemilihan Arsitektur**: Memilih struktur tiga tabel terpisah untuk menghindari kerumitan dan `bug` dalam satu tabel.
  * 🇬🇧 **Architecture Choice**: Choosing a separate three-table structure to avoid complexity and bugs from a single-table setup.

---

### 📦 Status Proyek / Project Status

✅ Aplikasi fungsional di AppSheet sudah selesai.

---

### 📸 Tangkapan Layar / Screenshots

*(Tambahkan tangkapan layar form kalkulator dan riwayat di sini.)*

---

### 🧠 Rencana Lanjutan / Future Plans

* **🇮🇩 Ekspor Data**: Mengeksplorasi fungsionalitas ekspor data (.txt, .xml) sesuai dengan format standar sistem perpajakan.
  * 🇬🇧 **Data Export**: Exploring the functionality to export data (.txt, .xml) in accordance with the standard format of the tax system.
* **🇮🇩 `Dashboard` Visual**: Mengimplementasikan `dashboard` visual untuk analisis data.
  * 🇬🇧 **Visual Dashboard**: Implementing a visual dashboard for data analysis.
* **🇮🇩 Integrasi API**: Mempertimbangkan integrasi dengan sistem lain melalui API AppSheet.
  * 🇬🇧 **API Integration**: Considering integration with other systems via AppSheet's API.

---

### 📁 Lisensi / License
MIT License
