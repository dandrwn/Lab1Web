# Tugas pertemuan ke 1
Repository ini digunakan untuk memenuhi Tugas Lab1Web

Nama    : Dani Darmawan
NIM     : 312010154
KELAS   : TI.20.B1 
## 1. Membuat Paragraf
![hasil1.1](gambar_latihan/1.1.jpg)
### Hasil
![Hasil1](gambar_latihan/1.jpg)

### Mengatur atribut Paragraph
**Penggunaan align Justify dan center**

![hasil1.2](gambar_latihan/1.1.2.jpg)

**Hasil**

![hasil2](gambar_latihan/1.1.1.jpg)

**Penjelasan**
**Paragraf Ke 1 Menggunakan "align="justify"**
pada screenshoot yang saya lampirkan memang tidak terlihat perbedaanya dengan
sebeleumnya karna kegunaan "align="justify" sebernya hanya pengatur agar teks dapat rata kanan dan juga kiri
 
 **Paragraf Ke 2 Menggunakan "align="center"**
 sedangkan center terlihat jelas terdapat perubahan yang dimana paragraf berubah posisi  menjadi di tengah

**Penggunaan align left dan right**

![hasil1.3](gambar_latihan/1.2.2.jpg)

**Hasil**

![hasil3](gambar_latihan/1.2.1.jpg)

**Penjelasan**
**Paragraf Ke 1 Menggunakan "align="left"**
pada screenshoot yang saya lampirkan memang tidak terlihat perbedaanya dengan
sebeleumnya karna kegunaan "align="left" sebernya hanya pengatur agar teks berada di Kiri
 **Paragraf Ke 2 Menggunakan "align="right"**
 sedangkan center terlihat jelas terdapat perubahan yang dimana paragraf berubah posisi menjadi di bagian kanan

 ## 2. Menambahkan Judul
![hasil1.4](gambar_latihan/2.1.jpg)

## Hasil
![Hasil4](gambar_latihan/2.jpg)

**Penjelasan**
Dalam Menambahkan Judul kita menggunakan Heading ``` html <h1></h1> <h2></h2> ```
Pembeda ```html <h1>``` dan ```hrml<h2>`` hanya dari ukurannya saja terlihat jelas dari Screenshoot yang telah saya tampilkan.

## 3. Memformat Teks
![hasil1.5](gambar_latihan/3.1.jpg)

## Hasil
![hasil5](gambar_latihan/3.jpg)

**Penjelasan**
``` html <i>teks</i> ``` Memiringkan teks (italic) <br>
``` html <b>teks</b> ``` Menebalkan teks (bold)<br>
``` html <mark></mark> ``` Memberi penanda seperti menggunakan stabilo<br>
``` html <u></u> ``` Memberi garis bawah (underline)<br>
``` html <del><del> ``` Mencoret teks<br>

## 4. Menyisipkan Gambar
![hasil1.6](gambar_latihan/4.jpg)

## Hasil
![hasil6](gambar_latihan/4.1.jpg)

**Penjelasan**
``` html <img src="D:\Tugas\WEB\tugas 1\gambar bahan\1.png" width="200" height="180" tittle="Logo Universitas Pelita Bangsa"/> ``` <br>
``` html src="D:\Tugas\WEB\tugas 1\gambar bahan\1.png"``` memasukan lokasi foto yang  ingin di tampilkan<br>
``` html width="200" height="180" ``` Mengatur ukuran pada foto<br>
``` html tittle="Logo Universitas Pelita Bangsa"``` Memberi nama pada foto <br>


## 5. Menambahkan Hyperlink
![hasil7](gambar_latihan/5.jpg)

## Hasil
![hasil7.1](gambar_latihan/5.1.jpg)

**Penjelasan**
``` html  <nav>
            <a href="lab1_tag_Halaman2.html">Halaman 2</a>
            <a href="http://www.google.com">Google search</a>
        </nav> 
``` 
``` html <a href="lab1_tag_Halaman2.html"> ``` alamat yang di tuju <br>
    ``` html Halaman 2</a> ``` teks yang akan di tampilkan <br>
    jadinya akan Muncul Halaman 2 dan saat kita klik akan berpindah ke halaman lab1_tag_Halaman2<br>
    Contohnya seperti ini
    ![hasil7.2](gambar_latihan/5.jpg)

# Jawab Pertanyaan
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah 
error ketika terjadi kesalahan penulisan tag? *Tidak Ada*
2. Apa perbedaan dari tag ```html<p>``` dengan tag ```html<br>```, berikan penjelasannya!<br>
 ```html<p>```*per paragraf* <br>
 ```html<br>``` *Pindah baris atau Enter*<br>
3. Apa perbedaan atribut title dan alt pada tag ```html<img>```, berikan penjelasannya!<br>
*tittle* Hanya Memberi Judul pada Gambar<br>
*alt* Judul akan tampil jika gambar gagal dimuat<br>

4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar<br> 
proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!<br>
*Tergantung bentuk gambarnya jika persegi bisa sama jika selain persegi maka harus berbeda dan di sesuaikan* <br>
*agar tetap proporsional* 
5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?<br>
``` html _self``` : Membuka halaman website di tab ini.
``` html _blank``` :Membuka halaman website di tab baru.
``` html _parent``` : Membuka halaman website pada parent frame.
``` html _top``` : Membuka halaman website dan membatalkan semua frame.