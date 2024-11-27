# Program Daftar Nilai Mahasiswa Menggunakan Dictionary
Perintah program menggunakan python dengan tampilan perintah sebagai berikut :

![Screenshot 2024-11-27 142438](https://github.com/user-attachments/assets/3cc13239-9daf-4c74-ada4-72211b7440da)

![Screenshot 2024-11-27 142529](https://github.com/user-attachments/assets/668b0df5-b33b-4daf-bb24-d9e98fb24d26)

![Screenshot 2024-11-27 142558](https://github.com/user-attachments/assets/3af453f5-3b30-423f-94a4-d41aad50eb25)

## Fungsi Utama

### `Hitung_nilai_akhir(nilai_tugas, nilai_uts, nilai_uas)`
- **Deskripsi**: Menghitung nilai akhir mahasiswa berdasarkan komponen nilai.
- **Parameter**:
  - `nilai_tugas`: Nilai tugas mahasiswa.
  - `nilai_uts`: Nilai UTS mahasiswa.
  - `nilai_uas`: Nilai UAS mahasiswa.
- **Rumus**:

  ![386917277-21ff5d05-c762-4684-abff-8379a6247b5a](https://github.com/user-attachments/assets/82a8e7d1-493b-4c67-8ba8-e4e095ed4962)

- **Return**: Mengembalikan nilai akhir yang telah dihitung.

## Struktur Data

### Dictionary `data_mahasiswa`
- **Kunci**: NIM mahasiswa.
- **Nilai**: Dictionary yang berisi:
  - `nama`: Nama mahasiswa.
  - `nilai_tugas`: Nilai tugas.
  - `nilai_uts`: Nilai UTS.
  - `nilai_uas`: Nilai UAS.
  - `nilai_akhir`: Nilai akhir yang dihitung.

## Daftar Menu

Pengguna diberikan pilihan untuk melakukan operasi berikut:

1. **L. Lihat Data**
   - Menampilkan seluruh data mahasiswa dalam format tabel.

2. **T. Tambah Data**
   - Meminta input dari pengguna untuk menambahkan data mahasiswa baru, termasuk nama, NIM, nilai tugas, nilai UTS, dan nilai UAS. Data yang dimasukkan akan dihitung nilai akhirnya dan disimpan.

3. **U. Ubah Data**
   - Meminta NIM mahasiswa yang ingin diubah. Jika data ditemukan, pengguna dapat memperbarui nilai tugas, UTS, dan UAS. Nilai akhir akan diperbarui sesuai dengan perubahan.

4. **H. Hapus Data**
   - Meminta NIM mahasiswa yang ingin dihapus. Jika data ditemukan, maka data mahasiswa tersebut akan dihapus dari daftar.

5. **C. Cari Data**
   - Meminta NIM mahasiswa yang ingin dicari. Jika data ditemukan, program akan menampilkan informasi mahasiswa tersebut.

6. **K. Keluar**
   - Mengakhiri program.

## Tampilan Program

![Screenshot 2024-11-27 143036](https://github.com/user-attachments/assets/5b02f1cd-bad4-4736-b49f-6d2d5491bd57)

![Screenshot 2024-11-27 143048](https://github.com/user-attachments/assets/e1d60273-4e5e-45f6-94d0-141512bd63ea)


Berikut adalah contoh interaksi pengguna dengan program:
1. Start: Titik awal program.
2. Inisialisasi Dictionary data_mahasiswa: Membuat dictionary kosong untuk menyimpan data mahasiswa.
3. Tampilkan Menu: Menampilkan pilihan menu kepada pengguna (Lihat, Tambah, Ubah, Hapus, Cari, Keluar).
4. Input Pilihan Menu: Pengguna memasukkan pilihan menu.
5. Pilihan Menu:
Jika pengguna memilih T (Tambah):
Input data mahasiswa (Nama, NIM, Nilai Tugas, Nilai UTS, Nilai UAS).
Hitung nilai akhir menggunakan fungsi hitung_nilai_akhir.
Simpan data ke dalam dictionary.
Tampilkan pesan bahwa data berhasil ditambahkan.
Jika pengguna memilih U (Ubah):
Input NIM mahasiswa yang ingin diubah.
Jika NIM ditemukan, input nilai baru (Tugas, UTS, UAS).
Hitung nilai akhir baru dan perbarui data.
Tampilkan pesan bahwa data berhasil diubah.
Jika pengguna memilih H (Hapus):
Input NIM mahasiswa yang ingin dihapus.
Jika NIM ditemukan, hapus data dari dictionary.
Tampilkan pesan bahwa data berhasil dihapus.
Jika pengguna memilih L (Lihat):
Tampilkan semua data mahasiswa dalam format tabel.
Jika pengguna memilih C (Cari):
Input NIM mahasiswa yang ingin dicari.
Jika NIM ditemukan, tampilkan informasi mahasiswa.
Jika pengguna memilih K (Keluar):
6. Tampilkan pesan bahwa program selesai dan keluar dari loop.
7. End: Titik akhir program.

## FLOWCHART 

![Screenshot 2024-11-27 151748](https://github.com/user-attachments/assets/e03f2a23-7fb6-4050-b0c3-80d8f18474f1)
