# Pemrograman Berbasis Mobile 

## Memuat dan Menampilkan Gambar dari Internet 

## TEORI DASAR  
<b>Coil</b> adalah library pengolahan gambar untuk Android yang dikembangkan oleh Kotlin. Coil merupakan singkatan dari <b>Co</b>routine <b>I</b>mage <b>L</b>oader. Library ini fokus pada kecepatan, efisiensi, dan kemudahan penggunaan, menjadikannya alternatif populer untuk library pengolahan gambar lainnya seperti Glide dan Picasso.  

### Fitur Utama Coil:  
1. <b>Modern dan Ringan</b>: Coil dibangun dengan memanfaatkan coroutine Kotlin dan memanfaatkan fitur-fitur modern Android, menghasilkan library yang ringan dan efisien.  
2. <b>Fast</b>: Coil mengoptimalkan proses pengolahan gambar, termasuk caching dan decoding, untuk memberikan waktu pemuatan gambar yang cepat.  
3. <b>Mudah Digunakan</b>: Coil memiliki API yang sederhana dan intuitif, sehingga mudah diintegrasikan ke dalam aplikasi Android.  
4. <b>Fleksibel</b>: Coil mendukung berbagai sumber gambar, termasuk URL, file lokal, resource drawable, dan lainnya.  
5. <b>Composable</b>: Coil menyediakan dukungan untuk Jetpack Compose melalui library coilcompose.  

### Cara Menggunakan Coil  
Tambahkan dependency:  
```
implementation("io.coil-kt.coil3:coil-compose:3.0.4")  
implementation("io.coil-kt.coil3:coil-network-okhttp:3.0.4")  
```   
  
Muat gambar:  
```
AsyncImage(
	model = "https://example.com/image.jpg", 
	contentDescription = "My Image"
)  
```  

### Contoh Proyek  
Ini adalah proyek memuat dan menampilkan gambar dari internet menggunakan Retrofit dan Coil dengan Jetpack Compose.  

URL yang diakses: https://android-kotlin-fun-mars-server.appspot.com/photos  
<br>
<b>Dikerjakan oleh:</b>  
Nama  : Fransiskus A Tekege  
NIM   : 215410072  
Kelas : IF-2  

Prodi Teknologi Informasi  
Fakultas Informatika  
Universitas Teknologi Digital Indonesia  
2024 / 2025  
<br>
<img src="https://github.com/Fransis96/IBD-CLOUD/blob/master/utdi321.jpg" width="300" height="80">  
