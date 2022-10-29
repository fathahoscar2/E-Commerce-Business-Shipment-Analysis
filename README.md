# E-Commerce-Business-Shipment-Analysis
Merupakan hasil dari Final Project yang diselenggarakan oleh Rakamin Academy
Data source : https://www.kaggle.com/prachi13/customer-analytics

<h2>Descriptive Statistics</h2>

Beberapa Informasi awal yang didapatkan dari dataset:
1. Semua nama dan tipe data dari kolom telah sesuai syarat
2. Tidak terdapat kolom yang bernilai Null atau Missing Value
3. Terdapat 2 kolom yang kemungkinan memiliki nilai outlier yaitu Purchases dan Discounts

<h2>Univariate Analysis</h2>

![image](https://user-images.githubusercontent.com/116931476/198826633-e661b6ce-a111-4677-b98d-f07ec75cc46f.png)










![image](https://user-images.githubusercontent.com/116931476/198826755-b6c0903f-8940-403b-a94b-13faf1ede974.png)
<strong>Beberapa kesimpulan dari Tabel di atas:</strong>
1. Variabel yang memiliki outlier (Purchases dan Discounts) pada grafik terlihat dengan pola Positively Skewed
2. Variabel Cost terlihat paling mendekati pola distribusi normal
3. Warehouse Block yang paling banyak digunakan adalah F
4. Shipment kapal yang paling sering digunakan yaitu Kapal
5. Jumlah data yang mengalami keterlambatan terlihat lebih banyak



<h2>Multivariate Analysis</h2>

![image](https://user-images.githubusercontent.com/116931476/198830375-3755c34a-7572-40ed-80db-ebdfd4a02d88.png)
<strong>Beberapa kesimpulan dari Tabel di atas:</strong>
1. Feature yang paling berkaitan dengan target yaitu Discount dan Weight
2. Korelasi antar feature yang cukup kuat yaitu pada Weight - Calls, Weight - Discount, Cost - Calls

<h2>Business Insight and Recommendation</h2>
<strong>- Untuk pembelian produk dengan discount diatas 10% banyak mengalami keterlambatan pengiriman.</strong>Dalam hal ini pihak e-commerce perlu memberikan notifikasi keterlambatan pengiriman kepada customer ketika melakukan pembelian dengan menggunakan discount yang besar yang memungkinkan produk yang dipesan tidak terkirim tepat waktu.

<strong>- Barang dengan berat 2-4 Kg terkonfirmasi mengalami keterlambatan pengiriman.</strong> Dalam hal ini, pihak e-commerce perlu memberikan notifikasi keterlambatan pengiriman kepada customer yang membeli produk di rentang berat produk 2-4 kg sebelum customer melakukan transaksi.

<strong>- Semakin banyak customer care calls yang terjadi maka tingkat keterlambatan pengiriman semakin menurun.</strong> Berdasarkan data jumlah keterlambatan pengiriman menurun dengan meningkatnya jumlah telepon yang diterima oleh customer care. Perusahaan perlu mencari informasi mengenai isi telepon customer kepada customer care (siapa penelpon, isi telepon), sehingga bisa menentukan korelasi dengan jumlah keterlambatan pengiriman.

<strong> Berikut ini rekomendasi bisnis dengan Asumsi:</strong>
1. Bila di asumsikan bahwa pelanggan menelpon untuk melakukan konfirmasi pemesanan, maka bisa dilakukan proses konfirmasi pemesanan dari pelanggan memberikan pengingat kepada penjual untuk segera melakukan konfirmasi ketersediaan barang dan kesiapaan pengiriman kepada bagian pengiriman atau kurir. (bisa dengan aplikasi atau ditambahkan pada petugas tertentu).

2. Bila di asumsikan bahwa penjual menelpon untuk melakukan konfirmasi kesediaan pesanan dan barang siap di kirim, maka bisa dilakukan proses otomatisasi saat penjual konfirmasi kesediaan barang, langsung barang disiapkan untuk di kirim pada hari yang sama dan mengirimkan konfirmasi untuk kurir mengirimkan.
