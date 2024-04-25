# Capstone-2_Analysis-Airbnb-Bangkok

## Latar Belakang 

Airbnb adalah sebuah perusahaan asal Amerika yang telah tersebar diseluruh dunia yang mengoperasikan pasar online untuk homestay dan pengalaman jangka pendek dan jangka panjang. Saat ini mereka sedang melakukan evaluasi terkait bagaimana prospek hotel di Bangkok dan sasaran pasar yang layak untuk ditingkatkan.

## Penyataan Masalah

Berdasarkan report yang dikeluarkan oleh Travel Weekly ASIA dan Bangkok Post, Bangkok saat ini sedang menghadapi 2 masalah utama khususnya dalam dunia perhotelan yaitu Oversupply dan Unable to Improve Room Rates, tapi disaat bersamaan berdasarkan report yang dikeluarkan oleh JLL Bangkok sedang berada dalam fase recovery pasca pandemi.

Berkaca dari report yang dikeluarkan oleh institusi-institusi tersebut Airbnb ingin mengetahui bagaimana sebenarnya kondisi hotel di Bangkok, apakah sudah sampai pada tahap Oversupply dan kategori hotel seprti pa yang masih dapat terserap dengan cukup baik oleh pasar. Informasi ini akan memudahkan Airbnb dalam menentukan strategi pemasaran, pembukaan hotel baru atau strategi untuk bisa melakukan improve room rates.

### Key Question :
1.	Seperti apakah tipe wisatawan yang mengunjungi Bangkok berdasarkan budget penginapan dan tujuan perjalanan?
2.	Apakah kondisi penginapan di Bangkok saat ini sudah mencapai fase Oversupply?
3.	Apakah memungkinkan untuk menaikan room rates?

#### Assumption and Limiting Conditions :
1.	Analyst meyakini bahwa data yang ada di dataset ini adalah valid sehingga analyst tidak melakukan verifikasi ulang terhadap data.
2.	Asumsi untuk setiap pengunjung hanya dapat memberikan 1 kali review, sehingga setiap review akan dianggap sebagai 1 orang.
3.	Analisa popularitas dari total review hanya menggambarkan seberapa populer tanpa mempertimbangkan apakah itu berupa sentimen positif atau negatif
4.	Untuk setiap angka yang kurang dari 365 pada kolom `availability_365` akan dianggap telah dibooking oleh tamu, sehingga kemungkinan bahwa itu bahwa penginapan tersebut dipakai pribadi oleh owner ditiadakan pada analisa ini.
5.	Asumsi mata uang yang digunakan adalah Baht Thailand (฿)

***Running the Program :***
Install : 
•	Missingno
•	Folium
•	Geopandas

## Kesimpulan:
•	Tujuan wisata yang paling populer diantara wisatawan di Bangkok adalah wisata belanja dan bisnis di Commercial & Trade and Service Area yang terpusat di district Khlonmg Toei, Vadhana dan Ratchathewi.
•	Mayoritas Wisatawan yang mengunjungi Bangkok adalah Luxury Traveler yang memiliki budget untuk penginapan sebesar ฿1.690 - ฿2.430/room/night dengan kecenderungan untuk memimilih penginapan dengan tipe Entire home/apartment.
•	Saat ini Bangkok sudah berada dalam fase Oversupply penginapan, dimana rata-rata occupancy penginapan hanya berada di 33,05%, dengan occupancy terendah ada pada penginapan dengan kategori Luxury Class. 
•	Ratio penginapan dengan Occupancy tertinggi yang masih layak secara ekonomi juga dimiliki oleh Luxury Class yaitu sebesar 27,3% dari semua jenis penginapan yang memiliki peak occupancy, sehingga masih memungkinkan untuk menaikan room rates.

## Rekomendasi :

**- Tahan Ekspansi pada Daerah yang Memiliki Destinasi Unggulan Berupa Kuil dan Situs Keagamaan:**

Airbnb saat ini menjadi market leader di Bangkok dengan market share sebesar 78,3% sehingga tidak perlu untuk melakukan ekspansi secara agresif terutama pada daerah yang destinasi utamanya adalah Kuil dan Situs Keagamaant. Selain karena jumlah wisatawan yang mengunjungi daerah tersebut cukup sedikit, tingkat occupancy di wilayah tersebut merupakan salah satu yang terendah.

**- Ekspansi Bisnis di Commercial & Trade and Service Area:**

Commercial & Trade and Service Area masih memiliki potensi untuk dikembangkan lagi oleh airbnb, disarankan untuk memperluas jumlah listing melalui district yang persebaran properti nya masih sedikit. Tipe penginapan yang disarankan adalah penginapan dengan tipe entire home/apartment dengan kategory Luxury Class yang memiliki harga diatas ฿2.430/room/night

**- Sediakan Akses atau Jalin Kerjasama dengan Pusat Perbelanjaan:**

Tujuan terbesar wisatawan yang ada di Bangkok adalah wisata belanja dan perjalanan bisnis, sehingga akan lebih menarik jika penginapan memiliki akses yang mudah menuju pusat-pusat perbelanjaan dan bisnis, serta memiliki kerjasama exclusive seperti potongan harga jika berbelanja di pusat perbelanjaan tertentu.

**- Berikan Promo Bundling untuk Wisata Kuil dan Situs Keagamaan:**

Sediakan promo bundling untuk setiap wisatawan yang mengunjungi Commercial & Trade and Service Area untuk merasakan pengalaman berlibur ditempat dengan keunggulan wisata berupa Kuil dan Situs Keagamaan, untuk meningkatkan occupancy district tersebut.


## Access to Tableu

You can access the visualization on Tableu via this [link](https://public.tableau.com/app/profile/hans.bonnie/viz/AirbnbAnalysis-HansBonnie/HomeDashboard?publish=yes)
