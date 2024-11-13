# ApkPenghitungKataFrame

**Aplikasi ini adalah aplikasi desktop berbasis Java Swing yang berfungsi untuk menghitung jumlah kata, karakter, kalimat, paragraf, serta mencari jumlah kemunculan kata tertentu dalam teks yang dimasukkan oleh pengguna.**

## Deskripsi
ApkPenghitungKataFrame memungkinkan pengguna untuk menghitung berbagai statistik dari teks, seperti jumlah kata, karakter, kalimat, paragraf, serta melakukan pencarian kata tertentu. Aplikasi ini dibangun menggunakan Java Swing dan dapat dijalankan di berbagai sistem operasi yang mendukung Java.

## Fitur
- **Penghitungan Statistik Teks**: Menampilkan jumlah kata, karakter, kalimat, paragraf.
- **Pencarian Kata**: Mencari kata tertentu dan menampilkan jumlah kemunculannya.
- **Simpan ke File**: Menyimpan teks dan hasil perhitungan ke dalam file `.txt`.
- **Pengaturan UI**: Tombol interaktif untuk memudahkan navigasi pengguna.

## Keunggulan
- **User-Friendly**: Antarmuka sederhana dengan tombol terpisah untuk setiap fungsi.
- **Multifungsi**: Menyediakan statistik teks lengkap dan pencarian kata.
- **Penyimpanan Hasil**: Menyimpan hasil perhitungan dalam format `.txt`.
- **Tampilan Responsif**: Dibuat dengan Java Swing untuk responsivitas lintas platform.

## Komponen GUI
- **JFrame**: Jendela utama aplikasi.
- **JPanel**: Panel utama untuk menampung semua komponen.
- **JScrollPane**: Area scrollable untuk teks yang panjang.
- **JTextArea**: Area input teks.
- **JTextField**: Kolom untuk input kata yang akan dicari.
- **JLabel**: Label untuk menampilkan hasil perhitungan dan instruksi.
- **JButton**: Tombol untuk berbagai aksi (Hitung, Simpan, Hapus, Keluar).

## Layout Tampilan
Aplikasi menggunakan `GroupLayout` untuk mengatur komponen di dalam `JPanel`. Komponen disusun agar tetap terstruktur dan responsif:
- **Panel Teks**: Area input teks dapat di-scroll.
- **Panel Pencarian Kata**: Kolom pencarian kata ditempatkan di atas area teks.
- **Panel Hasil**: Label hasil perhitungan berada di bawah teks.
- **Panel Tombol**: Tombol-tombol aksi berada di bawah label hasil.

## Cara Menggunakan
1. **Masukkan Teks**: Ketik atau tempel teks di area `JTextArea`.
2. **Hitung Statistik**: Klik "Hitung Kata" untuk melihat jumlah kata, karakter, kalimat, paragraf, dan kemunculan kata tertentu.
3. **Pencarian Kata**: Masukkan kata yang ingin dicari di kolom pencarian, lalu klik "Hitung Kata".
4. **Simpan Hasil**: Klik "Simpan Kata" untuk menyimpan ke file.
5. **Hapus Teks**: Klik "Hapus" untuk mengosongkan teks dan hasil.
6. **Keluar dari Aplikasi**: Klik "Keluar" untuk menutup aplikasi.

## Teknologi yang Digunakan
- **Java SE (Swing GUI)**: Untuk antarmuka pengguna.
- **Java I/O**: Untuk menyimpan teks ke dalam file.

## Struktur Kode
- **`initComponents()`**: Inisialisasi semua komponen GUI.
- **`countText()`**: Menghitung jumlah kata, karakter, kalimat, paragraf, dan hasil pencarian kata.
- **`saveToFile()`**: Menyimpan teks dan hasil perhitungan ke file `.txt`.
- **`resetLabels()`**: Mengatur ulang label hasil saat teks dihapus.

## Pembuat
Muhammad Ikhya 2210010405

## Demo



