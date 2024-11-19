# labpy04

Nama: Ica Rizqiah

Kelas: TI.24.A.5

Nim: 312410554

Mata kuliah: Bahasa Pemograman

# Berikut Flowchartnya

![foto](https://github.com/keeyyaaa/labpy04/blob/main/flowchart.png?raw=true)

# Penjelasan code program

## 1. Inisialisasi List untuk Menyimpan Data:

Di sini, kita membuat sebuah list kosong yang akan digunakan untuk menyimpan data siswa, termasuk nama, NIM, nilai tugas, UTS, UAS, dan nilai akhir.

## 2. Fungsi untuk Menghitung Nilai Akhir:

Fungsi ini menerima tiga parameter: tugas, uts, dan uas. Fungsi ini menghitung nilai akhir berdasarkan bobot yang telah ditentukan:

Nilai tugas memiliki bobot 30%
Nilai UTS memiliki bobot 35%
Nilai UAS memiliki bobot 35% Fungsi ini kemudian mengembalikan nilai akhir sebagai hasil dari perhitungan tersebut.

## 3. Loop untuk Meminta Input Data:

Program ini menggunakan loop while True untuk terus meminta input dari pengguna sampai pengguna memutuskan untuk berhenti. Di dalam loop, program meminta pengguna untuk memasukkan data siswa.

## 4. Meminta Input dari Pengguna:

Di sini, program meminta pengguna untuk memasukkan:

Nama siswa
NIM siswa
Nilai tugas
Nilai UTS
Nilai UAS Nilai tugas, UTS, dan UAS diubah menjadi tipe data float untuk memungkinkan perhitungan desimal.

## 5. Menyimpan Data ke dalam List:

Setelah semua data diambil, program menyimpan data dalam bentuk dictionary (kamus) ke dalam list data_nilai. Setiap dictionary berisi nama, NIM, nilai tugas, UTS, UAS, dan nilai akhir yang dihitung menggunakan fungsi hitung_nilai_akhir.

## 6. Menanyakan Apakah Pengguna Ingin Menambah Data Lagi:

Program menanyakan kepada pengguna apakah mereka ingin menambah data siswa lainnya. Jika pengguna memasukkan 't' (tidak), loop akan berhenti.

## 7. Menampilkan Tabel Data Siswa:

Setelah pengguna selesai memasukkan data, program mencetak header tabel yang menunjukkan kolom untuk nama, NIM, nilai tugas, UTS, UAS, dan nilai akhir. Garis pemisah (=) digunakan untuk memperjelas tampilan tabel.

## 8. Menampilkan Setiap Data dalam Format Tabel:

Program ini melakukan iterasi melalui setiap dictionary dalam list data_nilai dan mencetak data siswa dalam format tabel. Format spesifikasi digunakan untuk memastikan bahwa setiap kolom memiliki lebar yang konsisten:

<20, <15, <10, dan <15.2f digunakan untuk mengatur lebar kolom dan format angka desimal.

# berikut code programnya

![foto](

![foto](

# berikut hasil code programnya
![foto](

