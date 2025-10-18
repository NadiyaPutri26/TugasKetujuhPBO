# TugasKetujuhPBO
Praktikum ini dibuat untuk memenuhi tugas mata kuliah PBO dengan dosen pengampu Bapak Bayu Adhi Nugroho Ph. D.
Dalam praktikum ini akan dilakukan penerapan konsep iReports di Netbeans. iReports sendiri adalah GUI yang memudahan _user_ untuk membuat ataau mendesain laporan berupa JasperReports secara visual tanpa harus membuat _code_ manual dengan XML.
Dan di praktikum ini mahasiswa akan diminta membuat JasperReports dengan data dari praktikum sebelumnya. Dimana dengan menambahkan _button_ tambahan yakni _button print_ pada tampilan GUI utama untuk mencetak laporan JasperReports.
## Installing iReports dan pebnambahan file JAR di libraries untuk membuat JasperReports di Netbeans
1. Mengunduh iReports plugin terlebih dahulu (https://sourceforge.net/projects/erpbarcode/files/JasperSoft/iReport-5.6.0-plugin.zip/download) 
3. Mengunduh org-desktop-layout-RELEASE56 (https://mvnrepository.com/artifact/org.netbeans.api/org-jdesktop-layout/RELEASE65)
4. Melakukan penambahan di tools Netbeans bagian plugin
<img width="459" height="298" alt="image" src="https://github.com/user-attachments/assets/389139eb-10c1-4b9d-b326-d5904d110fe1" />
<img width="465" height="298" alt="image" src="https://github.com/user-attachments/assets/1730062b-a9c5-4f06-81f4-7a7fdd405c69" />
<img width="611" height="378" alt="image" src="https://github.com/user-attachments/assets/546d68e3-a16b-424f-b8c1-aed172590741" />
<img width="472" height="383" alt="image" src="https://github.com/user-attachments/assets/a5097a86-88ec-4f33-8951-75ee7cd046b9" />
<img width="423" height="379" alt="image" src="https://github.com/user-attachments/assets/31bf4163-86b0-4c03-9bee-ef57273030b3" />
<img width="434" height="396" alt="image" src="https://github.com/user-attachments/assets/4cfe5945-d386-4c9b-b775-adf4cabdab26" />
<img width="409" height="368" alt="image" src="https://github.com/user-attachments/assets/9ce8e581-7882-4d2f-a999-4120e6f62d82" />
<img width="716" height="402" alt="image" src="https://github.com/user-attachments/assets/05ab933f-19c7-4b1e-b34e-729ad4f4369b" />

6. Setelah plugin sudah terinstall dan aktif di Netbeans, maka selanjutnya adalah penambahan file JAR libraries.
   
8. Unduh file JAR di link berikut: https://drive.google.com/drive/folders/1mEDGZOasZkQrXUNV89_8L-qpoJMKescX?usp=sharing
   
   (file JAR ini saya mencari nya satu persatu menyesuaikan version JDK Netbeans saya)
   
   <img width="258" height="137" alt="image" src="https://github.com/user-attachments/assets/0065868d-20fc-49a5-a7c1-4b49cba0f4cf" />
   <img width="242" height="255" alt="image" src="https://github.com/user-attachments/assets/198c96b8-0f9f-42a2-be0a-edc8df550651" />
   
9. Proses installing tools nya sudah selesai
## Pembuatan JasperReports menggunakan _iReports Designer_
1. Buat "Jasper Wizard" pada menu "New" di Package
   <img width="457" height="325" alt="image" src="https://github.com/user-attachments/assets/2fd9aa63-2602-44aa-9569-3beb82fcadc5" />
   
3. Memilih layout untuk laporan
   <img width="563" height="411" alt="image" src="https://github.com/user-attachments/assets/52fc44d2-25d5-41a0-9ab8-f35a7ba367af" />
   
5. memberi nama terserah pada file laporannya
   <img width="766" height="335" alt="image" src="https://github.com/user-attachments/assets/24098d0d-7289-4203-9108-e08ab506f903" />
   
7. mengkoneksikannya dengan _database_
   <img width="536" height="389" alt="image" src="https://github.com/user-attachments/assets/020fdf92-e7a7-48b1-952a-f598126136ea" />
   <img width="579" height="418" alt="image" src="https://github.com/user-attachments/assets/00abebd6-00a1-4dc5-ba71-ba4dba885089" />
   
9. Membuat query untuk menampilkan semua data di tabel
    <img width="685" height="418" alt="image" src="https://github.com/user-attachments/assets/4051c2df-9815-4c07-afbb-4b9436d57ef6" />
    
11. Memindahkan semua data ke laporan
    <img width="464" height="340" alt="image" src="https://github.com/user-attachments/assets/11de506a-666f-4ac5-91f0-43f6e4135ff3" />
    <img width="448" height="322" alt="image" src="https://github.com/user-attachments/assets/fee50f80-8055-4529-a710-201057d5dfa0" />
    
13. laporan sudah jadi, tinggal di edit sesuai kemauan user
    <img width="451" height="326" alt="image" src="https://github.com/user-attachments/assets/91e1b07d-eb98-41b5-8230-37d70ed1d801" />
    <img width="800" height="423" alt="image" src="https://github.com/user-attachments/assets/8d17aa50-d1d3-4107-bead-8dd1deac05d9" />

## Cara menampilkan laporan
1. Pastikan program terhubung ke _database_
2. Menjalankan program GUI utama
   <img width="635" height="455" alt="image" src="https://github.com/user-attachments/assets/fe02bb0e-1869-446a-8371-a26f978053cf" />

4. Klik _button_ _print_
5. laporan muncul
   <img width="940" height="623" alt="image" src="https://github.com/user-attachments/assets/faeb6ccc-d1cf-4cda-908b-4ca19676f335" />

# Catatan
Sekian penjelasan mengenai JasperReports ini, semoga bermanfaat dan bisa digunakan sebagai pembelajaran untuk mempelajari konsep pembuatan laporan yang ada di Netbeans. 
Sekian saya Nadiya Putri Intan Nur Rahmadhani, mahasiswa semester 3 program studi sistem informasi UINSA mengucapkan terimakasih.
