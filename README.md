# Machine-Learning-week-8-16
![image](https://github.com/user-attachments/assets/398e1712-2730-4525-97c9-7a30bf2fda22)
## Bagian I. Dasar-dasar Pembelajaran Mesin		
1.	Lanskap Pembelajaran Mesin	1
  - Apa Itu Pembelajaran Mesin?	2
  - Mengapa Menggunakan Pembelajaran Mesin?	2
  - Contoh Aplikasi	5
  - Jenis Sistem Pembelajaran Mesin	7
  - Pembelajaran Terawasi/Tidak Terawasi	7
  - Pembelajaran Batch dan Online	14
  - Pembelajaran Berbasis Contoh versus Berbasis Model	17
  - Tantangan Utama Pembelajaran Mesin	23
  - Kuantitas Data Pelatihan yang Tidak Cukup	23
  - Data Pelatihan yang Tidak Representatif	25
  - Data Berkualitas Buruk	26
  - Fitur yang Tidak Relevan	27
  - Overfitting Data Pelatihan	27
  - Underfitting Data Pelatihan	29
  - Mundur Sejenak	30
  - Pengujian dan Validasi	30
  - Penyesuaian Hyperparameter dan Pemilihan Model	31
  - Ketidaksesuaian Data	32
  - Latihan	33
2.	Proyek Pembelajaran Mesin End-to-End	35
Bekerja dengan Data Nyata	35
Melihat Gambaran Besar	37
Merumuskan Masalah	37
Memilih Ukuran Kinerja	39
Mendapatkan Data	42
Membuat Ruang Kerja	42
Mengunduh Data	46
Melihat Cepat Struktur Data	47
Membuat Set Uji	51
Menjelajahi dan Memvisualisasikan Data untuk Mendapatkan Wawasan	56
Memvisualisasikan Data Geografis	56
Mencari Korelasi	58
Bereksperimen dengan Kombinasi Atribut	61
Mempersiapkan Data untuk Algoritma Pembelajaran Mesin	62
Pembersihan Data	63
Menangani Atribut Teks dan Kategorikal	65
Transformer Kustom	68
Skala Fitur	69
Pipeline Transformasi	70
Memilih dan Melatih Model	72
Melatih dan Mengevaluasi pada Set Pelatihan	72
Evaluasi yang Lebih Baik Menggunakan Cross-Validation	73
Menyesuaikan Model Anda	75
Pencarian Grid	76
Pencarian Acak	78
Metode Ensemble	78
Menganalisis Model Terbaik dan Kesalahan Mereka	78
Mengevaluasi Sistem Anda pada Set Uji	79
Meluncurkan, Memantau, dan Memelihara Sistem Anda	80
Cobalah!	83
Latihan	84
3.	Klasifikasi	85
MNIST	85
Melatih Pengklasifikasi Biner	88
Ukuran Kinerja	88
Mengukur Akurasi Menggunakan Cross-Validation	89
Matriks Kebingungan	90
Presisi dan Recall	92
Trade-off Presisi/Recall	93
Kurva ROC	97
Klasifikasi Multikelas	100
Analisis Kesalahan	102
Klasifikasi Multilabel	106
Klasifikasi Multioutput	107
Latihan	108
4.	Melatih Model	111
Regresi Linier	112
Persamaan Normal	114
Kompleksitas Komputasi	117
Penurunan Gradien	118
Penurunan Gradien Batch	121
Penurunan Gradien Stokastik	124
Penurunan Gradien Mini-batch	127
Regresi Polinomial	128
Kurva Pembelajaran	130
Model Linier Teregulasi	134
Regresi Ridge	135
Regresi Lasso	137
Jaring Elastis	140
Penghentian Awal	141
Regresi Logistik	142
Memperkirakan Probabilitas	143
Pelatihan dan Fungsi Biaya	144
Batas Keputusan	145
Regresi Softmax	148
Latihan	151
5.	Mesin Vektor Dukungan	153
Klasifikasi SVM Linier	153
Klasifikasi Margin Lunak	154
Klasifikasi SVM Nonlinier	157
Kernel Polinomial	158
Fitur Kesamaan	159
Kernel RBF Gaussian	160
Kompleksitas Komputasi	162
Regresi SVM	162
Di Bawah Kap	164
Fungsi Keputusan dan Prediksi	165
Tujuan Pelatihan	166
Pemrograman Kuadrat	167
Masalah Ganda	168
SVM Berkernel	169
SVM Online	172
Latihan	174
6.	Pohon Keputusan	175
Melatih dan Memvisualisasikan Pohon Keputusan	175
Membuat Prediksi	176
Memperkirakan Probabilitas Kelas	178
Algoritma Pelatihan CART	179
Kompleksitas Komputasi	180
Impuritas Gini atau Entropi?	180
Hyperparameter Regulasi	181
Regresi	183
Ketidakstabilan	185
Latihan	186
7.	Pembelajaran Ensemble dan Hutan Acak	189
Pengklasifikasi Pemungutan Suara	189
Bagging dan Pasting	192
Bagging dan Pasting di Scikit-Learn	194
Evaluasi Out-of-Bag	195
Patch Acak dan Subruang Acak	196
Hutan Acak	197
Extra-Trees	198
Pentingnya Fitur	198
Boosting	199
AdaBoost	200
Gradient Boosting	203
Stacking	208
Latihan	211
8.	Reduksi Dimensi	213
Kutukan Dimensi	214
Pendekatan Utama untuk Reduksi Dimensi	215
Proyeksi	215
Pembelajaran Manifold	218
PCA	219
Mempertahankan Varians	219
Komponen Utama	220
Memproyeksikan ke d Dimensi	221
Menggunakan Scikit-Learn	222
Rasio Varians yang Dijelaskan	222
Memilih Jumlah Dimensi yang Tepat	223
PCA untuk Kompresi	224
PCA Acak	225
PCA Inkremental	225
Kernel PCA	226
Memilih Kernel dan Menyesuaikan Hyperparameter	227
LLE	230
Teknik Reduksi Dimensi Lainnya	232
Latihan	233
9.	Teknik Pembelajaran Tanpa Pengawasan	235
Pengelompokan	236
K-Means	238
Batas K-Means	248
Menggunakan Pengelompokan untuk Segmentasi Gambar	249
Menggunakan Pengelompokan untuk Preprocessing	251
Menggunakan Pengelompokan untuk Pembelajaran Semi-Terawasi	253
DBSCAN	255
Algoritma Pengelompokan Lainnya	258
Campuran Gaussian	260
Deteksi Anomali Menggunakan Campuran Gaussian	266
Memilih Jumlah Klaster	267
Model Campuran Gaussian Bayesian	270
Algoritma Lain untuk Deteksi Anomali dan Kebaruan	274
Latihan	275
Bagian II. Jaringan Saraf dan Pembelajaran Mendalam		
10.	Pengantar Jaringan Saraf Tiruan dengan Keras	279
Dari Neuron Biologis ke Buatan	280
Neuron Biologis	281
Perhitungan Logis dengan Neuron	283
Perceptron	284
Perceptron Multilayer dan Backpropagation	289
MLP Regresi	292
MLP Klasifikasi	294
Mengimplementasikan MLP dengan Keras	295
Menginstal TensorFlow 2	296
Membangun Pengklasifikasi Gambar Menggunakan API Sekuensial	297
Membangun MLP Regresi Menggunakan API Sekuensial	307
Membangun Model Kompleks Menggunakan API Fungsional	308
Menggunakan API Subclassing untuk Membangun Model Dinamis	313
Menyimpan dan Mengembalikan Model	314
Menggunakan Callbacks	315
Menggunakan TensorBoard untuk Visualisasi	317
Penyesuaian Hyperparameter Jaringan Saraf	320
Jumlah Lapisan Tersembunyi	323
Jumlah Neuron per Lapisan Tersembunyi	324
Tingkat Pembelajaran, Ukuran Batch, dan Hyperparameter Lainnya	325
Latihan	327
11.	Melatih Jaringan Saraf Dalam	331
Masalah Gradien Menghilang/Meledak	332
Inisialisasi Glorot dan He	333
Fungsi Aktivasi Tidak Jenuh	335
Normalisasi Batch	338
Pemotongan Gradien	345
Menggunakan Kembali Lapisan yang Sudah Dilatih	345
Pembelajaran Transfer dengan Keras	347
Pretraining Tanpa Pengawasan	349
Pretraining pada Tugas Pembantu	350
Pengoptimal Lebih Cepat	351
Pengoptimalan Momentum	351
Gradien Percepatan Nesterov	353
AdaGrad	354
RMSProp	355
Pengoptimalan Adam dan Nadam	356
Penjadwalan Tingkat Pembelajaran	359
Menghindari Overfitting Melalui Regulasi	364
Regulasi l1 dan l2	364
Dropout	365
Dropout Monte Carlo (MC)	368
Regulasi Max-Norm	370
Ringkasan dan Pedoman Praktis	371
Latihan	373
12.	Model Kustom dan Pelatihan dengan TensorFlow	375
Tur Cepat TensorFlow	376
Menggunakan TensorFlow seperti NumPy	379
Tensor dan Operasi	379
Tensor dan NumPy	381
Konversi Tipe	381
Variabel	382
Struktur Data Lainnya	383
Menyesuaikan Model dan Algoritma Pelatihan	384
Fungsi Kerugian Kustom	384
Menyimpan dan Memuat Model yang Berisi Komponen Kustom	385
Fungsi Aktivasi, Inisialisasi, Regulator, dan Kendala Kustom	387
Metrik Kustom	388
Lapisan Kustom	391
Model Kustom	394
Kerugian dan Metrik Berdasarkan Internal Model	397
Menghitung Gradien Menggunakan Autodiff	399
Loop Pelatihan Kustom	402
Fungsi dan Grafik TensorFlow	405
AutoGraph dan Pelacakan	407
Aturan Fungsi TF	409
Latihan	410
13.	Memuat dan Memproses Data dengan TensorFlow	413
API Data	414
Rantai Transformasi	415
Mengacak Data	416
Memproses Data	419
Menyusun Semuanya	420
Pra-pengambilan	421
Menggunakan Dataset dengan tf.keras	423
Format TFRecord	424
File TFRecord Terkompresi	425
Pengantar Singkat Buffer Protokol	425
Buffer Protokol TensorFlow	427
Memuat dan Mengurai Contoh	428
Menangani Daftar Daftar Menggunakan Protokol SequenceExample	429
Memproses Fitur Input	430
Mengodekan Fitur Kategorikal Menggunakan Vektor One-Hot	431
Mengodekan Fitur Kategorikal Menggunakan Embeddings	433
Lapisan Praproses Keras	437
Transformasi TF	439
Proyek Dataset TensorFlow (TFDS)	441
Latihan	442
14.	Visi Komputer Mendalam Menggunakan Jaringan Saraf Konvolusional	445
Arsitektur Korteks Visual	446
Lapisan Konvolusional	448
Filter	450
Menumpuk Beberapa Peta Fitur	451
Implementasi TensorFlow	453
Persyaratan Memori	456
Lapisan Pooling	456
Implementasi TensorFlow	458
Arsitektur CNN	460
LeNet-5	463
AlexNet	464
GoogLeNet	466
VGGNet	470
ResNet	471
Xception	474
SENet	476
Mengimplementasikan CNN ResNet-34 Menggunakan Keras	478
Menggunakan Model yang Sudah Dilatih dari Keras	479
Model yang Sudah Dilatih untuk Pembelajaran Transfer	481
Klasifikasi dan Lokalisasi	483
Deteksi Objek	485
Jaringan Sepenuhnya Konvolusional	487
Anda Hanya Melihat Sekali (YOLO)	489
Segmentasi Semantik	492
Latihan	496
15.	Memproses Urutan Menggunakan RNN dan CNN	497
Neuron dan Lapisan Rekuren	498
Sel Memori	500
Urutan Input dan Output	501
Melatih RNN	502
Memperkirakan Deret Waktu	503
Metrik Baseline	505
Mengimplementasikan RNN Sederhana	505
RNN Dalam	506
Memperkirakan Beberapa Langkah Waktu ke Depan	508
Menangani Urutan Panjang	511
Melawan Masalah Gradien yang Tidak Stabil	512
Mengatasi Masalah Memori Jangka Pendek	514
Latihan	523
16.	Pemrosesan Bahasa Alami dengan RNN dan Perhatian	525
Membuat Teks Shakespeare Menggunakan RNN Karakter	526
Membuat Dataset Pelatihan	527
Cara Membagi Dataset Sekuensial	527
Memotong Dataset Sekuensial Menjadi Beberapa Jendela	528
Membangun dan Melatih Model Char-RNN	530
Menggunakan Model Char-RNN	531
Membuat Teks Shakespeare Palsu	531
RNN Stateful	532
Analisis Sentimen	534
Masking	538
Menggunakan Kembali Embeddings yang Sudah Dilatih	540
Jaringan Encoder-Decoder untuk Terjemahan Mesin Saraf	542
RNN Bidireksional	546
Pencarian Balok	547
Mekanisme Perhatian	549
Perhatian Visual	552
Perhatian Adalah Segalanya yang Anda Butuhkan: Arsitektur Transformer	554
Inovasi Terbaru dalam Model Bahasa	563
Latihan	565
17.	Pembelajaran Representasi dan Pembelajaran Generatif Menggunakan Autoencoder dan GAN	567
Representasi Data yang Efisien	569
Melakukan PCA dengan Autoencoder Linier Kurang Lengkap	570
Autoencoder Bertumpuk	572
Mengimplementasikan Autoencoder Bertumpuk Menggunakan Keras	572
Memvisualisasikan Rekonstruksi	574
Memvisualisasikan Dataset Fashion MNIST	574
Pretraining Tanpa Pengawasan Menggunakan Autoencoder Bertumpuk	576
Mengikat Bobot	577
Melatih Satu Autoencoder pada Satu Waktu	578
Autoencoder Konvolusional	579
Autoencoder Rekuren	580
Autoencoder Peredam Kebisingan	581
Autoencoder Sparse	582
Autoencoder Variasional	586
Membuat Gambar Fashion MNIST	590
Jaringan Adversarial Generatif	592
Kesulitan Melatih GAN	596
GAN Konvolusional Dalam	598
Pertumbuhan Progresif GAN	601
StyleGAN	604
Latihan	607
18.	Pembelajaran Penguatan	609
Belajar Mengoptimalkan Hadiah	610
Pencarian Kebijakan	612
Pengantar OpenAI Gym	613
Kebijakan Jaringan Saraf	617
Mengevaluasi Tindakan: Masalah Penugasan Kredit	619
Gradien Kebijakan	620
Proses Keputusan Markov	625
Pembelajaran Perbedaan Temporal	629
Q-Learning	630
Kebijakan Eksplorasi	632
Q-Learning Perkiraan dan Q-Learning Dalam	633
Mengimplementasikan Q-Learning Dalam	634
Varian Q-Learning Dalam	639
Target Nilai Q Tetap	639
Double DQN	640
Pengalaman Prioritas Replay	640
Dueling DQN	641
Perpustakaan TF-Agents	642
Menginstal TF-Agents	643
Lingkungan TF-Agents	643
Spesifikasi Lingkungan	644
Wrapper Lingkungan dan Praproses Atari	645
Arsitektur Pelatihan	649
Membuat Jaringan Q Dalam	650
Membuat Agen DQN	652
Membuat Buffer Replay dan Observer yang Sesuai	654
Membuat Metrik Pelatihan	655
Membuat Driver Pengumpul	656
Membuat Dataset	658
Membuat Loop Pelatihan	661
Ikhtisar Beberapa Algoritma RL Populer	662
Latihan	664
19.	Melatih dan Menyebarkan Model TensorFlow pada Skala Besar	667
Melayani Model TensorFlow	668
Menggunakan TensorFlow Serving	668
Mengekspor SavedModels	669
Menginstal TensorFlow Serving	672
Mengakses TF Serving melalui REST API	673
Mengakses TF Serving melalui gRPC API	674
Menyebarkan Versi Model Baru	675
Membuat Layanan Prediksi di GCP AI Platform	677
Menggunakan Layanan Prediksi	682
Menyebarkan Model ke Perangkat Seluler atau Tersemat	685
Menggunakan GPU untuk Mempercepat Komputasi	689
Mendapatkan GPU Sendiri	690
Menggunakan Mesin Virtual yang Dilengkapi GPU	692
Kolaborasi	693
Mengelola RAM GPU	694
Menempatkan Operasi dan Variabel pada Perangkat	697
Eksekusi Paralel di Beberapa Perangkat	699
Melatih Model di Beberapa Perangkat	701
Paralelisme Model	701
Paralelisme Data	704
Melatih pada Skala Besar Menggunakan API Strategi Distribusi	709
Melatih Model pada Klaster TensorFlow	711
Menjalankan Pekerjaan Pelatihan Besar di Google Cloud AI Platform	714
Penyesuaian Hyperparameter Kotak Hitam di AI Platform	716
Latihan	717
Ucapan Terima Kasih!		718
Lampiran A	Solusi Latihan	719
Lampiran B	Daftar Periksa Proyek Pembelajaran Mesin	755
Lampiran C	Masalah Dual SVM	761
Lampiran D	Autodiff	765
Lampiran E	Arsitektur ANN Populer Lainnya	773
Lampiran F	Struktur Data Khusus	783
Lampiran G	Grafik TensorFlow	791
Indeks		801
