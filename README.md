# Latihan5
Buat program sederhana yang akan menampilkan daftar nilai mahasiswa, dengan ketentuan :
* Program dibuat dengan menggunakan Dictionary
* Tampilkan menu pilihan: (Tambah Data, Ubah Data, Hapus Data, Tampilkan Data, Cari Data)
* Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%, uts: 35%, uas: 35%)
* Buat flowchart dan penjelasan programnya pada README.md.
* Commit dan push repository ke github.

# Flowchart

![Drawing5](https://user-images.githubusercontent.com/57052780/71552232-844fbd00-2a2b-11ea-86b6-4efd5c56e53e.jpeg)

# Penjelasan
1. daftar = {} Berikut adalah dictionary yang di definisikan terlebih dahulu.
2. while True: Berikut adalah perulangan yang digunakan.
3. Keluar
* if perintah.lower() == 'k':
* Perulangan di atas adalah perulangan yang akan berjalan terus menerus, dan akan berhenti jika kode berikut di eksekusi.

**Output**

![Latihan5_1](https://user-images.githubusercontent.com/57052780/71554461-02bf5580-2a52-11ea-9a62-5d9a9ab832b6.png)

4. Jika k di input dan lower() digunakan untuk mengkonversi input yang dimasukan ke bentuk lower case dan Input k digunakan berdasarkan perintah yang sudah di masukan dalam keterangan pada fungsi input di bawah ini :

![Latihan5_2](https://user-images.githubusercontent.com/57052780/71554575-6f871f80-2a53-11ea-97ef-c43a118d6475.png)

**Output**

![Latihan5_3](https://user-images.githubusercontent.com/57052780/71554607-da385b00-2a53-11ea-82de-be8c0c4d8f59.png)

5. Input data
* berikut digunakan untuk melakukan input data seperti Nama, NIM, Nilai Tugas, UTS dan UAS :

![Latihan5_4](https://user-images.githubusercontent.com/57052780/71554632-5c288400-2a54-11ea-89c9-9df718b0d03a.png)

* Untuk nilai akhir n_akhir, di buat berdasarkan operasi dari variabel n_tugas, n_UTS dan n_UAS yang mewakili Nilai Tugas, UTS dan UAS.

**Output**

![Latihan5_5](https://user-images.githubusercontent.com/57052780/71554658-d8bb6280-2a54-11ea-9cfc-9f33f2d8f24e.png)

6. Melihat Data
* Selanjutnya adalah kode yang digunakan untuk melihat input yang sudah dimasukan :

![Latihan5_6](https://user-images.githubusercontent.com/57052780/71554700-597a5e80-2a55-11ea-8916-9ba6f0fc9fe7.png)

* Data dalam perulangan for di ambil dari variabel dictionary daftar pada bagian value yang berbentuk list. variabel no diguanakan untuk membuat nomor. Data yang akan ditampilkan adalah Nama, NIM, Nilai Tugas, UTS, UAS, dan Nilai Akhir.

![Latihan5_7](https://user-images.githubusercontent.com/57052780/71554740-fd640a00-2a55-11ea-8654-a9b04522f5c6.png)

7. Mengubah data
* Perintah dijalankan jika input yang di masukan adalah u, di dalam kondisi ini terdapat input dan kondisi, dimana jika input nama ada di dalam variabel daftar.keys maka akan muncul beberapa pilihan untuk mengubah semua data atau data tertentu saja.

* Selanjutnya adalah kode yang digunakan untuk menggubah input yang sudah dimasukan :

![Latihan5_8](https://user-images.githubusercontent.com/57052780/71554789-a90d5a00-2a56-11ea-8d18-0bbfd3f7ca5f.png)

* Berikut kondisi yang digunakan untuk memasukan pilihan: 

![Latihan5_9](https://user-images.githubusercontent.com/57052780/71554862-65ffb680-2a57-11ea-9c71-1450213ce8d8.png)

**Output**

![Latihan5_10](https://user-images.githubusercontent.com/57052780/71554890-aeb76f80-2a57-11ea-8a0e-382adf10cca9.png)

8. Mencari Data
* Perbandingan untuk mencari data yang akan diubah sama seperti cara mengubah data, hanya saja perintah ini digunakan untuk menampilkan data yang di input berdasarkan nama.

* Berikut bagaimana mencari data yang sudah di inputkan sebelumnya :

![Latihan5_11](https://user-images.githubusercontent.com/57052780/71554969-5e8cdd00-2a58-11ea-8448-f5aab79b2858.png)

**Output**
