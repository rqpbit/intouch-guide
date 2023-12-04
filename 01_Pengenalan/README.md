# Wonderware InTouch

## Pengenalan Dasar

Pada dasarnya InTouch adalah software Human Machine Interface yg dilengkapi dengan fitur dasar SCADA software. Untuk menggunakan Wonderware inTouch ada 3 komponen penyusun utama yg harus diketahui yaitu :

- Intouch Application Manager; berfungsi untuk mengorganisasikan aplikasi yang akan dibuat.
- Intouch Window Maker; suatu development environment dari intouch, kita dapat membuat halaman-halaman HMI dengan grafik yang object-oriented untuk menciptakan layar tampilan yg dapat bergerak dan dapat menerima masukan dari pengguna.
- Intouch Window Viewer; suatu runtime environment yg dapat menampilkan layar grafik yg telah dibuat pada Window Maker, disini client menjalankan aplikasi Intouch.


## Installasi

### Hardware Requirements by Installation Size
| Tipe   | Tagname Limit  | CPU (GHz)  | Cores (Minimum) | Ram (GB) | Monitor Resolution |
| :-----: | :--------: | :--------: | :-------: | :-------: | :-------: |
| Compact Installation | (1 - 500 I/O per Node)    | 2.8 | 1 | 1 | 1074x768 |
| Small Installation | (1 - 5K I/O per Node)    | 2.8 | 1 | 1 | 1074x768 |
| Medium Installation | (5k - 50k I/O per Node)    | 2.8 | 4 | 8 | 1280x1024 |
| Large Installation | (50k - 400k I/O per Node)    | 2.8 | 8 | 16 | 1280x1024 |

### License

Setelah proses installasi selesai dilakukkan, maka License di-_import_ pada aplikasi ArchestrA License Manager, terdapat 2 tipe license yang bisa dipasang :

- <b>Licensse File</b>, file yang harus dilakukkan import secara manual seperti cara diatas 
- <b>USB Dongle</b>, usb yang khusus yang didalamnya terintergrasi license secara otomatis, tidak diperlukan import manual, karena secara otomatis terpasang


License path :
> C:\Program Files (x86)\Common Files\ArchestrA\License\ArchestrA.lic 