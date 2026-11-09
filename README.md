# NoteCL - Sistem Catatan & Monitoring Kiriman Lamaran Kerja

Aplikasi web modern untuk mendokumentasikan setiap berkas lamaran pekerjaan yang telah dikirim, memantau perkembangan tahapan seleksi secara real-time, mengorganisir jadwal tes & wawancara, serta mengevaluasi riwayat rekrutmen perusahaan secara terstruktur dan efisien.

## 🚀 Fitur Utama
- **Halaman Depan Minimalis**: Tampilan bersih pas 1 layar (100vh) tanpa scrollbar dengan tombol navigasi *Lanjut Ke Catatan*.
- **Integrasi Firebase Realtime Database**: Operasi CRUD langsung tersinkronisasi secara live ke database cloud Firebase.
- **Tabel Interaktif DataTables**:
  - Pilihan jumlah tampilan data: 10, 25, 50, 100, 500, 1000, All (Default: **All**).
  - Pengurutan data otomatis berdasarkan **waktu terbaru di posisi teratas** (No 1 di atas).
  - Pencarian instan (Live Search) berdasarkan nama perusahaan, posisi/role, level, atau email tujuan.
- **Aksi Cepat**:
  - ✏️ **Ubah Status Cepat**: Ikon pensil tersendiri barengan status untuk memperbarui status (*Dikirim, Screening HR, Psikotes, Interview, Offering, Ditolak*).
  - 📝 **Ubah Data Lengkap**: Form edit untuk seluruh kolom data.
  - 🗑️ **Hapus Data**: Konfirmasi penghapusan data secara aman.
  - ➕ **Input Catatan Baru**: Dilengkapi picker Tanggal & Waktu native serta tombol *🕒 Gunakan Waktu Sekarang*.
- **Mobile Responsive**: Tampilan dioptimasi penuh untuk perangkat smartphone/HP.

## 🛠️ Teknologi yang Digunakan
- HTML5 & CSS3
- [Bootstrap 5.3.3](https://getbootstrap.com/)
- [FontAwesome 6.5.1](https://fontawesome.com/)
- [jQuery 3.7.1](https://jquery.com/)
- [DataTables 1.13.7 Bootstrap 5](https://datatables.net/)
- [Firebase Realtime Database REST API](https://firebase.google.com/)

## 🌐 Akses Online
Aplikasi ini di-host secara online melalui GitHub Pages:
- **URL**: https://tijartaufikrahman.github.io/NoteCL/
