# Praktikum Teknologi Cloud Computing - Minggu 06

## Materi

**Data as A Service**

## Tujuan

1.  Mahasiswa memahami berbagai tipe software DBMS untuk mengelola berbagai model data.
2.  Mahasiswa memahami keterkaitan teknologi Cloud Computing dengan DBMS dalam konteks Data as a Service.
3.  Mahasiswa memahami arsitektur Data as A Service.
4.  Mahasiswa memahami dan mampu mengimplementasikan Data as a Service menggunakan Go dan DBMS.

## Pembahasan

1.  Berbagai tipe software DBMS untuk mengelola berbagai model data
2.  Pengertian Data as a Service dan Cloud Database
3.  Arsitektur Data as a Service
5.  Implementasi Data as a Service Menggunakan Go dan DBMS

## Software yang Diperlukan

* Sistem Operasi: Linux, Windows, Mac, FreeBSD, dan sistem operasi lain yang mendukung. 
* *Compiler* [Go](https://golang.org/). bisa diperoleh di [halaman download Go](https://golang.org/dl/). 
* [MySQL Community Edition](https://www.mysql.com/products/community/).
* [MongoDB Community Server](https://www.mongodb.com/download-center/community)

## Pembelajaran

```
Materi dan Penjelasan
```

1.  Pada dasarnya ada 2 tipe DBMS: [SQL](https://en.m.wikipedia.org/wiki/SQL) dan [NoSQL](https://en.wikipedia.org/wiki/NoSQL).
2.  Pelajari [Data as a Service di Wikipedia](https://en.wikipedia.org/wiki/Data_as_a_service) serta [Cloud database](https://en.wikipedia.org/wiki/Cloud_database).
3.  Arsitektur Data as a Service biasanya diwujudukan dengan menggunakan arsitektur [microservices](https://microservices.io/). *Compiler* dan *development tools* bersama dengan REST atau gRPC atau GraphQL serta berbagai protokol untuk implementasi *function as a service* digunakan untuk membangun *service*. Akses ke data biasanya melibatkan DBMS (SQL maupun NoSQL). Untuk Go, bisa digunakan [Gin](https://github.com/gin-gonic/gin) untuk [menghasilkan data JSON](https://github.com/gin-gonic/gin#api-examples) dalam respon.
4.  Akses ke DBMS di Go dilakukan dengan menggunakan pustaka standar serta driver. Untuk MySQL serta berbagai DBMS SQL (RDBMS), digunakan paket [database/sql](http://go-database-sql.org/). Untuk NoSQL (contoh: MongoDB), digunakan [driver MongoDB untuk Go](https://github.com/mongodb/mongo-go-driver).

```
Latihan
```

1.  Install Go, MySQL, dan MongoDB
2.  Buat 2 contoh program Go masing-masing untuk koneksi dan membaca data dari MySQL dan MongoDB.
3.  Dengan menggunakan Gin, buatlah RESTful API untuk membaca dara dari MySQL dan MongoDB tersebut.

```
Tugas
```

Buat 2 program menggunakan salah satu pustaka yang ada di [implementasi GraphQL di Go](https://graphql.org/code/#go) untuk membaca data dari MySQL serta MongoDB dan memberikan respon GraphQL, 1 program untuk MySQL, 1 program untuk MongoDB.



