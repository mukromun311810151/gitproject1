# TUTORIAL MENGGUNAKAN GIT #

* Membuat repository lokal
* buka directory aktif.
* klik kanan pada directory tersebut, pilih git bash /terminalsehingga muncul git bash comand.
* buat direktory dengan nama latihan1 mkdir latihan1
* kemudian masuk kedalam directory dengan perintah ( change directory ) cd latihan1
'1. Konversi Suhu.jpg'

jalankan perintah git init
maka repository baru berhasil di inisialisasi, dengan adanya folder baru di direktory hidden dengan nama .git
semua perubahan akan disimpan di directory tersebut.

Menambah file baru
buat file dengan nama readme.md di directory repository echo "#latihan1" >> readme.md
untuk menambahkan file tersebut gunakan perintah git add readme.md
cek status file dengan mengetik git status

Menyimpan perubahan ke database (comit)
untuk menyimpan perubahan ke repositorylokal, gunakan perintah git commit -m "file utama"

Membuat repository server
pada laman github klik start a project
isi nama repository
lalu klik tombol create repository

Menambah remot repository
untuk mengirim perubahan pada lokal repository ke server, gunakan perintah : git push -u origin master
masukan username dan password github
hasilnya dapat dilihat di repository github yang telah kita buat.

Tambahkan global config
ketikan perintah
git config --global user.name "nama-user"
git config --global user.email "akun-user"
