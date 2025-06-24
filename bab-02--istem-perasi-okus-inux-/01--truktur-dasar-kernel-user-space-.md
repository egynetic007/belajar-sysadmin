# Struktur dasar OS (kernel, user space)

- Karenl adalah : inti dari sistem operasi yang berjalan langsung di atas perangkat keras (Hardware).
    - Kernel adalah inti dari sistem operasi. Ia adalah bagian pertama yang dimuat ke memori saat komputer booting dan tetap berada di memori sepanjang waktu komputer beroperasi. Kernel bertindak sebagai jembatan antara aplikasi perangkat lunak (program) dan perangkat keras (hardware) komputer.
    - Fungsi utamanya untuk mengelola proses management, mengatur memori, mengelola perangkat I/O (device management), menyediakan system file, menyediakan keamanan dan akses control.
    - Contohnya : Linux Kernel, Window NT Kernel, XNU MacOS
- User Space    : adalah tempat di mana semua aplikasi pengguna, utilitas sistem, dan sebagian besar proses non-inti beroperasi. Program-program di user space tidak memiliki akses langsung ke perangkat keras atau bagian-bagian inti dari sistem operasi.
    - Fungsi utamanya : Menjalankan Aplikasi pengguna, hak akses nya terbatas, lingkungan terilolasi.
 
      Link : [https://www.itkoding.com/arsitektur-dasar-sistem-operasi/](https://www.itkoding.com/arsitektur-dasar-sistem-operasi/)
