# Ping, traceroute, netstat, ss, curl, dig

- PING (Packet Internet Groper) - adalah utilitas baris perintah yang digunakan untuk menguji konektivitas jaringan antara dua host. Ini bekerja dengan mengirimkan paket Internet Control Message Protocol (ICMP) "echo request" ke host target dan menunggu balasan "echo reply".
  ping google.con / ping 8.8.8.8
- Traceroute (atau Tracert di Windows) - Traceroute adalah utilitas diagnostik jaringan yang melacak jalur yang dilewati paket data dari sumber ke tujuan. Ini melakukannya dengan mengirimkan paket dengan nilai Time-To-Live (TTL) yang terus meningkat, yang menyebabkan setiap router di jalur untuk mengirimkan pesan ICMP "time exceeded" kembali ke sumber.
  traceroute google.com (Linux/macOS)
  tracert google.com (Windows)
- Netstat (Network Statistics) - adalah utilitas baris perintah yang menampilkan statistik jaringan aktif. Ini dapat menunjukkan koneksi TCP aktif, port yang mendengarkan (listening ports), statistik Ethernet, tabel routing IP, dan statistik untuk protokol jaringan lainnya.
  Netstat digunakan untuk memecahkan masalah jaringan, memantau kinerja jaringan, dan mengidentifikasi koneksi yang tidak diinginkan atau program yang menggunakan port tertentu.
- SS (Socket Statistics) - SS adalah utilitas yang lebih modern dan lebih cepat daripada Netstat, terutama di sistem Linux. Ini juga digunakan untuk menampilkan statistik soket jaringan.
  SS menyediakan informasi yang lebih detail tentang soket TCP dan UDP, termasuk koneksi yang didengarkan, koneksi yang terhubung, dan statistik penggunaan soket. Ini sering direkomendasikan sebagai pengganti Netstat di lingkungan Linux karena performa dan fitur tambahannya
- cURL (Client URL) -  cURL adalah alat baris perintah dan pustaka untuk mentransfer data dengan sintaks URL. Ini mendukung berbagai protokol, termasuk HTTP, HTTPS, FTP, FTPS, SCP, SFTP, TFTP, DICT, TELNET, LDAP, LDAPS, FILE, IMAP, SMTP, POP3, RTSP, dan RTMP.
   cURL sering digunakan untuk menguji API web, mengunduh atau mengunggah file dari server, dan berinteraksi dengan server web secara langsung dari terminal. Ini sangat serbaguna dan dapat digunakan untuk banyak tugas terkait jaringan dan transfer data.
- DIG (Domain Information Groper) - DIG adalah utilitas baris perintah untuk melakukan kueri server DNS (Domain Name System). Ini sangat berguna untuk memecahkan masalah DNS, memeriksa catatan DNS (seperti A, MX, NS, CNAME), dan memahami bagaimana nama domain diselesaikan menjadi alamat IP. DIG memberikan informasi rinci tentang jawaban DNS, termasuk server DNS yang menjawab, waktu kueri, dan semua catatan DNS yang relevan.

- Link :
  - [https://emka.web.id/2023/08/cara-menggunakan-perintah-ping-untuk-menguji-jaringan-anda.html](https://emka.web.id/2023/08/cara-menggunakan-perintah-ping-untuk-menguji-jaringan-anda.html)




  
