# Dashboard-Pengakuan-Pengalaman-Belajar

<d1> Dashboard ini mengelola data pengakuan pengalaman belajar Prodi ILKOM tahun pengakuan 2023 - 2024.
Perancangan dashboard dan manajemen data pengakuan pengalaman belajar ini menggunakan berbagai layanan dari Google, termasuk Google Sheets untuk pengelolaan data dan Google Apps Script (GAS) untuk integrasi, serta Google Looker Studio untuk visualisasi data. Dengan menggunakan kombinasi layanan ini, pengelolaan dan pemantauan pengakuan pengalaman belajar dapat dilakukan secara lebih efisien dan efektif. <br> </d1>
## A. Data Architecture Dashboard Pengakuan Pengalaman Belajar
<img src="https://github.com/Alfinnnnn/Dashboard-Pengakuan-Pengalaman-Belajar/blob/main/Image/Data_Architecture.png"> <br>
1.	Data source didapatkan dari dua sumber yaitu Google Sheets dan webssite input data.
-	Dokumen Google Sheets ini berisi data seluruh Mahasiswa aktif di DEPILKOM UPI yang akan dihubungkan ke dokumen pengelolaan data pengakuan pengalaman belajar.
-	Website input data ini merupakan form yang diisi Mahasiswa ketika akan melakukan pendataan pengakuan pengalaman belajar dari berbagai program.
2.	Data Mahasiswa aktif akan langsung dikirim ke dokumen utama ketika Google sheets yang berisi data Mahasiswa aktif mendapatkan trigger yaitu refresh data. Data hasil inputan dari website mengenai mahasiswa yang melakukan pengakuan pengalaman belajar akan masuk ke dokumen penyimpanan data pengelolaan pengakuan pengalaman belajar dan data akan langsung diolah dan disimpan dalam Google Sheets utama.
3.	Data yang telah diolah dan disimpan di dalam dokumen penyimpanan data pengelolaan pengakuan pengalaman belajar akan divisualisasikan melalui dashboard sebagai media informasi yang digunakan untuk melakukan pemonitoran terhadap proses pengakuan pengalaman belajar yang berjalan. 

## B. Database Architecture
<img src="https://github.com/Alfinnnnn/Dashboard-Pengakuan-Pengalaman-Belajar/blob/main/Image/2-Arsitektur_penyimpanan_data.png"> <br>
<p>Admin prodi memiliki dokumen tersendiri yang berisi data mahasiswa aktif di program studi. Data tersebut akan dihubungkan ke dokumen penyimpanan data pengelolaan pengakuan pengalaman belajar menggunakan Google Apps Script. Selain menghubungkan dokumen mahasiswa aktif Google Apps Script ini juga menyediakan website berupa form yang akan diisi mahasiswa yang akan melakukan pendataan pengakuan pengalaman belajar yang akan otomatis tersimpan dan diolah di dalam dokumen pengelolaan pengakuan pengalaman belajar.</p>
<P>Media penyimpanan data yang digunakan dalam sistem pengelolaan pengakuan pengalaman belajar ini seluruhnya menggunakan Google Sheets. Penggunaan Google Sheets sebagai media penyimpanan data dalam sistem pengelolaan pengakuan pengalaman belajar ini menawarkan banyak kelebihan terutama dari segi aksesibilitas, kolaborasi, dan kemudahan penggunaan. Google Sheets menjadi pilihan yang efisien dan efektif untuk kebutuhan sistem.</P> <br>

## C. Desain Awal Dashboard
<img src="https://github.com/Alfinnnnn/Dashboard-Pengakuan-Pengalaman-Belajar/blob/main/Image/3-DesainAwal.png"> <br>
<p>Desain dibuat untuk memenuhi kebutuhan yang telah dipaparkan. Chart yang dipilih dalam dashboard juga telah disesuaikan dengan kebutuhan. Chart tersebut disusun secara sistematis untuk mempermudah program studi dalam memperoleh informasi mengenai program pengakuan pengalaman belajar mahasiswa. Dengan desain dan visualisasi yang tepat program studi dapat dengan mudah mengakses dan menganalisis data yang relevan dan lebih efektif.</p> <br>

## D. Tampilan Dashboard
<img src="https://github.com/Alfinnnnn/Dashboard-Pengakuan-Pengalaman-Belajar/blob/main/Image/4-Dashboardview1.png"> <br>
<img src="https://github.com/Alfinnnnn/Dashboard-Pengakuan-Pengalaman-Belajar/blob/main/Image/5-Dashboardview2.png"> <br>
<p>Tampilan ini merupakan hasil penyusunan chart visualisasi menjadi dashboard. Setiap chart ditempatkan secara strategis agar saling melengkapi dan memberikan gambaran yang jelas serta terstruktur tentang data yang disajikan. Seperti penempatan control search berada tepat di atas table daftar mahasiswa bertujuan untuk menunjukkan hasil pencarian data mahasiswa secara langsung. Kemudian penempatan scorecard memenuhi dan tidak memenuhi target disusun secara berdampingan bertujuan untuk melihat perbandingan secara langsung antara jumlah dari keduanya. Warna dari scorecard tersebut juga secara langsung merujuk kepada table daftar mahasiswa yang memiliki conditional formatting yaitu ketika jumlah SKS yang dikonversi memenuhi target, data mahasiswa di table akan berwarna biru dan apabila tidak memenuhi akan berwarna merah. Selain itu, dashboard dirancang dengan mempertimbangkan aspek estetika dan fungsionalitas sehingga selain informatif juga nyaman digunakan.</p> <br>

 ## Dashboard Google Looker Studio
[Akses Dashboard Pengakuan Pengalaman Belajar](https://lookerstudio.google.com/reporting/ca3f3d51-9e64-4a50-bb0f-b0894ad8d423)
