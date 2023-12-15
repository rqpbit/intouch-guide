# Tutorial Intouch Wonderware

## Membuat Tanggal dan Jam

### Penjelasan
Cara membuat waktu secara realtime seperti menampilkan tanggal dan jam, biasanya diletakkan pada bawah screen seperti _footer_.

### Buka WindowMaker

<b>- Menampilkan Tanggal</b>

1. Buat atau siapkan text dan diisi nilai 'SSSSSSSSSS'
2. Double Click atau Klik Kanan → Animation Links.. pada text tersebut
3. Pilih bagian Value Display → String 
4. Isi nilai Expression dengan  `$DateString`
5. Selesai

<b>- Menampilkan Jam</b>

1. Buat atau siapkan text dan diisi nilai 'SSSSSSSS'
2. Double Click atau Klik Kanan → Animation Links.. pada text tersebut
3. Pilih bagian Value Display → String 
4. Isi nilai Expression dengan  `$TimeString`
5. Selesai


> Kedua nilai Expression (4.) tersebut merupakan fungsi bawaan / built-in inTouch yang dapat kita gunakan dalam pembuatan waktu secara realtime