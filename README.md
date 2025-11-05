LIL CHAMPS
Mobile Version

Chris Darren Imanuel
2406396956
PBP D

TUGAS 7
1. Widget Tree adalah struktur hierarkis yang menggambarkan hubungan antara widget yang ada dalam aplikasi Flutter. Hubungan antar widget disusun dalam relasi parent-children di mana anak terkandung dalam induk dan akan mewarisi konteks dari parentnya. Widget parent mengatur dan mengontrol properti dan perilaku widget child.
2. MaterialApp, Scaffold, Appbar, Text, TextStyle, Padding, Column, Row, Center, Card, Container, Snackbar, Icon, Material, InkWell, InfoCard, ItemCard
3. MaterialApp menyediakan kerangka kerja material design dan konfigurasi level atas. MaterialApp banyak digunakan karena berfungsi sebagai gerbang utama yang mengatur semua konfigurasi dan implementasi unsur-unsur visual, fungsional, dan navigasi untuk seluruh aplikasi.
4. StatelessWidget bersifat immutable (tidak dapat berubah setelah dibuat), tidak memiliki state, dan hanya bergantung pada konfigurasi pembuatan awal. Di sisi lain, StatefulWidget dapat berubah selama runtime, memiliki state internal yang dapat di-update, dan mendukung respon interaktif dengan user ataupun data eksternal. Kita dapat pilih StatelessWidget ketika apa yang mau kita tampilkan tidak perlu berubah selama penggunaan misal logo, judul, icon. Sedangkan, StatefulWidget kita gunakan apabila widget perlu diperbarui secara dinamis sebagai respons terhadap input pengguna atau ada data yang berubah.
5. BuildContext adalah objek yang menyediakan informasi tentang posisi widget dalam widget tree sehingga berfungsi sebagai acuan atau referensi ke lokasi widget tertentu. BuildContext penting untuk melacak dan mengindentifikasi lokasi widget dalam tree, menyediakan akses ke ancestor dan inherited widgets sehingga dapat berinteraksi dengan widget lain yang di atasnya (seperti theme, navigator, provider).
6. Hot Reload menyuntikkan kode yang diperbarui dari perubahan yang dibuat langsung ke aplikasi yang sedang berjalan dan state masih dipertahankan sehingga terjadi sangat cepat karena hanya memperbarui kode yang diubah. Sedangkan, Hot Restart memuat ulang seluruh aplikasi dan menjalankan kode dari awal, menyebabkan semua state yang ada hilang dan perlu untuk diatur ulang. Dari keduanya, Hot Reload mempunyai speed yang lebih tinggi sehingga lebih cepat daripada Hot Restart. Namun, Hot Restart perlu digunakan apabila ada perubahan yang memengaruhi inisialisasi aplikasi.