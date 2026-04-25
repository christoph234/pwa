Berdasarkan catatan pada papan tulis tersebut, berikut adalah penjelasan rinci mengenai manajemen proses dan memori dalam sistem operasi mobile (seperti Android) menggunakan pola **PREP** (**P**oint, **R**eason, **E**xample, **P**oint).

---

Penjelasan Sistem Operasi Mobile & Manajemen Memori

Point (Titik Utama)
Sistem operasi mobile mengelola aplikasi berdasarkan hirarki prioritas—yaitu **Foreground**, **Background**, dan **Cache**—untuk memastikan penggunaan sumber daya (RAM dan Baterai) tetap efisien dan sistem tetap responsif.

Reason (Alasan)
Perangkat mobile memiliki sumber daya yang terbatas dibandingkan komputer desktop. Oleh karena itu, sistem harus secara agresif menentukan aplikasi mana yang berhak mendapatkan memori penuh dan mana yang harus "dikurangi" atau dihentikan.
Foreground:Aplikasi yang sedang berinteraksi langsung dengan pengguna. Harus mendapat prioritas tertinggi agar tidak *lag*.
Background:Aplikasi yang tidak terlihat tapi masih menjalankan tugas (seperti mengunduh file atau sinkronisasi).
Cache (Inactive): Aplikasi yang sudah tidak digunakan tetapi masih disimpan di RAM agar saat dibuka kembali prosesnya lebih cepat. Namun, bagian ini adalah yang pertama dikorbankan jika sistem kehabisan memori.

Example (Contoh & Detail Teknis)
Berdasarkan diagram dan catatan di papan tulis:

Komponen Utama:
    Intent: Mekanisme pengiriman pesan antar komponen (seperti membuka kamera dari aplikasi WhatsApp).
    Provider:Mengelola akses ke kumpulan data terstruktur (seperti kontak atau galeri).
    FBE (File Based Encryption): Sistem keamanan di mana file-file berbeda dienkripsi dengan kunci yang berbeda pula.
    EDA (Event Driven Architecture): Arsitektur yang bereaksi terhadap "kejadian" tertentu dalam sistem.
Mekanisme Prioritas (Killer Priorities):
    Terlihat diagram kotak bertanda IG (Instagram), WA (WhatsApp), dan WB (Web Browser).
    Jika memori penuh, sistem akan melihat "Request Query" dan melakukan terminasi pada aplikasi dengan prioritas terendah (biasanya yang berada di kategori *Cache* atau *Inactive*).
    Ada catatan mengenai persentase baterai (10% - 9%) dan waktu (0m - 15m), yang menunjukkan bahwa status daya juga mempengaruhi bagaimana sistem mengelola proses di latar belakang.

Point (Kesimpulan)
Singkatnya, manajemen ini memastikan bahwa meskipun pengguna membuka banyak aplikasi, aplikasi yang sedang digunakan (**Foreground**) tetap lancar dengan cara secara otomatis mengelola, menidurkan, atau menghapus proses di **Background** dan **Cache** sesuai dengan kebutuhan memori dan kondisi baterai perangkat.
