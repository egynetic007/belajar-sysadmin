# Ping, traceroute, netstat, ss, curl, dig

- PING (Packet Internet Groper) - adalah utilitas baris perintah yang digunakan untuk menguji konektivitas jaringan antara dua host. Ini bekerja dengan mengirimkan paket Internet Control Message Protocol (ICMP) "echo request" ke host target dan menunggu balasan "echo reply".
  ping google.con / ping 8.8.8.8
- Traceroute (atau Tracert di Windows) - Traceroute adalah utilitas diagnostik jaringan yang melacak jalur yang dilewati paket data dari sumber ke tujuan. Ini melakukannya dengan mengirimkan paket dengan nilai Time-To-Live (TTL) yang terus meningkat, yang menyebabkan setiap router di jalur untuk mengirimkan pesan ICMP "time exceeded" kembali ke sumber.
  traceroute google.com (Linux/macOS)
  tracert google.com (Windows)
- Netstat (Network Statistics) - adalah utilitas baris perintah yang menampilkan statistik jaringan aktif. Ini dapat menunjukkan koneksi TCP aktif, port yang mendengarkan (listening ports), statistik Ethernet, tabel routing IP, dan statistik untuk protokol jaringan lainnya.
  Netstat digunakan untuk memecahkan masalah jaringan, memantau kinerja jaringan, dan mengidentifikasi koneksi yang tidak diinginkan atau program yang menggunakan port tertentu.
- SS (Socket Statistics) - SS adalah utilitas yang lebih modern dan lebih cepat daripada Netstat, terutama di sistem Linux. Ini juga digunakan untuk menampilkan statistik soket jaringan. SS menyediakan informasi yang lebih detail tentang soket TCP dan UDP, termasuk koneksi yang didengarkan, koneksi yang terhubung, dan statistik penggunaan soket. Ini sering direkomendasikan sebagai pengganti Netstat di lingkungan Linux karena performa dan fitur tambahannya

- test
  spapsi1
  spapci dua
  
  test
