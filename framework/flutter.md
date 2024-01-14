# Flutter

1. Silahkan melakukan instalasi program 7-Zip terlebih dahulu dengan mengikuti tahapan berikut ini: [Instalasi 7-Zip](../archive/1.7zip.md)

2. Silahkan unduh Flutter, melalui link berikut: [https://docs.flutter.dev/get-started/install/windows/mobile?tab=download](https://docs.flutter.dev/get-started/install/windows/mobile?tab=download)

3. Setelah berada di halaman unduh Flutter, pada bagian `Download then install Flutter` pilih pada tombol `flutter_windows_3.16.7-stable.zip`. Sesuaikan dengan versi yang tersedia. Pada saat modul ini dibuat versi yang tersedia adalah `3.16.7`.

   <img style="display: block;" src="img/flutter/1.jpg" alt="" />

4. Setelah selesai mengunduh, silahkan memindahkan file arsip flutter ke lokasi yang aman. Dalam kasus ini lokasi yang dipilih adalah `C:\framework\`.

   <img style="display: block; margin: 0;" src="img/flutter/2.jpg" alt="" />

5. Klik kanan pada file arsip flutter. Akan tampil context menu, silahkan pilih menu `7-Zip` selanjutnya pilih menu `Extract Here`. 

   <img style="display: block; margin: 0;" src="img/flutter/3.jpg" alt="" />

6. Tunggu sampai proses ekstraksi flutter selesai.

   <img style="display: block; margin: 0;" src="img/flutter/4.jpg" alt="" />

7. Setelah proses ekstraksi selesai akan terdapat folder baru bernama `flutter`.

   <img style="display: block; margin: 0;" src="img/flutter/5.jpg" alt="" />

8. Silahkan tambahkan lokasi flutter tersebut ke Windows path environment. Program flutter berada di lokasi `C:\framework\flutter\bin`. Lihat cara menambahkan lokasi program ke [Windows Path Environment](../tutorial/windows/path-environment.md)

   <img style="display: block; margin: 0;" src="img/flutter/6.jpg" alt="" />

9. Buka Windows Terminal. Selanjutnya tuliskan perintah `flutter doctor` untuk memeriksa konfigurasi sistem Anda dan memastikan bahwa Anda memiliki semua dependensi yang diperlukan untuk mengembangkan aplikasi dengan Flutter. Pastikan tidak terdapat issues saat menjalankan perintah tersebut.

   <img style="display: block; margin: 0;" src="img/flutter/7.jpg" alt="" />

10. Masih di Windows Terminal silahkan tuliskan perintah `flutter --version` dan `dart --version`. Jika berhasil maka akan tampil versi flutter dan dart yang digunakan. Selamat kamu telah berhasil melakukan instalasi Flutter.

   <img style="display: block; margin: 0;" src="img/flutter/8.jpg" alt="" />
