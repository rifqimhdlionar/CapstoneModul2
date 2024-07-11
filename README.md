# CapstoneModul2 menggunakan Data Transjakarta
## Latar Belakang
Transjakarta sebagai salah moda transportasi pilihan mobilitas penduduk di DKI Jakarta. Perkembangan teknologi dan persaingan yang semakin ketat dalam industri transportasi, Transjakarta menyadari pentingnya penggunaan data untuk meningkatkan layanan dan pendapatan mereka. Aspek yang perlu diperhatikan adalah operasional dan pemasaran Transjakarta guna memanfaatkan data secara efektif guna mengoptimalkan stategi operasional dan pemasaran.
Mencapai tujuan tersebut, Manajemen Transjakarta memutuskan merekrut *data scientist* yang bertanggung jawab untuk menganalisa data terkait penggunakan layanan Tranjakarta. Dengan keilmuan dan pemahaman data Scientist tentang transportasi dan perilaku pengguna, Transjakarta dapat meningkatkan layanan operasional dan pendapatan.

## StakeHolder
1. Operations Team
2. Marketing Team

## Pernyataan Masalah
Berdasarkan latar belakang di atas, Transjakarta ingin mengetahui hal apa saja yang bisa menjadi pola karakteristik dari data layanan Transjakarta
  1. Pengguna Tranjakarta berdasarkan demografi (gender dan usia)
  2. Pengguna Tranjakarta pada hari kerja dan hari akhir pekan
  3. Pengguna Tranjakarta berdasarkan koridor dan/ halte
  4. Pembayaran layanan berdasarkan PayCard dan pendapatan dari PayCard

Sebagai seorang data analyst, saya akan mencoba menjawab pertanyaan:
  1. Bagaimana cara mengoptimalkan pengelolaan armada dan jadwal operasional Transjakarta untuk memastikan ketersediaan bus yang memadai pada jam-jam sibuk dan meningkatkan kepuasan pengguna?
  2. Bagaimana cara optimalisasi pendapatan dapat diterapkan pada halte-halte teramai untuk mendukung operasional dan pengembangan Transjakarta?

## Simpulan
  1. Pengguna layanan Tranjakarta berdasarkan demografi (gender dan usia)
      a. Gender
          Berdasarkan gender pola pengguna layanan Transjakarta, jumlah wanita sebesar 19429 pengguna dan pria sebesar 17045 pengguna dengan persentase pengguna wanita mencakup 53.7% dan pengguna pria mencakup sekitar 46.3% dari total pengguna layanan Transjakarta. Pengguna layanan Transjakarta didominasi oleh pengguna wanita.
      b. Kelompok Usia
          - Kelompok Usia 25-54: Mayoritas pengguna Transjakarta berada dalam kelompok usia 25-54 tahun. Ini menunjukkan bahwa layanan    Transjakarta banyak digunakan oleh usia produktif yang kemungkinan besar adalah pekerja.
          - Kelompok Usia 15-24: Jumlah pengguna yang cukup signifikan berasal dari kelompok usia ini, yang mungkin terdiri dari pelajar  dan mahasiswa.
          - Kelompok Usia Lainnya: Pengguna dari kelompok usia lainnya (0-14, 55-64, dan lanjut usia) lebih sedikit, menunjukkan bahwa    layanan ini kurang digunakan oleh kelompok usia muda dan lanjut usia.
          
  2. Pengguna layanan Transjakarta pada hari kerja dan hari akhir pekan
      a. Hari kerja, terdapat lonjakan penumpang terjadi direntang jam 5-9 dan 15-21. Ini menunjukan waktu sibuk pengguna transjakarta berangkat dan pulang beraktivitas.
      b. Akhir pekan, tidak ada lonjakan jumlah pengguna layanan transjakarta dan cendrung stabil pada jam operasional
  
  3. Pengguna Tranjakarta berdasarkan koridor dan halte
      a. Koridor 
          - Pola pengguna terbanyak berada di koridor Cibubur - BalaiKota  dengan 389 pengguna, Ciputat - CSW dengan 383 pengguna, Harmoni - Jakarta International Stadium dengan 342 pengguna, Pulo Gadung - Monas dengan 339 pengguna, dan Kalideres - Bundaran HI via Veteran 335 pengguna. 5 koridor ini mengindikasikan bahwa rute ini melayani kebutuhan transportasi yang signifikan di kawasan tersebut.
  
          - Pola pengguna terendah berada pada koridor Kampung Rambutan - Blok M dengan 17 pengguna, Tanah Abang - Kebayoran Lama via Pos Pengumben 22 pengguna, Term. Pulo Gadung - Lampiri 30 pengguna, Senen - Tanah Abang 38 pengguna, dan Grogol - Pos Pengumben via Slipi 38 pengguna. 5 koridor memiliki pengguna yang sangat sedikit, menunjukkan kurangnya permintaan.
  
      b. Halte
          - 5 Halte Tersibuk Berdasarkan Tap In: Penjaringan : 235 pengguna, Garuda Taman Mini: 203 pengguna, BKN: 163 pengguna, BNN LRT: 150 pengguna, Pejaten: 146 pengguna
          - 5 Halte Tersibuk Berdasarkan Tap Out: BKN: 316 pengguna, Penjaringan: 265 pengguna, Term. Senen: 196 pengguna, Monas: 167 pengguna, Term. Kampung Rambutan: 164 pengguna
          - 5 halte tersepi berdasarkan Tap In dan Tap Out: Jln. Simprug Golf 2, Sbr. Jln. Sungai Barito Sembar, Taman Bambu 2, Megatama, Jln. Gunung Galunggung 1, Sbr. Klinik Kasih Medika, Sbr. SMAN 5, Simpang Tridharma Bango Raya, Jln. Villa Ampera, RSUD Cengkareng, halte- halte tersebut adalah tersepi pengguna kemungkinan kurang stategis dalam penempatan halte dan perlu pengamatan lebih lanjut.
      
  
  4. Pembayaran layanan berdasarkan PayCard dan pendapatan dari PayCard
      a. Tarif
          Mayoritas tarif yang dibayarkan berkisar di sekitar tarif standar Transjakarta, yaitu Rp3,500.
  
      b. Pengguna kartu pembayaran
          - Pembayaran mengguanakan Bank DKi : 17505
          - Pembayaran mengguanakan emoney : 6439 
          - Pembayaran mengguanakan brizzi : 3285 
          - Pembayaran mengguanakan flazz : 3013
          - Pembayaran mengguanakan online : 2503 
          - Pembayaran menggunakan bank BNI : 2503 
  
          Terdapat perbedaan signifikan distribusi penggunaan antara bank DKi dengan kartu lainnya.
  
      c. Pendapatan layanan Tranjakarta
          - Bank DKi  : Rp44,155,000
          - emoney    : Rp19,921,500
          - brizzi    : Rp11,883,000
          - flazz     : Rp8,611,500
          - online    : Rp6,939,000
          - BNI       : Rp6,664,000
  
          Bank DKI mendominasi dalam hal total pendapatan disusul oleh eMoney dan Brizzi juga menunjukkan pendapatan yang signifikan.
        
## Rekomendasi
  1. Rekomendasi mengoptimalkan pengelolaan armada dan jadwal operasional Transjakarta untuk memastikan ketersediaan bus yang memadai pada jam-jam sibuk dan meningkatkan kepuasan pengguna
      a. Optimalisasi Operasional
          - Ketersediaan jumlah armada pada koridor tersibuk dengan jumlah penumpang pada waktu tersibuk weekdays pada jam 5-9 pagi dan jam 16-21 malam.
          - Mengarahkan armada pada koridor padat pengguna seperti Cibubur-Balai Kota, Ciputat - CSW, Harmoni - Jakarta International Stadium, Pulo Gadung - Monas, Kalideres - Bundaran HI dari koridor yang sepi seperti kampung rambutan - Bllok M, Tanah Abang - Kebayoran Lama, term Pulo Gadung - Lampiri.
  
      b. Penyesuaian jam Operasional
          Mempertimbangkan penyesuaian jam operasional armada pada jam sibuk untuk menjaga kualitas pelayanan dan memecah penumpukan penumpang pada halte, salah satunya dengan cara membuka gate transjkarta lebih awal di pagi hari yaitu pada jam setengah 5 terutama pada koridor : Cibubur - Balai Kota, Ciputat - CSW. dan pada halte : Rusun Kapuk Muara- Penjaringan, Penjaringan-Rusun Kapuk Muara, Garuda Taman Mini- BKN , Cibubur Junction - BKN, Garuda Taman Mini-Pinang Ranti.
  
      c. Informasi Jadwal
          Memastikan informasi rute dan jadwal tersedia dan mudah diakses oleh pengguna melalui aplikasi dan layar informasi di halte secara real-time.
      
  2. Rekomendasi meningkatkan pendapatan dapat diterapkan pada halte-halte teramai untuk mendukung operasional dan pengembangan Transjakarta
      a. Optimalisasi Pendapatan
          Mengkaji kembali peraturan mengenai tarif Tranjakarta ([Tarif Transjakarta](https://transjakarta.co.id/faq-transjakarta/)), sebab tidak adanya kenaikan tarif sejak 2007 ([wacana kenaikan tarif Transkjakarta](https://megapolitan.kompas.com/read/2024/04/18/12005371/).
          
      b. Space Iklan
          Pasang iklan di halte-halte tersibuk seperti Penjaringan, BKN, dan Garuda Taman Mini untuk memaksimalkan visibilitas iklan. Gunakan space iklan yang menarik dan interaktif seperti digital signage atau layar LED untuk menarik perhatian pengguna. Manfaatkan data demografis pengguna untuk menyesuaikan konten iklan sesuai dengan profil penumpang yang sering menggunakan halte tersebut.
  
      c. Vending Machine:
          - Penempatan Strategis: Tempatkan vending machine di halte-halte dengan jumlah tap in dan tap out yang tinggi seperti BKN, Penjaringan, dan Terminal Senen.
          - Produk yang Ditawarkan: Sediakan produk yang sering dibutuhkan oleh penumpang seperti minuman, makanan ringan, masker, dan hand sanitizer.
          - Pemeliharaan Rutin: Pastikan vending machine selalu dalam kondisi baik dan produk yang dijual selalu tersedia melalui pemeliharaan rutin.
