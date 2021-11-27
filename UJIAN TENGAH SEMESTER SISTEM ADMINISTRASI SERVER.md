# UJIAN TENGAH SEMESTER SISTEM ADMINISTRASI SERVER

Nama	: Dinda Tresna Teja Nirwana

NIM	   : 1202190050

Kelas	 : IT 02-02

1. ### Instalasi Windows Server 2022

*Buka  Virtual Box dan create machine dan setting seperti gambar di bawah ini*

![1](https://user-images.githubusercontent.com/95134218/143684722-188364d0-b7e7-4136-9534-c8872c42810c.PNG)

*Kemudian setting memori dengan kapasitas 4GB atau 2048MB*

![2](https://user-images.githubusercontent.com/95134218/143684728-039a7eec-c8ea-4b20-a345-a2f6580b9f8b.PNG)

*Create VDI*

![4](https://user-images.githubusercontent.com/95134218/143684760-9fc86929-0a32-4d2d-a8c5-3b398c61bb52.PNG)

![5](https://user-images.githubusercontent.com/95134218/143684768-85046ec6-451a-4993-955e-8269a4eef219.PNG)

*Setting VDI dengan kapasitas 40 GB*

![6](https://user-images.githubusercontent.com/95134218/143684774-349d67b4-8fe7-4551-a65a-9249addf5a22.PNG)

*Masuk ke setting > network dan ubah NAT menjadi Bridge* Adapter

![8](https://user-images.githubusercontent.com/95134218/143684783-9da672f6-fbdb-438d-aacc-44e712ce1ff0.PNG)

*Klik start dan pilih file ISO yang sudah di download*

![9](https://user-images.githubusercontent.com/95134218/143684790-a38b4bd8-71f1-457c-b3ee-e65c7e8160b3.PNG)

*lakukan setting bahasa, waktu dan jenis keyboard*

![10](https://user-images.githubusercontent.com/95134218/143684795-1865f76c-a8a3-4a8c-88f3-ef5f106ce871.PNG)

*Kemudian klik Install Now*

![11](https://user-images.githubusercontent.com/95134218/143684797-35972371-bd8c-417c-96d2-0768954745d9.PNG)

*setelah itu pilih Windows Server 2022 Datacenter Evaluation (Desktop Experience)*

![13](https://user-images.githubusercontent.com/95134218/143684804-a269fa35-4754-46ac-9320-8e9384c61cbb.PNG)

*Klik next*

![14](https://user-images.githubusercontent.com/95134218/143684811-e74b88bd-18e1-4245-812d-c869eae20298.PNG)

Pilih Custom: Install Microsoft Server Operating System Only (advanced)

![15](https://user-images.githubusercontent.com/95134218/143684818-3e006d2f-1186-4497-a323-cebad76b64ad.PNG)

Klik Drive 0 lalu Klik Next

![16](https://user-images.githubusercontent.com/95134218/143684830-8708bb0e-06a5-426a-97c8-45a15c2b6692.PNG)

*Tunggu Proses instalasi sampai selesai*

![17](https://user-images.githubusercontent.com/95134218/143684836-db75c5ca-40bf-4793-ab8f-89854e8a52c3.PNG)

*Setelah proses install sudah selesai akan tampil seperti gambar dibawah ini*

![19](https://user-images.githubusercontent.com/95134218/143684839-9e4f5c22-1826-4610-813f-cd7a0ac39783.PNG)

*Setelah selesai buat password untuk login windows server 2022 *

![20](https://user-images.githubusercontent.com/95134218/143684852-4ae314e4-a120-4bc5-9f4c-b44a5a6cded8.png)

*Setelah selesai membuat password pergi ke input > keyboard >  insert ctrl-alt-del, lalu masukkan password yang sudah di buat tadi*

![21](https://user-images.githubusercontent.com/95134218/143684859-0358b56c-fb13-4d55-97fb-3d6e511841c2.PNG)

### 2. Instalasi Active Directory Domain Server

*Ubah nama computer di windows powershell dengan mengetik > “rename-computer -Newname Server2022”*

![22](https://user-images.githubusercontent.com/95134218/143684866-3a74b9db-2db0-4f72-9cdb-ad6c0a5e82d6.PNG)

*Kemudian masuk ke server manager pilih menu manage kemudian pilih add roles and features dan next*

![23](https://user-images.githubusercontent.com/95134218/143684872-77d04ec8-9a45-4a33-8982-ab7978d7e2eb.PNG)

*Pilih Role-Based or feature-based installation kemudian next*

![24](https://user-images.githubusercontent.com/95134218/143684878-617e0940-ed32-43f0-a31d-12bb57a0be76.PNG)

*Setelah itu pilih select a server from the server pool Lalu pilih active directory domain server*

![25](https://user-images.githubusercontent.com/95134218/143684887-bbf9bd3d-a0b7-43ed-8469-6f1a5b84ba50.PNG)

*Kemudain klik add features*

![26](https://user-images.githubusercontent.com/95134218/143684890-715c49b5-04ff-4af7-a5bd-a1188d3055fc.PNG)

*Kemudian ke features lalu centang Group Policy Management dan next*

![27](https://user-images.githubusercontent.com/95134218/143684894-4d2abec8-00de-47b5-b6c6-9cfcecf69d6f.PNG)

*Kemudian install*

![29](https://user-images.githubusercontent.com/95134218/143684901-05d2e962-6d35-4014-92bd-a814135bb17d.PNG)

*Setting ip static di cmd menggunakan command> sconfig*

![36](https://user-images.githubusercontent.com/95134218/143684905-bda28bab-27e4-45e4-b925-1122161d8923.PNG)

![37](https://user-images.githubusercontent.com/95134218/143684910-6d29e5dd-b97c-4d1c-82cb-4eb3406424dc.PNG)

![38](https://user-images.githubusercontent.com/95134218/143684914-7d823801-0665-4b47-9161-c5eedd23e355.PNG)

![39](https://user-images.githubusercontent.com/95134218/143684924-7f572685-3158-408b-ae1d-8e1e4dde37bb.PNG)

### 3. Instalasi DNS Server

*Instal DNS Server seperti yang telah dilakukan sebelumnya kemudian lanjutkan step seperti pada gambar*

![24](https://user-images.githubusercontent.com/95134218/143684933-7e5092dc-12a1-49e3-9c47-86898edff272.PNG)

![25](https://user-images.githubusercontent.com/95134218/143684944-d7b7b169-6506-4e65-b7ce-5f81a6494eb7.PNG)

![26](https://user-images.githubusercontent.com/95134218/143684951-756c5e1c-e57a-4d72-94d9-6b6d680888b4.PNG)

![31](https://user-images.githubusercontent.com/95134218/143684960-a3885bd1-a248-4c7d-a993-bbc3284eee91.PNG)

![27](https://user-images.githubusercontent.com/95134218/143684965-49c1d649-8663-4214-bd7a-3b0c8e21a198.PNG)

![33](https://user-images.githubusercontent.com/95134218/143684969-eadbb1b6-7148-4278-b423-116faa14757e.PNG)

![34](https://user-images.githubusercontent.com/95134218/143684974-9a25c2b4-2506-4659-a005-41f563e85254.PNG)

![35](https://user-images.githubusercontent.com/95134218/143684980-dacb03c2-2617-4321-b145-f402c676fc11.PNG)

### 4. Instalasi NET FRAMEWORK 3.5

![32](https://user-images.githubusercontent.com/95134218/143685000-7bd7b5a0-6464-44e9-b57c-fbe313ecc5fa.PNG)

![33](https://user-images.githubusercontent.com/95134218/143685006-3f29d58d-927a-4251-8e8c-ef2e269bd92f.PNG)

![34](https://user-images.githubusercontent.com/95134218/143685010-c91630e4-1e8c-42f7-a490-0ba9c61c0892.PNG)

![35](https://user-images.githubusercontent.com/95134218/143685014-8f449b2f-b534-42fa-87cf-10afbb23fd5d.PNG)

### 5. Promote Server  To a Domain

*Kemudian Promote Server to a Domain Controller dengan menekan tanda seru*

![41](https://user-images.githubusercontent.com/95134218/143685020-3d1513c9-70ca-43bb-9ce1-3caca55d0f15.PNG)

*Pilih add new forest dan beri nama*

![42](https://user-images.githubusercontent.com/95134218/143685023-48f4ee25-530e-49b4-93f7-d4cd708aa8f6.PNG)

*Kemudian isi Password*

![43](https://user-images.githubusercontent.com/95134218/143685031-b601a3b2-9ac9-4841-85be-897af95da018.PNG)

*Klik Next*

![44](https://user-images.githubusercontent.com/95134218/143685037-9312c956-e13f-4eb9-a052-7d98e1598011.PNG)

![46](https://user-images.githubusercontent.com/95134218/143685042-e89efaef-f887-4c78-91a0-ddaa0e508e4f.PNG)

![47](https://user-images.githubusercontent.com/95134218/143685049-ca3259d3-7bdf-49bd-a78f-658f37e6adc0.PNG)

*Kemudian Install*

![48](https://user-images.githubusercontent.com/95134218/143685052-097b2469-c651-45c9-91da-15de4ac7ec1e.PNG)

*Setelah close Windows Server akan restart dan akan berganti nama*

![50](https://user-images.githubusercontent.com/95134218/143685059-7ec72e64-6a94-4a92-b702-972ffa43477c.PNG)

*Lakukan pengecekan konfigurasi pada command prompt untuk mengetahui kesuksesan installasi*

![35](https://user-images.githubusercontent.com/95134218/143685069-d8574cf7-3a56-4de7-8e90-ecfe2aeb01d5.PNG)

*Kemudian cek ip address di network*

![36](https://user-images.githubusercontent.com/95134218/143685074-b8680bef-81ad-4f10-bb88-8c9bf8356a82.PNG)
