# Data Ulasan Kafe di Yogyakarta
Data `ulasan-kafe-jogja` merupakan dataset hasil scraping dari platform google maps. Data diambil dari 3 cabang dari 3 kafe yang berbeda sehingga total ada sebanyak 9 dataset yang dapat digunakan.

## Detail Dataset
Tabel 1 Contoh Dataset Mentah Ulasan Kafe di Yogyakarta
| rating | date           | snippet |
|--------|----------------|---------|
| 2      | seminggu lalu  | Ya seperti yg sudah pernah d ulas sblmnya sm yg lain<br><br>Kafe ini mmg cocok gen Z yg hanya sekedar nongkrong hangout ngopi dll<br><br>Tapi jgn pernah tanya soal rasa / kualitas makanannya<br><br>Karena mmg bukan cheff yang masak<br>Mesen hidangan aja anyep baru dateng dalam hati ku ini kapan masaknya?<br><br>Ya sbnrnya itu faktor penting tp mgkn mereka cuek karena mmg ini franchise sih |
| 2      | 7 bulan lalu   | Ayam Bakarnya rasanya pahit gosong bakarannya, bumbunya kurang.<br><br>Yang bawa Kopi dan wedang Jahe Kepruknya banjir alias tumpah2 di Lepek gelasnya.<br><br>Es tape lumayan enak,<br>Mie dokdoknya enak.<br><br>Pisang goreng dan pisang bakar kejunya biasa saja.<br><br>Pesan Kentang goreng gak datang2, saat beranjak pulang juga tak nampak itu kentang goreng. Akhirnya kita samperin ke kasir, kata kasirnya udah ready, ya udah kita minta dibungkus dibawa pulang saja, lhhaa kok tunggu bungkusnya aja superrr lama bingit gesss..<br>Kirain bungkus pakai daun atau apa kok lama bgt, ternyata cuma pakai bungkus kertas makanan aja lama bangettt.<br><br>Suasananya ramaaaiii banget tapi kasirnya cuma 1 jadi laaammaaaa buuuaanggeett.<br><br>Saran, mendingan customer ambil menu dan tulis orderan dikertas sambil cara tempat duduk, setelah itu baru ke kasir bayar, jadi depan kasir tuh gak antri panjaaangg. |
| 5      | 10 bulan lalu  | Aku udah beberapa kali nongkrong di Basa Basi Concat buat ngerjain tugas, dan menurutku harganya worth it banget sama kantong mahasiswa. Bisa jadi opsi tempat nongki murah selain coffeeshop. Tempatnya luas banget, mulai dari lesehan sampai duduk di kursi ada, cuma memang ada beberapa yang kurang srek menurutku.<br><br>Pertama, waktu pekan lalu aku kesini, cari tempat kosong yang ada stop kontak buat nugas, eh ternyata masih ada bekas minum kopi orang sebelumnya. Sampe aku yang bersihin sendiri sebelum ada karyawan yang bersihin 😓. Terus, kalau udah malem ada sekelompok orang main ML, aku gak masalah mereka main, cuma mereka sampe teriak-teriak jadi bikin sekitar merasa terganggu 😭🙏.<br><br>Kebersihan WC-nya juga perlu diperhatikan, soalnya ada yang bau pesing 😨. Untuk karyawan dan kasir, pelayanannya bagus banget. Menunya juga banyak. Menu andalanku di sini nasi goreng, susu jahe hangat, dan mie pastinya 👍🏼. Pembayaran bisa cash dan non-cash, jadi aman banget buat yang cashless.<br><br>Tempat ini overall recommended, tapi semoga kedepannya kebersihan lebih diperhatikan dan bisa ada aturan soal berisik biar semua nyaman. |
| 5      | 2 bulan lalu   | Kafe Basabasi Concat punya vibes yg cozy & cocok buat santai ato ngerjain tugas. Tempatnya luas, suasana tenang, apalg klo malem makin asik buat ngobrol. Minuman cukup variatif, ada kopi, non-kopi, dan minuman klasik kyk root beer yg disajiin dingin pake es, makin seger! Makanannya juga oke, tp msh bisa ditingkatin lg. Pelyanan lumayan, tp klo lg rame agak lama nunggu. Overall, tempat ini rekomen buat yg nyari suasana santai dgn konsep industrial yg keren. Klo cari tempat buat chill ato kerja, ini bisa jd opsi yg oke! ☕🍻 |
| 1      | seminggu lalu  | Semenjak di renovasi, pelayanan nya kurang baik.<br>Di google tutup jam 2 tetapi baru jam 1 sudah di usir oleh mba mba kasir nya.<br>Dan lampu langsung di matikan sehingga untuk kemas laptop dan barang kita lain nya tidak bisa karena gelap.<br>WiFi juga ikut mati semua lampu kafe mati dan gelap gelapan. |

Tabel 2 Detail Data
| Atribut | Keterangan |
|---------|------------|
| Jumlah Total Data | ± 7791 |
| Metode Pengambilan Data | Scraping melalui Google Maps API |
| Format File | `.csv` |

Tabel 3 Deskripsi Kolom
| Atribut | Tipe data (Python) | Deskripsi |
|---------|--------------------|-----------|
| rating  | int64              | Penilaian pelanggan terhadap kafe |
| date    | object             | Tanggal pelanggan memberikan ulasan berdasarkan waktu pengambilan data April 2025 |
| snippet | object             | Ulasan pelanggan terhadap kafe |