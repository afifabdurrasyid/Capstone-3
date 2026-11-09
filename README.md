# Capstone-3
Daegu Apartment - Machine Learning Regression

Proyek ini bertujuan untuk membangun model *Machine Learning* yang memprediksi harga jual apartemen di Daegu, Korea Selatan, serta memberikan strategi bisnis berbasis data untuk mengoptimalkan penetapan harga platform.

---

## Context & Problem Statement

Di pasar properti, penjual atau pemilik apartemen sering kali kesulitan menentukan harga sewa/jual yang tepat:
* **Harga Terlalu Tinggi:** Unit menjadi sulit terjual dan mengendap lama di platform (*high time-on-market*).
* **Harga Terlalu Rendah:** Pemilik apartemen kehilangan potensi keuntungan maksimal (*lost revenue*).

Model machine learning ini hadir sebagai panduan penentuan harga wajar (*fair price*) berbasis fitur internal dan eksternal apartemen.

---

## Dataset Overview

Dataset berisi **4.123 data transaksi apartemen** di Daegu dengan variabel utama:
* **Fitur Utama:** Luas unit (`Size(sqft)`), Tipe Lorong (`HallwayType`), dan Tahun Pembukaan (`YearBuilt`).
* **Aksesibilitas & Fasilitas:** Jarak ke stasiun subway (`TimeToSubway`), fasilitas sekitar (`PublicOffice`, `University`), serta fasilitas internal apartemen (`N_FacilitiesInApt`, `N_Parkinglot`).
* **Target Variable:** Harga Jual (`SalePrice` dalam Korean Won).

---

## Business Recommendations

1. **Smart Pricing Assistant & Fair Price Badge**
   * Integrasikan rekomendasi harga ML ke dasbor penjual dan beri *badge* **"Fair Price"** pada unit yang harganya sesuai pasar agar pembeli lebih tertarik.

2. **Insentif Adopsi (Komisi Berjenjang)**
   * Berikan potongan biaya/komisi platform bagi pemilik apartemen yang menyetujui rekomendasi harga model untuk mempercepat adopsi fitur.

3. **Monetisasi & Optimasi Fitur Kunci**
   * Optimalkan unit berdasarkan variabel paling berpengaruh (`Size`, `HallwayType`, `YearBuilt`) melalui tawaran paket renovasi/staging untuk unit lama.

4. **Uji Coba & Monitor KPI Bisnis**
   * Jalankan *A/B Testing* dan ukur tingkat adopsi fitur (*Adoption Rate*), kecepatan transaksi (*Days on Market*), serta total volume transaksi (*GTV*).
