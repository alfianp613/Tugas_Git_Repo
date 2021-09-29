# Tugas Laporan Git Repository

## Nama : Muhammad Alfian Pratama

## NIM : 162012133037

Lakukan inisialisasi repositori menggunakan Git (CLI) dan buat clonenya di Github. Lalu lakukan first commit berupa Readme.md dan isi dengan Tugas laporan ini. Dokumentasikan setiap langkah dan jelaskan tiap langkah dalam bentuk laporan.

**Jawab:**

1. Pertama buatlah folder baru terlebih dahulu, disini saya akan membuat folder baru dengan nama "Repo_1".

   ![image](https://user-images.githubusercontent.com/72260807/135118997-b461ed79-6429-47f8-b9a0-3058ddd54c34.png)
   ![image](https://user-images.githubusercontent.com/72260807/135119033-1819654a-6821-4207-ae76-a2c55ee67822.png)

2. Buka folder baru tersebut. Lalu, ketik "cmd" di bagian path folder tersebut seperti pada gambar dan klik Enter pada keyboard.

   ![image](https://user-images.githubusercontent.com/72260807/135119227-fe613c85-633a-4bc1-9af1-c797f5da92b5.png)
   
   Maka, aplikasi cmd akan terbuka pada path file yang sudah kita buat.
   
   ![image](https://user-images.githubusercontent.com/72260807/135119429-08dad690-cda8-4610-bcd0-79af79cb5278.png)

3. Buatlah file README.md berisi teks "First Commit" dengan command “echo “First Commit” >>  README.md” seperti pada gambar dibawah.

   ![image](https://user-images.githubusercontent.com/72260807/135119710-8a336793-a69a-4791-a509-70c3c116b7e8.png)

4. Ketik "git init" untuk membuat local git repository pada folder “Repo_1”.

   ![image](https://user-images.githubusercontent.com/72260807/135120257-12d42c17-f3c4-4b30-8a31-63aef11e5384.png)

5. Ketik "git add README.md" untuk menambahkan file README.md ke staging area.

   ![image](https://user-images.githubusercontent.com/72260807/135120505-e2a18b13-21db-46b9-94a4-90708f5c669b.png)

6. Ketik "git commit -m "First Commit" untuk memindahkan file yang saat ini berada di staging area untuk masuk ke repository dan git akan mencatat perubahan yang dimasukan ke repository-nya dengan diberi pesan "First Commit".

   ![image](https://user-images.githubusercontent.com/72260807/135120894-75021e8e-2a79-4467-ac2d-79cf599884d5.png)

7. Setelah local git repository kita selesai dibuat, sekarang kita akan beralih ke ![Github](https://github.com) untuk menyiapkan repository. Setelah web ![Github](https://github.com) sudah terbuka, klik new repository seperti pada gambar.

   ![image](https://user-images.githubusercontent.com/72260807/135121574-0ff50f89-9f4e-43e4-a388-a3daeca32b00.png)

8. Setelah itu, tampilan akan berubah seperti pada gambar. Lalu, kita masukkan nama repository-nya disini saya beri nama "Tugas_Git_Repo" dengan visibility "Public" yang berarti semua orang bisa mengakses repository ini, lalu klik "create repository".

   ![image](https://user-images.githubusercontent.com/72260807/135121711-4184c524-c824-4c4c-9f12-931f3a56ba0b.png)

9. Setelah repository selesai dibuat maka tampilan akan berubah seperti pada gambar. Setelah itu, kita kembali ke cmd untuk melakukan push ke repository kita di ![Github](https://github.com).

   ![image](https://user-images.githubusercontent.com/72260807/135122255-952943e9-24c5-4804-95a3-6dd31e6f9397.png)

10. Ketik "git branch -M main" untuk membuat branch baru dengan nama "main".

    ![image](https://user-images.githubusercontent.com/72260807/135122485-5dfa55fc-0612-4843-bea8-f4a1d9851297.png)

11. Ketik "git remote add origin https://github.com/alfianp613/Tugas_Git_Repo.git" untuk memilih target repository kita yang ada di ![Github](https://github.com).

    ![image](https://user-images.githubusercontent.com/72260807/135122941-8b0584f0-fa22-4d2b-b132-54e29e9d3b26.png)

12. Ketik "git push -u origin main" untuk melakukan push local git repository ke Github repository yang sudah dibuat sebelumnya. Apabila belum pernah melakukan proses ini, maka kita akan diperintahkan untuk login ke akun Github kita terlebih dahulu untuk melakukan autentik.

    ![image](https://user-images.githubusercontent.com/72260807/135123059-eae5e82e-7b58-4e53-b093-f5da59f11240.png)

13. Setelah itu, kita kembali ke ![github](https://github.com). Lalu klik refresh ada browser.

    ![image](https://user-images.githubusercontent.com/72260807/135123416-4b0e0e71-d35c-4ab4-a65f-956f607ccaae.png)

14. Apabila tampilan sudah seperti pada gambar artinya local git repository kita telah berhasil di-clone ke Github repository.

    ![image](https://user-images.githubusercontent.com/72260807/135123581-5cd8883a-4be0-4c50-a591-dce9bbe55d5e.png)


Link Repository : https://github.com/alfianp613/Tugas_Git_Repo 
