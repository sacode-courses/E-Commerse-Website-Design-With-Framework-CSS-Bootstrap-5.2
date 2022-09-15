# Day01 - 📚 Git & GitHub

## Basic Git Commands

### git config

Perintah ini digunakan untuk mengatur nama dan alamat email untuk digunakan dalam proses melakukan perubahan-perubahan pada project repository

```git
git config --global user.name "[Nama Lengkap]"
```

```git
git config --global user.email "[alamat@email.com]"
```

### git clone

Perintah ini digunakan untuk mendapatkan / mendownload repository dari alamat url github repository yang telah dibuat


```git
git clone https://github.com/username/alamat-repository
```

### git status

Perintah ini digunakan untuk melihat status perubahan di dalam project directory yang harus di commit (akan berwarna merah). Sedangkan file yang sudah dilakukan proses commit akan berwarna hijau.


```git
git status
```

### git add .

Perintah ini digunakan untuk menambah semua file baru atau file hasil perubahan ke dalam 'staging area'

```git
git add .
```

### git commit -m "commit pertama"

Perintah ini digunakan untuk memasukan hasil perubahan ke dalam catatan versi (version history) secara permanent

```git
git commit -m "commit pertama"
```


### git push

Perintah ini digunakan untuk mengirim hasil commit atau perubahan dari direktori lokal ke direktory remote pada GitHub

```git
git push
```

### git branch

Perintah ini digunakan untuk menampilkan semua branch yang sudah dibuat.

Saat repository pertama kali dibuat, hanya ada satu branch dengan nama branch : main.


```git
git branch
```

### git branch [nama-branch]

Perintah ini digunakan untuk membuat branch baru dengan nama tertentu

```git
git branch [nama-branch]
```

### git checkout

Perintah ini digunakan digunakan untuk berpindah dari satu branch ke branch lain

```git
git checkout nama-branch
```

### git checkout -b [nama-branch]

Perintah ini digunakan digunakan untuk membuat branch baru dan juga langsung berpindah ke dalam branch terebut

```git
git checkout -b [nama-branch]
```

### git push --all -u

Perintah ini digunakan untuk mengirim semua branch baru yang dibuat di repository lokal ke repository remote di GitHub

```git
git push --all -u
```

### git remote

Perintah ini digunakan untuk menghubungkan repository lokal di komputer dengan repository di server GitHub

```git
git remode add [variable-name] [remote-server-link]
```

### git pull

Perintah ini digunakan untuk mencocokan dan menggabungkan perubahan dari server remote ke dalam direktori yang sedang dikerjakan

```git
git pull
```