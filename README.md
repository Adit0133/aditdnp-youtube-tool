​🚀 Aditdnp YouTube Tool
​Interactive Bash-Based YouTube Management Suite for Termux
​1. Deskripsi Umum (Overview)
​aditdnp-youtube-tool adalah perangkat lunak utilitas baris perintah (CLI) interaktif tingkat lanjut yang dirancang khusus untuk lingkungan Termux di Android. Dibangun sepenuhnya menggunakan skrip Bash native, alat ini bertindak sebagai pusat kendali (all-in-one suite) yang menjembatani interaksi pengguna dengan platform YouTube, pemutaran media lokal/streaming, serta manajemen riwayat aktivitas secara efisien langsung dari genggaman ponsel Anda.  
​2. Fungsi Utama (Core Functions)
​Fungsi esensial dari tool ini meliputi:
​Manajemen Konten YouTube Terpadu: Memungkinkan pengguna mencari, mengelola, mengunduh, dan memutar konten dari YouTube tanpa memerlukan aplikasi pihak ketiga yang berat.  
​Ekstraksi Media Fleksibel: Mengonversi dan mengunduh video YouTube baik dalam format video utuh maupun audio murni (MP3) dengan kontrol kualitas tinggi.  
​Pemutar Musik & Streaming Mandiri: Mendukung pemutaran audio langsung secara streaming menggunakan integrasi mesin pemutar media berbasis MPv.  
​Pencarian Cerdas Tanpa Browser: Mencari lagu atau video langsung melalui terminal dengan hasil instan.  
​3. Fitur Unggulan (Key Features)
​Antarmuka Interaktif Berbasis Bash: Navigasi menu yang bersih, dinamis, dan ramah pengguna (user-friendly) meskipun dijalankan di dalam terminal teks.  
​Pengunduh Video & Audio MP3 Otomatis: Mengunduh file media dengan opsi penamaan dan penyimpanan yang terstruktur rapi ke direktori penyimpanan perangkat.  
​Integrasi Streaming MPv: Memungkinkan pengguna mendengarkan musik atau lagu langsung dari tautan atau hasil pencarian tanpa harus mengunduh file fisiknya terlebih dahulu ke memori HP.  
​Sistem Riwayat Aktivitas (Activity Logging): Mencatat setiap rekam jejak pencarian, unduhan, atau pemutaran yang pernah dilakukan sehingga memudahkan pengguna melacak kembali riwayat aktivitas sebelumnya.  
​Arsitektur Keamanan Terenkripsi (Binary Protection): Struktur kode inti dikemas dalam bentuk biner terenkripsi (download), memastikan keamanan logika program sekaligus menjaga performa eksekusi agar tetap ringan dan cepat.
​4. Kelebihan & Perbedaan Dibandingkan Tool Lain
​Mengapa aditdnp-youtube-tool berbeda dan lebih unggul dibanding downloader konvensional biasa?
Tool Konvensional / Skrip Biasaaditdnp-youtube-tool
FungsionalitasBiasanya hanya fokus pada satu fungsi saja (misal: hanya download video atau hanya download MP3).Multifungsi (All-in-One): Mencakup manajemen unduhan, pemutar musik/streaming, pencarian langsung, hingga pelacakan riwayat dalam satu tempat.
Kenyamanan PemutaranPengguna harus mengunduh file terlebih dahulu sebelum bisa mendengarkannya.Dilengkapi Fitur Streaming: Bisa langsung memutar musik via MPv tanpa menghabiskan ruang penyimpanan untuk file unduhan.
Pengalaman PenggunaSeringkali berupa skrip baris perintah mentah (raw command) yang membingungkan pemula.Menu Interaktif: Dirancang dengan sistem menu interaktif berbasis Bash yang intuitif dan mudah dioperasikan bahkan oleh pengguna baru.
Portabilitas & KeamananSkrip terbuka rentan diubah atau rusak, serta berukuran besar.Terenkripsi & Ringan: Dikemas dalam bentuk biner terenkripsi yang aman, sangat ringan dijalankan di sumber daya Termux yang terbatas, serta mudah di-clone ke perangkat lain.

## carane masang nang hp :

```bash
$ pkg update && pkg upgrade -y
$ git clone https://github.com/Adit0133/aditdnp-youtube-tool.git
$ cd aditdnp-youtube-tool
$ chmod +x download
$ ./download
