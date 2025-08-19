# Analisis Pasar Airbnb Bangkok

## 1. Project Overview
Bangkok adalah salah satu kota yang ramai dikunjungi di Asia Tenggara. Setiap tahun nya kota ini dapat menarik jutaan wisatawan dari mancanegera. Di tengah lonjakan pariwisata, banyak calon investor, pemilik properti, dan penyedia akomodasi profesional yang melihat peluang keuntungan dari penyewaan properti di Kota Bangkok. Namun sebelum itu, calon investor dan pemilik properti ingin melakukan analisis terhadap *opportunity* penyewaan properti pada platform Airbnb.

Key Objectives:
1. Menganalisis distribusi properti berdasarkan lokasi
2. Mengevaluasi strategi harga berdasarkan jenis kamar dan lokasi
3. Melihat ketersediaan unit sepanjang tahun, untuk melihat seberapa sering properti banyak disewakan dan bagaimana keuntungannya
4. Mengidentifikasi host dengan jumlah listing terbanyak, untuk melihat *market share*
5. Menganalisis durasi minimum pemesanan untuk melihat apakah listing lebih cocok untuk sewa jangka panjang atau pendek

## 2. Dataset Overview
Data berisi detail mengenai properti listing di kota Bangkok yang terdiri dari nama host, daerah, harga, tipe properti, hingga data review properti.

## 3. Technologies Used
- Programming Language: Python
- Visualization: Matplotlib, Seaborn
- Interactive Dashboard: Tableau
- Development: Jupyter Notebook
- Version Control: Git

## 4. Project Structure
```bash
📁 bangkok-airbnb/
├── 📊 Capstone2_AirbnbAnalysis.ipynb        # analysis report
├── 📊 Capstone2-dashboard-Airbnb.twbx       # dashboard
├── 📖 dataset
    ├── Airbnb Listings Bangkok.csv          # raw data
    ├── Cleaned_Airbnb Listings Bangkok.csv  # cleaned data
    ├── Bangkok-districts.geojson            # geojson of bangkok map
├── 📝 README.md
```
### Delivarables
- [Presentation Link](https://www.canva.com/design/DAGwf1gVV9Q/hiEl4ZXtEq3idXzSkkyBuQ/edit?utm_content=DAGwf1gVV9Q&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
- [Tableau Dashboard Link](https://public.tableau.com/shared/ZYYCB7D8Q?:display_count=n&:origin=viz_share_link)

## 5. Summary of Findings

### 5.1 Business Insights
- Daerah yang berdekatan dengan pusat kota, perbelanjaan, dan wisata sudah memiliki banyak properti listing. Namun, di daerah ini juga memiliki potensi penyewaan yang tinggi.
- Semakin posisi properti dekat dengan pusat kota, maka harga sewa dapat semakin tinggi.
- Dalam usaha properti listing, terdapat kemungkinan bahwa properti tidak terisi secara penuh sepanjang hari dalam satu tahun.
- Jika diasumsikan bahwa host yang memiliki 1 properti bukan merupakan professional host, maka terdapat peluang besar bagi investor untuk menjadi host listing, karena market share tidak dikuasai oleh satu atau sekelompok host tertentu.
- Customer/Penyewa listing dapat dikatakan lebih menyukai penyewaan jangka pendek. Hal ini dapat diasumsikan karena mayoritas tujuan penyewa ke Kota Bangkok adalah untuk berwisata.

### 5.2 Actionable Recommendations
| Aspek                          | Rekomendasi                                                                                                                                                       |
|--------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **1. Pemilihan Lokasi**        | - Pilih lokasi strategis dekat pusat kota, perbelanjaan, dan wisata (contoh: Vadhana, Khlong Toei). <br> - Jika memilih lokasi ramai, berikan *value* lebih (desain menarik, amenities lengkap). |
| **2. Penentuan Harga**         | - Sesuaikan harga dengan rata-rata harga di area sekitar. <br> - Untuk bersaing di lokasi mahal, gunakan strategi *competitive pricing* (sedikit di bawah rata-rata). <br> - Berikan diskon untuk long-stay atau pemesanan awal (*early bird*). |
| **3. Strategi Tingkat Keterisian** | - Terapkan *dynamic pricing* sesuai musim, hari libur, dan permintaan. <br> - Optimalkan deskripsi dan foto di platform agar menarik. <br> - Berikan promo atau potongan harga di musim sepi. |
| **4. Persaingan antar Host**   | - Bangun *brand image* dengan konsistensi layanan (review positif, komunikasi cepat). <br> - Tambahkan layanan ekstra: sarapan gratis, rekomendasi lokal, *self check-in*. <br> - Diferensiasi properti (tema unik, interior aesthetic). |
| **5. Durasi Penyewaan**        | - Fokus pada penyewaan jangka pendek karena lebih diminati wisatawan. <br> - Sediakan opsi fleksibel (mingguan/bulanan) untuk menjangkau digital nomad atau remote worker. |
