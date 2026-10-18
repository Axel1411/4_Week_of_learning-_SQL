# 👩🏻‍💻 Learn SQL

Hi, Selamat Datang to my Small SQL Study Case Repo! 🙋🏻‍♀️

Selama belajar SQL saya sadar bahwa cara belajar paling efektif adalah langsung praktik. Jadi saya membuat database rumah sakit sendiri, lalu mencoba menjawab pertanyaan bisnis yang mungkin muncul darinya.

**INTRODUCTION**
**Rumah_sakit_Axel_Studi_Kasus (Dummy Data)**
Proyek ini memodelkan sistem rawat jalan rumah sakit skala kecil dan menggunakan SQL untuk menjawab pertanyaan bisnis tentang pasien, dokter, poli, kunjungan, dan resep obat. Saya merancang database relasional, menerapkan integritas data dengan primary key dan foreign key, serta menulis query analisis menggunakan PostgreSQL. <br>

**Struktur Database**
Enam tabel yang saling berelasi: pasien, dokter, poli, kunjungan, resep, dan obat. Foreign key menghubungkan seluruh tabel, sehingga setiap kunjungan pasti milik pasien dan dokter yang valid, dan setiap resep terhubung ke kunjungan dan obat yang valid.
<br>
<img width="796" height="392" alt="image" src="https://github.com/user-attachments/assets/9dbe45fa-3975-4d0e-b055-742bb4623501" />
<br>
**Pertanyaan Bisnis yang Dianalisis**
<br>
1. Berapa jumlah kunjungan setiap bulan?
2. Pasien mana yang paling sering berkunjung?
3. Apa keluhan pasien yang paling umum?
4. Bagaimana distribusi usia pasien?
5. Dokter mana yang menangani pasien terbanyak?
