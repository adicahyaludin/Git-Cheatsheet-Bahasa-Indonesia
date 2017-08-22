# GIT CHEATSHEET BAHASA INDONESIA

```
git init
git config --global user.email "mail@mail.co" 
git config --global user.name "nama anda"
git status
git add .
git add nama_file.php
git commit -m "pesan"
git log
git log --oneline
git log --author='nama_author'
git log nama_file.php
git log nomor_commit
git diff
git diff nama_file.php
git checkout nama_file.html // kembalikan file modified ke sebelum modified
git reset nama_file.html // kembalikan file staged ke modified
git checkout HEAD~3 index.php // kembalikan file ke 3 commit sebelumnya 
git checkout nomor_commit nama_file.php // kembalikan file ke commit tertentu menggunakan nomor_commit
git revert 32d5e -n // kembalikan semua file ke suatu commit dan dalam kondisi staged
git branch nama_branch
git checkout nama_branch
ls
git merge nama_branch
git remote -v
git remote add nama url
git remote rm nama
git remote rename nama_lama nama_baru
git pull nama_remote nama_branch
git fetch nama_remote // buat cabang baru nama_remote/nama_branch di repo lokal dan import semua commit dari repo remote ke repo lokal cabang baru tersebut
git log nama_remote/nama_branch
git merge nama_remote/nama_branch
git push nama_remote nama_branch
CATATAN CONFLICT
HEAD // revisi di repo lokal 
MASTER // revisi dari repo remote
git clone URL
git command --help
```

## Catatan

Bagi yang mau belajar git secara interaktif bahasa indonesia silahkan belajar di [codesaya.com/git](https://codesaya.com/git), git cheatsheet diatas juga merupakan rangkuman dari perintah git di codesaya yang sudah cukup mewakili perintah git yang sering digunakan sehari-hari oleh para coders.

_\* Perintah git diatas hanya perintah git umum, masih banyak perintah git lainnya, untuk melihat perintah git secara lengkap silahkan kunjungi [git-scm.com/docs](https://git-scm.com/docs)_