1)What does git clean do?
---
Membersihkan pohon kerja dengan menghapus file yang tidak berada di bawah kontrol versi secara rekursif, mulai dari direktori saat ini.

2)What do the -d and -f flags for git clean do?
---
1. -d : 
Ketika tidak ada <path> yang ditentukan, git clean tidak akan muncul kembali ke direktori yang tidak terlacak untuk menghindari penghapusan terlalu banyak. Tentukan -d untuk membuatnya berulang ke direktori seperti itu juga.
2. -f : hapus paksa . Jika variabel konfigurasi Git clean.requireForce tidak disetel ke false, git clean akan menolak untuk menghapus file atau direktori kecuali diberikan -f atau -i

3)What git command creates a branch?
---
git branch <namabranch>

4)What is the difference between a fast-forward and recursive merge?
---
fast-forward merge menggabungkan tanpa membuat commit, dan recursive merge digunakan saat menggabungakan 1 head

5)What git command changes to another branch?
---
git checkout <branchtujuan>

6)How do you remove modified or deleted files from the working directory?
---
rm <namafile>

7)What git command deletes a branch?
---
git branch -d <namabranch>

8)What does the git diff command do?
---
Menampilkan perubahan antara working tree dan indeks atau tree, perubahan antara indeks dan tree, perubahan antara dua tree, perubahan yang dihasilkan dari merge, perubahan antara dua blob object, atau perubahan antara dua file pada disk

9)How do you remove files from the staging area?
---
Lakukan perintah git rm <namafile>, kemudian lakukan commit
  
10)How do merge conflicts happen?
---
Konflik terjadi jika terdapat 2 perubahan pada file yang sama ketika digabungkan

