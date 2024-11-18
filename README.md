# Latihan-Praktikum-pert-10
LATIHAN 1
Buat Dictionary daftar kontak
• Nama sebagai key, dan nomor sebagai value

• Tampilkan kontaknya Ari
• Tambah kontak baru dengan nama Riko, nomor 087654544
• Ubah kontak Dina dengan nomor baru 088999776
• Tampilkan semua Nama
• Tampilkan semua Nomor
• Tampilkan daftar Nama dan nomornya
• Hapus kontak Dina.

PROGRAM LATIHAN 1
![Latihan 1](https://github.com/user-attachments/assets/1d5c921e-43fd-45e0-8296-f1764c4ab0b2)

PROGRAM HASIL LATIHAN 1
![Hasil latihan 1](https://github.com/user-attachments/assets/1b6e7e29-951d-476a-b3c2-81fea35cd7d1)

PENJELASAN LATIHAN 1
Penjelasan Program:

    Membuat Dictionary: Kita membuat dictionary daftar_kontak dengan nama sebagai key dan nomor sebagai value.
    Tampilkan Kontak Ari: Mengakses nomor kontak Ari menggunakan key "Ari".
    Tambah Kontak Baru: Menambahkan kontak baru dengan nama "Riko" dan nomor "087654544" ke dalam dictionary.
    Ubah Kontak Dina: Mengubah nomor kontak Dina dengan nomor baru "088999776".
    Tampilkan Semua Nama: Menggunakan keys() untuk menampilkan semua nama yang ada dalam dictionary.
    Tampilkan Semua Nomor: Menggunakan values() untuk menampilkan semua nomor yang ada dalam dictionary.
    Tampilkan Daftar Nama dan Nomornya: Menggunakan items() untuk menampilkan semua pasangan nama dan nomor dalam format yang lebih terstruktur.
    Hapus Kontak Dina: Menghapus kontak Dina dari dictionary menggunakan del.

PRAKTIKUM PERTEMUAN 10
Buat program sederhana yang akan menampilkan daftar nilai
mahasiswa, dengan ketentuan
• Program dibuat dengan menggunakan Dictionary
• Tampilkan menu pilihan: (Tambah Data, Ubah Data, Hapus Data,
Tampilkan Data, Cari Data)
• Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%,
uts: 35%, uas: 35%)
• Buat flowchart dan penjelasan programnya pada README.md
• Commit dan push repository ke github.


PROGRAM PRAKTIKUM
![Praktikum (1)](https://github.com/user-attachments/assets/62329737-e5e6-441f-9489-8e1003cd48ab)
![Praktikum (2)](https://github.com/user-attachments/assets/0423d1a0-a394-4f94-b18b-5096ce031a28)
![Praktikum (3)](https://github.com/user-attachments/assets/41d105cb-9648-4362-805c-48698a96f709)

HASIL PROGRAM PRAKTIKUM
![Hasil praktikum (1)](https://github.com/user-attachments/assets/325fff43-d12a-489c-83b2-2086182048e5)
![Hasil praktikum (2)](https://github.com/user-attachments/assets/c3bbd50b-ca60-4e80-ae0c-8a212b15ad75)
![Hasil Praktikum (3)](https://github.com/user-attachments/assets/61e8d979-9328-4813-8504-7811d366743c)

PENJELASAN PROGRAM PRAKTIKUM

Struktur Program

    Dictionary untuk Menyimpan Data:
        Program menggunakan dictionary bernama daftar_nilai untuk menyimpan data mahasiswa. Kunci (key) dari dictionary ini adalah NIM mahasiswa, sedangkan nilai (value) adalah dictionary lain yang berisi informasi tentang nama mahasiswa, nilai tugas, UTS, UAS, dan nilai akhir.

    Fungsi hitung_nilai_akhir:
        Fungsi ini menerima tiga parameter: nilai tugas, UTS, dan UAS. Fungsi ini menghitung nilai akhir berdasarkan bobot yang telah ditentukan:
            Tugas: 30%
            UTS: 35%
            UAS: 35%
        Rumus perhitungan nilai akhir adalah: [ \text{Nilai Akhir} = (Tugas \times 0.3) + (UTS \times 0.35) + (UAS \times 0.35) ]

    Fungsi tambah_data:
        Fungsi ini digunakan untuk menambahkan data mahasiswa baru ke dalam dictionary daftar_nilai.
        Pengguna diminta untuk memasukkan NIM, nama, dan nilai tugas, UTS, dan UAS.
        Setelah data dimasukkan, fungsi ini menghitung nilai akhir dan menyimpan semua informasi dalam dictionary.

    Fungsi ubah_data:
        Fungsi ini memungkinkan pengguna untuk mengubah data mahasiswa yang sudah ada.
        Pengguna diminta untuk memasukkan NIM mahasiswa yang ingin diubah. Jika NIM ditemukan, pengguna dapat memasukkan data baru (nama, tugas, UTS, UAS), dan nilai akhir akan dihitung ulang.

    Fungsi hapus_data:
        Fungsi ini digunakan untuk menghapus data mahasiswa berdasarkan NIM.
        Pengguna diminta untuk memasukkan NIM mahasiswa yang ingin dihapus. Jika NIM ditemukan, data mahasiswa tersebut akan dihapus dari dictionary.

    Fungsi tampilkan_data:
        Fungsi ini menampilkan semua data mahasiswa dalam format tabel.
        Jika tidak ada data mahasiswa, program akan memberi tahu pengguna. Jika ada data, program akan mencetak header tabel dan setiap baris data mahasiswa dengan format yang rapi.
        Format tabel menggunakan f-string untuk memastikan kolom-kolom teratur.

    Fungsi cari_data:
        Fungsi ini memungkinkan pengguna untuk mencari data mahasiswa berdasarkan NIM.
        Pengguna diminta untuk memasukkan NIM yang ingin dicari. Jika NIM ditemukan, informasi mahasiswa akan ditampilkan.

    Fungsi main:
        Fungsi ini adalah titik masuk program. Di dalamnya terdapat loop yang menampilkan menu pilihan kepada pengguna.
        Pengguna dapat memilih opsi untuk menambah, mengubah, menghapus, menampilkan, atau mencari data mahasiswa, atau keluar dari program.
        Setiap pilihan menu akan memanggil fungsi yang sesuai.

FLOWCHART PRAKTIKUM


![image](https://github.com/user-attachments/assets/a2e3ce61-8e29-4b4f-8c41-8ca2fa25cb02)









