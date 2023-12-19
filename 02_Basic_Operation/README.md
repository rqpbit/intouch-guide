# Wonderware InTouch

## Penggunaan Dasar (Basic Operation)

Intouch Wonderware memiliki banyak aplikasi yang dipisah-pisah, tapi pada pembahasan kali ini kita fokus untuk membahas 2 aplikasi yang sering digunakan dalam pembuatan HMI.


### InTouch WonderMaker
Aplikasi ini merupakan _environment development_ yang digunakan untuk membuat / membangun sebuah aplikasi HMI, disini proses penanganan alur logika, mendesain tampilan (GUI) dan juga menghubungkan ke PLC/DCS.

> PLC (Programmable Logic Controller) merupakan rangkaian elektronik yang dapat mengerjakan berbagai fungsi kontrol yang kompleks. PLC merupakan mikroprosesor yang digunakan untuk otomasi proses industri.

> DCS (Distributed Control System) merupakan sistem yang merangkum dan mengolah data serta mengorganisasikan berbagai tipe pengendalian proses secara terpadu dan real time

### InTouch WonderView
Aplikasi ini merupakan re-presentasi dari hasil yang telah dirancang/dibuat pada aplikasi WindowMaker, aplikasi ini yang dijalankan sebagai _HMI_ untuk _client_.

<hr>

> Pembahasan dibawah ini menggunakan aplikasi WindowMaker

## Konsep Dasar
Sebelum memulai, kamu harus mengerti beberapa penulisan _scripting_ pada intouch
- **QuickScript** merupakan bahasa _scriping language_ dari Intouch HMI
- **QuickFunctions** adalah fungsi yang dapat digunakan kembali dmanapun, untuk membuatnya pertama kamu membuat QuickScript dan beri nama, QuickFunction dapat dipanggil oleh script lain atau _expression_ pada kondisi _Script Direct_ 
- **Animation Link** adalah kondisi yang sudah diatur untuk reaksi yang telah ditentukan _(Contoh. ketika diklik, animasi dan lainnya)_ script disini harus bernilai _Expression_ atau diisi dengan tagname
- **Function** script merupakan script yang dapat dipanggil oleh function lain, InTouch HMI juga memiliki standar function yang siap digunakan.

### Window Scripts
![it2](https://github.com/rqpbit/intouch-guide/assets/148553161/eff1505d-320b-4db4-bd7e-597aa6d74f38)

Merupakan source code dari setiap screen/windows, kamu bisa membuka Windows Script dengan melakukkan **klik kanan pada screen dan pilih Windows Scripts**, terdapat 3 kondisi untuk dijalankan :
- **On Show** script akan dijalankan ketika pertama kali screen/windows dibuka
- **While Showing** script akan dijalankan secara terus menerus berdasarkan interval waktu yang ditentukan menggunakan satuan millisecond
- **On Hide** script akan dijalan ketika screen/windows ditutup