# ☕ Coffee Shop Sales Dashboard

Dashboard interaktif Power BI untuk menganalisis 149.000+ transaksi sebuah coffee shop selama periode Januari–Juni: dari total revenue, tren bulanan, kategori dan produk terlaris, sampai perbandingan performa antar lokasi toko. Hasil analisis diterjemahkan menjadi rekomendasi untuk perencanaan stok dan operasional.

---

## 🖼 Preview
![Dashboard Coffe Shop Sales](Dashboard%20Coffe%20Shop%20Sales.png)

---

## 📊 Isi Dashboard
* KPI Card:	Total Revenue, Total Transaction, Total Quantity Sold
* Total Revenue by Month:	Tren revenue Januari–Juni
* Total Revenue by store_location:	Perbandingan 3 lokasi (Hell's Kitchen, Astoria, Lower Manhattan)
* Total Revenue by product_category:	Komposisi revenue per kategori (pie chart)
* Total Revenue by product_type:	Jenis produk dengan revenue terbesar (treemap)
* Top Product:	Produk dengan penjualan tertinggi

---

## 🔗 Link
- [File Power BI (.pbix)](Penjualan%20Coffe%20Shop.pbix)

---

## 🛠 Tools & Teknologi
1. Data cleaning & transformasi:	Python (Pandas, NumPy)
2. Data: Kaggle
3. Visualisasi & dashboard:	Power BI

---

## 📌 Insight Utama
1. 💰 **Total revenue** ±26 juta dari 149.120 transaksi dan 214 ribu unit terjual.
2. ☕ **Kategori Coffee** menyumbang 43,53% dari total revenue, kontribusi terbesar di antara semua kategori.
3. 🏆 **Jenis produk dengan revenue terbesar** adalah Barista Espresso dan Hot Chocolate, disusul Premium Brewed Coffee, Scone, dan Pastry.
4. 📈 **Revenue** bulanan naik hampir dua kali lipat dari Februari (±3 juta) ke Juni (±6 juta).
5. 📍 **Hell's Kitchen** memiliki revenue tertinggi, tetapi selisihnya tipis: ketiga lokasi berkontribusi hampir merata (±8–9 juta per lokasi).

---

## 💡Temuan	Rekomendasi
1. Coffee menyumbang 43,53% revenue: Jadikan Coffee prioritas perencanaan stok dan promosi, dan pastikan ketersediaannya di semua lokasi
2. Barista Espresso dan Hot Chocolate memimpin revenue:	Perketat pemantauan stok bahan baku kedua produk ini agar tidak kehabisan
3. Scone dan Pastry termasuk jenis produk dengan revenue besar: Uji paket bundling minuman + bakery untuk menaikkan nilai per transaksi
4. Revenue naik hampir 2× dari Februari ke Juni: Siapkan kapasitas stok dan staf untuk tren naik ini, dan telusuri penyebabnya (jumlah transaksi atau nilai per transaksi)
5. Revenue antar lokasi hampir merata: Terapkan strategi stok dan promosi yang konsisten di semua lokasi, dan fokus pada efisiensi operasional per lokasi

---

## 🔭 Rencana Pengembangan
1. Menambahkan analisis jam dan hari tersibuk (data transaction_time sudah tersedia) untuk perencanaan jadwal staf.
2. Menambahkan KPI rata-rata revenue per transaksi dan rata-rata kuantitas per transaksi.
3. Membandingkan performa produk per lokasi toko.

---

## 👤 Author

Adi Dwi Ribowo
adibowo703@gmail.com
