# Tutorial Intouch Wonderware

## Membuat Versi Aplikasi

### Penjelasan
Cara membuat versi pada project intouch, ini berguna untuk mengetahui perbedaan antar project lama dan baru. Biasanya ketika kita melakukkan _Update HMI_. 

> Perlu diketahui bahwa setiap proses simpan pada semua windows/screen, versi akan menambah +1

### Buka WindowMaker

1. Buat atau siapkan text dan diisi nilai '#####'
2. Double Click atau Klik Kanan → Animation Links.. pada text tersebut
3. Pilih bagian Value Display → Analog 
4. Isi nilai Expression dengan  `$ApplicationVersion`
5. Selesai

> Nilai Expression (4.) merupakan fungsi bawaan / built-in inTouch yang dapat kita gunakan dalam pengecekan versi pada setiap perubahan
