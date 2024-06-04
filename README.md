# Capstone-2

**Latar Belakang**

"Green Taxi" atau "Boro Taxis" atau selanjutnya kita akan sebut taksi hijau, merupakan bagian dari inisiatif yang dikenal sebagai "Borough Taxi Program" yang dimulai pada 2013 di kota New York. Taksi hijau diatur oleh NYC Taxi and Limousine Commission (TLC). Mereka beroperasi dengan aturan yang mirip dengan taksi kuning, tetapi dengan izin khusus untuk melayani wilayah-wilayah tertentu di luar Manhattan.

Analisis perjalanan menggunakan GPS oleh Komisi Taksi dan Limusin menemukan bahwa 95% penjemputan taksi kuning terjadi di Manhattan di bawah 96th Street dan di bandara JFK dan LaGuardia. Oleh karena itu adanya taksi hijau ini diharapkan mampu memenuhi permintaan akan taksi yang melebihi pasokan selama berjam-jam setiap hari diluar daerah padat tersebut, terutama di wilayah Brooklyn, Queens, The Bronx, dan Staten Island. Pada bulan Desember 2011, Gubernur Andrew Cuomo menandatangani undang-undang negara bagian yang mengesahkan Rencana Taksi Lima Wilayah yang mencakup 18.000 izin taksi boro baru dan penjualan 2.000 medali kuning baru, yang semuanya dapat diakses oleh kursi roda. Meskipun undang-undang tersebut akan membuat panggilan taksi livery di jalan menjadi legal, hal ini tidak disambut baik oleh beberapa pengemudi taksi livery dan politisi karena kekhawatiran bahwa biayanya akan terlalu mahal seperti yang terlihat pada medali taksi kuning yang dijual melalui lelang dengan rata-rata \$700.000 per medali. Komisi Taksi dan Limusin mengklarifikasi bahwa izin taksi boro hanya menelan biaya \$1.500 dan berlaku selama tiga tahun. [disini](https://en.wikipedia.org/wiki/Boro_taxi)

Namun solusi dengan program taksi hijau tak semulus yang dikira. Fakta yang ada menunjukkan kemrosotan performa taksi hijau dibanding dengan taksi kuning. Berdasarkan laporan bulanan NYC TLC [disini]((https://www.nyc.gov/site/tlc/about/aggregated-reports.page)). Angka yang ada menunjukkan sejak 2020 taksi hjau mengalami penurunan jumlah trip, jumlah pengemudi dan jumlah kendaraan aktif hal ini berbanding terbalik dengan taksi kuning yang sempat drop di tahun 2020 dan terus naik di tahun-tahun berikutnya

**Pernyataan Masalah**

Telah diuraikan pada latar belakang bahwa taksi hijau terus mengalami penurunan transaksi perjalanan bahkan sejak tahun 2015. Jika diawal kemunculan taksi hijau diharapkan menjadi solusi kendaraan untuk wilayah yang tidak terjangkau oleh taksi kuning dengan biaya lisensi yang jauh lebih murah dibanding taksi kuning. Apakah taksi hijau masih terus bisa menjadi harapan kendaraan yang baik untuk jangkauan wilayah yang tak terjangkau oleh taksi kuning?

**Batasan Masalah**

Untuk menjawab permasalahan diatas kami menggunakan data trip record TLC NYC periode Januari 2023 [disini](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

**Tujuan**

Analisa ini diharapkan mampu menjawab pernyataan masalah diatas serta menjadi acuan NYC Taxi and Limousine Commission (TLC) untuk mempertimbangkan ulang adanya taksi hijau.

**Analisa**
Analisa ini terbagi menjadi 2 file worksheet , yang pertama adalah Data Preparation untuk medapatkan data bersih yang siap pakai dan pada worksheet ini kami khususkan untuk analisa data.


*Analisa data akan dilakukan dengan melihat aspek-aspek berikut*

1. Semua pendapatan yang diterima oleh pengemudi selama Januari 2023

2. Mengidentifikasi biaya opersional dan mendapatkan Pendapatan bersih yang diterima oleh pengemudi setelah diketahui biaya operasional

3. Kepuasan penumpang terhadap pengemudi ditinjau dari tip yang diberikan

**Kesimpulan**

Dari analisis yang telah dilakukan, sebanyak 63.833 data transaksi hijau setelah dilakukan cleaning, dapat kita buat kesimpulan berikut:

*Permintaan dan Preferensi Penumpang*

Rata-rata transaksi perjalanan yang didapat perhari oleh pengemudi adalah sebanyak 2 kali, dengan perjalanan paling popular di lokasi East Harlem dan hari selasa menjadi hari yang paling banyak penumpang. Rata-rata total pendapatan yang diperoleh setiap pengemudi taksi hijau pada Januari 2023 adalah \$47,16. Penumpang lebih senang memanggil taksi langsung dijalan, membayar menggunakan kartu kredit dan menggunakan tarif standard dalam perjalanannya.

*Distribusi Pendapatan Bersih Pengemudi*

Pendapatan bersih seluruh taksi hijau per hari pada data Januari 2023 setelah diidentifikasi biaya-biaya operasional adalah `$42418.7` per hari. Jumlah pengemudi yang aktif pada saat itu sebanyak 960 orang, maka rata-rata pendapatan bersih per pengemudi adalah `$42,46` per hari

*Faktor Kepuasan Penumpang*

Dari setiap perjalanan peluang pengemudi mendapatkan tip adalah sebesar 55.7%, namun ketika perjalanan mengalami macet, peluang pengemudi mendapat tip menurun menjadi 20.57%. Perjalanan yang paling sering memberikan tip kepada pengemudi adalah dari East Harlem North ke East Harlem South. Lokasi East Harlem North merupakan lokasi yang paling popular untuk memberikan tip.

**Rekomendasi**

Regulasi pendapatan minumun kota New York adalah`$ 15` per jam atau setara `$ 120` per hari [disini](https://sgp.fas.org/crs/misc/R43792.pdf). Pengemudi taksi hijau hanya mendapat `$42.46` setiap harinya dengan hanya 2 kali panggilan setiap armada per hari, dan setiap panggilan hanya memakan jarak 1.8 mil. Dengan memperhatikan aspek kesejahteraan pengemudi. Jika penerunan pada pengemudi merupakan kebijakan yang dibuat oleh Komisi NYC TLC, maka keputusan tersebut sudah tepat. Namun jika penurunan terjadi begitu saja maka, Komisi NYC TLC bisa mempertimbangkan untuk tidak mengeluarkan lisensi untuk sementara waktu.

Jika ditinjau dari komersial, maka Komisi NYC TLC dapat mempertimbangkan untuk memperhatikan pada opsi pembayaran agar dipastikan sistem pembayaran dengan credit card berfungsi dengan baik dan menambah opsi pembayaran digital lain yang mungkin diminati pelanggan, seperti e-wallet atau aplikasi pembayaran digital lainnya. Kemudian promosi penggunaan aplikasi pemanggilan taksi hijau dapat lebih digalakkan untuk menjangkau kalangan yang lebih luas mengingat penetrasi smartphone di Amerika Serikat sangat tinggi yaitu 81,6% [disini](https://whatsthebigdata.com/smartphone-stats/) .

**Visualisasi data dapat dilihat pada [link ini](https://public.tableau.com/app/profile/deva.merinne/viz/NYCTLCCapstone2_17139850553860/DistanceGreenTaxiNYCTLCJanuari2023)**
