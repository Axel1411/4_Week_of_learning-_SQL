**Rumah_sakit_Axel_Studi_Kasus (Dummy Data)**
Proyek ini memodelkan sistem rawat jalan rumah sakit skala kecil dan menggunakan SQL untuk menjawab pertanyaan bisnis tentang pasien, dokter, poli, kunjungan, dan resep obat. Saya merancang database relasional, menerapkan integritas data dengan primary key dan foreign key, serta menulis query analisis menggunakan PostgreSQL. <br>
**Struktur Database**
Enam tabel yang saling berelasi: pasien, dokter, poli, kunjungan, resep, dan obat. Foreign key menghubungkan seluruh tabel, sehingga setiap kunjungan pasti milik pasien dan dokter yang valid, dan setiap resep terhubung ke kunjungan dan obat yang valid.
<img width="796" height="392" alt="image" src="https://github.com/user-attachments/assets/9dbe45fa-3975-4d0e-b055-742bb4623501" />

**Pertanyaan Bisnis yang Dianalisis**
Berapa jumlah kunjungan setiap bulan?
Pasien mana yang paling sering berkunjung?
Apa keluhan pasien yang paling umum?
Bagaimana distribusi usia pasien?
Dokter mana yang menangani pasien terbanyak?
