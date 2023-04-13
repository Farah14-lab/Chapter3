# Chapter3
Nama  : Farah Zulfa Hamidah</br>
Absen : 07</br>
Kelas : TI-3B</br>

# Jelaskan masing-masing maksud kode berikut sesuai nomor kode!
## Kode 1:

- sc: singkatan dari Spark Context, objek utama yang digunakan untuk berinteraksi dengan Spark.
- accumulator: variabel yang dapat diakses oleh semua tugas pada node yang sama, digunakan untuk melakukan agregasi.
- parallelize: method untuk membuat RDD (Resilient Distributed Dataset) dari koleksi data pada driver program.
- lambda: fungsi anonim yang dapat digunakan untuk melakukan operasi pada RDD.
- value: method untuk mengakses nilai yang disimpan pada variabel yang terhubung ke RDD.

## Kode 2:

- broadcast: method untuk mendistribusikan variabel yang dapat diakses oleh semua tugas pada node yang sama.
- list: tipe data yang menyimpan kumpulan nilai.
- range: method untuk membuat urutan bilangan bulat.

## Kode 3:

- textFile: method untuk membaca file teks dan membuat RDD berisi baris-baris teks.
- filter: method untuk memfilter data berdasarkan suatu kondisi dan mengembalikan RDD yang terdiri dari data yang lolos filter.
- cache: method untuk menyimpan RDD dalam memori agar dapat diakses lebih cepat.
- count: method untuk menghitung jumlah elemen dalam RDD.

## Kode 4:

- map: method untuk melakukan transformasi pada setiap elemen RDD.
- collect: method untuk mengambil seluruh elemen RDD dan mengembalikannya ke driver program.
- len: method untuk menghitung panjang sebuah objek, seperti RDD.
- keys: method untuk mengambil kunci dari sebuah RDD yang berisi pasangan kunci-nilai.
- values: method untuk mengambil nilai dari sebuah RDD yang berisi pasangan kunci-nilai.

## Kode 5:

- defaultParallelism: jumlah partisi default yang digunakan oleh RDD.
- getNumPartitions: method untuk mengambil jumlah partisi dari sebuah RDD.
- mapPartitionsWithIndex: method untuk melakukan transformasi pada setiap partisi RDD dengan mengakses indeks partisi.
- repartition: method untuk mengubah jumlah partisi RDD menjadi jumlah partisi yang baru.
- coalesce: method untuk menggabungkan beberapa partisi RDD menjadi satu partisi.
- toDebugString: method untuk mengambil informasi rinci tentang RDD.

## Kode 6:

- flatMap: method untuk melakukan transformasi pada setiap elemen RDD dan mengembalikan kumpulan nilai.
- reduceByKey: method untuk menghitung hasil agregasi pada pasangan kunci-nilai yang sama.
- split: method untuk membagi sebuah string menjadi beberapa bagian berdasarkan pemisah yang ditentukan.

## Hasil Screenshot </br>

**Accumulator.py**
![Screenshot](images/img1.png) </br>
</br>
**Broadcast.py**
![Screenshot](images/img2.png) </br>
</br>
**PairRDD.py**
![Screenshot](images/img3.png) </br>
</br>
**SystemCommandsOutput.scala**
![Screenshot](images/img4.png) </br>
</br>
**SystemCommandsReturnCode.scala**
![Screenshot](images/img5.png) </br>
![Screenshot](images/img6.png) </br>
</br>
**WordCount.py**
![Screenshot](images/img7.png) </br>
