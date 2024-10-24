# New York Data

New York merupakan salah satu kota tersibuk di dunia. Trasnportasi yang paling sering digunakan sebagai transpotasi sehari - hari adalah taxi. Project ini akan akan berfokus pada melakukan analisa terhadap data dan memberikan insight berdasarkan data taxi NYC trip sehingga dapat melihat pattern, melakukan optimalisasi service, dan provide      
Project ini bertujuan untuk melakukan

Initially appeared on
[gist](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2). But the page cannot open anymore so that is why I have moved it here.
##  Garis besar Project

### Analisis Data Eksplorasi (EDA):
- Identifikasi pola frekuensi perjalanan, jarak, dan jumlah tarif.
- emukan jam sibuk dan zona penjemputan/pengantaran yang populer.
Analisis perilaku penumpang (misalnya, jenis perjalanan, metode pembayaran).

Rekomendasi:

Memberikan wawasan untuk membantu operator taksi mengoptimalkan rute dan mengelola distribusi armada.
Menyarankan perbaikan operasional untuk meminimalkan jarak tempuh kosong dan waktu tunggu.


## Project Use Case
1. Pengoptimalan driver dan armada taksi
Masalah : Bagaimana cara mengoptimalkan operasi dari fleet dengan meningkatkan efisiensi dan mengurangi waktu idle
    Analisa yang akan dilakukan : 
        - Menganalisa rata-rata panjang trip dan durasi trip 
        - Mengidentifikasi zona pick up dan drop off yang paling tinggi berdasarkan waktu
        - Melakukan pengoptimalan distribusi  armada dengan melakukan perbaningan demand tinggi dan  low ddemand
2. Cara mengidentifikasi waktu paling ramai dan memprediksi jumlah demand pada waktu tertentu
Masalah Kapan dan dimana demand taxi meningkat 
    Analisa :
        - Menggunakan lpep_pickup_datetime untuk melakukan analisa waktu pick up paling ramai
        - mengidentifikasi peak hours, days of the week, and seasons
        - Segment by payment types to identify high-revenue periods.

3. Preferensi Pembayaran dan Pengaruh Pendapatan Driver
Masalah: Metode pembayaran mana yang paling populer, dan bagaimana pengaruhnya terhadap pendapatan driver
   Analisa
        - Analisis jenis pembayaran 
        - Membandingkan pendapatan total dan perilaku tip di seluruh metode pembayaran.

4. Hubungan antara Tarif Perjalanan dan Jarak
Masalah: Apakah ada korelasi antara jarak perjalanan dan jumlah tarif?
    Analisa
        - Buat diagram sebar antara Jarak_perjalanan dan Jumlah_tarif.
        - Hitung korelasi untuk memahami perilaku penetapan harga.
        - Melakukan analisa outlier (misalnya, tarif sangat tinggi dengan jarak pendek).

5. Analisis Durasi Perjalanan dan Zona
Masalah: Zona mana (PULocationID, DOLocationID) yang mengalami waktu tempuh terlama?
Pendekatan:
        - Hitung durasi perjalanan dari lpep_pickup_datetime hingga lpep_dropoff_datetime.
Bagikan waktu tempuh berdasarkan zona penjemputan dan pengantaran.
Identifikasi zona dengan kemacetan lalu lintas atau penundaan yang sering terjadi.

6. Dampak Biaya Tambahan pada Total Tarif
Masalah: Bagaimana biaya tambahan (pajak MTA, biaya tambahan, tol) memengaruhi total tarif?
Pendekatan:
Bandingkan Total_amount dengan Fare_amount di berbagai perjalanan.
Analisis frekuensi dan dampak biaya tambahan dan biaya tambahan.
Identifikasi pola (misalnya, biaya tol yang lebih tinggi pada rute bandara).
Potensi Hasil:
Rincian komponen total tarif dengan rekomendasi untuk penetapan harga yang transparan.
7. Mendeteksi Perjalanan Fraud
Masalah: 
Apakah ada perjalanan yang tidak biasa yang dapat mengindikasikan kesalahan entri data atau penipuan?
Analsia
Identifikasi perjalanan dengan durasi yang sangat panjang atau jarak pendek dengan tarif tinggi.
Mendeteksi perjalanan yang ditandai sebagaiPerjalanan yang dibatalkan" (Payment_type = 4 atau 6).
Menandai perjalanan dengan nilai yang mencurigakan untuk Passenger_count (misalnya, jumlah yang sangat tinggi).
Hasil/ visualisasi 
Jumlah perjalanan yang mungkin merupakan penipuan

4. Perbandingan antara performa vendor
Key Questions:
Apakah ada perbedaan antara average trip distance , waktu dan biaya dari vendor 1 dan 2
Customer satisfaction berdasarkan tip yang diberikan user

Lorem Ipsum

### Library

Requirements for the software and other tools to build, test and push 
- [Example 1](https://www.example.com)
- [Example 2](https://www.example.com)

### Installing

A step by step series of examples that tell you how to get a development
environment running

Say what the step will be

    Give the example

And repeat

    until finished

End with an example of getting some data out of the system or using it
for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Sample Tests

Explain what these tests test and why

    Give an example

### Style test

Checks if the best practices and the right coding style has been used.

    Give an example

## Deployment

Add additional notes to deploy this on a live system

## Built With

  - [Contributor Covenant](https://www.contributor-covenant.org/) - Used
    for the Code of Conduct
  - [Creative Commons](https://creativecommons.org/) - Used to choose
    the license

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code
of conduct, and the process for submitting pull requests to us.

## Versioning

We use [Semantic Versioning](http://semver.org/) for versioning. For the versions
available, see the [tags on this
repository](https://github.com/PurpleBooth/a-good-readme-template/tags).

## Authors

  - **Billie Thompson** - *Provided README Template* -
    [PurpleBooth](https://github.com/PurpleBooth)

See also the list of
[contributors](https://github.com/PurpleBooth/a-good-readme-template/contributors)
who participated in this project.

## License

This project is licensed under the [CC0 1.0 Universal](LICENSE.md)
Creative Commons License - see the [LICENSE.md](LICENSE.md) file for
details

## Acknowledgments

  - Hat tip to anyone whose code is used
  - Inspiration
  - etc
