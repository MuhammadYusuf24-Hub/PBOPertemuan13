# PBOPertemuan13
Dalam proses pengembangan perangkat lunak, sistem login merupakan komponen dasar yang berfungsi untuk mengontrol akses pengguna terhadap suatu aplikasi. Dengan adanya sistem login, hanya pengguna yang terdaftar dan memiliki kredensial yang valid yang dapat mengakses fitur-fitur tertentu.  

Pada praktikum ini dibuat sebuah aplikasi Login Form menggunakan Java Swing di NetBeans IDE dengan koneksi ke database MySQL melalui Java Persistence API (JPA). JPA memudahkan pengembang dalam melakukan operasi CRUD (Create, Read, Update, Delete) terhadap database tanpa perlu menulis banyak perintah SQL secara manual, karena seluruh proses interaksi data dikelola melalui entity class dan EntityManager.  

Aplikasi ini tidak hanya menyediakan fitur login dan registrasi pengguna, tetapi juga lupa password (forgot password) dan reset password untuk meningkatkan keamanan dan kemudahan pengguna.  

1.	Mempelajari cara membuat form login berbasis Java Swing.  
2.	Menerapkan Java Persistence API (JPA) untuk menghubungkan aplikasi dengan database MySQL.  
3.	Membuat entity class untuk merepresentasikan tabel database dalam bentuk objek Java.  
4.	Membuat fitur login, register, forgot password, dan reset password dengan transaksi JPA.  
5.	Melatih kemampuan memahami konsep EntityManager, Persistence Unit, dan ORM (Object Relational Mapping).  

# Langkah – Langkah Project
1.	Buat table login pada database seperti berikut  
 <img width="648" height="319" alt="image" src="https://github.com/user-attachments/assets/3e6e8fea-96a2-4c29-aa68-8f7d47873ad4" />  

2.	Buka neatbeans dan buat project baru   
3.	Kemudian buat koneksi persistence untuk menghubungkan ke postgre   
4.	Buat 4 jframe form, untuk login, register, forgot password, dan reset password  
5.	Kemudian design ke empat jframe form nya  
Login :  
 <img width="468" height="420" alt="image" src="https://github.com/user-attachments/assets/6270c763-9751-4cc5-893e-ce630ac52423" />  

Register :  
 <img width="460" height="370" alt="image" src="https://github.com/user-attachments/assets/2f67e1c8-1974-4c79-a4ab-201698f99519" />  

Forgor Password :  
 <img width="519" height="361" alt="image" src="https://github.com/user-attachments/assets/f5048f7d-0373-4a09-bd11-302c36a118e8" />  

Reset Password :  
 <img width="497" height="469" alt="image" src="https://github.com/user-attachments/assets/99511050-cd30-4961-b12a-c2ce45634502" />  

6.	Pada bagian Login agar tulissan “Forgot password” dan “Belum Punya Akun” bisa di klik lakukan cara ini   
 <img width="654" height="402" alt="image" src="https://github.com/user-attachments/assets/8a57dbdd-ab59-4165-a801-42b34bf51387" />  

Setelah itu tambahkan source code berikut pada masing masing tulisan  
 <img width="563" height="254" alt="image" src="https://github.com/user-attachments/assets/a202f545-bc3e-4bbe-a7b2-726d983f955c" />  

7.	Kemudian ketik source code berikut untuk setiap jframe  
Login :  
 <img width="734" height="386" alt="image" src="https://github.com/user-attachments/assets/6d363102-7930-4845-bfa1-8ada003f1960" />  

Register :  
 <img width="800" height="596" alt="image" src="https://github.com/user-attachments/assets/a601d913-6120-4866-b926-916ab78e0150" />  

Forgot Password :  
 <img width="808" height="510" alt="image" src="https://github.com/user-attachments/assets/ec124f70-7ef0-44cd-b647-615b31839c88" />  


Reset Password :  
 <img width="888" height="652" alt="image" src="https://github.com/user-attachments/assets/88ffc636-26d3-4826-ab15-d82486f94795" />  
 <img width="715" height="112" alt="image" src="https://github.com/user-attachments/assets/0afdf911-1344-418a-b06c-e4efd0c800b9" />  

Tambah variable dan parameter berikut  
 <img width="280" height="36" alt="image" src="https://github.com/user-attachments/assets/e430c1d6-f430-406a-b60e-b487a0eb8e5a" />  
 <img width="492" height="161" alt="image" src="https://github.com/user-attachments/assets/935a4715-ea61-48c2-b7d4-21188656f214" />  

8.	Import berikut pada setiap class jframe form  
<img width="369" height="81" alt="image" src="https://github.com/user-attachments/assets/e5eae411-ce95-49b4-94b1-2b1c00cf3243" />  

9.	Tambahkan library berikut  
 <img width="494" height="97" alt="image" src="https://github.com/user-attachments/assets/7c846881-96a3-4ae4-b913-c0177e6827c7" />  

10.	Ketika selesai coba jalankan program yang telah dibuat   

