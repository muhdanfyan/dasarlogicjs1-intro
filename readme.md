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

## Tugas
---

### **1. Menyusun Puzzle: Nilai Sementara**
**Deskripsi:** Anda diminta untuk menukar nilai dua variabel tanpa langsung menggantinya.

**Soal:**
Diberikan dua variabel:
```javascript
let a = 10;
let b = 20;
```
Tukar nilai `a` dan `b` sehingga hasilnya menjadi:
```javascript
a = 20;
b = 10;
```

Namun, Anda hanya boleh menggunakan **variabel sementara** untuk membantu.

**Petunjuk:**
Gunakan pendekatan dengan **variabel ketiga** untuk menampung nilai sementara. Jangan menulis langsung `a = 20` atau `b = 10`.

---

### **2. Operasi Aritmatika**
**Deskripsi:** Hitung total harga belanjaan.

**Soal:**
Diberikan harga barang sebagai berikut:
```javascript
let hargaApel = 3000;
let hargaJeruk = 5000;
let hargaPisang = 2000;
```
Tulis sebuah program yang menghitung total harga untuk membeli:
- 3 Apel.
- 2 Jeruk.
- 5 Pisang.

Tampilkan total harga belanjaan dalam format:
```
Total belanja: Rp[Total Harga]
```

---

### **3. Logika Perbandingan**
**Deskripsi:** Membandingkan nilai variabel.

**Soal:**
Diberikan dua variabel:
```javascript
let nilaiA = 15;
let nilaiB = 10;
```
Tulis logika menggunakan **operator perbandingan** yang menghasilkan output berikut:
- Jika `nilaiA` lebih besar dari `nilaiB`, tampilkan: `"nilaiA lebih besar dari nilaiB."`
- Jika `nilaiA` sama dengan `nilaiB`, tampilkan: `"nilaiA sama dengan nilaiB."`
- Jika `nilaiA` lebih kecil dari `nilaiB`, tampilkan: `"nilaiA lebih kecil dari nilaiB."`

---

### **4. Konversi Tipe Data**
**Deskripsi:** Hitung total menggunakan input pengguna.

**Soal:**
Buat sebuah program yang meminta pengguna memasukkan harga barang dalam bentuk string, lalu konversikan menjadi number untuk menghitung total harga.

**Contoh Input:**
```javascript
let hargaBarang1 = "10000"; // string
let hargaBarang2 = "20000"; // string
```

**Tugas:**
1. Konversikan kedua variabel menjadi number.
2. Hitung total harga.
3. Tampilkan hasil dalam format:
```
Total harga barang: Rp[Total Harga]
```

---

### **5. Menghitung Umur**
**Deskripsi:** Gunakan operator matematika untuk menghitung umur seseorang.

**Soal:**
Diberikan tahun lahir seseorang:
```javascript
let tahunLahir = 2005;
```
Tulis sebuah program yang menghitung umur orang tersebut berdasarkan tahun saat ini (misalnya, `2024`) dan tampilkan dalam format:
```
Umur Anda adalah [umur] tahun.
```

**Petunjuk:** Gunakan operator pengurangan untuk menghitung umur.

---

### **6. Operasi String**
**Deskripsi:** Memahami operasi pada string.

**Soal:**
Diberikan nama lengkap:
```javascript
let namaLengkap = "Andi Wijaya";
```
Tulis program untuk:
1. Tampilkan jumlah karakter dalam nama lengkap.
2. Pisahkan nama depan dan nama belakang.
3. Ubah seluruh huruf menjadi huruf kecil.
4. Ubah seluruh huruf menjadi huruf kapital.

**Contoh Output:**
```
Jumlah karakter: 11
Nama depan: Andi
Nama belakang: Wijaya
Huruf kecil: andi wijaya
Huruf besar: ANDI WIJAYA
```

---

### **7. Kalkulator Sederhana**
**Deskripsi:** Gunakan operator aritmatika untuk membuat kalkulator.

**Soal:**
Buat program kalkulator sederhana yang:
1. Meminta dua angka dari pengguna.
2. Meminta jenis operasi yang ingin dilakukan: tambah (+), kurang (-), kali (*), atau bagi (/).
3. Menampilkan hasil perhitungan.

**Contoh Input:**
```
Masukkan angka pertama: 10
Masukkan angka kedua: 5
Masukkan operasi (+, -, *, /): +
```

**Contoh Output:**
```
Hasil: 15
```

---

### **8. Daftar Tugas dengan Array**
**Deskripsi:** Simpan dan manipulasi data dengan array.

**Soal:**
Buat program yang menyimpan daftar tugas harian dalam array:
1. Tambahkan tiga tugas ke dalam array.
2. Hapus tugas terakhir.
3. Tampilkan semua tugas yang tersisa.

**Contoh Output:**
```
Daftar tugas:
1. Bangun tidur
2. Sarapan
3. Belajar JavaScript
Tugas terakhir dihapus.
Daftar tugas terbaru:
1. Bangun tidur
2. Sarapan
```

---

### **9. Memilih Diskon**
**Deskripsi:** Gunakan variabel dan logika untuk menentukan diskon.

**Soal:**
Diberikan total belanja:
```javascript
let totalBelanja = 120000;
```
Gunakan logika berikut untuk menentukan diskon:
- Jika total belanja di atas Rp100.000, berikan diskon 20%.
- Jika total belanja di bawah atau sama dengan Rp100.000, berikan diskon 10%.

Hitung total yang harus dibayar setelah diskon dan tampilkan hasilnya dalam format:
```
Total belanja: Rp120000
Diskon: 20%
Total setelah diskon: Rp96000
```

---

### **10. Sistem Penilaian**
**Deskripsi:** Gunakan tipe data dan operator logika.

**Soal:**
Buat program yang menilai skor ujian berdasarkan nilai berikut:
```javascript
let skor = 85;
```
Gunakan logika berikut untuk menentukan grade:
- Skor >= 90: "A"
- Skor >= 80 dan < 90: "B"
- Skor >= 70 dan < 80: "C"
- Skor < 70: "D"

Tampilkan hasil dalam format:
```
Nilai Anda: 85
Grade: B
```

---
