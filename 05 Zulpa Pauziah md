
Mobile Computing & OS — Pola PREP
MK = Mobile Computing & OS | Jelaskan secara rinci dan komprehensif
________________________________________
FOREGROUND
Point — Foreground adalah proses/aplikasi yang sedang aktif dan langsung berinteraksi dengan pengguna di layar utama.
Reason — Foreground mendapat prioritas tertinggi dari OS karena langsung melayani pengguna. OS wajib menjaga proses ini tetap responsif dan tidak boleh dimatikan sembarangan meski RAM menipis.
Example — Contohnya adalah Anti Virus yang sedang scan aktif, Task/tugas yang sedang dikerjakan, serta Overlay/Typing seperti keyboard yang muncul di atas layar.
Point (Penutup) — Selama pengguna masih berinteraksi dengan aplikasi, OS tidak akan pernah mematikan foreground process dalam kondisi apapun.
________________________________________
BACKGROUND
Point — Background adalah proses yang berjalan di balik layar tanpa tampilan langsung ke pengguna namun tetap aktif menjalankan tugas penting.
Reason — Dibutuhkan agar aplikasi tetap bisa sinkronisasi data, menerima notifikasi, dan memproses informasi tanpa harus selalu tampil di layar.
Example — Contohnya adalah GPS yang melacak lokasi, NFC yang mendeteksi sinyal, Files yang berjalan sinkronisasi, serta FBT (Foreground Bound Task) dan KP (Key Process) yang tetap aktif di background.
Point (Penutup) — Background process mendapat prioritas lebih rendah dari foreground. Android membatasinya melalui mekanisme Doze Mode dan App Standby untuk menghemat baterai.
________________________________________
CACHE
Point — Cache adalah kondisi di mana aplikasi sudah tidak aktif (inactive) namun masih tersimpan di RAM untuk mempercepat akses kembali.
Reason — Membuka aplikasi dari cache (warm start) jauh lebih cepat dibanding membuka dari awal (cold start), sehingga pengalaman pengguna lebih mulus dan efisien.
Example — Aplikasi kalkulator yang baru ditutup masuk ke status Cache Inactive. Ketika dibuka kembali, tampil instan tanpa loading ulang dari nol.
Point (Penutup) — Cache process adalah yang pertama dimatikan OS saat RAM kritis menggunakan mekanisme LRU (Least Recently Used) Killing — aplikasi yang paling lama tidak dipakai dimatikan lebih dulu.
________________________________________
INTENT
Point — Intent adalah mekanisme pesan dalam Android untuk meminta komponen lain melakukan suatu aksi, baik dalam satu aplikasi maupun antar aplikasi berbeda.
Reason — Intent membuat arsitektur Android modular dan fleksibel karena setiap komponen tidak perlu tahu detail implementasi komponen lain untuk bisa berkomunikasi.
Example — Contohnya Intent untuk membuka file PDF, memproses tag NFC, menangani Pending Data Transfer (PDTR), dan membuka Google Drive dari aplikasi lain.
Point (Penutup) — Tanpa Intent, setiap aplikasi akan berdiri sendiri dan tidak bisa berkolaborasi. Intent adalah fondasi utama interoperabilitas ekosistem Android.
________________________________________
MEMORY MANAGEMENT
Point — Memory Management adalah proses OS dalam mengalokasikan, memantau, dan membebaskan RAM agar semua proses berjalan optimal.
Reason — RAM perangkat mobile sangat terbatas. OS harus dinamis menjaga foreground tetap responsif, membatasi background, dan membersihkan cache saat diperlukan.
Example — Dari diagram papan tulis, saat aplikasi baru dibuka konsumsi memori ~10%, lalu setelah 15 menit tidak aktif turun menjadi ~1%. Proses secara bertahap berpindah dari aktif → background → cache → dimatikan.
Point (Penutup) — OS menggunakan strategi LMK (Low Memory Killer) untuk otomatis mengakhiri proses cache dan background saat RAM menyentuh batas kritis demi menjaga stabilitas sistem.
________________________________________
FBE (File-Based Encryption)
Point — FBE adalah metode enkripsi di mana setiap file dienkripsi secara individual dengan kunci unik yang berbeda-beda.
Reason — Lebih unggul dari Full Disk Encryption karena sebagian file sistem tetap bisa diakses sebelum perangkat di-unlock, seperti alarm dan panggilan darurat, sementara data pribadi tetap terenkripsi penuh.
Example — Sebelum unlock: sistem bisa menjalankan alarm dan menerima panggilan (Direct Boot Mode). Setelah unlock: foto, chat, dan dokumen pribadi bisa diakses penuh.
Point (Penutup) — FBE wajib diterapkan sejak Android 10 ke atas sebagai standar keamanan untuk memastikan data pengguna tetap aman meski perangkat dicuri dalam kondisi mati.
________________________________________
CDA (Event-Driven Architecture)
Point — CDA adalah pola arsitektur di mana alur sistem dikendalikan oleh event yang dipicu pengguna, sistem, atau sumber eksternal secara asinkron.
Reason — Sangat cocok untuk lingkungan mobile yang penuh interupsi seperti notifikasi, sentuhan layar, dan sinyal jaringan karena memungkinkan sistem merespons tanpa memblokir proses lain.
Example — Dari papan tulis, BQ (Background Queue) memproses Request Query dengan sistem antrian secara batch. Setiap event "terikat dari anteceden" — saling berantai dari pemicu sebelumnya.
Point (Penutup) — CDA memastikan sistem mobile tetap responsif dan stabil dengan memproses setiap event melalui antrian terstruktur sesuai prioritasnya.
________________________________________
KESIMPULAN
Mobile Computing & OS mengelola proses dalam tiga lapisan utama yaitu Foreground, Background, dan Cache, masing-masing dengan tingkat prioritas yang berbeda sesuai kebutuhan pengguna dan kondisi sistem.
OS menggunakan komponen seperti Intent untuk komunikasi antar aplikasi, Content Provider untuk berbagi data secara aman, dan Window Manager untuk mengatur tampilan layar. Di sisi keamanan, FBE memastikan data pengguna terenkripsi secara individual, sementara CDA menjamin sistem merespons setiap event secara efisien melalui antrian terstruktur.
Inti dari keseluruhan materi ini adalah bahwa OS pada perangkat mobile dirancang untuk menyeimbangkan antara performa, efisiensi baterai, keamanan data, dan pengalaman pengguna dalam satu ekosistem yang saling terhubung. Memahami hierarki proses dan mekanisme manajemen memori adalah kunci untuk membangun aplikasi mobile yang efisien, responsif, dan tidak boros sumber daya.
