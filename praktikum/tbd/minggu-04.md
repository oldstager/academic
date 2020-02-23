# Praktikum Teknologi Basis Data - Minggu 4

## Materi

**NoSQL - Key Value / Tuple 1: Memulai Redis**

## Tujuan

1.  Mahasiswa memahami cara melakukan instalasi Redis (melalui distro Linux maupun Docker).
2.  Mahasiswa memahami cara konfigurasi dan mampu mengkonfigurasi Redis.
3.  Mahasiswa mampu menjalanjan server Redis maupun redis-cli untuk akses klien default.
4.  Mahasiswa memahami basis data key-value serta penggunaannya
5.  Mahasiswa memahami dan mampu menggunakan perintah-perintah dasar di Redis.

## Pembahasan

1.  Instalasi Redis (jika menggunakan Linux), atau menjalankan Redis menggunakan Docker (jika menggunakan Mac, Windows, maupun Linux).
2.  Konfigurasi Redis
3.  Redis Server
4.  Redis cli
5.  Memahami key-value dan penggunaan Redis
6.  Perintah-perintah dasar dari Redis

## Software yang Diperlukan

* Sistem Operasi: Linux, Windows, Mac, dan sistem operasi lain yang mendukung Docker.
* Docker:
    - [Docker Desktop for Windows](https://hub.docker.com/editions/community/docker-ce-desktop-windows/). Lihat di [petunjuk](https://docs.docker.com/docker-for-windows/install/) untuk instalasi.
    - [Docker Desktop for Mac](https://hub.docker.com/editions/community/docker-ce-desktop-mac/). Lihat di [petunjuk](https://docs.docker.com/docker-for-mac/install/) untuk instalasi.
    - [Docker for Linux](https://download.docker.com/linux/static/).

## Pembelajaran

```
Materi dan Penjelasan
```

1.  Redis tidak tersedia dalam versi selain Linux. Ada beberapa versi untuk Windows tetapi biasanya versi Redis yang disediakan adalah versi lama. Untuk menjalankan praktikum ini, kita bisa [menggunakan Docker](https://hub.docker.com/_/redis/?tab=description).  
2.  [Dokumentasi untuk konfigurasi Redis](https://redis.io/topics/config).
3.  [Dokumentasi redis-cli](https://redis.io/topics/rediscli).
4.  [Cheatsheet Redis basic commands](https://gist.github.com/LeCoupa/1596b8f359ad8812c7271b5322c30946).
5.  [Introduction to Redis](https://auth0.com/blog/introduction-to-redis-install-cli-commands-and-data-types/).
6.  [Tipe data di Redis](https://redis.io/topics/data-types).

```
Latihan
```

1.  Jalankan Redis server menggunakan Docker
2.  Dengan menggunakan Docker, koneksikan redis-cli ke server redis yang anda jalankan pada langkah
    pertama.
3.  Kerjakan `Materi dan Penjelasan` nomor 4, khusus untuk` cli commands` serta `data types`.

```
Tugas
```

Kerjakan [Redis Quick Guide](https://www.tutorialspoint.com/redis/redis_quick_guide.htm), untuk bagian instalasi serta redis cli, gunakan Docker.

