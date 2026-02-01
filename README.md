# ♻️ Integrated Circular Economy Hub: Bandung City

Proyek ini merupakan analisis geospasial tingkat lanjut untuk menentukan lokasi optimal pembangunan **Integrated Circular Economy Hub** di Kota Bandung. Dengan menggabungkan metode **Multi-Criteria Decision Analysis (MCDA)** dan eksplorasi data **Hyperlocal**, proyek ini bertujuan menciptakan ekosistem sampah mandiri yang menghubungkan sumber limbah domestik dengan unit pengolahan nilai tambah (*upcycling*).

## 📌 1. Penjelasan Studi Kasus
Fokus utama studi ini adalah mengoptimalkan pemilihan lokasi guna mencapai efisiensi operasional tertinggi. Hub ini dirancang untuk:
* Mendekatkan sumber bahan baku (sampah domestik) ke unit pengolahan.
* Menyeimbangkan ketersediaan input dengan potensi komersial hasil olahan.
* Menghindari kejenuhan layanan dengan mengisi celah pasar (*gap*) pada area yang belum terlayani fasilitas serupa.

## ⚙️ 2. Parameter & Pembobotan MCDA
Analisis menggunakan klasifikasi berbasis **Grid** untuk presisi lahan. Parameter dibagi menjadi kriteria **Benefit (Positif)** dan **Cost (Negatif)**.

### A. Kriteria Positif (Benefit) - Total Bobot: 1.0
| Parameter | Bobot | Keterangan |
| :--- | :--- | :--- |
| **Kepadatan Penduduk 2024** | 0.50 | Faktor penentu utama sumber input sampah. |
| **Pasar** | 0.10 | Konsentrasi sampah organik & residu tinggi. |
| **Supermarket** | 0.10 | Potensi limbah kemasan anorganik. |
| **Toko Souvenir & Kerajinan** | 0.08 | Mitra pemasaran produk upcycling. |
| **Toko Furniture** | 0.07 | Sumber material sisa (kayu/logam). |
| **Toko Kelontong** | 0.07 | Potensi titik drop-off berbasis komunitas. |
| **Toko Kostum & Alat Pesta** | 0.06 | Sumber limbah tekstil dan plastik. |
| **Outdoor** | 0.02 | Ruang terbuka untuk operasional/edukasi. |

### B. Kriteria Negatif (Cost) - Total Bobot: 1.0
| Parameter | Bobot | Keterangan |
| :--- | :--- | :--- |
| **Pengolahan Limbah** | 0.40 | Kompetitor teknis utama (Hindari tumpang tindih). |
| **Komunitas Lingkungan** | 0.30 | Area yang sudah memiliki aktivasi sosial lingkungan. |
| **Wisata Alam** | 0.10 | Mitigasi dampak estetika/lingkungan. |
| **Wisata Budaya & Sejarah** | 0.10 | Perlindungan situs bersejarah. |
| **Rest Area** | 0.10 | Menjaga kenyamanan fasilitas umum. |

## 🛠️ 3. Metodologi Analisis
1.  **Grid-Based Classification**: Membagi wilayah menjadi satuan grid kecil untuk kalkulasi skor kumulatif.
2.  **MCDA Processing**: Menjalankan algoritma pembobotan untuk menghasilkan *Suitability Map*.
3.  **Site Analysis by SINI**: Eksplorasi mendalam pada grid skor tertinggi untuk verifikasi kondisi lapangan nyata.

## 📍 4. Temuan Hyperlocal: Karang Anyar, Astana Anyar
Berdasarkan verifikasi pada titik koordinat terpilih, didapatkan profil mikro sebagai berikut:

* **Demografik**: Terletak di Kelurahan Karang Anyar, Kecamatan Astana Anyar, dengan total penduduk terpapar mencapai **186.381 jiwa**.
* **Ekonomi**: Rata-rata pengeluaran makanan sebesar **Rp803.842** dan non-makanan sebesar **Rp1.633.032**, menunjukkan daya beli yang stabil.
* **Estimasi Lahan**: Harga tanah berkisar **Rp20.510.000/m²** dengan dominasi penggunaan lahan sebagai pemukiman (sangat cocok untuk objek kajian sampah domestik).
* **Resiliensi Bencana**: Lokasi memiliki risiko **banjir**. Pembangunan Hub diharapkan menjadi solusi dengan mencegah penyumbatan saluran air melalui pengelolaan sampah yang terintegrasi.
* **Sektor Minat**: Dominasi tinggi pada sektor **Perdagangan & Retail**, serta Layanan Jasa dan Kesehatan.

## 🏁 Kesimpulan & Rekomendasi
Lokasi terpilih di Astana Anyar menawarkan keseimbangan antara ketersediaan bahan baku yang melimpah dan potensi serapan ekonomi. Fokus pengembangan pada sektor perdagangan sangat sejalan dengan fungsi Hub sebagai unit bisnis *upcycling* dan pusat edukasi masyarakat perkotaan.