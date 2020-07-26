# Pengenalan Android

### Pengertian Android
Android adalah sistem operasi yang dikeluarkan oleh Google. Android dibuat khusus untuk smartphone dan tablet. Berbagai macam produsen telah menggunakan Android sebagai sistem operasi untuk peranti (device) yang mereka produksi. Android juga mempunyai store dengan lebih dari 2 miliar pengguna aktif per bulannya, per Januari 2018.

### Mengapa Harus Android?
Android memanjakan penggunanya dengan fitur yang sangat canggih dan tampilan yang bagus. Sistem Android dapat digunakan sebagai alat multimedia seperti pemutar musik dan video. Ia juga memiliki perangkat keras seperti accelerometer, gyroscope dan sensor lainnya. Di samping itu ada beberapa hal yang membuat Android menjadi sistem operasi yang memang layak digunakan oleh pengguna atau dikembangkan para developer, seperti yang akan diuraikan berikut ini.

### Fitur Android :
1. **Sistem Operasi Smartphone Terpopuler** <br>
Sejak dirilis tahun 2008, Google telah mengeluarkan beberapa versi, dengan "Pie" sebagai versi yang terbaru.
Pada tahun 2013, Android menjadi operation system (OS) terlaris pada tablet dan smartphone. Kini market share Android sedikitnya 80 % dari total penjualan smarphone di tingkat global (statista.com). Tercatat pada tahun 2016 Android store memiliki lebih dari 2.8 juta aplikasi.
Android menarik bagi perusahaan teknologi yang membutuhkan barang siap jadi, biaya rendah dan kustomisasi OS untuk perangkat teknologi tinggi mereka. Hal ini menjadi daya tarik bagi banyak perusahaan, sehingga mereka memilih Android.
Source code dari Android bersifat open source. Ini adalah hal menarik bagi komunitas developer, karena lisensi open source sangat mendukung untuk mengembangkan produknya dengan aman. <br>

2. **Store**
Aplikasi Android bisa didistribusikan menggunakan web, copy APK, dan store. Android store, yaitu Google Play, merupakan cara termudah bagi para developer untuk mendistribusikan aplikasinya ke pasar dengan miliaran pengguna.
Google play merupakan store resmi Android yang dikelola oleh Google. Pengguna bisa mencari dan mengunduh aplikasi yang dikembangkan dengan menggunakan Android Software Development Kit.
Google Play tak hanya menawarkan aplikasi. Ada beragam konten lainnya yang dapat dinikmati pengguna, misalnya media digital, musik, buku, majalah, film dan program televisi.
Bagaimana para developer memonetisasi aplikasi yang ada di dalam Google Play?
Strategi monetisasi aplikasi yang ditawarkan Google Play ada bermacam-macam. Dimulai dari app berbayar (paid distribution), pembelian dalam aplikasi (in-app purchase), langganan (subscriptions), dan iklan (ads). Tentunya developer harus mengikuti aturan yang ada untuk memastikan bahwa pengguna mendapatkan pengalaman (user experience) terbaik. <br>

### Apa Iru ART dan DVM? : <br>
Dari tabel sejarah perkembangan di atas dapat kita lihat ada kolom DVM / ART. Kolom ini menunjukkan eksekusi kompilasi ketika menjalankan aplikasi Android. Pada API KitKat dan sebelumnya Android menggunakan DVM (Dalvik Virtual Machine). DVM menerapkan pendekatan JIT (Just-In-Time), di mana kompilasi dijalankan ketika ada permintaan untuk menjalankan aplikasi.
Sedangkan ART (Android Runtime) menerapkan pendekatan berbeda yaitu AOT (Ahead-Of-Time). AOT melakukan kompilasi pada saat proses instalasi aplikasi.
DVM menggunakan JIT yang berarti kompilasi dilakukan setiap kali aplikasi dijalankan. Hal ini sangat mempengaruhi kecepatan respon aplikasi. Setiap kali kita menyentuh ikon aplikasi maka kompilasi akan dilakukan. Tentu proses ini menghabiskan CPU dan berimbas pada relatif lebih borosnya penggunaan baterai.
Beda dengan DVM, ART melakukan proses kompilasi pada saat proses instalasi. Jadi setiap kali aplikasi dijalankan, sudah tidak ada lagi proses kompilasi. Hal ini meningkatkan performa dalam menjalankan aplikasi. Selain itu karena penggunaan sumber daya CPU bisa dikurangi, pemakaian baterai jadi lebih hemat. Akan tetapi ART membutuhkan space (ukuran berkas) yang lebih besar jika dibandingkan dengan DVM. <br>

### Development Kit untuk Developer <br>
Android Software Development Kit (SDK) merupakan kit yang bisa digunakan oleh para developer untuk mengembangkan aplikasi berbasis Android. Di dalamnya, terdapat beberapa tools seperti debugger, software libraries, emulator, dokumentasi, sample code dan tutorial.
Bahasa pemrograman yang sering digunakan untuk mengembangkan aplikasi Android adalah Java. Namun ada beberapa bahasa lainnya yang dapat digunakan, seperti C++ dan Go. Pada IO 2017 Google juga menetapkan Kotlin sebagai tambahan bahasa resmi.
Berbicara tentang pemrograman tentunya tak lepas dari Integrated Development Environment (IDE). Pada 2014 Google mengeluarkan IDE yang bernama Android Studio yang berbasiskan Intellij IDEA.
Dengan menggunakan Android Studio, para developer dapat membuat aplikasi dari nol hingga dipublikasikan ke dalam store. Android Studio juga mempunyai beberapa fitur built-in yang sangat membantu para developer untuk memaksimalkan proses pembuatan aplikasi. Fitur-fitur ini misalnya Gradle, Code Completion, dan beragam integrasi dengan layanan dari Google, seperti Firebase. <br>

### Android Studio
Android Studio adalah Lingkungan Pengembangan Terpadu - Integrated Development Environment (IDE) untuk pengembangan aplikasi Android, berdasarkan IntelliJ IDEA. Selain merupakan editor kode IntelliJ dan alat pengembang yang berdaya guna, Android Studio menawarkan fitur lebih demi meningkatkan produktifitas Anda saat membuat aplikasi Android, misalnya: <br>
•	Sistem versi berbasis Gradle yang fleksibel <br>
•	Emulator yang cepat dan kaya fitur <br>
•	Lingkungan yang menyatu untuk pengembangan bagi semua perangkat Android <br>
•	Instant Run untuk mendorong perubahan ke aplikasi yang berjalan tanpa membuat APK baru <br>
•	Template kode dan integrasi GitHub untuk membuat fitur aplikasi yang sama dan mengimpor kode contoh <br>
•	Alat pengujian dan kerangka kerja yang ekstensif <br>
•	Alat Lint untuk meningkatkan kinerja, kegunaan, kompatibilitas versi, dan masalah-masalah lain <br>
•	Dukungan C++ dan NDK <br>
•	Dukungan bawaan untuk Google Cloud Platform, mempermudah pengintegrasian Google Cloud Messaging dan App Engine <br>

### Persyaratan : <br>
#### Windows : <br>
•	Microsoft® Windows® 7/8/10 (32- atau 64-bit) <br>
•	RAM minimum 3 GB, RAM yang disarankan 8 GB; tambah 1 GB untuk Android Emulator <br>
•	Ruang disk minimum yang tersedia 2 GB, 
Disarankan 4 GB (500 MB untuk IDE + 1,5 GB untuk Android SDK dan gambar sistem emulator) <br>
•	Resolusi layar minimum 1280 x 800 <br>

#### MAC : <br>
•	Mac® OS X® 10.10 (Yosemite) atau lebih baru, hingga 10.13 (macOS High Sierra) <br>
•	RAM minimum 3 GB, RAM yang disarankan 8 GB; tambah 1 GB untuk Android Emulator <br>
•	Ruang disk minimum yang tersedia 2 GB,
Disarankan 4 GB (500 MB untuk IDE + 1,5 GB untuk Android SDK dan gambar sistem emulator) <br>
•	Resolusi layar minimum 1280 x 800 <br>

#### Linux : <br>
•	Desktop GNOME atau KDE <br>
Telah diuji pada Ubuntu® 14.04 LTS, Trusty Tahr (distribusi 64-bit yang mampu menjalankan aplikasi 32-bit) <br>
•	Distribusi 64-bit yang mampu menjalankan aplikasi 32-bit <br>
•	GNU C Library (glibc) 2.19 atau lebih baru <br>
•	RAM minimum 3 GB, RAM yang disarankan 8 GB; tambah 1 GB untuk Android Emulator <br>
•	Ruang disk minimum yang tersedia 2 GB,
Disarankan 4 GB (500 MB untuk IDE + 1,5 GB untuk Android SDK dan gambar sistem emulator) <br>
•	Resolusi layar minimum 1280 x 800 <br>






