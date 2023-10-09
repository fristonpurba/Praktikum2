# Praktikum 2 - pemograman Web
### Friston Purba
### 312210595
### TI.22.A1

## Langhak-langka praktikum CSS dasar
pertama buka `VS Code` maka tampilannya awal akan seperti ini.
![gamabr-1][def-1]

[def-1]: /image/ss1.jpg

Selanjutnya membuat dokumen `HTML`, pada bagaian title uabah menjadi `CSS Dasar` agar tampilan judul halaman akan berubah menjadi `CSS Dasar`.
![gambar-2][def-2]

[def-2]: /image/ss2.jpg

Lalu buat Kode didalam tag `body` seperti berikut.
![gambar-3][def-3]

[def-3]: /image/ss3.jpg

Selanjutnya buka pada browser untuk melihat hasilnya.
![gambar-4][def-4]

[def-4]: /image/ss4.jpg

Kemudian mendeklarasikan CSS Internal, tambahkan deklarasi CSS internal pada bagian `head` lalu tambahkan `style` untuk membuat CSS internal.
![gambar-5][def-5]

[def-5]: /image/ss5.jpg

Lalu save perubahan tadi terus kembali ke browser dan refresh untuk melihat hasilnya.
![gambar-6][def-6]

[def-6]: /image/ss6.jpg

Selanjutnya menambahkan `Inline CSS`, untuk melakukannya tambahkan deklarasi inline CSS pada tag `<p>` seperti ini.
![gambar-7][def-7]

[def-7]: /image/ss7.jpg

lalu save perubahan lagi terus kembali ke browser refresh dan lihat hasilnya.
![gambar-8][def-8]

[def-8]: /image/ss8.jpg

Selanjutnya membuat `CSS Eksternal`, buat file baru terlebih dahulu dengan nama `style_eksternal.css` lalu buat deklarasi CSS seperti berikut.
![gambar-9][def-9]

[def-9]: /image/ss9.jpg

Tambahkan tag `<link>` pada bagian `head` untuk menghubungkan `style_eksternal.css` yang sudah dibuat tadi.
![gambar-10][def-10]

[def-10]: /image/ss14.jpg

Lalu save kembali ke browser refresh maka hasilnya seperti ini.
![gambar-11][def-11]

[def-11]: /image/ss10.jpg

Selanjutnya menambahkan `CSS Selector` menggunakan `ID` dan `class selector` pada file `style_eksternal.css`
![gambar-12][def-12]

[def-12]: /image/ss11.jpg

Lalu save lagi dan kembali ke browser dan refresh.
![gambar-13][def-13]

[def-13]: /image/ss12.jpg

## Pertanyaan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
```
Yang saya lakukan disini menambahkan hayperlink pada dokumen HTML saya lalu menambahkan juga kode pada style CSS maka hasilnya seprti ini
```
![gambar-14][def-14]

[def-14]: /image/ss13.jpg

2. Apa perbedaan pendeklarasian CSS elemen `h1 {...}` dengan `#intro h1 {...}`? berikan penjelasannya!
```
Pada pendeklarasian CSS elemen h1 maka yang akan berubah adalah seluruh tag h1 pada halam web berdeda dengan #intro h1 atau tag yang ada id maka itu saja yang akan berubah pada tampilan web.
```

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
```
Jika ada ketiga deklarasi css secara internal, css eksternal, dan inline css maka yang akan di tampilkan pada browser adalah deklarasi css inline karena memiliki prioritas tertinggi dalam aturan css cascade
```
contohnya : 
![gambar-15][def-15]

[def-15]: /image/ss15.jpg

4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! `<p id="paragraf-1" class="text-paragraf">`
```
Ketika dalam satu tag html terdapat id dan class didalamnya maka yang akan di tampilkan oleh browser adalah deklarasi css dengan id karena id menjadi prioritas tertinggi dalam aturan css cascade sedangkan class menjadi peioritas kedua setelah id
```
contoh penulisan pada tag p di halaman HTML :
![gambar-16][def-16]

[def-16]: /image/ss16.jpg

contoh penulisan CSS iinternal atau eksternal
![gambar-17][def-17]

[def-17]: /image/ss17.jpg