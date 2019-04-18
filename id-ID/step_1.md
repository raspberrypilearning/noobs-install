### Mengunduh NOOBS

Menggunakan NOOBS adalah cara termudah untuk menginstal Raspbian pada kartu SD Kamu. Untuk mendapatkan salinan NOOBS:

+ Kunjungi [www.raspberrypi.org/downloads/](https://www.raspberrypi.org/downloads/)

![Halaman unduhan](images/downloads-page.png)

+ Kamu akan melihat kotak dengan tautan ke file NOOBS. Klik pada link.

![Klik pada NOOBS](images/click-noobs.png)

+ Opsi paling sederhana adalah dengan mengunduh berkas zip nya.

![Unduh zip](images/download-zip.png)

### Memformat Kartu SD

Jika kartu SD yang Kamu gunakan untuk menginstal Raspbian saat ini memiliki versi Raspbian yang lebih lama didalamnya, Kamu sebaiknya membackup semua file dari kartu terlebih dahulu, karena kartu tersebut akan ditimpa selama proses ini.

+ Kunjungi situs web SD Association dan unduh [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) untuk Windows atau Mac.

+ Ikuti instruksi untuk menginstal perangkat lunak.

+ Masukkan kartu SD Kamu ke komputer atau pembaca kartu SD laptop dan catat huruf drive yang dialokasikan padanya, misalnya `F: /`.

+ Di dalam SD Formatter, pilih huruf drive untuk kartu SD Kamu, dan formatlah.

### Mengekstrak NOOBS dari arsip zip

Selanjutnya, Kamu perlu mengekstrak file dari arsip zip NOOBS yang Kamu unduh dari situs web Raspberry Pi.

+ Buka folder *Downloads* dan temukan file zip yang Kamu unduh.

+ Ekstrak file dan biarkan jendela Explorer / Finder terbuka.

### Menyalin file

+ Sekarang buka jendela Explorer / Finder lain dan arahkan ke kartu SD. Yang terbaik adalah memposisikan dua jendela berdampingan.

+ Pilih semua file dari folder *NOOBS* dan seret semua file tersebut ke kartu SD.

![salinan windows](images/copy3.png)

![salinan macos](images/macos_copy.png)

+ Keluarkan kartu SD.

### Booting dari NOOBS

+ Setelah file-file tersebut disalin, masukkan Micro SD Card ke Raspberry Pi Kamu, dan tancapkan Pi ke sumber daya.

+ Kamu akan ditawari pilihan ketika installer telah dimuat. Kamu harus mencentang kotak untuk **Raspbian**, lalu klik **Install**.

![memasang](images/install.png)

+ Klik **Yes** pada dialog peringatan, lalu duduk dan rileks. Ini akan memakan waktu cukup lama, tetapi Raspbian akan melakukan instalasi.

![menginstal](images/installing.png)

+ Ketika Raspbian telah diinstal, klik **OK** dan Raspberry Pi Kamu akan merestart dan Raspbian akan kemudian melakukan boot.

![terinstall](images/installed.png)