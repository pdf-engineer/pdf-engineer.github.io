# PDF Engineer

**Editor PDF yang berjalan sepenuhnya di browser. File Anda tidak pernah diunggah ke server mana pun.**

🔗 **Buka aplikasinya:** https://pdf-engineer.github.io/

## Fitur

| Menu | Kegunaan |
|---|---|
| **Edit & tanda tangan** | Ubah, geser, atau hapus tulisan asli PDF; pasang tanda tangan (digambar atau dari foto, latar dihapus otomatis); tambah teks, centang, gambar, Shapes (kotak, elips, garis, panah, bisa diberi tulisan dan diputar); kotak penutup; tandai kata (stabilo, garis bawah, coret); catatan; pena |
| **Atur halaman** | Putar, hapus, dan ubah urutan halaman |
| **Gabung PDF** | Satukan beberapa file dan atur urutannya per dokumen atau per halaman |
| **Pisah PDF** | Ambil halaman tertentu, pecah tiap halaman, tiap beberapa halaman, atau rentang sendiri |
| **Kompres PDF** | Perkecil ukuran file (paling efektif untuk PDF hasil scan atau yang banyak gambar) |
| **PDF ke Word** | Ubah PDF menjadi dokumen Word (.docx) yang bisa diedit |
| **JPG ke PDF** | Jadikan foto atau gambar sebagai halaman PDF |

## Privasi: kenapa aman?

Di layanan PDF online pada umumnya, file harus **diunggah ke server** mereka dulu sebelum diproses.
PDF Engineer bekerja berbeda:

- Seluruh proses (membuka, mengedit, mengompres, menyimpan) berjalan **di browser perangkat Anda sendiri**.
- Aplikasi **tidak mengirim data** ke internet dan **tidak menyimpan apa pun** di browser (tanpa cookie, tanpa pelacak, tanpa statistik pengunjung).
- Semua pustaka yang dipakai sudah tertanam di dalam `index.html`, jadi tidak ada kode yang diambil dari server lain saat aplikasi dibuka.

**Buktikan sendiri:** buka aplikasinya, tunggu sampai tampil, lalu **matikan Wi-Fi**. Semua fitur tetap berjalan normal.
Atau tekan **F12 → tab Network** di Chrome/Edge: tidak ada permintaan baru saat Anda memproses PDF.

> Catatan: seperti semua situs, GitHub mencatat *kunjungan* ke halaman ini (alamat IP dan jenis browser).
> Isi dokumen tidak ikut tercatat karena dokumen tidak pernah dikirim.

## Tips & batasan

- Paling nyaman dipakai di **Chrome atau Edge di laptop**.
- **Edit teks** dan **Tandai** hanya berlaku untuk PDF asli, bukan hasil scan (hasil scan berupa gambar, tidak berisi teks).
- **PDF ke Word**: halaman hasil scan masuk sebagai gambar; tata letak yang rumit mungkin perlu dirapikan sedikit.
- **Kotak penutup** hanya menutupi tampilan; tulisan di baliknya masih ada di file. Jangan dipakai untuk menyembunyikan data rahasia.
- Kalau setelah pembaruan tampilan masih versi lama, tekan **Ctrl+F5**.

## Isi repositori

| File | Keterangan |
|---|---|
| `index.html` | Seluruh aplikasi dalam satu file (kode aplikasi + pustaka + huruf + logo) |
| `THIRD-PARTY-NOTICES.md` | Daftar pustaka open source yang dipakai beserta lisensinya |

## Saran & masukan

Punya ide fitur atau menemukan masalah? Sampaikan lewat tab **Issues** di repositori ini, atau hubungi pembuatnya langsung.
