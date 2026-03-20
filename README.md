# STRUKTUR DATA - ARRAY

## Dewa Gede Maha Putra (2501010018-Kelas A)

## KONSEP ARRAY :thinking:

Array adalah struktur data yang digunakan untuk menyimpan sekumpulan data dengan tipe yang sama dalam satu variabel. Array dapat dipahami sebagai sebuah wadah tunggal yang mampu menampung banyak nilai sekaligus, asalkan seluruh nilai tersebut memiliki jenis atau tipe data yang seragam. Setiap data yang tersimpan di dalamnya diletakkan pada posisi yang berurutan, sehingga kita bisa memanggil data tertentu dengan merujuk pada nomor urutnya yang disebut sebagai indeks. Perlu diingat bahwa dalam dunia pemrograman, penghitungan posisi ini hampir selalu dimulai dari angka 0, bukan 1.

Dalam program ini, array digunakan untuk menyimpan nilai mahasiswa. Dengan menggunakan array, proses pengolahan data seperti mencari nilai tertinggi, nilai terendah, menghitung rata-rata, serta menghitung jumlah mahasiswa yang lulus dapat dilakukan dengan lebih mudah dan terstruktur.

### :point_down: Contoh sederhana penggunaan Array dalam pemrograman python :point_down: ###

```
value = [55, 95, 80, 67, 100]
```
Pada contoh tersebut, semua nilai disimpan dalam satu variabel yaitu _value_.

## SCREENSHOOT HASIL EKSEKUSI :point_down:
<img width="1919" height="1079" alt="Screenshot 2026-03-21 013721" src="https://github.com/user-attachments/assets/cc590752-34c1-4fb7-bc1f-d7166ec9fb62" />
<img width="1919" height="1074" alt="Screenshot 2026-03-21 013735" src="https://github.com/user-attachments/assets/6e68dcf0-4c1d-401c-b1fd-f2cebbd95e75" />
<img width="1919" height="1079" alt="Screenshot 2026-03-21 013746" src="https://github.com/user-attachments/assets/b09f55b8-c77e-4207-9431-ef240e514590" />
<img width="1919" height="1079" alt="Screenshot 2026-03-21 013810" src="https://github.com/user-attachments/assets/1c15e8cd-849d-45d5-b000-97f78d7f6445" />

## Analisis Kompleksitas :page_facing_up:
| Operasi | Kompleksitas |
| --- | --- |
| Input Nilai | O(n) |
| Mencari Nilai Tertinggi | O(n) |
| Mencari Nilai Terendah | O(n) |
| Menghitung Rata - Rata | O(n) |
| Menghitung Jumlah Lulus | O(n) |
| Menampilkan Jumlah Grafik | O(n) |

### Input Nilai Mahasiswa
Di sini program menggunakan perulangan untuk mengisi tiap slot di dalam array. Karena setiap nilai mahasiswa harus dimasukkan satu per satu, maka total langkah yang dijalankan akan bertambah sebanding dengan jumlah mahasiswa yang diinput.

**Kompleksitas waktu: O(n)**

### Menentukan Nilai Tertinggi dan Nilai Terendah
Untuk mendapatkan angka maksimum dan minimum, program harus memindai seluruh elemen array dari awal sampai akhir. Setiap data dibandingkan untuk memastikan hasilnya akurat, sehingga waktu prosesnya sangat bergantung pada banyaknya data.

**Kompleksitas waktu: O(n)**

### Menghitung Rata-rata Nilai
Nilai rata-rata mahasiswa diperoleh dengan menjumlahkan seluruh nilai mahasiswa terlebih dahulu, lalu hasil penjumlahan tersebut dibagi dengan jumlah data yang tersedia. Karena semua nilai harus diproses untuk mendapatkan totalnya, maka proses ini memerlukan pemeriksaan terhadap seluruh elemen array.

**Kompleksitas waktu: O(n)**

### Menghitung Jumlah Mahasiswa yang Lulus
Program akan melakukan pengecekan pada tiap indeks untuk melihat apakah nilainya mencapai batas minimal 60. Jika nilai memenuhi kriteria, maka jumlah mahasiswa yang lulus akan bertambah. Proses ini berlaku untuk semua data nilai yang ada.

**Kompleksitas waktu: O(n)**

### Menampilkan Grafik Data Nilai
Pembuatan Grafik dengan memanfaatkan data yang telah diperoleh dari proses sebelumnya, seperti nilai tertinggi, nilai terendah, serta jumlah mahasiswa yang lulus dan tidak lulus. Proses pembuatan grafik bergantung pada data yang tersedia yang diperlukan tetap berkaitan dengan jumlah data yang diproses sebelumnya.

**Kompleksitas waktu: O(n)**


## Refleksi Pembelajaran :envelope_with_arrow: :envelope_with_arrow:

Melalui tugas ini, saya jadi lebih paham cara kerja array untuk menyimpan dan mengelola banyak data sekaligus dalam satu variabel. Saya juga belajar menerapkan logika dasar seperti mencari nilai tertinggi, menghitung rata-rata, hingga mengecek status kelulusan setiap mahasiswa.

Selain itu, Saya juga memahami bagaimana pentingnya analisis kompleksitas algoritma untuk mengetahui seberapa efisien suatu program dalam memproses data. Dengan mengetahui kompleksitas waktu, kita dapat memperkirakan performa program ketika jumlah data semakin besar.
