Capstone Project Module 2 JCDSLS - Kevin Pratama

# Customer Personality Analysis
<br>

## Latar Belakang
---
Selama 2 tahun terakhir sebuah perusahaan telah beberapa kali menjalankan marketing campaign untuk menarik customer dan diharapkan dapat meningkatkan penjualan produk-produk mereka. Perusahaan ingin mengetahui hasil dari marketing campaign yang telah dijalankan dengan Customer Personality Analysis.
<br>

## **Pernyataan Masalah**
---
Perusahaan ingin mengetahui karakteristik customer yang paling memungkinkan untuk membeli tiap-tiap produk agar strategi marketing campaign dapat difokuskan ke karakteristik customer tersebut daripada membuat strategi marketing campaign untuk semua tipe customer. <br>
Dengan membuat strategi marketing campaign yang terfokus pada karakteristik customer per masing-masing produk diharapkan dapat menekan biaya marketing campaign dan dapat meningkatkan penjualan masing-masing produk tersebut.

Sebagai seorang *data analyst*, kita akan mencoba menjawab pertanyaan berikut:
- **Bagaimana performa marketing campaign yang telah dijalankan oleh perusahaan?**
- **Bagaimana karakteristik customer dari masing-masing produk yang dipasarkan oleh perusahaan?**
<br>

## **Data**
---
Untuk menjawab pertanyaan di atas, kita akan menganalisa data peserta yang sudah dikumpulkan oleh perusahaan. Dataset dapat diakses [di sini](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis). <br>
Dataset ini berisi informasi terkait karakteristk populasi customer dari banyak variable seperti tahun kelahiran, tingkat pendidikan, status perkawinan dll. Ada 29 kolom yang dibagi ke dalam 5 bagian di dataset marketing_campaign, yaitu:

People

- ID: Id unik tiap customer
- Year_Birth: Tahun kelahiran
- Education: Tingkat pendidikan customer
- Marital_Status: Status perkawinan customer
- Income: Pendapatan customer per tahun
- Kidhome: Jumlah anak kecil yang dimiliki customer
- Teenhome: Jumlah anak remaja yang dimiliki customer
- Dt_Customer: Tanggal pendaftaran customer ke perusahaan
- Recency: Jumlah hari sejak customer melakukan transaksi terakhir
- Complain: 1 jika customer melakukan komplain sejak dua tahun terakhir, 0 lainnya

Products

- MntWines: Jumlah belanja untuk produk Wine selama dua tahun terakhir
- MntFruits: Jumlah belanja untuk produk Buah selama dua tahun terakhir
- MntMeatProducts: Jumlah belanja untuk produk daging selama dua tahun terakhir
- MntFishProducts: Jumlah belanja untuk produk Ikan selama dua tahun terakhir
- MntSweetProducts: Jumlah belanja untuk produk Manisan selama dua tahun terakhir
- MntGoldProds: Jumlah belanja untuk produk Emas selama dua tahun terakhir

Promotion

- NumDealsPurchases: Jumlah pembelian menggunakan diskon
- AcceptedCmp1: 1 jika customer menerima penawaran di campaign ke-1, 0 lainnya
- AcceptedCmp2: 1 jika customer menerima penawaran di campaign ke-2, 0 lainnya
- AcceptedCmp3: 1 jika customer menerima penawaran di campaign ke-3, 0 lainnya
- AcceptedCmp4: 1 jika customer menerima penawaran di campaign ke-4, 0 lainnya
- AcceptedCmp5: 1 jika customer menerima penawaran di campaign ke-5, 0 lainnya
- Response: 1 jika customer menerima penawaran di campaign yang terakhir (diasumsikan campaign terakhir adalah campaign ke-6), 0 lainnya

Place

- NumWebPurchases: Jumlah pembelian melalui website perusahaan
- NumCatalogPurchases: Jumlah pembelian melalui menggunakan katalog
- NumStorePurchases: Jumlah pembelian langsung di toko
- NumWebVisitsMonth: Jumlah kunjungan ke website perusahaan pada bulan terakhir

Other

- Z_CostContact: Kolom tidak mempunyai arti pada dataset dan tidak mempunyai peran dalam analisis.
- Z_Revenue: Kolom tidak mempunyai arti pada dataset dan tidak mempunyai peran dalam analisis.
<br>

## **Data Understanding**
---
Di step data understanding dilakukan:
- cek info dataset
- cek unique value
- cek duplicate
- cek missing value
- cek outlier
<br>

## **Data Preparation**
---
Di step data preparation dilakukan:
- penanganan kolom-kolom yang memiliki anomali
- penanganan missing value
- penanganan outlier
- membuat kolom baru yang dibutuhkan untuk analisis data
- menghsopus kolom yang redundant
<br>

## **Data Analysis**
---
Di step data analysis dilakukan:
- analisa korelasi antar kolom
- analisa penerimaan customer terhadap marketing campaign yang telah berjalan sebelumnya
- analisa karakteristik customer untuk setiap produk
<br>

## **Kesimpulan**
---
Dari analisis yang telah dilakukan, kita bisa membuat kesimpulan berikut :
* Marketing campaign yang telah dijalankan perusahaan selama 2 tahun terakhir kurang berhasil karena hanya 27% saja dari total populasi customer yang menerima campaign.
* Engagement customer dari web perusahaan kurang baik
* Karakteristik customer dari produk-produk yang dipasarkan perusahaan sepertinya mengarah kepada kelompok usia Babyboomers, status parent ,dan tingkat pendidikan yang hampir seimbang antara undergraduate dan post graduate.
* Kelompok usia Millenials hampir menyamai rata-rata Babyboomers dalam mengeluarkan uang untuk membeli produk Meat dan Fish


## **Rekomendasi**
---
1. Perusahaan diharapkan meningkatkan kualiitas dari web miliknya agar dapat meningkatkan engagement customer dari web.
2. Perusahaan diharapkan dapat menjalankan strategi marketing campaign yang menyasar usia Babyboomers dan status parent untuk seluruh produk yang dijual
3. Untuk produk Meat dan Fish perusahaan juga dapat melakukan strategi marketing campaign yang menyasar kelompok usia Millenials

Dengan mengetahui karakteristik customer dari analisa ini diharapkan perusahaan dapat menjalankan strategi marketing campaign yang terfokus, sehingga dapat menekan biaya marketing campaign, serta dapat meningkatkan performa marketing campaign selama 2 tahun terakhir yang kurang baik.
