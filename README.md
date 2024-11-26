# PBO_UAS

Berikut saya akan memaparkan hasil dari UAS matkkul PBO yang memiliki porgram CRUD dengan Persistence

- Pertama buat project baru dengan nama PBO_UAS dengan menekan tombol diatas ini
  ![image](https://github.com/user-attachments/assets/08aca2a8-2963-404b-97c6-058f4972946d)
  ![image](https://github.com/user-attachments/assets/1a34dfac-605f-47f9-9a51-15665c63310c)

- Tambahkan Library dengan link berikut
  Yakni dengan library Utama = Jasper Report, Groovy dan beberapa library tambahan yang akan saya share juga di repository ini
  ![image](https://github.com/user-attachments/assets/e63c68ea-b8cc-49cf-9f07-df8a34aae0b8)

- Buat database dengan dengan query sebagai berikut
  ````sql
  CREATE TABLE Mahasiswa (
  Nim VARCHAR(12) PRIMARY KEY,
  Nama VARCHAR(20) NOT NULL,
  Alamat VARCHAR(100) NOT NULL,
  AsalSMA VARCHAR(50) NOT NULL,
	NamaOrtu VARCHAR(20) NOT NULL 
  );
  CREATE TABLE Pengguna (
  Username VARCHAR(20) PRIMARY KEY,
  Password VARCHAR(20) NOT NULL
  );

- Buat koneksi di Java Netbeans di Services
  ![image](https://github.com/user-attachments/assets/e4e98a0b-d207-42f9-9aeb-2e94fba95e0b)


- Setelah itu tambahkan entity classes from database
  ![image](https://github.com/user-attachments/assets/257b0e25-4f4c-481a-a36d-c1ad7c0b18a6)
  ![image](https://github.com/user-attachments/assets/5fc16197-e81e-45b3-bd00-aec917755739)


- Setelah itu buat frame baru untuk Mahasiswa
  ![image](https://github.com/user-attachments/assets/d02efc88-c4d7-4824-bf13-7ca7b9af3c83)

- buat desain seperti ini
  ![image](https://github.com/user-attachments/assets/7a0e0cd8-ecfb-478b-9b00-6187ae74c950)


- Masukkan kode seperti yang ada di repositori ini
- Buat File jasper dengan cara
  ![image](https://github.com/user-attachments/assets/ecf89440-65a2-4c33-a1c6-26a901f43b40)
  ![image](https://github.com/user-attachments/assets/243a9d78-73a5-43a5-9648-b9c5583c0cf1)


- Masukkan query seuai dengan kebutuhan dan klik finish, sehingga muncul file
  ![image](https://github.com/user-attachments/assets/fccece37-8bfa-472a-9fdc-df4d0f0b8c27)

- Lakukan desain dan jika sudah lakukann preview untuk melihat hasil
  ![image](https://github.com/user-attachments/assets/53872a37-e60b-4421-8edc-5b60f9b3713f)

- Maka otomatis akan ada file baru
  ![image](https://github.com/user-attachments/assets/dab69fd3-5c7e-4ef6-8619-ad7f67f03b0d)

- Buat Frame SignIN dan SignUp untuk Login
  ![image](https://github.com/user-attachments/assets/e66fcf7a-80e3-4ae9-906f-7f7bd3e1f8a2)
  ![image](https://github.com/user-attachments/assets/6f382c79-dbd9-47f0-bb98-3813b1abc8c4)
  ![image](https://github.com/user-attachments/assets/b656a739-763e-4f81-8dba-42667f59f71a)



- Masukkan kode pada button yang telah dibuat seperti yang telah saya bagikan di repository ini
- Lakukan Clean and Build Porject lalu jalankan
  ![image](https://github.com/user-attachments/assets/68882f76-682f-4747-8b16-9b45c660591c)
  ![image](https://github.com/user-attachments/assets/dc657057-8a88-4157-8ae0-53ede55ba46d)
  ![image](https://github.com/user-attachments/assets/7de96775-7ee7-48fa-a43a-0992c720ee8d)

