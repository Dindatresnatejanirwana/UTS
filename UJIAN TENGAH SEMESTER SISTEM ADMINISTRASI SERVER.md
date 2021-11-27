# UJIAN TENGAH SEMESTER SISTEM ADMINISTRASI SERVER

Nama	: Dinda Tresna Teja Nirwana

NIM	   : 1202190050

Kelas	 : IT 02-02

1. ### Instalasi Windows Server 2022

*Buka  Virtual Box dan create machine dan setting seperti gambar di bawah ini*

![](C:\Users\Lenovo\Pictures\sas uts\1.PNG)

*Kemudian setting memori dengan kapasitas 4GB atau 2048MB*

![](C:\Users\Lenovo\Pictures\sas uts\2.PNG)

*Create VDI*

![](C:\Users\Lenovo\Pictures\sas uts\4.PNG)

![](C:\Users\Lenovo\Pictures\sas uts\5.PNG)

*Setting VDI dengan kapasitas 40 GB*

![](C:\Users\Lenovo\Pictures\sas uts\6.PNG)

*Masuk ke setting > network dan ubah NAT menjadi Bridge* Adapter

![](C:\Users\Lenovo\Pictures\sas uts\8.PNG)

*Klik start dan pilih file ISO yang sudah di download*

![](C:\Users\Lenovo\Pictures\sas uts\9.PNG)

*lakukan setting bahasa, waktu dan jenis keyboard*

![](C:\Users\Lenovo\Pictures\sas uts\10.PNG)

*Kemudian klik Install Now*

![](C:\Users\Lenovo\Pictures\sas uts\11.PNG)

*setelah itu pilih Windows Server 2022 Datacenter Evaluation (Desktop Experience)*

![](C:\Users\Lenovo\Pictures\sas uts\13.PNG)

*Klik next*

![](C:\Users\Lenovo\Pictures\sas uts\14.PNG)

Pilih Custom: Install Microsoft Server Operating System Only (advanced)

![](C:\Users\Lenovo\Pictures\sas uts\15.PNG)

Klik Drive 0 lalu Klik Next

![](C:\Users\Lenovo\Pictures\sas uts\16.PNG)

*Tunggu Proses instalasi sampai selesai*

![](C:\Users\Lenovo\Pictures\sas uts\17.PNG)

*Setelah proses install sudah selesai akan tampil seperti gambar dibawah ini*

![](C:\Users\Lenovo\Pictures\sas uts\19.PNG)

*Setelah selesai buat password untuk login windows server 2022 *

![](C:\Users\Lenovo\Pictures\sas uts\20.png)

*Setelah selesai membuat password pergi ke input > keyboard >  insert ctrl-alt-del, lalu masukkan password yang sudah di buat tadi*

![](C:\Users\Lenovo\Pictures\sas uts\21.PNG)

### 2. Instalasi Active Directory Domain Server

*Ubah nama computer di windows powershell dengan mengetik > “rename-computer -Newname Server2022”*

![](C:\Users\Lenovo\Pictures\sas uts\22.PNG)

*Kemudian masuk ke server manager pilih menu manage kemudian pilih add roles and features dan next*

![](C:\Users\Lenovo\Pictures\sas uts\23.PNG)

*Pilih Role-Based or feature-based installation kemudian next*

![](C:\Users\Lenovo\Pictures\sas uts\24.PNG)

*Setelah itu pilih select a server from the server pool Lalu pilih active directory domain server*

![](C:\Users\Lenovo\Pictures\sas uts\25.PNG)

*Kemudain klik add features*

![](C:\Users\Lenovo\Pictures\sas uts\26.PNG)

*Kemudian ke features lalu centang Group Policy Management dan next*

![](C:\Users\Lenovo\Pictures\sas uts\27.PNG)

*Kemudian install*

![](C:\Users\Lenovo\Pictures\sas uts\29.PNG)

*Setting ip static di cmd menggunakan command> sconfig*

![](C:\Users\Lenovo\Pictures\sas uts\36.PNG)

![](C:\Users\Lenovo\Pictures\sas uts\37.PNG)

![](C:\Users\Lenovo\Pictures\sas uts\38.PNG)

![](C:\Users\Lenovo\Pictures\sas uts\39.PNG)

### 3. Instalasi DNS Server

*Instal DNS Server seperti yang telah dilakukan sebelumnya kemudian lanjutkan step seperti pada gambar*

![](C:\Users\Lenovo\Pictures\sas uts\24.PNG)

![](C:\Users\Lenovo\Pictures\sas uts\25.PNG)

![](C:\Users\Lenovo\Pictures\sas uts\26.PNG)

![](C:\Users\Lenovo\Pictures\sas uts\31.PNG)

![](C:\Users\Lenovo\Pictures\sas uts\27.PNG)

![](C:\Users\Lenovo\Pictures\sas uts\33.PNG)

![](C:\Users\Lenovo\Pictures\sas uts\34.PNG)

![](C:\Users\Lenovo\Pictures\sas uts\35.PNG)

### 4. Instalasi NET FRAMEWORK 3.5

![](C:\Users\Lenovo\Pictures\sas uts\32.PNG)

![](C:\Users\Lenovo\Pictures\sas uts\33.PNG)

![](C:\Users\Lenovo\Pictures\sas uts\34.PNG)

![](C:\Users\Lenovo\Pictures\sas uts\35.PNG)

### 5. Promote Server  To a Domain

*Kemudian Promote Server to a Domain Controller dengan menekan tanda seru*

![](C:\Users\Lenovo\Pictures\sas uts\41.PNG)

*Pilih add new forest dan beri nama*

![](C:\Users\Lenovo\Pictures\sas uts\42.PNG)

*Kemudian isi Password*

![](C:\Users\Lenovo\Pictures\sas uts\43.PNG)

*Klik Next*

![](C:\Users\Lenovo\Pictures\sas uts\44.PNG)

![](C:\Users\Lenovo\Pictures\sas uts\46.PNG)

![](C:\Users\Lenovo\Pictures\sas uts\47.PNG)

*Kemudian Install*

![](C:\Users\Lenovo\Pictures\sas uts\48.PNG)

*Setelah close Windows Server akan restart dan akan berganti nama*

![](C:\Users\Lenovo\Pictures\sas uts\50.PNG)

*Lakukan pengecekan konfigurasi pada command prompt untuk mengetahui kesuksesan installasi*

![](C:\Users\Lenovo\Pictures\sas uts\Screenshot (35).png)

*Kemudian cek ip address di network*

![](C:\Users\Lenovo\Pictures\sas uts\Screenshot (36).png)