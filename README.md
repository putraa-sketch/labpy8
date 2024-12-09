# TUGAS PRAKTIKUM 8
# Data Diri

Nama : Abdi Putra Perdana

NIM : 312410426

Kelas : TI 24.A3

# Flowchart 

![image](https://github.com/user-attachments/assets/073701cf-fdd5-46c9-ab90-38e8f8cd7a9c)


# diagram class

![image](https://github.com/user-attachments/assets/b296df38-98a5-446d-8724-134d10b9d7bb)

# input dan output dari Praktikum 8

## 1. input tambah data 

![code12](https://github.com/user-attachments/assets/6b33cb85-44b1-4ff5-9f2a-84a4a117ac31)


## output tambah data 

<img width="416" alt="image" src="https://github.com/user-attachments/assets/7bc4fdee-ecc1-426a-9081-6b7fe7758c0b">

1. Metode `__init__()`:
   - Inisialisasi kelas dengan membuat list kosong `student_grades` untuk menyimpan data mahasiswa

2. Metode `tambah(name, grade)`:
   - Menambahkan data mahasiswa baru ke dalam list
   - Menerima parameter nama dan nilai mahasiswa
   - Menambahkan data sebagai dictionary ke `student_grades`
   - Mencetak pesan konfirmasi penambahan data

3. Metode `tampilkan()`:
   - Menampilkan seluruh daftar mahasiswa
   - Jika list kosong, mencetak pesan "Tidak ada data mahasiswa"
   - Jika ada data, mencetak nama dan nilai setiap mahasiswa

4. Metode `hapus(name)`:
   - Menghapus data mahasiswa berdasarkan nama
   - Mencari mahasiswa dengan nama yang sesuai
   - Jika ditemukan, menghapus data dan mencetak konfirmasi
   - Jika tidak ditemukan, mencetak pesan bahwa data tidak ada

5. Metode `ubah(name, new_grade)`:
   - Mengubah nilai mahasiswa berdasarkan nama
   - Mencari mahasiswa dengan nama yang sesuai
   - Jika ditemukan, mengupdate nilai dan mencetak konfirmasi perubahan
   - Jika tidak ditemukan, mencetak pesan bahwa data tidak ada

Contoh penggunaan di akhir code menunjukkan:
- Membuat objek `grade_list`
- Menambahkan dua mahasiswa
- Menampilkan daftar
- Mengubah nilai Abdi Putra Perdana
- Menghapus data Putra Abdi
- Menampilkan daftar terakhir


