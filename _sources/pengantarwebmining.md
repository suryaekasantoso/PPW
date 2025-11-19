# Pengantar Web Mining

### Web Mining

Web mining atau penambangan web merupakan serangkaian teknik untuk menggali serta mengambil informasi dari internet. Proses ini mengombinasikan pendekatan dari data mining, machine learning, pemrosesan bahasa alami, hingga analisis graf. Hasil dari web mining dapat digunakan untuk mendukung pengambilan keputusan, memahami perilaku pengguna, maupun memprediksi tren di berbagai bidang. Web Mining adalah pemanfaatan metode data mining untuk menemukan informasi secara otomatis dari layanan berbasis web. Tujuan dari penambangan web adalah menemukan pola atau pengetahuan yang bermanfaat dari hyperlink, konten halaman, maupun interaksi pengguna.

### Web Crawling

Web crawling adalah proses otomatis untuk menjelajahi dan mengumpulkan data dari halaman-halaman web dengan menggunakan perangkat lunak khusus yang disebut crawler atau spider. Crawler bekerja dengan cara mengunjungi sebuah halaman web, membaca isinya, lalu mengikuti hyperlink yang ada di dalamnya untuk menemukan halaman-halaman baru. Proses ini berjalan terus-menerus sehingga memungkinkan pengumpulan data dalam skala besar dari berbagai situs web. Hasil crawling dapat berupa teks, metadata, atau struktur halaman yang kemudian disimpan dalam basis data untuk dianalisis lebih lanjut. Teknologi ini menjadi dasar bagi mesin pencari seperti Google dalam membangun indeks halaman web, sekaligus mendukung berbagai aplikasi web mining yang membutuhkan data masif sebagai bahan analisis.

### Web Data Preprocessing

Web Data Preprocessing adalah tahap penting dalam web mining yang bertujuan menyiapkan data mentah dari web agar dapat digunakan secara efektif dalam proses penambangan. Data yang diperoleh dari internet biasanya dalam kondisi tidak terstruktur, berisik (noisy), atau bahkan redundan, sehingga perlu dilakukan pembersihan dan transformasi. Tahapan preprocessing meliputi pembersihan data dari elemen yang tidak relevan (seperti tag HTML atau script), normalisasi teks (misalnya tokenization, stopword removal, stemming), pengubahan data ke dalam format terstruktur seperti tabel atau vektor, serta integrasi dari berbagai sumber data. Selain itu, sering dilakukan juga reduksi dimensi dan seleksi fitur untuk menyederhanakan representasi data tanpa menghilangkan informasi penting.

### Pembelajaran Terawasi (Supervised Learning)

Pembelajaran Terawasi (Supervised Learning) adalah metode machine learning yang memanfaatkan data berlabel, artinya setiap data masukan memiliki jawaban yang benar. Model dilatih untuk mengenali pola dari data tersebut sehingga dapat memprediksi label pada data baru. Contoh penerapannya adalah deteksi email spam, klasifikasi dokumen, serta analisis sentimen pada ulasan produk atau media sosial.

### Pembelajaran Tak terawasi (Unsupervised Learning)

Pembelajaran Tak Terawasi (Unsupervised Learning) adalah metode machine learning yang digunakan pada data tanpa label, sehingga sistem berusaha menemukan pola atau struktur tersembunyi secara otomatis. Tujuannya bukan untuk memprediksi jawaban, melainkan untuk mengelompokkan data atau menemukan keterkaitan di dalamnya. Contoh penerapannya antara lain clustering dokumen untuk menemukan topik, pengelompokan pelanggan berdasarkan perilaku belanja, serta dimensionality reduction untuk menyederhanakan data besar agar lebih mudah dianalisis.

### Web Content Mining (Text Mining)

Web content mining berfokus pada isi halaman web, baik berupa teks, gambar, audio, video, maupun data terstruktur. Dalam konteks text mining, tujuannya adalah mengekstrak informasi berharga dari teks, seperti klasifikasi dokumen, analisis sentimen, topic modelling, atau peringkasan otomatis.

### Web Usage Mining

Web usage mining menganalisis data perilaku pengguna yang terekam dalam log server, cookies, maupun clickstream. Dari data ini dapat ditemukan pola kunjungan, jalur navigasi, atau preferensi pengguna. Aplikasinya antara lain sistem rekomendasi produk, personalisasi konten, dan optimasi tampilan website.

### Web Structure Mining (Graph Mining)
Web structure mining memanfaatkan struktur hyperlink atau hubungan antar pengguna di web, yang biasanya direpresentasikan dalam bentuk graf. Analisis ini dapat digunakan untuk menentukan otoritas halaman (misalnya algoritma PageRank), mendeteksi komunitas, serta mengidentifikasi aktor penting seperti influencer dalam jaringan sosial.

### Deployment System
Deployment system adalah tahap penerapan hasil web mining ke dalam sistem nyata agar dapat dimanfaatkan pengguna. Contohnya adalah mesin pencari yang menampilkan hasil peringkat halaman, sistem rekomendasi pada e-commerce, atau dashboard analisis data. Tahap ini memastikan pola dan model yang ditemukan bisa memberi nilai praktis dan mendukung pengambilan keputusan.