What is the difference between git reset and git revert. When would you use one over the other?
---
1. Git reset mengembalikan repository ke satu ke satu atau beberapa commit sebelumnya dan tidak bisa kembalisetelah dikembalikan
2. Git revert membuat repository berpindah ke commit yang ditentukan tanpa menghapus commit lainnya

What is the difference between git merge and git rebase. When would you use one over the other?
---
git merge melakukan penggabungan antra branch cabang ke branch master dengan mengabaikan semua commit yang ada sebelumnya jika telah digabung , sedangkan git rebase menggabungkan dengan mengambil titik di mana ia bercabang untuk pindah ke titik awal yang baru supaya memerhatikan tiap commit yang dilakukan pada branch

What is the difference between git stash pop and git stash apply. When would you use one over the other?
---
1.git stash pop membuang simpanan (paling atas, secara default) setelah menerapkannya 
2.git stash apply meninggalkannya di daftar simpanan untuk kemungkinan digunakan kembali nanti (atau Anda kemudian dapat git stash menjatuhkannya).

What kinds of things can you do in interactive mode when rebasing?
---
interactive (disingkat -i), akan membuka editor dengan daftar commit yang akan diubah. Daftar ini akan menerima perintah, memungkinkan pengguna untuk mengedit daftar sebelum memulai tindakan rebase.
