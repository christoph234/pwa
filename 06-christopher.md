Ini foto whiteboard tentang **perbandingan jenis pengembangan aplikasi mobile/web**. Saya akan jelaskan menggunakan pola **PREP (Point, Reason, Example, Point)**.

---

## Struktur Whiteboard

Papan dibagi menjadi **3 kolom utama**:

| Aspek | Native | Hybrid | PWA |
|---|---|---|---|
| Tools | Kotlin, IoT, ARK | HP (plugin) | HTML/JS/CSS + Worker |
| Akses Hardware | NFC, BT, Camera | Plugin | API: Cam, GPS, WA, BT |
| Performa | Tertinggi (to Height) | Medium | Height (cukup tinggi) |
| Biaya | 3x lebih mahal | 2x | 1x (paling murah) |
| Developer | Android, iOS, MS | HTML/JS/CSS | HTML/JS/CSS |
| Distribusi | App Store, Play Store | 2x kanal | URL (langsung akses) |
| Pilihan terbaik | Game, VR/AR | HP Bisnis | Web Apps |

---

## Penjelasan PREP

### 1. Native App

**Point:** Native adalah pengembangan aplikasi langsung di platform aslinya (Android/iOS).

**Reason:** Karena dibangun khusus untuk satu platform, native memiliki akses penuh ke hardware perangkat dan performa paling optimal. Di whiteboard tertulis "Height" untuk performa, dan biaya 3x lebih mahal dibanding PWA.

**Example:** Aplikasi seperti PUBG Mobile, Google Maps versi mobile, atau kamera bawaan HP — semuanya native karena butuh akses NFC, Bluetooth, dan kamera secara langsung.

**Point:** Jadi Native cocok untuk aplikasi yang membutuhkan performa tinggi dan akses hardware penuh seperti **Game dan VR/AR** (sesuai catatan di whiteboard: *"Pilihan tepat: Game, VR/AR"*).

---

### 2. Hybrid App

**Point:** Hybrid adalah aplikasi yang menggabungkan teknologi web (HTML/JS/CSS) dengan wrapper native.

**Reason:** Karena menggunakan satu codebase untuk banyak platform, biaya dan waktu pengembangan lebih hemat (2x dibanding native). Performa-nya "medium" — tidak sebaik native, tapi lebih baik dari website biasa. Akses hardware dilakukan melalui **plugin**.

**Example:** Aplikasi seperti Instagram (sebagian), Shopee, atau Tokopedia yang perlu berjalan di Android dan iOS sekaligus tanpa membangun dua aplikasi terpisah.

**Point:** Hybrid paling tepat untuk **aplikasi bisnis (HP Bisnis)** yang butuh multi-platform dengan budget terbatas — sesuai catatan whiteboard *"HP Bisnis"*.

---

### 3. PWA (Progressive Web App)

**Point:** PWA adalah aplikasi berbasis web yang bisa "terasa seperti aplikasi native" di browser.

**Reason:** Karena hanya menggunakan HTML/JS/CSS + Service Worker, PWA adalah yang **paling murah (1x biaya)** dan paling mudah didistribusikan — cukup lewat **URL**, tidak perlu install dari app store. Namun akses hardware terbatas pada API browser (Camera, GPS, Web Bluetooth).

**Example:** Twitter Lite, Starbucks PWA, atau Google Maps Go — bisa diakses langsung dari browser tanpa download, ringan, dan bisa dipakai offline.

**Point:** PWA paling cocok untuk **Web Apps** yang ingin menjangkau pengguna luas tanpa hambatan instalasi, sesuai catatan whiteboard *"Web Apps"*.

---

## Kesimpulan PREP Keseluruhan

**Point:** Tidak ada satu jenis pengembangan yang paling baik secara mutlak.

**Reason:** Setiap jenis punya trade-off antara **biaya, performa, akses hardware, dan kemudahan distribusi**.

**Example:** Seperti di whiteboard — Native untuk game, Hybrid untuk bisnis, PWA untuk web apps.

**Point:** Pilih jenis pengembangan berdasarkan **kebutuhan proyek, budget, dan target pengguna** — bukan hanya tren teknologi.
