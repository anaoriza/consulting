# 07 — Guesstimate Book Vol. 1 (180 Degrees Consulting SRCC, India, 2024-25)

> Sumber: *Guesstimates-Book-Volume-1-6.pdf* (61 halaman). Berisi teori, pro tips/framework, **cheat sheet** demografi & ekonomi India, dan ±40 guesstimate yang ditanyakan di wawancara **Accenture, Bain Capability Network, BCG, McKinsey, Indus Insights, Kepler Cannon, Nation with NaMo, RedSeer, Trinity Life Sciences**.
> Catatan: angka adalah konteks **India**; untuk Indonesia, ganti benchmark (lihat bagian 3B). Saya menambahkan **catatan kritis** pada contoh yang aritmetika/logikanya cacat — karena *sanity check* adalah bagian dari keterampilan.

---

## 1. TEORI

### 1.1 Apa itu guesstimate & fungsinya di wawancara
- Pertanyaan mengestimasi suatu angka dengan **informasi sangat terbatas** memakai kombinasi tebakan & **asumsi masuk akal**.
- Menguji: **kemampuan mengolah angka**, **berpikir cepat**, dan **mendekati masalah secara sistematis & terstruktur** (jawaban akhir kurang penting dibanding logika).

### 1.2 Struktur 5 langkah
1. **Clarification** — pahami pertanyaan "dalam esensinya"; **klarifikasi istilah ambigu** (global vs lokal? tahunan vs bulanan? unit: orang, transaksi, rupiah? termasuk apa?).
2. **Approach** — pilih **demand-side** atau **supply-side**.
3. **Segmentation** — bangun **issue tree MECE** (mis. demand-side: populasi → filter).
4. **Estimation** — isi nilai dengan faktor demografis kunci (usia, gender, distribusi pendapatan, dsb.).
5. **Validation** — gabungkan menjadi angka akhir, lalu **validasi dengan pendekatan lain atau benchmark kasar (ballpark)**.

### 1.3 Pro tips
- **Ask questions** — "Global atau lokal?", "Tahunan atau bulanan?"
- **Leverage benchmarks** — statistik yang diketahui (populasi India 140 cr = 1,4 M; dunia 8 M).
- **Analogies** — "Jika AS punya X mobil, India mungkin Y berdasarkan populasi & pendapatan."
- **Round off numbers** — pakai 100 jt, bukan 103 jt.
- **Think in layers:** *Primary drivers* (faktor terbesar: populasi, pendapatan, frekuensi pemakaian) → *Secondary factors* (nuansa: musiman, perbedaan regional) → **Sanity test** ("Benarkah ada 1 miliar mobil di satu kota? Tidak mungkin.").

### 1.4 Frameworks
| Framework | Inti | Contoh |
|---|---|---|
| **Bottom-up** | mulai dari komponen kecil terukur lalu agregasi | mobil di kota = mobil per rumah tangga × jumlah rumah tangga |
| **Top-down** | mulai estimasi tingkat tinggi lalu pecah | revenue industri kopi dari konsumsi kopi global → harga per cangkir |
| **Pareto (80/20)** | 20% aktivitas menghasilkan 80% hasil → estimasi efisien | 80% revenue restoran kota dari 20% restoran teratas |
| **MECE** | kategori saling lepas & menyeluruh | efektivitas kampanye = total impresi × conversion rate |
| **Unit economics** | pecah per unit (per pelanggan/produk) lalu skala | biaya layanan antar = biaya per antaran × jumlah antaran |
| **Extrapolation** | proyeksi tren bila variabel tumbuh persentase | **Y = Y′ × (1 + r)^t** (Y = nilai masa depan, Y′ = nilai kini, r = pertumbuhan, t = periode) |

### 1.5 Demand-side vs Supply-side
- **Demand-side** — *kapan:* estimasi ukuran pasar, revenue, pola konsumsi. *Cara:* pecah permintaan → **populasi target × frekuensi pemakaian × konsumsi rata-rata**. *Contoh:* pasar pembalut di India; penumpang metro harian Delhi. **Parameter:** usia, gender, pendapatan, pekerjaan, lokasi (urban/rural), negara, literasi, penetrasi ponsel, penetrasi internet.
  - **Contoh — jumlah pelat nomor di Maharashtra:** populasi 120 jt ÷ 4 orang/RT = **30 jt RT** → high income 10% = 3 jt RT × 90% punya kendaraan = 2,7 jt × **2 kendaraan** = 5,4 jt; middle 60% = 18 jt × 50% = 9 jt × **1,5** = 13,5 jt; low 30% = 9 jt × 30% = 2,7 jt × **1** = 2,7 jt → **21,6 jt kendaraan × 2 pelat/kendaraan = 43,2 jt pelat**.
- **Supply-side** — *kapan:* ada **kendala pasokan**: kapasitas produksi tetap, lead time, batasan regulasi, keterbatasan transportasi. *Cara:* estimasi dari **kapasitas produksi/pasokan/jangkauan distribusi**, bukan permintaan. *Contoh:* paket Amazon India per hari; sneakers edisi terbatas yang dijual ulang per tahun.
  - **Contoh — revenue harian fast food di New Delhi (dine-in saja):** Total revenue = harga rata-rata (₹100) × jumlah item terjual; item dine-in = **jam operasional × kapasitas (kursi) × okupansi rata-rata × item per orang ÷ rata-rata lama kursi terisi** (takeaway & delivery bisa ditambahkan).
- **TAM–SAM–SOM:** TAM = peluang pasar maksimum; SAM = porsi TAM yang bisa dilayani sesuai kapabilitas & demografi operasi; SOM = porsi SAM yang bisa direbut dengan sumber daya & persaingan saat ini.

---

## 2. CHEAT SHEET INDIA (benchmark untuk guesstimate India)
**Demografi**
- Populasi: dunia **8 M**, India **1,40 M**. Kota: **Delhi 33,8 jt**, **Mumbai 21,67 jt**, **Kolkata 15,57 jt**, **Bengaluru 14 jt**, **Chennai 12,05 jt**, **Hyderabad 11,07 jt**.
- Gender 50/50; harapan hidup **70 tahun**; usia: **0–15 = 30%, 15–35 = 40%, 35–60 = 25%, 60+ = 5%**.
- Angka kelahiran **16/1.000**, kematian **7/1.000**.
- Kendaraan: **260 jt** (mobil? ikon mobil) & **50 jt** (dua roda? — ikon); **milik pribadi 88%**, komersial 12%. Per 1.000 orang: **185 punya motor**, **34 punya mobil**.
- Vegetarian 40% / non-vegetarian 60%; menikah 45% / belum 55%.
- **Urban vs rural:** porsi populasi 30% vs 70%; literasi 90% vs 77%; ukuran keluarga 4 vs 5; penetrasi smartphone 70% vs 30%; penetrasi internet 70% vs 50%.

**Ekonomi**
- PDB nominal **₹324,11 lakh crore**, riil ₹184,88 lakh crore; pertumbuhan **6,4%**.
- Sektor: pertanian 20%, industri 26%, jasa 54%.
- Digital: e-commerce "120BN" (nilai), social media **460 jt**, OTT **100 jt** pelanggan.
- Pengeluaran rumah tangga: **makanan & bahan pokok 25%, perumahan 25%, tabungan 15%, pendidikan 10%, transportasi 10%, utilitas 5%, lain-lain 10%**.
- Bracket pendapatan: **lower 30%, lower-middle 40%, upper-middle 20%, high 10%**.
- Tier kota: Tier 1 ≥ 100.000 penduduk (Bengaluru, Delhi, Chennai, Hyderabad, Mumbai); Tier 2 50.000–99.999 (Amritsar, Bhopal, Bhubaneswar, Chandigarh); Tier 3 10.000–49.999 (Bhadreswar, Datia, Gangtok, Kalyani).
- Agama: Hindu 80%, Muslim 15%, Kristen 2%, lainnya 3%. Ponsel: Android 70%, Apple 29%, lainnya 1%. Luas India **3,287 jt km²**.

**Formula**
- **Market size × market share = Revenue = Profit + Fixed cost + Variable cost**.
- **Profit = Revenue − COGS − (SG&A + licensing) − (interest + tax + D&A)**.

**Konversi:** 1 hektar = 10.000 m² · 1 mil = 1,6 km · 1 kaki = 0,3 m · 1 m³ = 1.000 L · 1 galon AS = 3,8 L · °F = °C × 9/5 + 32 · 1 m/s = 3,6 km/jam.

---

## 3. CONTOH GUESSTIMATE (rumus, asumsi, hasil)

### Accenture
1. **Pasar biskuit sehat (India) = ₹231,5 miliar.** 1,4 M → **urban 35%** (490 jt; biskuit sehat untuk urban karena kesadaran & keterjangkauan) → **upper income 10%** (49 jt; produk mahal) → **usia 40+ 35%** (17,15 jt; alasan kesehatan) → × **540 biskuit/tahun** (1,5 biskuit/hari, dihitung 360 hari… ditulis "3 tiap 2 hari, 180 hari") × **₹25/biskuit** (₹50 per 2-pack).
2. **Taksi Ola & Uber yang beroperasi di Delhi NCR per hari = 71,8 ribu.** Tanpa split perusahaan; cab = kategori kendaraan komersial; operasi 24 jam. Populasi 33 jt → rural 19,8 jt / urban 13,2 jt → per kelas pendapatan × % pemakai cab (10–20%) → **2,24 jt perjalanan/hari** → peak 40% (897 rb × okupansi 50% = 448 rb) + non-peak 60% (1,34 jt × 20% = 269 rb) = **718 rb cab-dipakai** ÷ **10 perjalanan per cab/hari** = 71,8 rb cab.
   - *Catatan kritis:* segmentasi angka "lower 118 million" adalah salah ketik; logika "okupansi" dipakai untuk mengonversi permintaan ke kebutuhan armada — sebaiknya dijelaskan eksplisit.
3. **Penerbangan lepas landas dari Delhi per minggu = 5.880.** 6 terminal (asumsi); peak: 1 pesawat/5 menit (12/jam), non-peak 1/10 menit (6/jam). Sen–Jum: peak 8 jam, non-peak 6 jam → per terminal 8×12 + 6×6 = 132 → ×6 = 792 ≈ **800/hari** × 5 = 4.000. Sab–Min: peak 10 jam → 10×12 + 6×6 = 156 × 6 = 936 ≈ **940/hari** × 2 = 1.880. Total **5.880**.
   - *Catatan kritis:* Delhi (IGI) sebenarnya punya 3 terminal & ~1.400 pergerakan/hari (naik+turun); asumsi "per terminal" seharusnya "per runway". Gunakan sebagai latihan struktur supply-side (kapasitas × utilisasi × waktu).
4. **Cangkir teh di Delhi per hari = 6,34 crore (63,36 jt).** Populasi 40 jt; anak 0–15 (20%) dikecualikan → 32 jt. Rural 60% (19,2 jt): 70% peminum × 3 cangkir. Urban 40% (12,8 jt): 60% peminum; **office-goers 30% urban** minum 4 cangkir (2 rumah + 2 kantor), lainnya 2 cangkir. Hasil: 4,03 cr + 1,54 cr + 0,77 cr.
   - *Catatan:* populasi Delhi di halaman lain 33 jt — **konsistensi angka basis** penting.

### Bain Capability Network
5. **Revenue tahunan salon = ₹3,55 crore.** 20 kursi × buka 11 jam = **220 kursi-jam/hari** (kapasitas). Pria: 0,5 jam, ₹250; wanita: 2 jam, ₹2.000. Campuran contoh: 22 pria (₹5.500) + 5,5 wanita (₹11.000) → 11 jam terisi… **AOV ₹600**. Hari kerja 258 (okupansi 70% dari 220), akhir pekan 104 (85%); 362 hari revenue (dikurangi libur nasional). **Revenue = okupansi × AOV × jumlah hari**.
   - *Catatan kritis:* perhitungan AOV & "customer-hours" di sumber tidak konsisten (₹16.500/27,5 pelanggan ≈ ₹600 benar, tapi kemudian okupansi kursi-jam langsung dikali AOV per pelanggan). **Pelajaran: jaga satuan** (kursi-jam vs pelanggan) — konversi kursi-jam → pelanggan dengan rata-rata durasi layanan tertimbang.
6. **Pasar fantasy sports India = 22,4 jt pengguna.** Hanya pria (700 jt) → usia 18–25 (20% = 140 jt; punya akses pembayaran & aktif menonton olahraga) → penetrasi ponsel 80% (112 jt) → internet 50% (56 jt) → tertarik olahraga 80% (44,8 jt) → memakai aplikasi 50% (**22,4 jt**).
7. **Pesanan Swiggy di Delhi per hari ≈ 24,8 lakh (2,48 jt).** 40 jt → rural 60% dikecualikan; urban 16 jt → BPL 40% dikecualikan; middle 40% (6,4 jt) × ponsel 85% × internet 80% × adopsi 50% × share Swiggy 40% × **1 order/hari**; high 20% (3,2 jt) × ponsel 100% × internet 90% × adopsi 70% × 40% × **2 order/hari**.
   - *Catatan kritis:* asumsi "1–2 order per hari per pengguna" sangat tinggi (realistis: ~2–4 order per **bulan**). **Sanity test frekuensi** sering terlupa.
8. **Revenue harian tol Delhi–Gurgaon = ₹28,46 lakh.** 24 jam; 15 + 15 = **30 booth**; jam low/medium/high = 10/6/8 jam; satu kendaraan tiap 10 / 5 / 1 menit per booth → 1.800 + 2.160 + 14.400 = **18.360 kendaraan**. Mix: motor 10% (₹50), mobil 60% (₹100), kendaraan berat 30% (₹300).
   - *Catatan:* di India motor tak bayar tol di expressway — **cek realita regulasi**.
9. **Jumlah kartu kredit di India = 160 jt.** 1,4 M → high 10% (140 jt), middle 60% (840 jt), low 30% (420 jt) → yang berpenghasilan (high 100%, middle 50%, low 100%) → kemauan kredit (50% / 30% / 10%) → benar-benar mengajukan (70% / 40% / 20%) → kartu per orang (high 2, middle 1, low 1) → 100 jt + 50 jt + 10 jt. Asumsi: low income lebih suka pinjaman informal; middle income tumbuh & butuh kredit; termasuk semua kartu (bukan hanya aktif).
   - *Catatan:* realita ~100 jt kartu (2024) — urutan besaran tepat.
10. **Cat untuk mobil = 20 galon.** Hatchback standar dimodelkan sebagai **2 balok** (bawah 1,8×1,8×1,3 → 2×(p+l+t)… 15,8 m²; atas 1,5×1,5×0,8 → 7,5 m²) − jendela 2,7 m² ≈ **20 m²**; proxy: **pintu 2 m² butuh 1 galon** → 20 galon.
    - *Catatan kritis:* luas permukaan balok = 2(pl + pt + lt), bukan 2(p+l+t); dan 1 galon untuk 2 m² terlalu boros (1 galon ≈ 30–40 m² sekali lapis). **Pelajaran: cek rumus geometri & proxy fisik.**
11. **Film Bollywood rilis per tahun = 340.** Rilis tiap **Jumat** (48 Jumat efektif): high budget 1/Jumat (48), medium 2 (96), low 4 (192) + **4 film di hari libur nasional** = 340.
12. **Pasar ban India (revenue) ≈ ₹410 miliar.** Hanya roda empat; berbasis rumah tangga. Rural 70% → populasi pengguna roda empat 30% → ÷ 5 orang/RT → faktor RT mampu mobil 0,426 → 1 mobil/RT → 4,26 jt mobil → 21,3 jt ban; urban 30% → pengguna roda empat 90% → ÷ 4 orang/RT → faktor 0,548 → 3 mobil/RT → 16,44 jt mobil → 82,17 jt ban → **mobil × 5 ban** (4 + cadangan) = 103,48 jt ban × **₹4.000** = ₹413,9 miliar.
    - *Catatan kritis:* menghitung **stok** ban terpasang, bukan **penjualan tahunan** (seharusnya: mobil baru × 5 + mobil eksisting × 4 ÷ umur ganti ban ~3–4 tahun). **Pelajaran: bedakan stock vs flow.**

### Boston Consulting Group
13. **Pinjaman pendidikan outstanding di India = 46,76 jt.** Hanya S1 (usia 18–25 = 20% populasi = 280 jt); BPL tak kuliah. Kelas: lower-middle 35% (98 jt) → kuliah 50% (49 jt) → publik 80% (39,2 jt) × pinjam 50% = 19,6 jt; swasta 20% (9,8 jt) × 80% = 7,84 jt. Upper-middle 25% (70 jt) → kuliah 90% (63 jt) → publik 60% (37,8 jt) × 20% = 7,56 jt; swasta 40% (25,2 jt) × 40% = 10,08 jt. Elite 10% (28 jt) → kuliah 100% → publik 40% × 0% = 0; swasta 60% (16,8 jt) × 10% = 1,68 jt. Total **46,76 jt**. (Outstanding = pinjaman ≤7 tahun terakhir.)
    - *Catatan kritis:* realita ~3–4 jt rekening. Persentase peminjam terlalu tinggi; **validasi dengan benchmark** akan menangkap kesalahan 10×.
14. **Cat untuk mobil** (juga ditanyakan McKinsey/BCG) — lihat #10.

### Indus Insights
15. **Revenue dokter gigi per hari ≈ ₹10.993** (rata-rata seminggu). Buka 11.00–20.00 (9 jam), 7 hari. **Turnover 20 menit/pasien** (5 intro + 10 diagnosis + 5 bayar) → 3 pasien/jam. Okupansi peak 100%, non-peak 50%. Hari kerja: peak 6 jam × 3 = 18, non-peak 3 × 1,5 = 4,5; akhir pekan: peak 3 × 3 = 9, non-peak 6 × 1,5 = 9 → 40,5 pasien … mix: complicated 50% (₹2.500), simple 30% (₹1.500), consultation only 20% (₹1.000) → ₹76.950/7 = ₹10.993.
    - *Catatan:* asumsi teks (fee 1.000/1.500/500) & perhitungan (2.500/1.500/1.000) tak konsisten; menjumlahkan pasien hari kerja + akhir pekan lalu dibagi 7 tidak tepat bobotnya. **Tulis satu set asumsi & gunakan konsisten.**
16. **Revenue tahunan laundry di Delhi ≈ ₹3,38 lakh.** Aliran revenue: **utama** — wash & fold 100 baju/hari × ₹9 = ₹900; **sekunder** — dry cleaning 7 × ₹60 = ₹420, same-day service 10 × ₹40 = ₹400, pickup & delivery 10 × ₹30 = ₹300 → **₹2.020/hari**. Jam operasi: peak 1.460 jam/th + non-peak 2.555 jam/th = 4.015 jam. Asumsi: area umum (bukan posh/terbelakang), drop-off + layanan antar-jemput, jumlah mesin & baju diasumsikan, tahun non-kabisat, musiman diabaikan.
    - *Catatan:* ₹2.020 × 365 = ₹7,37 lakh ≠ ₹3,38 lakh — **cek ulang aritmetika akhir**.
17. **Revenue mingguan stall food court mal Delhi = ₹1,56 lakh (per stall?)** 30 restoran (high cost 6, medium 15, low/quick 9); footfall mal weekday 22 rb, weekend 24 rb; footfall food court/minggu 23.460 → per stall 782 × AOV ₹200 = ₹1,56 lakh. (Teks asumsi menyebut AOV ₹400 — inkonsisten.)
18. **Buku yang dibaca orang India seumur hidup = 127.** Semua jenis & bahasa (termasuk buku sekolah); literasi 70%; mulai baca usia 7. 7–18 (≈10 th): avid 50% @10, non-avid 50% @5 → rata 7,5 × 10 = 75; 18–35 (17 th): avid 30% @3, non-avid 70% @1 → ≈3 × 17 = 51; 35–60 (25 th): avid 30% @4, non 70% @2 → ≈2 × 25 = 50 → 176–181 × 0,7 literasi ≈ **127**.
19. **Waktu komuter mingguan pekerja kantor Delhi = 4,98 crore jam.** Populasi 30 jt; workforce 14,5 jt; sektor (primer 2%, sekunder 38%, tersier 60%); urban 97%; usia 0–20 28%, 20–35 35%, 35–50 15%, 50+ 22%. Segmen pekerja × jam komuter/hari × hari kerja kantor/minggu: **self-employed 20%** (1 jam × 6 hari), **public sector 10%** (1,5 jam × 6 hari), **corporate komuter ke luar Delhi 20%** (Gurugram/Noida/Faridabad 1,5 jam sekali jalan = 3 jam/hari × **3,5 hari WFO**), **corporate dalam Delhi 20%** (1,5 jam × 5 hari), other service. **Pekerja × jam komuter/hari × hari WFO/minggu**.
20. **Biaya pemerintah India untuk Pemilu Lok Sabha 2024 ≈ ₹12.180 crore.** Data lampau: 2014 ₹3.780 cr, 2019 ~₹8.000 cr (≈2×). Pemilih 2019 ~910 jt → 2024 ~960 jt (+5%). Pertumbuhan: populasi/pemilih 5% + inflasi 30% + faktor tambahan (teknologi, keamanan) 10% = **45%** → ₹11.600 cr + **buffer kontinjensi 5%** = ₹12.180 cr. (Pendekatan **ekstrapolasi dari data historis** + penyesuaian.)

### Kepler Cannon
21. **Pasar perusahaan minuman beralkohol di Mumbai = 2,5 jt orang.** 20 jt → **slum 40% dikecualikan** (aksesibilitas) → urban non-slum 12 jt → usia 0–18 dikecualikan (etika, tidak menarget di bawah umur) → 18–30 (20%) × 80% tertarik = 1,92 jt; 30–50 (30%) × 50% = 1,8 jt; 50+ (30%) × 20% = 0,72 jt → ≈4 jt tertarik → kelas: upper 15% × 90%, upper-middle 40% × 75%, lower-middle 35% × 50%; BPL dikecualikan → **2,5 jt**.

### Nation with NaMo
22. **Mobil merah di Delhi = 433 rb.** 33 jt orang, keluarga 4 orang; hanya mobil pribadi; **15% mobil berwarna merah**; lower-middle tak punya mobil. Total mobil 2,89 jt × 15% = 433.125.
    - *Catatan kritis:* angka cabang (6,19 jt / 1,65 jt / 1,24 jt) tak menjumlah ke 2,89 jt & lupa membagi dengan ukuran keluarga. **Pelajaran: setiap cabang harus menjumlah ke total — "sum check".**
23. **Kursi di rumah tangga Delhi = 28,4 jt.** 20 jt orang ÷ 5/keluarga = 4 jt keluarga; low 30% × 2 kursi, lower-middle 30% × 5, upper-middle 30% × 10, high 10% × 20 → 2,4 + 6 + 12 + 8 = **28,4 jt**. (Bersih & konsisten — contoh baik.)
24. **Mahasiswa SRCC yang naik metro per hari = 504.** 3.500 mahasiswa (S1 3 angkatan + S2); hadir 100%; non-Delhi 60% tinggal dekat kampus (tak naik metro); dari Delhi 40% = 1.400 → low 40% (bus 70%, metro 30%), middle 50% (metro 40%, bus 30%, cab 20%, pribadi 10%), high 10% (metro 40%, cab 30%, pribadi 30%) → 168 + 280 + 56 = **504**.
25. **Botol wine terjual di India per tahun = 3,13 M.** 1,43 M; usia 0–21 tak minum (35%); wine = minuman mewah untuk high income; low income tak minum; regular vs occasional drinkers; **40 botol/orang/tahun**; 20% wine tidak dalam botol (kaleng/barel).
    - *Catatan kritis:* 40 botol/orang/tahun & 3 miliar botol jauh di atas realita (India ~30–40 jt liter/tahun). **Sanity test per kapita** akan menangkapnya.
26. **Pengunjung India Gate per hari = 116.500.** Hari kerja biasa; 20 jt penduduk (low 10 jt, middle 8 jt, high 2 jt) → kemampuan rekreasi → **10 tempat populer**, India Gate salah satunya (peluang) + **turis 1 lakh/hari** × % mengunjungi India Gate.
27. **Mahasiswa yang naik metro ke North Campus DU = 10.540.** 10 kampus × 5.000 = 50 rb (teks) — pecah: hostel 3.000, PG 30.000 (tak naik metro), **day scholars 17.000** → income: high 680 (tak naik metro), middle 7.480 (90% metro), low 5.440 (70% lebih suka bus DTC → 30% metro) → **10.540**.
28. **Penerbangan di bandara Delhi per hari = 576 (kedatangan).** 1 bandara, 3 terminal, **2 runway per terminal**; peak 08.00–20.00 (12 jam, jeda 10 menit = 6/jam), non-peak 12 jam (jeda 30 menit = 2/jam) → rata 4/jam × 24 = **96/runway** × 2 × 3 = 576. Domestik + internasional.
29. **Revenue bulanan Saravana Bhavan (restoran India Selatan) = ₹58,14 lakh.** Kapasitas 120 orang/jam; peak (11–12, 15–17, 20–21 = 4 jam) okupansi 100%; non-peak (7 jam) 50%; 22 hari kerja & 8 hari akhir pekan; akhir pekan 1,5× pengunjung hari kerja; menu: dosa ₹200 (50%), special dosa ₹300 (20%), kopi ₹100 (30%) → **rata ₹190/pelanggan**. Hari kerja: 4×22×120 = 10.560 + 7×22×120×50% = 9.240 → 19.800 (900/hari); akhir pekan 1,5 × 900 × 8 = 10.800 → **30.600 pelanggan × ₹190 = ₹58,14 lakh**. (Contoh supply-side yang rapi.)

### RedSeer Strategy Consultants
30. **Pasar quick commerce India = 111,2 jt pengguna.** Hanya urban (30%; rural & tier 2/3 tak terjangkau) → metro 10%, tier 1 50%, tier 2/3 40% (dikecualikan) → usia: 0–30 (40%) × 70%, 30–50 (30%) × 50%, 50+ (30%) × 0% … → total 111,2 jt.
31. **Pasar iklan di platform non-tradisional = "25.225,2 miliar" (impresi).** Populasi 1,4 M × akses internet 75% (1,05 M) × pengguna aktif 90%? (945 jt) × pelanggan platform 70% → 882/735 jt pengguna; **pasar = pengguna × waktu/hari (11 jam lintas OTT 60%, apps 90%, social 50%, e-commerce 40%) × iklan/jam (26)**. (Satuan = jumlah impresi; untuk ₹ kalikan CPM.)
32. **Pasar animasi/VFX India = 4,18 M (views/konsumsi).** Film, TV, game/kartun; rural 70%, urban 30%; internet penetration; usia 5–15 (dominan kartun), 15–40 (film & TV), 45+ (TV) → matriks usage per segmen.
    - *Catatan:* hasil bukan dalam rupiah/₹ — **selalu nyatakan satuan output** (pengguna? views? nilai?).

### Trinity Life Sciences
33. **Cat untuk Airbus "620" = 207,24 L.** Panjang badan: 20 baris ekonomi × 3 kaki + 5 baris bisnis × 5 kaki + kokpit 10 + dapur 10 + … = **110 kaki**; diameter: tinggi orang 6 kaki + bagasi kabin 2 + bagasi tercatat 2 … ≈ 10 kaki; luas silinder ≈ 3.454 ft²; **sayap & ekor = luas badan** → 6.908 ft²; **5 L untuk 500 ft²** → 69,08 L × **3 lapis** = 207,24 L.
34. **Susu per kedai kopi di Connaught Place = 9,56 L/hari.** Waktu buat kopi 7 menit (1 barista/mesin); slot okupansi weekday 08–12 70%, 12–16 50%, 16–22 80% → 24 + 17 + 41 = 82 kopi; weekend 60/80/90% → 20 + 27 + 46 = 94; rata tertimbang (82×5 + 94×2)/7 = **85 kopi/hari**; mix: black 20% (0 ml), latte/cappuccino 50% (75 ml), regular 30% (250 ml) → 0 + 3,19 + 6,38 = **9,56 L**.
35. **Pulpen dibeli di India per hari = 6,44 crore (64,4 jt).** Anak 6–18 (20% = 28 cr) × aktif 80% × 4 pulpen/bulan = 89,6 cr; dewasa 19–60 (50% = 70 cr) × 70% × 2 = 98 cr; lansia 60+ (20% = 28 cr) × 40% × 0,5 = 5,6 cr → 193,2 cr/bulan ÷ 30 = **6,44 cr/hari**.
36. **Pelanggan Spotify Premium India ≈ 20 jt.** Urban 35% (high 20% internet 100%, middle 40% × 70%, low 40% × 30%) + rural 65% (high 10% × 50%, middle 40% × 20%, low 50% × 5%) → **435 jt online** → usia & % pendengar musik (0–14 26% × 50%, 15–24 18% × 90%, 25–34 16% × 85%, 35–44 24% × 60%, 45+ 26% × 40%) → **Spotify 30%** → % premium per usia (5%, 40%, 40%, 20%, 10%) → 19,96 jt. (Premium lebih tinggi di usia muda; internet berkorelasi dengan pendapatan.)

### Lainnya (di indeks)
- Market size of tyre industry, number of outstanding education loans, dll. sudah di atas; indeks juga mencantumkan **"Number of students that use the metro to commute to North Campus"**, **"Monthly revenue of Saravana Bhavan"**, **"Volume of paint to paint an Airbus"**, **"Number of pens bought in a day"** — semuanya tercakup.

---

## 4. POLA BERPIKIR YANG DAPAT DIGENERALISASI

### 4.1 Template pohon demand-side (konsumen)
**Populasi → (lokasi: urban/rural/tier) → (usia relevan) → (pendapatan/kemampuan beli) → (akses: ponsel/internet) → (minat/adopsi) → (pangsa merek) → × frekuensi × kuantitas × harga**.

### 4.2 Template supply-side (outlet/kapasitas)
**Kapasitas (kursi/booth/runway/barista) × jam operasi (peak/non-peak) × okupansi/utilisasi ÷ waktu layanan × AOV × hari (weekday/weekend)**.

### 4.3 Template fisik/geometri
**Model bentuk sederhana (balok/silinder) → luas permukaan (rumus benar!) − bukaan → × lapisan → ÷ daya sebar (m²/L)**.

### 4.4 Template ekstrapolasi
**Nilai historis × (1 + pertumbuhan volume) × (1 + inflasi) × (1 + faktor tambahan) + buffer kontinjensi**.

### 4.5 Checklist anti-salah (dari kesalahan di buku ini)
1. **Satuan konsisten** (orang vs rumah tangga vs kursi-jam vs transaksi; per hari vs per bulan).
2. **Stock vs flow** (jumlah ban terpasang ≠ penjualan ban per tahun).
3. **Sum check** — cabang harus menjumlah ke total.
4. **Frekuensi realistis** (order makanan 1×/hari per orang = terlalu tinggi).
5. **Per-kapita sanity test** (40 botol wine/orang/tahun? 1 galon cat untuk 2 m²?).
6. **Benchmark eksternal** (bandingkan dengan angka publik yang diketahui; selisih 10× = salah struktur).
7. **Satu set asumsi**, ditulis di awal, dipakai konsisten (jangan beda antara teks & hitungan).
8. **Nyatakan satuan output** & definisi (pengguna? revenue? volume?).
9. **Bulatkan** untuk kecepatan, tapi catat pembulatan.
10. **Validasi dengan metode kedua** (top-down vs bottom-up; demand vs supply) — jika bertemu, kredibilitas naik.

### 4.6 Benchmark Indonesia (tambahan untuk konteks pengguna — perkiraan publik umum, verifikasi bila perlu)
- Populasi ±280 jt (2024); urban ±57%; rumah tangga ±4 orang (≈70 jt RT); usia produktif 15–64 ±69%.
- Jabodetabek ±30–34 jt; Jakarta ±10,7 jt; Surabaya ±3 jt; Bandung ±2,5 jt; Medan ±2,5 jt.
- Pengguna internet ±78–80% populasi; smartphone ±70%+; PDB per kapita ±US$4.900–5.000; PDB ±Rp21.000–22.000 triliun.
- Gunakan pola yang sama: populasi → urban/rural → kelas ekonomi (mis. kelas menengah ±17–20%, aspiring middle class ±45–50%) → akses → adopsi → frekuensi → harga.
