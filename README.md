# AutoBerkas Skripsi ILKOM

Sebuah *tool* berbasis Excel VBA untuk membantu mahasiswa dalam proses pemberkasan skripsi. *Tool* ini mengotomatiskan pengisian data (seperti nama, NIM, judul, dosen) ke dalam berbagai templat dokumen Word (.docx).

![Platform](https://img.shields.io/badge/Platform-Windows%20Only-blue)
![Requires](https://img.shields.io/badge/Requires-MS%20Office-orange)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## Fitur Utama

* **Generate Dokumen**: Mengisi data dari satu file Excel ke banyak template `.docx` sekaligus.
* **Batch Processing**: Dapat memproses banyak file template dalam satu kali klik.
* **Dua Pilihan Output**: Menghasilkan file dalam format `.docx` atau langsung mengonversinya ke `.pdf`.
* **Input Terkendali**: Input data dosen sudah menggunakan *drop-down list* untuk menghindari salah ketik.

## Kebutuhan Sistem

* Sistem Operasi: **Windows**
* Perangkat Lunak: **Microsoft Office** (Excel & Word)

## Panduan Penggunaan

1.  **Buka File Excel**: Buka file utama `(Otomatisasi.xlsm)`.
2.  **Input Data**: Buka *sheet* `"Input"` dan isi atau ganti data sesuai dengan data kalian.
3.  **Mulai Generate**: Klik tombol `"Generate WORD"` atau `"Generate PDF"` pada *sheet* `Input`.
4.  **Pilih Template**: Arahkan ke *folder* tempat kalian menyimpan semua *template* `.docx` yang ingin diproses.
5.  **Pilih File**: Pilih satu atau beberapa file `.docx` sekaligus. (Tahan tombol `Ctrl` sambil mengklik untuk memilih banyak file).
6.  **Proses**: Klik `"OK"` dan tunggu beberapa saat hingga muncul notifikasi `"BERHASIL!"`.
7.  **Selesai**: Cek file baru kalian di dalam *folder* `"Hasil"` (pastikan ada folder HASIL).

## Catatan Penting

* ⚠️ **Just to be safe...**: Sangat disarankan untuk menutup semua aplikasi Microsoft Word yang sedang terbuka sebelum menjalankan proses *generate* untuk menghindari konflik.
* ⏳ **Waktu Proses**: Proses *generate* mungkin akan memakan waktu sedikit lebih lama jika kalian memilih banyak file sekaligus. Harap bersabar.
* 🚫 **Kompatibilitas**: *Tool* ini **hanya berfungsi** di lingkungan Windows dengan Microsoft Office yang terinstal.
* 🔧 **As-Is**: Tool ini bersifat "as-is" (apa adanya) dan tidak ada jaminan tanpa error. *May or may not work* good luck might save you lot of time or not.
* ✍️ **Edit Manual**: Terkadang, kalian mungkin masih perlu melakukan penyesuaian atau edit manual pada file hasil generate (misalnya merapikan spasi, paragraf, *yada yada lainnya*).

## Tentang Proyek Ini

Proyek mini ini dibuat untuk membantu mempercepat dan mempermudah proses pemberkasan dokumen skripsi. GLHF!

Terinspirasi dari "[Goes to S.Kom Era](https://meftahmafazy.notion.site/Goes-to-S-Kom-Era-12f7895c4d33438dac0fa5422d3c0762)" oleh Bang Meftah Ilkom'19 untuk menaikkan Kualitas Hidup (QOL) pengerjaan skripsi.
