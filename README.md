# labspy03
Tugas Praktikum 3

Nama : Rosa Putri Eka Yetsi

Kelas : IE.23.C12

NIM : 352310841


LATIHAN 1

Perintah :

1. Tampilkan nilai n bilangan acak yang lebih kecil dari 0.5

2. Nilai n diisi saat run time

3. Menggunakan while atau for

4. Menggunakan fungsi random

Hasil program yang dibuat :
<img width="960" alt="image" src="https://github.com/user-attachments/assets/b81a095f-eeb0-49f6-9646-c2eb655f5258">

Algoritma dan penjelasan :

1. Buat program terlebih dahulu menggunakan Idle

2. Saat membuat program, yang pertama kita buat sistem input terlebih dahulu agar kita bisa menginput suatu bilangan saat di runtime dengan rumus n = int(input("Masukkan jumlah bilangan acak yang ingin ditampilkan: "))

3. Selanjutnya inisialisasi variabel untuk menghitung jumlah bilangan yang telah ditampilkan dengan rumus count = 0

4. Lalu kita akan Menggunakan while untuk terus menghasilkan bilangan acak sampai mencapai n, dengan rumus while count < n:

5. Setelah itu kita akan menghasilkan bilangan acak dengan a = random()

6. Terakhir, periksa apakah bilangan acak kurang dari 0.5, rumus: if a < 0.5: count += 1 # Menambah hitungan bilangan yang ditampilkan print(f"Data ke : {count} => {a}")

7. Selesai


LATIHAN 2 

Intruksi : 

Buat program untuk menampilkan bilangan terbesar dari n buah data yang diinputkan. Masukkan angka 0 untuk berhenti.

Hasil program yang dibuat :

<img width="960" alt="image" src="https://github.com/user-attachments/assets/499daf0d-6641-4c79-a71e-a4bc468cf8d5">

Algoritma dan penjelasan

1. Buat program terlebih dahulu menggunakan Idle

2. Buat Inisialisasi variabel untuk menyimpan bilangan terbesar dengan rumus max_number = None

3. Lalu buat while true : Mengambil input dari pengguna,

4. Periksa apakah pengguna memasukkan 0, Memperbarui bilangan terbesar jika diperlukan

5. Selanjutnya kita akan menampilkan bilangan terbesarnya dengan rumus, if max_number is not None: print("Bilangan terbesar adalah:", max_number) else: ("Tidak ada angka yang dimasukkan.")

6. Selesai


PROGRAM 1 

Intruksi : 

Seorang pengusaha menginvestasikan uangnya untuk memulai usahanya dengan modal awal 100 juta, pada bulan pertama dan kedua belum mendapatkan laba. pada bulan ketiga baru mulai mendapatkan laba sebesar 1% dan pada bulan ke 5, pendapatan meningkat 5%, selanjutnya pada bulan ke 8 mengalami penurunan keuntungan sebesar 2%, sehingga laba menjadi 3%. Hitung total keuntungan selama 8 bulan berjalan usahanya.

Hasil program yang dibuat :

<img width="960" alt="image" src="https://github.com/user-attachments/assets/5ad6f9bf-9507-420a-b9f3-cc1ea4d920d0">

Algoritma dan penjelasan :

1. Buat program terlebih dahulu menggunakan Idle

2. Buat print modal awal,rumus :modal_awal = 100_000_000

3. Lalu buat nisialisasi list untuk menyimpan laba setiap bulan dengan menggunakan statement for, in, If, elif

4. Hitung total laba dengan rumus SUM

5. Menampilkan hasil dengan rumus For 1 in
  
6. Selesai
