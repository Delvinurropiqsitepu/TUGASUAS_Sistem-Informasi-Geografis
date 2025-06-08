Prediksi Risiko Banjir di Kabupaten Badung, Provinsi Bali
Gambaran Umum Proyek

Proyek ini bertujuan untuk memprediksi wilayah rawan banjir di Kabupaten Badung, Provinsi Bali, dengan memanfaatkan data spasial dan non-spasial. Analisis ini dilakukan menggunakan pendekatan berbasis spasial dan pemodelan indeks kerawanan, yang kemudian divisualisasikan dalam bentuk peta menggunakan Python dan library GIS seperti GeoPandas dan Folium.
Data yang Digunakan
Data Spasial

    Shapefile Batas Administratif Kecamatan di Kabupaten Badung (kab badung.zip).

    Data Curah Hujan dari stasiun klimatologi (klimatologi (1).zip).

    Data Ketinggian Wilayah (Elevasi) berdasarkan file raster DEM SRTM 30M.

Data Non-Spasial

    Ketinggian Ibu Kota Kabupaten, Nama dan Luas Danau di Provinsi Bali.csv

    Luas Daerah dan Jumlah Pulau Menurut Kabupaten_Kota di Provinsi Bali, 2023.xlsx

File Output

    hasil_prediksi_rawan_banjir_fix.shp: hasil akhir berupa shapefile peta prediksi rawan banjir.

Metodologi

Indeks rawan banjir dihitung berdasarkan dua parameter utama:

    Curah Hujan (bobot 0.8)

    Ketinggian/DEM (bobot 0.2)

Setelah nilai indeks dihitung, wilayah kecamatan dikelompokkan ke dalam kategori risiko rendah, sedang, dan tinggi. Visualisasi akhir dilakukan dalam peta interaktif berbasis Folium untuk memudahkan interpretasi hasil.
Hasil Proyek

    Peta prediksi rawan banjir untuk wilayah Kabupaten Badung.

    Notebook prediksi_rawan_banjir_wilayah_bali_kabupaten_badung.ipynb berisi seluruh proses mulai dari data loading, preprocessing, perhitungan indeks, hingga visualisasi.

Cara Penggunaan

    Buka notebook .ipynb di Jupyter atau Google Colab.

    Ekstrak file shapefile (kab badung.zip) dan data klimatologi (klimatologi (1).zip).

    Jalankan notebook untuk menghasilkan peta prediksi.

    Gunakan file shapefile hasil (hasil_prediksi_rawan_banjir_fix.shp) untuk visualisasi lebih lanjut atau integrasi ke sistem SIG.

Tujuan

Hasil dari proyek ini diharapkan dapat digunakan oleh pihak berwenang dan masyarakat untuk mengetahui daerah yang rawan banjir, serta menjadi dasar dalam upaya mitigasi bencana di Kabupaten Badung.
