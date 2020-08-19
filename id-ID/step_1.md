### Mengunduh NOOBS

Menggunakan NOOBS adalah cara termudah untuk menginstal Raspbian pada kartu SD kamu. Untuk mendapatkan salinan NOOBS:

+ Kunjungi [www.raspberrypi.org/downloads/](https://www.raspberrypi.org/downloads/)

![halaman Downloads](images/downloads-page.png)

+ Kamu akan melihat kotak dengan link ke file NOOBS. Klik pada link tersebut.

![Klik pada NOOBS](images/click-noobs.png)

+ Pilihan termudah adalah dengan mengunduh arsip zip nya.

![Unduh zip](images/download-zip.png)

### Memformat Kartu SD

Jika kartu SD yang kamu gunakan untuk menginstal Raspbian sudah berisikan versi Raspbian terdahulu didalamnya, kamu sebaiknya mencadangkan semua file dari kartu terlebih dulu, karena mereka akan ditimpa selama proses ini.

+ Kunjungi situs web SD Association dan unduh [SD Formatter](https://www.sdcard.org/downloads/formatter_4/index.html) untuk Windows atau Mac.

+ Ikuti instruksi untuk menginstal perangkat lunak.

+ Masukkan kartu SD ke pembaca kartu SD di komputer dan catat huruf drive yang dialokasikan padanya, misalnya `F:/`.

+ Di dalam SD Formatter, pilih huruf drive untuk kartu SD dan lakukan format.

### Mengekstrak NOOBS dari arsip zip

Selanjutnya, kamu perlu mengekstrak file dari arsip zip NOOBS yang kamu unduh dari situs web Raspberry Pi.

+ Buka folder *Downloads* dan cari file zip yang kamu unduh.

+ Ekstrak file dan biarkan jendela Explorer/Finder yang muncul terbuka.

### Menyalin file

+ Sekarang buka jendela Explorer/Finder lain dan arahkan ke kartu SD. Kami sarankan untuk menaruh dua jendela tersebut berdampingan.

+ Pilih semua file dari folder *NOOBS* dan seret mereka ke kartu SD.

![penyalinan di Windows](images/copy3.png)

![penyalinan di MacOS](images/macos_copy.png)

+ Keluarkan kartu SD.

### Booting dari NOOBS

+ Setelah semua file berhasil disalin, masukkan kartu SD ke Raspberry Pi, dan tancapkan Pi ke sumber daya.

+ Kamu akan ditawari pilihan saat installer telah dimuat. Centanglah kotak untuk **Raspbian**, lalu klik **Install**.

![instal](images/install.png)

+ Klik **Yes** pada dialog peringatan, lalu duduk dan tunggu. Proses ini lumayan lama, tetapi Raspbian akan terinstal.

![menginstal](images/installing.png)

+ Setelah Raspbian terinstal, klik **OK** dan Raspberry Pi akan merestart dan melakukan boot.

![terinstal](images/installed.png)