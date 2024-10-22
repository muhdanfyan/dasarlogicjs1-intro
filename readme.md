# Pengenalan JavaScript, Variabel, dan Tipe Data

## 1. Apa itu JavaScript?
JavaScript adalah bahasa pemrograman yang digunakan untuk mengembangkan halaman web yang interaktif. Dengan JavaScript, kita bisa mengontrol elemen HTML, memanipulasi data, dan membuat aplikasi web yang lebih dinamis.

## 2. Pengenalan Variabel
Variabel adalah tempat untuk menyimpan data. Dalam JavaScript, kita bisa mendeklarasikan variabel menggunakan tiga kata kunci:
- **`var`**: Digunakan pada versi lama JavaScript, jarang digunakan pada versi modern.
- **`let`**: Digunakan untuk variabel yang nilainya dapat diubah di kemudian hari.
- **`const`**: Digunakan untuk variabel yang nilainya tidak bisa diubah setelah diinisialisasi.

Contoh penggunaan variabel:
```
let nama = 'Budi';
const umur = 25;
```

### 3. Tipe Data
JavaScript memiliki beberapa tipe data utama yang sering digunakan:

1. String: Untuk menyimpan teks, ditulis di dalam tanda kutip.

```
Salin kode
let pesan = "Selamat datang";
```

2. Number: Untuk menyimpan angka, baik bilangan bulat maupun desimal.

```
let umur = 30;
let harga = 99.99;
```
3. Boolean: Tipe data yang hanya memiliki dua nilai, yaitu true atau false.
```
let isStudent = true;
```

4. Null: Menyimpan nilai "kosong" atau tidak ada nilai sama sekali.

```
let kosong = null;
```
5. Undefined: Variabel yang telah dideklarasikan tetapi belum memiliki nilai.
```
let belumDiisi;
```

## Tugas: Menukar Isi Gelas
Sekarang saatnya untuk berlatih menggunakan variabel dalam sebuah program sederhana.

Deskripsi:
Kamu diminta membuat program yang memeragakan proses menukar isi dua gelas. Misalnya, gelas pertama berisi air putih, dan gelas kedua berisi jus jeruk. Tujuan dari program ini adalah untuk menukar isi kedua gelas tersebut.

Instruksi:
1. Buat dua variabel untuk merepresentasikan isi dari masing-masing gelas. Misalnya:
```
let gelasA = "Air Putih";
let gelasB = "Jus Jeruk";
```
2. Gunakan variabel ketiga untuk membantu proses penukaran.

3. Setelah proses penukaran selesai, tampilkan hasil akhir:
Sebelum menukar: Gelas A berisi Air Putih, Gelas B berisi Jus Jeruk.
Setelah menukar: Gelas A berisi Jus Jeruk, Gelas B berisi Air Putih.
Contoh Output:
```
Sebelum menukar:
Gelas A berisi: Air Putih
Gelas B berisi: Jus Jeruk

Setelah menukar:
Gelas A berisi: Jus Jeruk
Gelas B berisi: Air Putih
```