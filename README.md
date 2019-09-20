<h1>Install Flutter Di Mac Menggunakan Android Studio</h1>
Catatan untuk melakukan instal menggunakan android studio yang memiliki Ram tidak kecil dan storage lumayan besar.<br>
<h1>Persyaratan sistem</h1>
Untuk menginstal dan menjalankan Flutter, lingkungan pengembangan Anda harus memenuhi persyaratan minimum ini:<br>
  •	Sistem Operasi : macOS (64-bit)<br>
  •	Disk Space : 700 MB (tidak termasuk ruang disk untuk IDE / alat).<br>
  •	Alat : Flutter tergantung pada alat baris perintah ini yang tersedia di lingkungan Anda.<br>
  <p>
    &nbsp -	bash <br>
    &nbsp -	curl <br>
    &nbsp -	git 2.x <br>
    &nbsp -	mkdir <br>
    &nbsp -	rm <br>
    &nbsp -	unzip <br>
    &nbsp -	which <br>
  </p>
<h1>Langkah-langkah instalasi</h1><br>
•	Unduh Flutter SDK <br>
•	Unduh Xcode (IOS) dan Android Studio(Android)<br>
•	Download plugin dart & flutter<br>
•	Membuat aplikasi pertama kali<br>
 

<h1>Mulai instalasi</h1>
•	Download SDK flutter untuk macOS dengan klik disni.<br>
•	Setelah mendownload SDK tersebut silakan untuk di ekstrak.<br>
•	Lalu tambahkan PATH flutter dengan membuka terminal dengan langkah ini :<br>
&nbsp o	Silakan buka terminal lalu copy dan paste di terminal kalian :<br><br>

  <b>touch ~/.bash_profile; open ~/.bash_profile</b> <br><br>
 
o	Setelah terbuka .bash_profile  silakan kalian copy dan paste :<br><br>

  <b>export PATH="$PATH:/Users/nama_user/flutter/bin"</b><br><br>

ganti nama_user dengan user kalian, guna menambahkan path ini agar path tidak berulang-ulang dalam pemanggilan sehingga flutter dapat berjalan secara permanent <br><br>

•	Setelah selesai menambahkan PATH flutter, Jalankan perintah berikut untuk melihat apakah ada dependensi yang perlu Anda instal untuk menyelesaikan pengaturan (untuk output verbose, tambahkan -vflag):<br><br>

<b>$ flutter doctor</b><br><br>

•	Perintah ini memeriksa lingkungan Anda dan menampilkan laporan ke jendela terminal. Dart SDK dibundel dengan Flutter; tidak perlu menginstal Dart secara terpisah. Periksa output dengan cermat untuk perangkat lunak lain yang mungkin perlu Anda instal atau tugas lebih lanjut untuk dilakukan (ditunjukkan dalam teks tebal )<br><br>

<img src="Screen Shot 2019-09-20 at 08.05.02.png" style="height:400px;width:700px"><br><br>
    


•	Unduh dan instal Android Studio .<br>
•	Mulai Android Studio, dan buka 'Android Studio Setup Wizard'. Ini menginstal Android SDK terbaru, Android SDK Platform-Tools, dan Android SDK Build-Tools, yang diperlukan oleh Flutter saat mengembangkan untuk Android. <br>
•	Aktifkan opsi Pengembang dan debugging USB di perangkat Anda. Instruksi lengkap tersedia di dokumentasi Android .<br>
•	Khusus Windows: Instal Driver USB Google .<br><br>
•	Menggunakan kabel USB, colokkan ponsel Anda ke komputer Anda. <br>Jika diminta pada perangkat Anda, beri otorisasi komputer Anda untuk mengakses perangkat Anda. <br>
•	Di terminal, jalankan flutter devices perintah untuk memverifikasi bahwa Flutter mengenali perangkat Android Anda yang terhubung. Secara default, Flutter menggunakan versi Android SDK tempat adb alat Anda berada. Jika Anda ingin Flutter menggunakan instalasi Android SDK yang berbeda, Anda harus mengatur ANDROID_HOME environment variabel ke direktori instalasi itu.<br>



<h1>Mulai Aplikasi Pertama</h1><br>
•	Pertama-pertama silakan buka Android Studio :<br><br>

<img src="Android.png"><br><br>

 

•	Lalu Klik Start a new Flutter project.<br><br>

Note : Start a new Flutter project tidak ada silakan anda cek kembali plugin Flutter dan Dart sudah terinstal di android studio. Jika  belum terinstall silakan anda pilih Configure -> <b>Plugins</b> .<br>
•	Setelah itu akan tampil screenshot dibawah ini :<br><br>
 
<img src="Android2.png"><br><br>

Lalu Klik Flutter Application.<br>
•	Setelah itu silakan klik Next : <br><br>
 <img src="Android3.png"><br><br>

Disini kalian akan diminta untuk menamai Project kalian, Flutter SDK Path, dan Project Location.<br>

Flutter SDK Path adalah file zip yang telah kalian ekstrak dan masukan lokasi dimana folder tersebut berada.<br>

•	Setelah kalian selesai silakan klik tombol Next kembali :<br><br>
 
  <img src="Android4.png"><br><br>

Disini kalian akan diminta untuk memasukkan Company domain serta Platform yang Support untuk Android dan IOS.
•	Lalu setelah klik Finisih maka akan tampil :<br><br>

 <img src="Android5.png"><br><br>
 
•	Silakan anda copy source code dibawah ini dan copy paste di folder lib -> main.dart :<br><br>
  
  <img src="Screen Shot 2019-09-20 at 08.05.53.png"><br><br>

•	Setelah selesai lalu silakan klik tombol hijau yang berada di pojok kanan atas :<br><br>

<img src="Android6.png"><br><br>

 
Disini saya menggunakan emulator dari xcode yaitu iPhone Xr , kalian dapat mengganti dengan emulator android yang kalian sukai :<br><br>
 
 <img src="Android7.png"><br><br>


•	Jika sudah selesai mari kita lihat hasil dari code diatas pada emulator : <br><br>
 
 <img src="Android8.png"><br><br>
 

Maka akan tertampil text Hello World.<br><br>
 

Info Lebih Lengkap<br>
•	Pelajaran : Pemprograman Mobile<br>
•	Dosen : Ary Budi Warsito<br>
•	Universitas : Matana University<br>
•	Penulis : Anton Kurniawan<br>
•	NIM : 20175520005<br>


