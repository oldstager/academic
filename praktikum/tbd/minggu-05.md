# Praktikum Teknologi Basis Data - Minggu 5

## Materi

**NoSQL - Key Value / Tuple 2: Redis Lanjut**

## Tujuan

1.  Mahasiswa memahami dan mampu menggunakan Python untuk mengakses Redis
2.  Mahasiswa mampu membuat aplikasi Python yang memanfaatkan Redis

## Pembahasan

1.  Menggunakan Python untuk mengakses Redis

## Software yang Diperlukan

* Sistem Operasi: Linux, Windows, Mac, dan sistem operasi lain yang mendukung Docker / VistualBox.
* Jika menggunakan Docker, gunakan [image resmi dari Redis](https://hub.docker.com/_/redis/?tab=tags) setelah sebelumnya menginstall Docker:
    - [Docker Desktop for Windows](https://hub.docker.com/editions/community/docker-ce-desktop-windows/). Lihat di [petunjuk](https://docs.docker.com/docker-for-windows/install/) untuk instalasi.
    - [Docker Desktop for Mac](https://hub.docker.com/editions/community/docker-ce-desktop-mac/). Lihat di [petunjuk](https://docs.docker.com/docker-for-mac/install/) untuk instalasi.
    - [Docker for Linux](https://download.docker.com/linux/static/).
* Jika menggunakan [VirtualBox](https://www.virtualbox.org/wiki/Downloads), gunakan [image Ubuntu Server](https://www.osboxes.org/ubuntu-server/) versi terakhir. Setelah aktif, install Redis dengan menggunakan:
    - `apt-cache search redis`, catat semua paket Redis yang muncul
    - Install menggunakan `apt install nama-paket` sesuai dengan nama-nama paket yang muncul sebelumnya.
* Python dari distribusi [Miniconda](https://docs.conda.io/en/latest/miniconda.html).

## Pembelajaran

```
Materi dan Penjelasan
```

0.  [Python client untuk Redis](https://redis.io/clients#python).
1.  [Driver redis-py](https://github.com/andymccurdy/redis-py), beserta [dokumentasinya](https://redis-py.readthedocs.io/en/latest/). 
2.  [Getting started with redis-py](https://www.agiliq.com/blog/2015/03/getting-started-with-redis-py/).
3.  [Using Redis In-memory Storage for your Python Applications](https://hackersandslackers.com/redis-py-python/).
4.  [Build Your First Redis Hello World Application in Python](https://opensource.com/article/18/4/how-build-hello-redis-with-python).
5.  

```
Latihan
```

1.  Hidupkan server Redis
2.  Kerjakan `Materi dan Penjelasan` nomor 2, 3, dan 4 

```
Tugas
```

Kerjakan sesuai dengan artikel dari [RealPython.com](https://realpython.com/python-redis/#using-redis-py-redis-in-python) ini.

