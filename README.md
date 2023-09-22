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
![Jarkom M1 N3](https://github.com/farhandp93/Jarkom-Modul-1-B10-2023/assets/128909158/d8513517-c3fb-4e95-baa6-13c7a9e20ed5)


Nomor 4
  
  Berapa nilai checksum yang didapat dari header pada paket nomor 130?
    a.	Cari frame.number == 130 
    b.	Pilih yang user Datagram Protocol 
    c.	Pilih yang Checksum = …
![Jarkom M1 N4](https://github.com/farhandp93/Jarkom-Modul-1-B10-2023/assets/128909158/5ebde308-6ce7-4a54-9168-101c5b2316b4)


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




Keterangan Tambahan :
Untuk semua nomor kami submit menggunakan laptop Hasan karena terdapat masalah dengan laptop Farhan saat waktu praktikum, tapi kami mengerjakan bersama.
