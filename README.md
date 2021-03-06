## Belajar HTML

**Nama     : Fery Affandi** <br>
**Kelas    : TI.20.A.1**  <br>
**NIM      : 312010018** <br>

## Tugas

Mendapatkan tugas dari dosen Pemrograman Web pada pertemuan ke-2 ,yaitu:

![Tugas](foto/tugas_kuliah.png)

## Langkah-langkah membuat web sederhana menggunakan HTML melalui vscode: <br>

**Buka Vscode dan akan muncul tampilan awal seperti dibawah ini** 

![tampilan Vscode](foto/tampilan_VScode.png)

**Kemudian buat file dengan format lab1_tag_dasar.html** 

![format html](foto/formal_html.png)

**Kemudian buka formatnya di Vscode**

![html di vscode](foto/tampilan_html_vscode.png)

**Lalu menulis kode awal dengan menuliskan html:5 dan hasilnya seperti dibawah ini**

![code awal](foto/code_awal.png)

kemudian mmengubah nama web menjadi Belajar HTML

![belajar HTML](foto/ubah_title.png)

dan tampilan web akan seperti ini

![tampilan web](foto/tampilan_web.png)

## 1. Lalu membuat Paragraf

selanjutnya membuat paragraf sederhana seperti dibawah ini

![paragraf](foto/paragraf.png)

lalu disimpan perubahannya dan lakukan refresh pada web html tersebuat dan terajadi perubahan seperti dibawah ini

![hasil paragraf](foto/hasil_paragraf.png)

kemudian atur paragraf seperti dibawah ini dan lihat lah perubahannya.

![ubah paragraf](foto/ubah_paragraf.png)

kemudian hasil formatnya akan seperti ini.

![hasil ubah](foto/hasil_ubah_paragraf.png)

Simpan kembali dan amatilah perubahannya dengan 
melakukan refresh pada web browser.
Selanjutnya silahkan  diubah-ubah atributnya (<i>align => justify, left, right, dan center</i>) untuk melihat
perbedaan lainnya.

## 2. Menambahkan Judul

Seperti sudah dijelaskan pada materi bahwa judul (h) memiliki 6 level yaitu mulai h1 sampai h6.
Kemudian tambahkan judul h1 <b>sebelum</b> paragraf pertama dan tambahkan sub judul h2 <strong>sebelum</strong>
paragraf kedua.

![judul](foto/judul.png)

Simpan perubahan tersebut dan lihat dengan melakukan refresh pada browser.

![hasil judul](foto/hasil_judul.png)

## 3. Memformat Teks

Kita akan mencoba memformatan teks yang ada pada paragraf yang sudah ada sebelumnya, mengacu kepada
penjelasan materi pemformatan teks, sehingga tampilan codingannya seperti ini.

![coding format teks](foto/codingan_format_teks.png)

setelah membuat codingan seperti diatas, kalian bisa simpan kemudian lihatlah perubahannya di browser.

![hasil format](foto/hasil_format_teks.png)

## 4. Menyisipkan gambar

Untuk menyisipkan gmbar, siapkan gambar yang akan disisipkan pada halaman web, kemudian
simpan file gambar tersebut satu folder dengan file dokumen html.

![gambar](foto/gambar.png)

Kemudian tambahkan tag img setelah paragraf yang kedua, dengan menambahkan heading 3
sebelumnya.

![tag gambar](foto/tag_gambar.png)

Simpan perubahannya, dan lihar kembali browser.

![tampilan gambar](foto/tampilan_logo.png)

Gambar akan ditampilkan apa adanya sesuai dengan ukuran aslinya. Untuk mengatur ukuran
gambar, dapat digunakan atribut witdh dan height dengan nilai integer yang disesuaikan.

![gambar width](foto/gambar_width.png)

## 5. Menambahkan Hyperlink

Tambahkan hyperlink pada dokumen sebelum heading 1 seperti berikut.

![navigasi](foto/navigasi.png)

Buat satu file lagi dengan nama lab1_halaman2.html kemudian isi dokumen tersebut dengan tag
html dasar dan dengan isi bebas, boleh mengcopy dari halaman sebelumnya.

![hasil navigasi](foto/hasil_navigasi.png)

## Jawab Pertanyaan Berikut 

1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah
error ketika terjadi kesalahan penulisan tag? <br>
2. Apa perbedaan dari tag `<p>` dengan tag `<br>`, berikan penjelasannya! <br>
3. Apa perbedaan atribut title dan alt pada tag `<img>`, berikan penjelasannya! <br>
4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar
proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya! <br>
5. Pada link tambahkan atribut target dengan nilai atribut bervariasi <i><b>(_blank, _self, _top,
_parent)</i></b>, apa yang terjadi pada masing-masing nilai antribut tersebut? <br>

## Jawaban Pertanyaan

1. Saya akan melakukan perubahan pada tag HTML,
        gambar yang dibawah ini merupakan <b>syntax HTML</b>di aplikasi VScode sebelum saya merubahnya. <br>
    
    ![jawaban 1](foto/pertanyaan_ke1.png)

    Lalu ketika saya hilangkan akhiran pada Tag `</h1>` menjadi `<h1>`, maka yang akan terjadi adalah seluruh elemen dibawah tag tersebut akan berubah mengikuti Tag `<h1>`, dikarenakan tidak ada akhiran/penutup Tag tersebut.

2. Tag `<p>` berfungsi untuk memberi perintah <b>paragraf</b>pada halaman HTML,
sedangkan Tag `<br>` berfungsi untuk memberikan perintah <b>breakline</b> atau <b>baris baru, contohnya:</b>

![jawaban 2](foto/pertanyaan_ke2.png)

3. `title` berfungsi untuk menunjukan judul pada gambar, lalu `alt`
berfungsi untuk menunjukan sebuah alternatif teks <i>(teks pengganti)</i> 
yang akan muncul apabila gambar tidak dapat ditampilkan.<br>

![gambar alt title](foto/gambar_title_alt.png)

dan ini codingannya <br>

![coding alt title](foto/codingan_title_alt.png)

pada codingan <b>`alt`</b> sengaja ditulis nama file tidak lengkap, dikarenakan hanya untuk menampilkan fungsi dari alt <br>

4. Menurut saya kedua properti ini sangat penting dan merupakan
bagian yang tidak terpisahkan dari sebuah website karena masing masing
Tag atau Element pada sebuah HTML perlu memiliki ukuran yang ideal,
sebab itu berpengaruh dalam pengaturan tata letak dan tampilan
sebuah website,
<br>
kecuali pada kondisi tertentu seperti gambar sudah memiliki 
ukuran yang pas tau proporsional cukup mengatur widthnya saja <br>

![gambar nomor 4](foto/gambar_nomor4.png)

dan codingannya seperti ini.
![coding nomor 4](foto/codingan_nomer4.png)

5. `_blank` digunakan untuk membuka link tab baru. <br>
`_self` digunakan untuk membuka link di frame link itu berada.<br>
`_top` digunakan untuk membuka lik di frame paling atas(paling luar).
contohnya jika di website(1) dan didalamnya ada website(2) lalu di wesite (2) 
didalamnya ada website(3) lalu di website(3) ini ada link, 
dan kita klik maka akan terbuka wesite(1).<br>
`_parent` digunakan untuk membuka link di frame yang satu tingkat 
diatas frame link tersebut berada. Contohnya jika di website(1)
didalamnya  ada website(2) lalu di website(2) ini ada link dan 
kita klik, maka yang akan terbuka adalah website(1).<br> 


