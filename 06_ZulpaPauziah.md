1. Native App (Aplikasi Native)
- Point (Titik Utama): Aplikasi Native adalah aplikasi yang dibangun khusus untuk platform tertentu (seperti Android dengan Kotlin/Java atau iOS dengan Swift) untuk mendapatkan performa maksimal.
- Reason (Alasan): Karena dibangun menggunakan bahasa pemrograman "ibu" dari sistem operasi tersebut, aplikasi memiliki akses penuh ke seluruh fitur perangkat keras secara langsung tanpa perantara.
- Example (Contoh): Akses Hardware: Mendukung penuh NFC, Bluetooth (BT), dan Kamera secara instan.
    - Performa: Sangat Tinggi (Height).
    - Distribusi: Melalui App Store (AS), Play Store (PS), dan Microsoft Store (MS).
    - Kegunaan: Sangat tepat untuk Game berat, VR (Virtual Reality), dan AR (Augmented Reality).
- Point (Penegasan): Jika prioritas Anda adalah kecepatan dan fitur hardware yang kompleks, Native adalah pilihan mutlak.

2. Hybrid App (Aplikasi Hybrid)
- Point (Titik Utama): Aplikasi Hybrid adalah perpaduan antara aplikasi web dan native, di mana kode web (HTML/JS/CSS) dibungkus dalam "wadah" native.
- Reason (Alasan): Pendekatan ini memungkinkan pengembang menggunakan satu basis kode untuk berbagai platform, namun memerlukan plugin tambahan untuk berkomunikasi dengan perangkat keras.
- Example (Contoh):
    - Akses Hardware: Menggunakan Plugin untuk mengakses fitur ponsel.
    - Performa: Menengah (Medium).
    - Biaya/Waktu: Lebih efisien karena hanya perlu membangun 2 varian utama (Android & iOS) namun tetap bisa didistribusikan lewat toko aplikasi.
    - Kegunaan: Cocok untuk aplikasi bisnis atau aplikasi konten yang tidak membutuhkan pemrosesan grafis berat.
- Point (Penegasan): Hybrid adalah solusi jalan tengah untuk efisiensi biaya tanpa meninggalkan eksistensi di toko aplikasi resmi.

3. PWA (Progressive Web App)

- Point (Titik Utama): PWA adalah situs web yang dioptimalkan sehingga memiliki pengalaman pengguna menyerupai aplikasi ponsel (bisa diinstal tanpa lewat store).
- Reason (Alasan): Berjalan di atas browser dengan teknologi *Service Workers*, sehingga sangat ringan dan tidak memerlukan proses unduhan yang besar melalui toko aplikasi.
- Example (Contoh):
    - Teknologi: Menggunakan HTML, JS, CSS, dan Service Workers.
    - Akses Hardware: Terbatas melalui API browser (seperti Kamera, GPS, atau Bluetooth dasar).
    - Distribusi: Cukup melalui **URL** atau link web; tidak perlu masuk ke Play Store/App Store.
    - Performa: Cukup tinggi untuk standar web (*Height* dalam konteks web app).
- Point (Penegasan): PWA adalah pilihan terbaik untuk jangkauan pengguna yang luas secara cepat tanpa hambatan birokrasi toko aplikasi.


|        Fitur        |          Native          |          Hybrid        |            PWA        |
|_____________________|__________________________|________________________|_______________________|
|  Akses Hardware     | Langsung (NFC, BT, Cam)  | Lewat Plugin           | Lewat Web API         |
|  Performa           | Sangat Tinggi | Menengah | Tinggi (Web-based)     |
|  Distribusi         | App Store / Play Store   | App Store / Play Store | URL / Web Link        |
|  Sangat Cocok Untuk | Game, VR/AR              | Aplikasi Bisnis        | Web App / Marketplace |
