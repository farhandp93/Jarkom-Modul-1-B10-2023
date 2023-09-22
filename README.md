# Jarkom-Modul-1-B10-2023
Laporan Resmi 


Anggota :

Farhan Dwi Putra (5025211093)

Yusuf Hasan Nazila (5025211225)


Nomor 1
  
  User melakukan berbagai aktivitas dengan menggunakan protokol FTP. Salah satunya adalah mengunggah suatu file.
  Berapakah sequence number (raw) pada packet yang menunjukkan aktivitas tersebut? 
  Berapakah acknowledge number (raw) pada packet yang menunjukkan aktivitas tersebut? 
  Berapakah sequence number (raw) pada packet yang menunjukkan response dari aktivitas tersebut?
  Berapakah acknowledge number (raw) pada packet yang menunjukkan response dari aktivitas tersebut?
![Jarkom M1 N1](https://github.com/farhandp93/Jarkom-Modul-1-B10-2023/assets/128909158/4b89d204-94e0-4b33-bbf9-365d6183cb34)
![Jarkom M1 N1 A](https://github.com/farhandp93/Jarkom-Modul-1-B10-2023/assets/128909158/a7f12aee-8ead-4c49-b102-1ff10f04a281)
  Lakukan filter ftp contains “STOR”
  Lakukan filter ftp contains “c75-GrabThePicher.zip”


Nomor 2
  
  Sebutkan web server yang digunakan pada portal praktikum Jaringan Komputer!
  pada kolom apply display tulis http contains "server web praktikum", lalu apply display filter.
![Jarkom M1 N2](https://github.com/farhandp93/Jarkom-Modul-1-B10-2023/assets/128909158/24601a53-e400-4c5e-8fc3-0e8792ff98a3)
![Jarkom M1 N2 A](https://github.com/farhandp93/Jarkom-Modul-1-B10-2023/assets/128909158/68dd0b69-d94c-4921-8e3c-59463a4bba0c)


Nomor 3
  
  Dapin sedang belajar analisis jaringan. Bantulah Dapin untuk mengerjakan soal berikut:
    a.	Berapa banyak paket yang tercapture dengan IP source maupun destination address adalah 239.255.255.250 dengan port 3702?
    b.	Protokol layer transport apa yang digunakan?
  Lakukan filter ip.addr == 239.255.255.250 && udp.port == 3702, lalu hitung jumlah ip untuk bagian a dan jenis port untuk bagian b
![WhatsApp Image 2023-09-22 at 6 56 25 PM](https://github.com/farhandp93/Jarkom-Modul-1-B10-2023/assets/128909158/3f044d63-3b38-4285-beef-101e3e9563eb)

![Jarkom M1 N3](https://github.com/farhandp93/Jarkom-Modul-1-B10-2023/assets/128909158/d8513517-c3fb-4e95-baa6-13c7a9e20ed5)


Nomor 4
  
  Berapa nilai checksum yang didapat dari header pada paket nomor 130?
    a.	Cari frame.number == 130 
    b.	Pilih yang user Datagram Protocol 
    c.	Pilih yang Checksum = …
![Jarkom M1 N4](https://github.com/farhandp93/Jarkom-Modul-1-B10-2023/assets/128909158/5ebde308-6ce7-4a54-9168-101c5b2316b4)


Nomor 5

  Elshe menemukan suatu file packet capture yang menarik. Bantulah elshe untuk menganalisis file packet capture tersebut.
  Langkah pertama cari smtp, lalu klik kanan pada file 13.
![WhatsApp Image 2023-09-22 at 6 22 59 PM](https://github.com/farhandp93/Jarkom-Modul-1-B10-2023/assets/128909158/71ac1922-9c6e-4c7d-99cc-9cc17b6a07f8)
![WhatsApp Image 2023-09-22 at 6 23 54 PM](https://github.com/farhandp93/Jarkom-Modul-1-B10-2023/assets/128909158/8fda4ed2-e846-4af2-a41c-cea7c7a7245d)
  Follow -> TCP STREAM, copy note pad lalu cari here the password.
![image](https://github.com/farhandp93/Jarkom-Modul-1-B10-2023/assets/114125438/b39ffacf-e82d-4e18-aac6-db4f301890fc)
  Passwordnya yaitu 5implePas5word. Setelah itu masukan nc... di ubuntu lalu 
a. Berapa banyak packet yang berhasil di capture dari file pcap tersebut?
Your answer: 60
Correct answer!
![image](https://github.com/farhandp93/Jarkom-Modul-1-B10-2023/assets/114125438/9637a3d7-a586-4ace-b63c-da0a996721a2)

b. Port berapakah pada server yang digunakan untuk service SMTP?
Your answer: 25
Correct answer!
c. Dari semua alamat IP yang tercapture, IP berapakah yang merupakan public IP?
Your answer: 74.53.140.153
Correct answer!
Correct answers, you are good at analysis!
Here is your flag: Jarkom2023{k0w4lski_1124_hEimORNOiAv_4nalys1s}


Nomor 6

  Seorang anak bernama Udin Berteman dengan SlameT yang merupakan seorang penggemar film detektif. sebagai teman yang baik, Ia selalu mengajak slamet untuk bermain valoranT bersama. suatu malam, terjadi sebuah hal yang tak terdUga. ketika udin mereka membuka game tersebut, laptop udin menunjukkan sebuah field text dan Sebuah kode Invalid bertuliskan "server SOURCE ADDRESS 7812 is invalid". ketika ditelusuri di google, hasil pencarian hanya menampilkan a1 e5 u21. jiwa detektif slamet pun bergejolak. bantulah udin dan slamet untuk menemukan solusi kode error tersebut.
  cari frame.cumber == 7812
![WhatsApp Image 2023-09-22 at 6 30 23 PM](https://github.com/farhandp93/Jarkom-Modul-1-B10-2023/assets/128909158/befe4e22-c727-4a32-a1ff-ca668fb9bdfd)
![WhatsApp Image 2023-09-22 at 6 31 09 PM](https://github.com/farhandp93/Jarkom-Modul-1-B10-2023/assets/128909158/c52216b6-c097-4cbe-a33f-810f0435d872)
  source addres 104.18.14.101 dipecah menjadi huruf = 10 4 18 14 10 1


Nomor 7
  
  Berapa jumlah packet yang menuju IP 184.87.193.88?
  ip.dst == 184.87.193.88
![Jarkom M1 N7](https://github.com/farhandp93/Jarkom-Modul-1-B10-2023/assets/128909158/a7b70be0-141d-475f-92b8-97594ef15eb6)
![Jarkom M1 N7 A](https://github.com/farhandp93/Jarkom-Modul-1-B10-2023/assets/128909158/6f060eba-0bbe-4f3a-90b0-05415c3d6c55)


Nomor 8
  
  Berikan kueri filter sehingga wireshark hanya mengambil semua protokol paket yang menuju port 80! (Jika terdapat lebih dari 1 port, maka urutkan sesuai dengan abjad)
  tcp.dstport == 80 || udp.dstport == 80
![Jarkom M1 N8](https://github.com/farhandp93/Jarkom-Modul-1-B10-2023/assets/128909158/3e522e91-9f08-41c1-84c4-53f802567975)
![Jarkom M1 N8 A](https://github.com/farhandp93/Jarkom-Modul-1-B10-2023/assets/128909158/f712be3c-ea4d-4d7a-ab59-6e256faeb6cb)


Nomor 9
  
  Berikan kueri filter sehingga wireshark hanya mengambil paket yang berasal dari alamat 10.51.40.1 tetapi tidak menuju ke alamat 10.39.55.34!
  Ip.src == 10.51.40.1 && ip.dst != 10.39.55.34
![Jarkom M1 N9](https://github.com/farhandp93/Jarkom-Modul-1-B10-2023/assets/128909158/6d7b6a43-5b27-4991-9f43-20d28b094f08)


Nomor 10
  
  Sebutkan kredensial yang benar ketika user mencoba login menggunakan Telnet
![Jarkom M1 N10](https://github.com/farhandp93/Jarkom-Modul-1-B10-2023/assets/128909158/042a1aea-6245-45d8-945a-90a4336ee6e4)
![Jarkom M1 N10 A](https://github.com/farhandp93/Jarkom-Modul-1-B10-2023/assets/128909158/2518909c-0eac-4d67-8a27-0a005cf5d818)
![Jarkom M1 N10 B](https://github.com/farhandp93/Jarkom-Modul-1-B10-2023/assets/128909158/7bf3ec2e-dcd6-4a5f-9786-35a2dee93ba0)


Kendala:
Kesulitan yang kami temukan pada praktikum modul 1 banyak ditemukan untuk nomor 5 dan 6 karena rumit untuk menemukan jawaban dan vpn yang cukup lambat.


Keterangan Tambahan :
Untuk semua nomor kami submit menggunakan laptop Hasan karena terdapat masalah dengan laptop Farhan saat waktu praktikum, tapi kami mengerjakan bersama.
