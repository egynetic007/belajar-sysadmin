# File system hierarchy (/, /etc, /var, /home, dll)

- File System Hierarchy (FSH) pada Sistem Mirip Unix (Linux)
File System Hierarchy (FSH) adalah standar struktur direktori dan file pada sistem operasi mirip Unix, seperti Linux. Ini mendefinisikan lokasi dan tujuan dari setiap file dan direktori, memastikan konsistensi dan keteraturan dalam sistem. Standard ini diatur oleh Filesystem Hierarchy Standard (FHS).

  - /root : direktori paling atas dalam seluruh hirarki sistem file. Semua direktori dan file lainnya berada di bawah direktori ini.
  - /etc  : Berisi file-file konfigurasi untuk sistem dan aplikasi yang diinstal. File-file di sini biasanya berformat teks sederhana yang dapat diedit.
  - /var  : Berisi file-file yang datanya cenderung bervariasi selama operasi sistem, seperti log file, spool file, cache, dan data runtime aplikasi.
  - /home : Berisi direktori pribadi (home directory) untuk setiap pengguna standar di sistem. Setiap pengguna memiliki direktori sendiri di sini untuk menyimpan dokumen, unduhan, konfigurasi aplikasi pribadi, dll.
  - /boot : Berisi file-file yang diperlukan untuk proses booting sistem, seperti kernel Linux dan file-file yang digunakan oleh boot loader (misalnya GRUB atau LILO).
  - /bin  : Berisi perintah-perintah eksekusi penting (binary executables) yang dibutuhkan oleh pengguna dan sistem untuk beroperasi dalam mode single-user dan untuk booting.
  - /dev  : Berisi file-file khusus yang merepresentasikan perangkat keras (hardware) yang terhubung ke sistem, seperti hard drive, CD-ROM, printer, terminal, dll
  - /lib  :  Berisi pustaka bersama (shared libraries) penting yang dibutuhkan oleh binary executable di /bin dan /sbin untuk menjalankan program.
  - /usr  : direktori terpenting dan terbesar, berisi sebagian besar utilitas dan aplikasi yang diinstal di sistem. Berisi "user-land" dari sistem operasi.
  - /tmp  : Berisi file-file sementara yang dibuat oleh program. File-file di sini dapat dihapus saat sistem reboot atau secara berkala oleh sistem.
