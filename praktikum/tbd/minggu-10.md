# Praktikum Teknologi Basis Data - Minggu 10

## Materi

**NoSQL - Time Series DB 1: Memulai InfluxDB**

## Tujuan

1.  Mahasiswa memahami pengertian Time Series DB.
2.  Mahasiswa memahami berbagai contoh masalah yang bisa diselesaikan menggunakan Time Series DB.
3.  Mahasiswa mampu melakukan instalasi software InfluxDB
4.  Mahasiswa memahami dan mampu menggunakan berbagai perintah dasar untuk mengelola *time series data* menggunakan InfluxDB.

## Pembahasan

1.  Pengertian Time Series Database
2.  Pemakaian Time Series Database
3.  Instalasi InfluxDB
4.  Perintah-perintah dasar InfluxDB

## Software yang Diperlukan

* Sistem Operasi: Linux, Windows, Mac, FreeBSD, dan sistem operasi lain yang mendukung 
* [InfluxDB](https://portal.influxdata.com/downloads/), silahkan ambil versi terakhir (bisa dicoba di versi stabil maupun versi beta). Jika anda menggunakan Windows, anda hanya bisa menggunakan versi stabil saja.

## Pembelajaran

```
Materi dan Penjelasan
```

1.  [Ringkasan artikel Time Series Database di Wikipedia](https://en.wikipedia.org/wiki/Time_series_database).
2.  [Masalah-masalah yang bisa diselesaikan oleh *Time Series Database*](https://www.influxdata.com/solutions/).
3.  Instalasi InfluxDB:
    * [Versi stabil](https://docs.influxdata.com/influxdb/v1.8/introduction/install/)
    * [Versi beta](https://v2.docs.influxdata.com/v2.0/get-started/)
4.  Perintah-perintah dasar InfluxDB:
    * [Versi stabil](https://docs.influxdata.com/influxdb/v1.8/introduction/get-started/)
    * Versi beta: [Write data](https://v2.docs.influxdata.com/v2.0/write-data/) dan [Query data](https://v2.docs.influxdata.com/v2.0/query-data/).

```
Latihan
```

Untuk mengerjakan latihan, gunakan file-file berikut jika diminta:

1.  Line Protocol:

```
mem,host=host1 used_percent=23.43234543 1556892576842902000
cpu,host=host1 usage_user=3.8234,usage_system=4.23874 1556892726597397000
mem,host=host1 used_percent=21.83599203 1556892777007291000
```

2.  Annotated CSV:

```
result,table,_start,_stop,_time,region,host,_value
my-result,0,2018-05-08T20:50:00Z,2018-05-08T20:51:00Z,2018-05-08T20:50:00Z,east,A,15.43
my-result,0,2018-05-08T20:50:00Z,2018-05-08T20:51:00Z,2018-05-08T20:50:20Z,east,B,59.25
my-result,0,2018-05-08T20:50:00Z,2018-05-08T20:51:00Z,2018-05-08T20:50:40Z,east,C,52.62
```

1.  Install InfluxDB sesuai dengan `Materi dan Pembahasan` point 3.
2.  Kerjakan perintah-perintah dasar di InfluxDB sesuai `Materi dan Pembahasan` point 4. Jika anda
    menggunakan versi stabil, silahkan diikuti secara langsung. Jika anda menggunakan versi Beta,
    untuk *write data* kerjakan dengan menggunakan Influx CLI saja, data *line protocol* dan
    *annotated CSV* ada di atas. Silahkan dikerjakan juga bagian untuk query data menggunakan Flux.

```
Tugas
```

Carilah perbedaan antara versio 1.x.x dengan versi 2.x.x (masih versi Beta). Jelaskan dan tulis dalam file markdown dengan nama: `beda-1-2.md`. Push file tersebut ke repo anda sesuai ketentuan.

