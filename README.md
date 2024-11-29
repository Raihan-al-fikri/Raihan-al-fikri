Nama : Moh. Raihan Al Fikri
Nim  : 352310871
Kelas: IE.23.C12

Program Pengolah Data Nilai Akhir Mahasiswa

 Deskripsi Program
 Program ini adalah program yang dibuat mengguanakan Dictionary untuk mengolah data nilai akhir mahasiswa. Program ini
 dibuat untuk mengelola data mahasiswa termasuk menampilkan, menambah, mengubah, menghapus, dan mencari data
 nilai mereka. Program ini dibuat dengan menggunakan NIM sebagai Key dan data mahasiswa (Nama, Nilai Tugas, Nilai
 UTS, Nilai UAS) sebagai Value. Program ini menggunakan perhitungan nilai akhir dengan bobot sebesar Nilai Tugas 30%
 lalu Nilai UTS 35% dan Nilai UAS 35%

HASIL NANTTIII


Menu Program

 Program ini mempunyai beberapa menu yang akan ditampilkan di awal ketika dijalankan, diantaranya
 L: Melihat daftar nilai mahasiswa.
 T: Menambahkan data mahasiswa baru.
 U: Mengubah data mahasiswa berdasarkan NIM.
 H: Menghapus data mahasiswa berdasarkan NIM.
 C: Mencari data mahasiswa berdasarkan NIM.
 K: Keluar dari program.
 
 Fungsi Program
 1. Menghitung Nilai
  Program ini menghitung Nilai Akhir berdasarkan formula yang ada.
  
    ![Screenshot 2024-11-29 213240](https://github.com/user-attachments/assets/003811e4-e93a-40f4-925c-bead9da23540)

 2. Menampilkan Data
 Program ini menampilkan data mahasiswa dalam bentuk tabel. Apabila data di dalam program kosong maka tampilan tabel
 tersebut juga kosong.

![Screenshot 2024-11-29 213529](https://github.com/user-attachments/assets/fb4a23a1-142e-49b0-9c0b-a5d18422a2e4)

 3. Menambahkan Data
 Program ini akan meminta untuk memasukan data mahasiswa (Nama, Nilai Tugas, Nilai UTS, Nilai UAS) untuk selanjutnya
 akan dihitung menjadi data nilai akhir. Apabila program ini berhasil maka program akan menampilkan "Data berhasil
 ditambahkan!" dan program akan kembali ke menu awal.

![Screenshot 2024-11-29 213723](https://github.com/user-attachments/assets/56fd44d0-1944-49a6-b2cb-d5549b9b966b)

4. Mengubah Data
 Program ini akan meminta untuk memasukan NIM mahasiswa sebagai Key. Selanjutnya program akan meminta untuk
 memasukan data (Nama, Nilai Tugas, Nilai UTS, Nilai UAS) untuk kemudian akan diganti menjadi data yang baru. Apabila
 program ini berhasil maka program akan menampilkan "Data berhasil diubah!", namun apabila NIM yang dimasukan salah
 maka tambilan program "Data tidak ditemukan!".

![Screenshot 2024-11-29 214005](https://github.com/user-attachments/assets/e9c279eb-0053-4097-8bc4-ea4f6ca732c1)

 5. Menghapus Data
 Program ini akan meminta untuk memasukan NIM mahasiswa sebagai Key. Selanjutnya apabila program ini berhasil maka
 program akan menampilkan "Data berhasil dihapus!", namun apabila NIM yang dimasukan salah maka tambilan program
 "Data tidak ditemukan!".

![Screenshot 2024-11-29 214201](https://github.com/user-attachments/assets/247c5040-1674-4ee0-9883-3baf1b74232d)

 6. Mencari Data
 Program ini akan meminta untuk memasukan NIM mahasiswa sebagai Key. Selanjutnya apabila program ini berhasil maka
 program akan menampilkan data yang dicari, namun apabila NIM yang dimasukan salah maka tampilan program "Data tidak
 ditemukan!".

![Screenshot 2024-11-29 214519](https://github.com/user-attachments/assets/8f24cbc9-bf8c-4bc5-91a6-b426e255dbe2)

 Alur Penggunaan Program

 ![Screenshot 2024-11-29 214609](https://github.com/user-attachments/assets/993c21e3-2369-456b-9070-ec9d7f3d0f33)

  1. Menjalankan Program
 Program akan menampilkan menu ketika dijalankan.
 Ketika menu yang dipilih salah maka akan menampilkan "Pilihan tidak valid! Silakan coba lagi."

 2. Memilih Menu
 Ketik huruf sesuai pilihan menu:
 L: Melihat daftar nilai mahasiswa.
 T: Menambahkan data mahasiswa baru.
 U: Mengubah data mahasiswa berdasarkan NIM.
 H: Menghapus data mahasiswa berdasarkan NIM.
 C: Mencari data mahasiswa berdasarkan NIM.
 K: Keluar dari program.

 3. Menambahkan Data
 Pilih menu T (Tambah).
 Masukkan informasi berikut:
 NIM: Nomor Induk Mahasiswa.
 Nama: Nama mahasiswa.
 Nilai Tugas, UTS, UAS: Nilai numerik.
 Program akan otomatis menghitung nilai akhir dan menyimpan data.

 4. Melihat Data
 Pilih menu L (Lihat).
 Data akan ditampilkan dalam tabel, termasuk NIM, nama, nilai tugas, UTS, UAS, dan nilai akhir.

 5. Mengubah Data
 Pilih menu U (Ubah).
 Masukkan NIM mahasiswa yang ingin diubah.
 Jika ditemukan, masukkan data baru (nama, nilai tugas, UTS, UAS).
 Data akan diperbarui.

 6. Menghapus Data
 Pilih menu H (Hapus).
 Masukkan NIM mahasiswa yang ingin dihapus.
 Jika ditemukan, data akan dihapus dari daftar.

 7. Mencari Data
 Pilih menu C (Cari).
 Masukkan NIM mahasiswa yang dicari.
 Jika ditemukan, data akan ditampilkan.

 8. Keluar dari Program
 Pilih menu K (Keluar).
 Program akan berhenti dengan pesan terima kasih.
 Kesimpulan

 Program ini sangat cocok untuk mengelola data sederhana, seperti nilai akhir semester, dengan fitur CRUD (Create, Read,
 Update, Delete). Dengan mengikuti alur di atas, pengguna dapat dengan mudah mengelola data mahasiswa.









