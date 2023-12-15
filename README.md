# IMPLEMENTASI SVM SEBAGAI PENGGANTI PENGENDALI PID PADA KIT ITCLAB

![JUDUL](https://github.com/Aliefindymillani/Mikrokontroler/assets/89888415/cd78f8b6-163b-4944-a817-e28578725250)

## Mikrokontroler

Mikrokontroler merupakan bentuk kecil dari komputer yang tertanam dalam sebuah chip IC (Integrated Circuit) dan dirancang khusus untuk menjalankan tugas atau operasi tertentu. Fungsinya utama adalah sebagai pengontrol atau pengendali dalam suatu rangkaian elektronika. Komponen-komponen umum pada mikrokontroler meliputi CPU (Central Processing Unit), memori sebagai tempat penyimpanan data, I/O (Input dan Output), serta unit pendukung lainnya, sebagaimana dijelaskan oleh Dewinta (2022). Penggunaan mikrokontroler sangat luas dan mencakup berbagai aplikasi elektronik, seperti sistem otomotif, peralatan rumah tangga, perangkat medis, sistem keamanan, perangkat pintar, dan lainnya. Proses kerja mikrokontroler melibatkan penerimaan input dari perangkat eksternal melalui kode inputnya, yang kemudian diolah menggunakan program yang telah dimuat ke dalam memori internal.

Salah satu keunggulan utama mikrokontroler adalah ukurannya yang kecil, memungkinkan integrasi yang mudah ke dalam perangkat elektronik yang memiliki batasan ruang. Kehandalannya menjadikannya solusi ideal untuk perangkat dengan ruang terbatas, seperti peralatan, kendaraan, atau perangkat medis bergerak. Daya rendah konsumsi daya merupakan karakteristik lain mikrokontroler, yang sangat penting dalam aplikasi baterai atau perangkat berdaya rendah. Kelebihan ini membuatnya sesuai untuk perangkat yang harus beroperasi dalam jangka waktu lama dengan sumber daya yang terbatas. Mikrokontroler juga dikenal dengan harga yang relatif terjangkau, menawarkan berbagai pilihan fitur dan harga sehingga memungkinkan pengembang dan produsen mengimplementasikannya secara hemat biaya dalam produk-produk mereka.

## IOT
Internet of Things (IoT) adalah suatu konsep di mana objek ditanamkan dengan teknologi seperti sensor dan perangkat lunak untuk dapat berkomunikasi, mengendalikan, dan bertukar data melalui internet (Setiawan, 2021). Tujuan utama dari pengembangan IoT adalah memberikan solusi bagi berbagai masalah dan tugas manusia (Angela, 2022). Cara kerjanya sangat sederhana, di mana instruksi program digunakan untuk menghasilkan interaksi antar perangkat yang terhubung tanpa memerlukan intervensi pengguna (Angela, 2022). IoT mengandalkan unsur-unsur pendukung seperti kecerdasan buatan, sensor, dan konektivitas untuk menciptakan ekosistem yang memberikan manfaat dalam berbagai bidang seperti pertanian, kesehatan, transportasi, dan lingkungan. Dengan adanya IoT, perangkat terhubung dapat bekerja terkoordinasi, melakukan pengumpulan data secara otomatis, dan merespons terhadap lingkungan sekitarnya, menciptakan dunia yang lebih terhubung, efisien, dan cerdas. Walaupun demikian, penting untuk memperhatikan aspek keamanan dan privasi terkait dengan penggunaan data yang terkumpul.

## Sistem Kendali PID
Sistem kendali yang paling terkenal di industri adalah Sistem Kendali Proporsional Integral dan Derivatif (PID). Diagram blok Sistem Kendali PID ditunjukkan pada gambar di atas. PID menggabungkan tiga aksi kendali, yaitu proporsional, integral, dan derivatif. Setiap aksi kendali ini memiliki keunggulan tertentu. Aksi kendali proporsional memiliki keunggulan rise time yang sangat cepat. Aksi kendali integral efektif dalam mengurangi error. Sementara aksi kendali derivatif dapat membantu mengurangi error dan meredam overshoot. Penggabungan ketiga aksi kendali ini bertujuan untuk menghasilkan keluaran dengan risetime yang cepat dan error yang kecil.

## Deep Learning
Deep Learning merupakan suatu metode dalam bidang kecerdasan buatan (AI) yang terinspirasi oleh cara kerja otak manusia. Tujuan utama dari deep learning adalah mencapai tingkat pemahaman dan pengambilan keputusan tinggi seperti yang dimiliki manusia. Metode ini sangat populer di kalangan praktisi data dan telah diterapkan dalam berbagai produk berteknologi tinggi, seperti mobil otonom.

Dalam konteks deep learning, komputer diajarkan untuk memproses data yang kompleks dan tidak terstruktur dengan cara menghasilkan representasi yang lebih abstrak dan mendalam. Daya tarik utama dari metode ini terletak pada kemampuannya yang luar biasa dalam mengolah informasi. Hal ini membuka pintu menuju perkembangan AI yang lebih maju dan potensial inovasi di berbagai bidang.

Dengan adanya peningkatan terus-menerus dalam kekuatan komputasi dan ketersediaan data yang melimpah, deep learning menjadi alat yang sangat kuat dalam menganalisis data kompleks dan memberikan solusi inovatif di berbagai bidang.

## SVM
Support Vector Machine (SVM) adalah suatu metode atau algoritma pembelajaran mesin yang digunakan untuk klasifikasi dan regresi. SVM efektif digunakan untuk tugas-tugas seperti pengelompokkan data ke dalam kategori atau menentukan hubungan antara variabel. Prinsip dasar dari SVM adalah mencari pemisah optimal atau hyperplane yang memaksimalkan jarak antara dua kelas data yang berbeda.

Keunggulan utama dari SVM adalah kemampuannya bekerja dengan baik dalam ruang fitur yang tinggi dan memberikan performa yang baik dalam menangani data yang kompleks. Hal ini membuat SVM menjadi pilihan yang populer dalam berbagai aplikasi seperti pengenalan pola, klasifikasi teks, pengenalan wajah, dan banyak lagi.

Dalam konteks klasifikasi, SVM berusaha menemukan batas keputusan (decision boundary) yang paling baik memisahkan dua kelas data. Hyperplane yang dihasilkan oleh SVM merupakan batas keputusan ini. Selain itu, SVM juga dapat digunakan untuk masalah regresi, di mana tujuannya adalah menemukan garis (atau hyperplane) yang paling baik memprediksi nilai kontinu.

## Metode Penelitian

![Metode](https://github.com/Aliefindymillani/Mikrokontroler/assets/89888415/85cc8a19-3ed3-4b36-86a6-16be76ec11f4)


Metode penelitian adalah metode yang digunakan dalam mengumpulkan, menganalisis, dan menginterpretasi data untuk menjawab pertanyaan penelitian atau mencapai tujuan penelitian yang telah ditetapkan. Pada sub bab ini kami ingin menjelaskan metode penelitian yang digunakan dalam studi ini, yang meliputi pengumpulan data, pra proses data, pelatihan model, dan evaluasi.

### Pengumpulan Data
Dalam penelitian ini, pengumpulan data dilakukan dengan memanfaatkan perangkat lunak emulasi TCLab. Pada tahap pengumpulan data, TCLab emulator diatur pada kecepatan 100 kali. Selama simulasi berlangsung, setpoint suhu diberikan dengan variasi yang beragam. Setpoint ini mencerminkan nilai target suhu yang diinginkan dalam pengendalian suhu. Untuk memastikan kualitas pelatihan model, variasi d
iberlakukan pada setpoint dalam penelitian ini. TCLab emulator dijalankan selama 540 loop. Loop atau siklus pengendalian suhu merujuk pada jumlah iterasi di mana TCLab emulator melakukan pembacaan sensor suhu dan mengatur aktuator suhu untuk mencapai setpoint yang telah ditetapkan. Pada setiap iterasi, sensor suhu membaca nilai aktual, dan aktuator disesuaikan untuk mendekati setpoint yang diinginkan. Grafik setpoint dataset yang digunakan untuk melatih model juga disajikan dalam penelitian ini.

![Pengumpulan Data](https://github.com/Aliefindymillani/Mikrokontroler/assets/89888415/a97dadc5-8266-42b7-9ec3-ead8c81b1d51)

### Pra Proses Data
Setelah mendapatkan data set point dan error dari tahap pengumpulan data, dilakukan pra proses data untuk menyiapkan data sebelum memasuki tahap pelatihan model. Salah satu langkah kunci dalam pra proses data adalah pemilihan fitur atau ciri yang akan digunakan. Dalam penelitian ini, fitur yang terpilih adalah set point dan error. Set point merepresentasikan nilai target suhu dalam pengendalian suhu, sementara error adalah perbedaan antara set point dan suhu aktual yang terukur. Selain itu, output yang akan diprediksi dalam penelitian ini adalah Q, yang merupakan hasil penjumlahan dari tiga komponen, yaitu P (Proporsional), I (Integral), dan D (Derivative). Komponen-komponen ini merujuk pada algoritma kontrol PID (Proporsional-Integral-Derivative) yang digunakan untuk mengendalikan suhu.

Selain pemilihan fitur dan pembentukan output, tahap pra proses data juga mencakup normalisasi data. Normalisasi dilakukan untuk mengubah rentang nilai setiap fitur agar sejajar dan dapat diolah dengan baik oleh model pembelajaran mesin. Dalam penelitian ini, digunakan normalisasi Min-Max Scaling, suatu metode yang mengubah skala nilai data dari rentang nilai aktual menjadi rentang nilai antara 0 hingga 1 atau -1 hingga 1 (Naufal et al., 2023). Formula Min-Max Scaling digunakan untuk mencapai normalisasi, dengan X scaled sebagai hasil scaling data ke-i, 𝑥 sebagai nilai asli data ke-i, xmin sebagai nilai minimum dari X, dan xmax sebagai nilai maksimum dari X.

![Pra Proses Data](https://github.com/Aliefindymillani/Mikrokontroler/assets/89888415/bbaa2265-1824-4f0b-a025-6bd866e0854a)

### Pelatihan Mode
Pelatihan model dalam arsitektur SVM (Support Vector Machine) merujuk pada proses di mana algoritma SVM belajar dari data latihan untuk membuat model yang dapat digunakan untuk melakukan prediksi atau klasifikasi pada data baru. Dalam SVM, model yang dihasilkan bertujuan untuk memisahkan data ke dalam kelas-kelas yang berbeda dengan menemukan hyperplane (bidang pemisah) optimal. Proses pelatihan ini melibatkan dua tahap utama: pembentukan model dan penentuan parameter.

![SVM](https://github.com/Aliefindymillani/Mikrokontroler/assets/89888415/55edb2ab-dabb-4ca6-beb8-f56ec28c6270)

Proses pelatihan model SVM ini bertujuan untuk mencapai generalisasi yang baik, di mana model dapat mengklasifikasikan data baru dengan akurasi tinggi. Penting untuk memahami karakteristik data, memilih parameter dengan bijak, dan melakukan validasi untuk memastikan kinerja model yang baik pada data yang tidak terlihat selama pelatihan.

### Evaluasi
Proses evaluasi dilakukan untuk membandingkan kinerja implementasi jaringan SVM sebagai pengganti pengendali PID dalam sistem kontrol. Evaluasi ini akan menilai tiga indikator utama, yakni rising time, settling time, dan overshoot. Rising time mengindikasikan durasi yang dibutuhkan oleh sistem untuk mencapai 90% dari nilai setpoint setelah terjadinya perubahan input. Semakin cepat sistem mencapai nilai setpoint, semakin optimal kinerja sistemnya. Settling time merujuk pada waktu yang diperlukan oleh sistem untuk mencapai nilai yang mendekati setpoint secara stabil, biasanya dalam rentang toleransi tertentu. Semakin singkat settling time, semakin baik kinerja sistemnya. Overshoot mencerminkan kelebihan dari nilai output yang melebihi setpoint sebelum akhirnya mencapai nilai stabil. Overshoot yang tinggi menunjukkan ketidakstabilan atau respons sistem yang tidak diinginkan. Oleh karena itu, semakin rendah nilai overshoot, semakin optimal kinerja sistemnya. Dalam evaluasi ini, kinerja jaringan LSTM akan dibandingkan dengan pengendali PID tradisional dan pengendali PID yang menggunakan deep learning berdasarkan kriteria-kriteria tersebut.

## Hasil Penelitian
Dalam penelitian ini, dilakukan evaluasi kinerja antara pengendali PID tradisional, pengendali PID berbasis deep learning, dan pengendali berbasis LSTM. Tiga metrik evaluasi utama yang digunakan adalah rising time, settling time, dan overshoot.

![PID_Result](https://github.com/Aliefindymillani/Mikrokontroler/assets/89888415/65e20e3a-0a3b-4397-9a3d-267dfc76e8f2)

PID RESULT

![SVM_Result](https://github.com/Aliefindymillani/Mikrokontroler/assets/89888415/1d1b2d0c-7ca9-4559-b181-2d6d81369c8a)

SVM RESULT

Grafik kinerja PID berbasis deep learning memperlihatkan perbandingan antara sistem PID tradisional dan PID SVM dalam beberapa aspek kritis. Pertama, dari segi rising time, sistem PID tradisional menunjukkan kinerja lebih cepat, dengan perbedaan waktu 15 detik lebih singkat dibandingkan dengan PID SVM. Artinya, PID tradisional lebih efisien dalam mencapai 90% dari nilai setpoint setelah terjadinya perubahan input.

Namun, perbandingan pada settling time menunjukkan hasil sebaliknya. Sistem PID tradisional memerlukan waktu lebih lama 1 detik daripada PID SVM untuk mencapai nilai yang mendekati setpoint secara stabil. Ini menunjukkan bahwa, meskipun PID tradisional lebih cepat mencapai 90% setpoint, PID SVM lebih unggul dalam mencapai penyelesaian yang stabil dan mendekati setpoint dengan lebih efisien.

Selanjutnya, analisis pada overshoot menunjukkan bahwa PID tradisional memiliki nilai overshoot yang lebih kecil, yaitu sebesar 0.81%, dibandingkan dengan PID SVM. Hal ini menandakan bahwa sistem kontrol PID tradisional lebih mampu menghasilkan respons yang lebih stabil dan minim overshoot jika dibandingkan dengan implementasi PID SVM.

Dengan demikian, hasil grafik kinerja memberikan gambaran yang komprehensif tentang keunggulan dan kelemahan masing-masing metode pengendalian, memungkinkan pemahaman yang lebih baik tentang performa keduanya dalam konteks spesifik sistem dan tujuan kontrol yang diinginkan.

## Kesimpulan
Berdasarkan hasil evaluasi kinerja sistem kendali, dapat disimpulkan bahwa sistem kendali berbasis SVM memiliki potensi sebagai alternatif yang menarik untuk menggantikan sistem kendali PID tradisional. PID SVM menunjukkan kinerja yang lebih baik dalam hal settling time dan overshoot, menandakan bahwa sistem ini mampu mencapai nilai yang mendekati setpoint secara stabil dengan waktu yang lebih efisien serta menghasilkan respons yang lebih terkontrol dengan overshoot yang lebih kecil dibandingkan dengan PID tradisional. Meskipun demikian, perlu diperhatikan bahwa PID SVM memiliki sedikit kelemahan dalam hal rising time, yang menunjukkan waktu yang dibutuhkan oleh sistem untuk mencapai 90% dari nilai setpoint setelah terjadinya perubahan input. Meskipun demikian, kelebihan pada settling time dan overshoot dapat dianggap sebagai faktor positif yang menunjukkan bahwa pengendalian SVM memiliki performa yang sangat baik dalam mencapai stabilisasi dan respons yang diinginkan dalam suatu sistem. Oleh karena itu, implementasi sistem kendali berbasis SVM dapat menjadi pilihan yang lebih optimal tergantung pada kebutuhan spesifik dan prioritas performa kontrol yang diinginkan dalam suatu aplikasi.









