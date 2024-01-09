# Android Studio : Create Virtual Device

1. Silahkan membuka kembali proyek Android Studio yang pernah kamu buat sebelumnya.

2. Setelah proyek terbuka selanjutnya pada toolbar di bagian sebelah kanan pilih ikon `Device Manager`.

   <img style="display: block; margin: 0;"  src="img/create-virtual-device/1.jpg" alt="" />

3. Akan tampil jendela `Device Manager` selanjutnya pilih ikon `+` untuk membuat Virtual Device baru.

	<img style="display: block; margin: 0;"  src="img/create-virtual-device/2.jpg" alt="" />
	
4. Akan tampil jendela `Select Hardware` silahkan cari dan pilih pada `Pixel 7 Pro`. Setelah itu pilih tombol `Next`.

	<img style="display: block; margin: 0;"  src="img/create-virtual-device/3.jpg" alt="" />
	
5. Akan tampil jendela `Select a system image`. Apabila tampilan versi Android memiliki warna yang redup itu berarti versi Android belum pernah diinstal sebelumnya.  Dalam kasus ini perhatikan border merah pada versi Android 9 (Pie) yang memiliki warna redup.

	<img style="display: block; margin: 0;"  src="img/create-virtual-device/4.jpg" alt="" />
	
6. Dalam kasus ini kita akan membuat Virtual Device dengan versi Android 9 (Pie), tetapi versi Android ini belum terinstal. Oleh karena itu untuk menginstal versi Android ini silahkan pilih ikon `Download` yang berada disebelah kanan nama versi Android.

	<img style="display: block; margin: 0;"  src="img/create-virtual-device/5.jpg" alt="" />
	
7. Akan tampil jendela untuk melakukan unduh versi Android sesuai dengan yang dipilih. Tunggu sampai proses instalasi selesai.

	<img style="display: block; margin: 0;"  src="img/create-virtual-device/6.jpg" alt="" />
	
8. Setelah proses instalasi selesai selanjutnya pilih tombol `Finish`.

	<img style="display: block; margin: 0;"  src="img/create-virtual-device/7.jpg" alt="" />

9. Sekarang versi Android 9 (Pie) memiliki warna yang cerah itu berarti versi Android ini telah berhasil terinstall. Selanjutnya pilih pada versi Android tersebut kemudian pilih tombol `Next`.

	<img style="display: block; margin: 0;"  src="img/create-virtual-device/8.jpg" alt="" />
	
10. Silahkan melakukan pengaturan Android Virtual Device (AVD) sesuai dengan kebutuhan kamu. Untuk mengatur penggunaan jumlah ram dan storage yang digunakan silahkan memilih tombol `Show Advanced Settings` dan lakukan pengaturan sesuai kebutuhan. Setelah selesai melakukan pengaturan silahkan memilih tombol `Finish`.

	<img style="display: block; margin: 0;"  src="img/create-virtual-device/9.jpg" alt="" />
	
11. Sekarang pada tampilan Device Manager sudah terdapat Device baru dengan nama `Pixel 7 Pro API 28`. Selamat kamu telah berhasil membuat Virtual Device baru pada Android Studio.

	<img style="display: block; margin: 0;"  src="img/create-virtual-device/10.jpg" alt="" />
	
12. Untuk menjalankan Virtual Device silahkan memilih ikon `Play` pada AVD yang ingin dijalankan.

	<img style="display: block; margin: 0;"  src="img/create-virtual-device/11.jpg" alt="" />
	
13. Tunggu beberapa saat sehingga tampilan Running Device terbuka dan menampilkan AVD sesuai dengan yang dijalankan sebelumnya.

	<img style="display: block; margin: 0;"  src="img/create-virtual-device/12.jpg" alt="" />
	
14. Pada proyek Android Studio, AVD akan terdeteksi dan dapat dipilih sebagai Device untuk menjalankan aplikasi yang sedang dikembangkan. Silahkan memilih AVD yang telah kamu jalankan sebelumnya. Setelah itu pilih tombol `Run`.

	<img style="display: block; margin: 0;"  src="img/create-virtual-device/13.jpg" alt="" />
	
15. Ikon `Run` yang dipilih sebelumnya akan berubah menjadi `circle loading bar` dan kamu dapat melihat indikator proses build aplikasi pada bagian bawah di proyek Android Studio.

	<img style="display: block; margin: 0;"  src="img/create-virtual-device/14.jpg" alt="" />
	
16. Jika proses build aplikasi telah selesai maka akan terdapat toast message, seperti berikut:

	<img style="display: block; margin: 0;"  src="img/create-virtual-device/15.jpg" alt="" />
	
17. Tampilan Running Device akan terbuka dan pada AVD tempat aplikasi dijalankan akan menampilkan text `Hello World` ini berarti Android Studio dan AVD berhasil terinstall dengan baik. Selamat telah berhasil membuat dan menjalankan proyek Android pada AVD.

	<img style="display: block; margin: 0;"  src="img/create-virtual-device/16.jpg" alt="" />