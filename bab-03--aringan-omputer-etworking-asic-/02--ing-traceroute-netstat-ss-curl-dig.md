# Ping, traceroute, netstat, ss, curl, dig

- PING (Packet Internet Groper) - adalah utilitas baris perintah yang digunakan untuk menguji konektivitas jaringan antara dua host. Ini bekerja dengan mengirimkan paket Internet Control Message Protocol (ICMP) "echo request" ke host target dan menunggu balasan "echo reply".
  ping google.con / ping 8.8.8.8
- Traceroute (atau Tracert di Windows) - Traceroute adalah utilitas diagnostik jaringan yang melacak jalur yang dilewati paket data dari sumber ke tujuan. Ini melakukannya dengan mengirimkan paket dengan nilai Time-To-Live (TTL) yang terus meningkat, yang menyebabkan setiap router di jalur untuk mengirimkan pesan ICMP "time exceeded" kembali ke sumber.
  traceroute google.com (Linux/macOS)
  tracert google.com (Windows)
