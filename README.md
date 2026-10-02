# Generator Jadwal Fleksibel Multi-Kebutuhan 📅

Aplikasi manajemen dan pembuat jadwal otomatis yang dirancang untuk berbagai kebutuhan organisasi, komunitas, ibadah lingkungan/sektor, regu piket & ronda malam, shift kerja operasional, hingga rapat & event organisasi. Dibangun dengan fokus pada fleksibilitas tinggi, kemudahan penggunaan, estetika modern, dan fungsionalitas rotasi penugasan yang cerdas.

---

## ✨ Fitur Unggulan

### 1. ⚡ Preset Template Siap Pakai
Tersedia berbagai templat siap pakai yang langsung menyesuaikan nama kolom dan struktur jadwal:
*   **Ibadah Lingkungan**: Pengkhotbah, Paragenda, Pembawa Acara, serta Tuan Rumah & Alamat.
*   **Piket & Ronda Malam**: Komandan Pos, Petugas Utama, Petugas Pendamping, Pos/Wilayah & Area Patroli.
*   **Shift Kerja Operasional**: Shift Pagi (08:00 - 16:00), Shift Siang (16:00 - 24:00), Shift Malam (00:00 - 08:00), Unit/Cabang & Lokasi.
*   **Rapat & Event Organisasi**: Moderator/Ketua, Notulis/Sekretaris, PJ Logistik/Operator, Tempat/Ruang & Link Meeting.
*   **Kustom / Bebas**: Struktur fleksibel untuk peran dan lokasi sesuai kebutuhan spesifik Anda.

### 2. 🤖 Flexible Schedule Generator
*   **Pilih Hari (Mingguan)**: Tentukan rentang tanggal dan pilih hari-hari tertentu dalam seminggu.
*   **Pola Bulanan**: Hasilkan jadwal berdasarkan urutan minggu dalam bulan (misalnya: Minggu ke-1 & ke-3).
*   **Interval Harian**: Rotasi otomatis setiap N hari (misalnya: piket 2 hari sekali).
*   **Opsi Waktu / Jam**: Sertakan jam pelaksanaan (misal: `19:00 WIB`) secara otomatis ke setiap baris jadwal.

### 3. 🎛️ Pengaturan Kolom Dinamis & Kustomisasi UI
*   **Tambah & Hapus Kolom**: Tambahkan kolom tugas baru dengan singkatan kustom (misal: "Pemusik" dengan kode "PM").
*   **Urutkan & Sembunyikan**: Ubah urutan kolom tugas (naik/turun) atau sembunyikan kolom yang sedang tidak digunakan.
*   **Sertakan/Sembunyikan Bagian**: Toggle untuk menampilkan/menyembunyikan bagian Tuan Rumah/Lokasi serta Kolom Keterangan.

### 4. 👥 Pool & Rule-Based Assignment (Zap ⚡)
*   **Database Pelayan Mandiri**: Kelola daftar nama petugas per masing-masing kolom peran secara independen.
*   **Algoritma Anti-Bentrok (Zap ⚡)**: Fitur pengisian otomatis (**Zap ⚡**) merotasi nama petugas secara merata serta mencegah satu orang bertugas ganda dalam satu hari yang sama.
*   **Manajemen Tuan Rumah / Lokasi Massal**: Fitur *Bulk Import* memungkinkan Anda mengimpor puluhan nama & lokasi sekaligus (Copy-Paste dari Excel/WA).
*   **Deteksi Cadangan (Reserve)**: Jika daftar lokasi/tuan rumah lebih banyak dari slot jadwal, sisanya ditampilkan otomatis sebagai bagian cadangan.

### 5. 📊 Dashboard Statistik Penugasan
*   **Real-Time Counter**: Pantau akumulasi partisipasi setiap anggota per peran dan total keseluruhan secara otomatis.
*   **Distribusi Merata**: Membantu pengurus memantau dan membagi beban tugas secara adil.

### 6. 🎨 UI/UX & Formatting Modern
*   **Dark Mode Support**: Mode gelap dan terang yang nyaman di mata dengan transisi halus.
*   **Cetak PDF / Print-Ready**: Tata letak teroptimasi untuk cetak lanskap langsung dengan tampilan bersih dan rapi.
*   **Modal Tentang Aplikasi**: Akses informasi versi, panduan fitur, dan detail aplikasi langsung dari antarmuka.

### 7. 📤 Ekspor & Penyimpanan Lokal
*   **Export Excel (`.xlsx`)**: Unduh data lengkap dalam format spreadsheet untuk arsip digital.
*   **LocalStorage Sync**: Data tersimpan otomatis di browser dengan penomoran versi otomatis (auto-versioning) dan penanda waktu pembaruan terakhir (*last updated*).

---

## 🛠️ Panduan Penggunaan

1.  **Pilih Template**: Pilih preset template yang sesuai di bagian atas (Ibadah, Piket, Shift, Rapat, atau Kustom).
2.  **Generate Jadwal**: Tentukan moda generator (Mingguan/Pola Bulanan/Interval), pilih rentang tanggal dan jam, lalu klik **Generate Jadwal**.
3.  **Kelola Daftar Nama/Lokasi**: Masukkan nama petugas di masing-masing kolom tugas dan daftar lokasi/tuan rumah.
4.  **Inject Otomatis (Zap ⚡)**: Klik tombol **Inject** (ikon petir ⚡) pada kolom peran atau lokasi untuk mengisi secara otomatis dengan algoritma rotasi cerdas.
5.  **Edit & Adjust**: Edit teks atau ubah pilihan secara manual langsung pada tabel interaktif.
6.  **Cetak atau Ekspor**: Klik **Cetak PDF** untuk mencetak/simpan sebagai PDF, atau **Ekspor Excel** untuk menyimpan file `.xlsx`.

---

## ⚠️ Catatan Mengenai Penyimpanan Data

*   Aplikasi ini menyimpan data secara lokal pada **LocalStorage Browser** perangkat Anda.
*   Data tersimpan aman selama cache browser tidak dibersihkan atau tidak menggunakan mode Incognito/Private.
*   **Saran**: Lakukan **Ekspor Excel** secara berkala setelah jadwal selesai dibuat untuk cadangan.

---

## 🚀 Teknologi yang Digunakan

*   **Core**: React 19 + Vite 6
*   **Bahasa**: TypeScript (Type-safe)
*   **Styling**: Tailwind CSS 4.0
*   **Animasi**: Motion (Framer Motion)
*   **Ikon**: Lucide React
*   **Pemrosesan Excel**: XLSX (SheetJS)
*   **Storage**: Browser LocalStorage

---

## 📄 Lisensi

Dibuat dengan ❤️ untuk kemudahan pengelolaan jadwal organisasi, komunitas, dan pelayanan. Bebas digunakan dan dikembangkan.
