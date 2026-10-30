# 23 — Model Valuasi Ekuitas: PT Bayan Resources Tbk (IDX: BYAN) — "Legacy Bridge Capital"

> Sumber: *BYAN Model_Legacy Bridge Capital.xlsx* (34 sheet). Dibuat oleh **Nabil Sachio Refat & M. Rizky Narindra** (juga anggota tim JFCC — file 22) untuk **Legacy Bridge Capital** (legacybridgecapital.id) — gaya **equity research / sell-side initiation**. Semua angka USD juta kecuali disebut.
> Nilai pelajaran: **template model 3-statement + valuasi lengkap untuk perusahaan tambang** (DCF perpetuity & exit multiple, comparable company analysis, **NAV per tambang (sum-of-the-parts)**, beta regresi, WACC, rasio & DuPont, output target price). Beberapa sheet adalah sisa template lain (Under Armour, WMUU, athleisure, Indofood) — abaikan.

---

## 1. Arsitektur model (urutan sheet = alur kerja analis)
1. **Cover** → 2. **FA Model** (main model: IS, CF, BS 2021A–2025A + 2026F–2030F, balance check) → 3. **Supp. Schedules** (revenue per produk, cost of revenue rinci, opex, depresiasi per kelas aset, NWC, capex, utang, ekuitas — dengan kolom **"Assumptions / Rationale"**) → 4. **3-Statement Summary** → 5. **FA Ratio Analysis** → 6. **3-Step DuPont Pyramid** → 7. **FA Output** (financial summary + market snapshot + target price) → 8. **Beta** (regresi & peer unlevered beta) → 9. **NWC Check** → 10. **Valuation Model** (WACC, DCF perpetuity & exit multiple, CCA, final weighted valuation, sensitivitas) → 11. **NAV Model** + 8 sheet **NAV per tambang** → 12. **Supporting Data** (pemetaan kualitas batubara per tambang) → Graphs.

## 2. Model operasi & keuangan
- **Historis → proyeksi:** revenue $2.852 (2021) → **$4.704 (2022, boom harga batubara)** → $3.581 → $3.446 → $3.428 (2025A) → proyeksi $3.645 (2026F) → $3.436 → $3.286 → $3.078 → **$2.954 (2030F)** (tren turun karena harga batubara normalisasi & biaya naik).
- **Margin:** gross margin 63% → 69% (2022) → 36% (2025) → **24% (2030F)**; EBITDA margin 61% → 64% → 33% → 20%; net income $1.266 → $2.301 → … → $784 (2025) → $357 (2030F); net margin 44% → 49% → 23% → 12%. Pajak ~22%.
- **Arus kas:** CFO $1.510 → $2.130 (2022) → $978 (2025) → $532 (2030F); capex ~$170–234/tahun (PP&E + mining properties); **dividen besar** ($1.085 (2022), $1.844 (2023), $703 (2025); proyeksi ~payout tinggi); kas akhir $575 (2025) → $971 (2030F). Total aset ~$3,4–3,8 M; liabilitas turun ke ~$0,7 M; ekuitas ~$2,7–3,1 M; utang sangat kecil ($12,7).
- **Asumsi biaya (rasio % revenue, rata-rata 2 tahun terakhir + rasionalisasi):** overburden removal 24,3% (naik karena strip ratio lebih dalam), mining & hauling 11,5% (naik dengan kedalaman pit & jarak angkut), barging 7,3% (BBM & volume), karyawan 2,8%, repair & maintenance 1,8% (armada menua), PBB 0,6%, lain-lain 2,9%, **royalti/biaya eksploitasi 7,8% (ditetapkan pemerintah)**, pembelian batubara 2,5% (turun karena swasuplai), persediaan datar; selling: agency fee 0,6%, kompensasi **DMO** 0,2%, analisis batubara 0,2%; G&A: karyawan 1,5%, fee profesional 0,15%, lain-lain 0,5%; depresiasi per kelas aset (bangunan & infrastruktur, fasilitas pelabuhan, peralatan transportasi, mesin, bearer plants — garis lurus).
- **Rasio (FA Output):** ROA 52% (2021) → 23% (2025) → 12% (2030F); **RONA** (NI / (PP&E + NWC)); **ROE** 68% → 115% (2022) → 29% (2025); **ROIC** (NOPAT / invested capital) 37% (2025); EPS $0,14 (2025). DuPont 3 langkah: **ROE = net margin × asset turnover × equity multiplier**.

## 3. WACC & beta
- **Rf** = yield SUN 10 tahun (~6%); **MRP** = estimasi Damodaran (~7%); **beta 0,64**; **Ke ≈ 11%**; obligasi peringkat **idA+ (PEFINDO)**, Kd pra-pajak ~9%, setelah pajak ~7%; struktur modal hampir 100% ekuitas (utang $12,7 vs ekuitas ~$20,9 M market) → **WACC ≈ 10,76–11%**.
- **Beta regresi (BYAN vs IHSG, mingguan, Feb 2020–Mar 2026):** periode penuh β 0,20, R² 0,01, t 1,28 → **tidak signifikan**; 5 tahun 0,56; 3 tahun 0,71; **2 tahun 0,74** → catatan: "*kami pakai 2 tahun karena beta periode penuh tidak signifikan secara statistik*".
- **Peer unlevered beta** (unlever dengan D/E & pajak efektif; Hamada): ITMG 0,57, HRUM 0,73, PTBA 0,61 (included); CUAN dikeluarkan (leverage ekstrem D/E 2,31), GEMS (41 obs, R² 4,8%), BUMI (restrukturisasi — beta mencerminkan kredit), ADRO (data tak tersedia) → **median unlevered β 0,61, mean 0,64**. Pelajaran: **saring peer berdasarkan kualitas statistik & komparabilitas, dokumentasikan alasan eksklusi.**

## 4. Valuasi
### 4.1 DCF (perpetuity / Gordon growth)
- UFCF = EBIT − pajak atas EBIT (NOPAT) + D&A − capex − ΔNWC: $165 (2025A) → $914 (2026F) → $734 → $599 → $458 → $346 (2030F).
- **Terminal growth 2%**, WACC ~11% → **TV $4.050 M** (implied TV/EBITDA 6,9×); PV FCF $2.297 + PV TV $2.199 → **EV $4.496 M** (51% dari FCF, 49% dari TV — cek porsi TV!) + kas $575 − utang $12,7 − minoritas 0 → **equity $5.057 M** × kurs 16.000 ÷ 5.471 jt saham → **Rp14.790/saham** vs harga **Rp10.650** (4 April) → **upside 48%**.
### 4.2 DCF exit multiple
- EV/EBITDA target **5,0×** atas EBITDA tahun terminal → **Rp9.739/saham**.
### 4.3 Comparable Company Analysis (S&P Capital IQ)
- Peer batubara Indonesia: ABMM, DSSA, CUAN, ADRO, GEMS, ITMG, HRUM, PTBA, ARII, UNTR (EV/EBITDA, EV/EBIT, P/E, P/BV, EV/forward); **outlier DSSA & CUAN dikeluarkan** (multiple sangat tinggi). Median: **EV/EBITDA 5,48×, EV/EBIT 8,18×, P/E 9,98×, P/BV 1,11×, EV/Fwd EBITDA 4,57×**. BYAN sendiri diperdagangkan 18,5× EV/EBITDA, 27,7× P/E, 8,3× P/BV (premium tinggi).
- Implied price: EV/EBITDA → Rp19.675; EV/EBIT → Rp25.626; P/E → Rp22.888; P/BV → Rp11.006; fwd EV/EBITDA → Rp19.599.
### 4.4 Final weighted valuation
| Metode | Bobot | Nilai/saham |
|---|---|---|
| DCF perpetuity | 30% | Rp14.790 |
| DCF exit multiple | 25% | Rp9.739 |
| EV/EBITDA target | 15% | Rp19.675 |
| EV/EBIT target | 10% | Rp25.626 |
| P/E target | 10% | Rp22.888 |
| P/BV target | 10% | Rp11.006 |
| **Intrinsic value** | 100% | **Rp15.775** → upside **48%** vs Rp10.650 |
- **Sensitivitas:** EV terhadap WACC × terminal growth.
### 4.5 NAV (Sum-of-the-parts per tambang) — metode khas perusahaan tambang
- Asumsi: harga saham Rp9.550; 5.471 jt saham; kurs 16.000; market cap $3.265 M; WACC 10,76%; **harga jual ICI4 $48,4/t**; biaya tambang rata-rata $32,5/t; pajak 22%; penjualan 95% dari produksi; **kewajiban DMO 25%**.
- **NPV per tambang** (cadangan Mt; produksi Mt/th; kepemilikan; NPV 100% → atribusi): **Pakar (PT Fajar Sakti Prima)** 2.707 Mt; 32 Mt/th; 100%; **$2.377 M** · **Tabang (PT Bara Tabang)** 319,5 Mt; 50,5 Mt/th; 49%; $3.678 → $1.802 M · Wahana Baratama 325 Mt; 10; $578 M · Perkasa Inakakerta 204 Mt; 6; $376 M · Melak (Dermaga Energi) 180 Mt; 5; $338 M · GPK 97,5 Mt; 4; 77%; $207 M · Gunungbayan Block II 26,5 Mt; 0,3; 93%; $6 M · Mamahak 13,9 Mt; 1; 99%; $66 M → **total cadangan 3.873 Mt, produksi 108,8 Mt/th, NPV atribusi $3.450 M**.
- **NAV bridge:** aset tambang $3.450 M (XNPV 8 DCF tambang) + **upside eksplorasi $500 M** (estimasi konservatif dari resource JORC 3,87 Bt) + kas $575 − utang $12,7 + aset lain $200 (JV nikel, land bank) − **PV biaya G&A korporat $150** (~$15 jt/th) − **provisi penutupan & reklamasi tambang $100** (kewajiban AMDAL 8 IUP) → **NAV $4.462 M = Rp13.049/saham**; harga Rp9.550 → **P/NAV 0,73 (diskon 27%), upside 37%**; sensitivitas NAV/saham terhadap **harga ICI4 × WACC**.
- **Model per tambang** (contoh Pakar): price deck (harga terakhir & rata-rata; peramalan **ARIMA/SARIMA**; HBA II/III), harga FOB domestik (70 × CV aktual/6.332), jadwal produksi (saldo awal cadangan, produksi, recovery rate, saldo akhir, % umur tambang; skenario best/base/worst disesuaikan permintaan domestik **RUPTL 2025–2034**), penjualan domestik (DMO) vs ekspor, biaya operasi per ton (mining & stripping, SG&A, lain-lain), royalti % penjualan, PP&E & asset turnover, depresiasi, **sustaining capex = depresiasi**, write-off sisa PP&E di akhir umur tambang, **strip ratio** (best/base/worst) → waste & total material moved, NWC (AR/inventory/AP days), **FCF = EBIT + D&A − capex − pajak − ΔNWC − reklamasi** → NPV.
- **Supporting data:** pemetaan kualitas batubara per tambang/blok (CV GAR kcal/kg, sub-bituminous, kategori HBA II/III, posisi strategis: "core production asset" vs "future reserve optionality").

## 5. Output (FA Output — gaya laporan riset)
- **Market snapshot:** harga Rp9.500; **target price Rp13.912**; horizon investasi 9 bulan; market cap Rp52,3 T (US$3,3 M); rentang 52 minggu Rp8.200–10.500; 5.471 jt saham; free float ~41%; pemegang saham: **PT APP Purinusa Ekapersada (Sinar Mas) 58,31%**, Cakrawala Mega Indah 0,20%, Wirakarya Sakti 0,19%, publik ~41%.
- Financial summary 2021–2030F (revenue, EBITDA, NI, EPS, margin, ROA, RONA, ROE, ROIC).

---

## 6. Pelajaran membangun valuasi ekuitas (equity research)
1. **Bangun 3-statement yang seimbang** (balance check = 0) dengan **driver % revenue berbasis rata-rata historis + alasan tertulis** per baris.
2. **Gunakan beberapa metode & beri bobot beralasan**: DCF perpetuity, DCF exit multiple, CCA (EV/EBITDA, EV/EBIT, P/E, P/BV), dan untuk tambang **NAV sum-of-the-parts**; tampilkan **football field**/tabel bobot.
3. **Beta**: regresi dengan uji signifikansi (t-stat, R²); bila tak signifikan gunakan periode lain atau **beta peer yang di-unlever lalu di-relever**; dokumentasikan eksklusi peer.
4. **Cek porsi terminal value** (di sini ~49%) dan implied multiple TV (6,9× EBITDA) agar masuk akal vs peer.
5. **Bersihkan outlier** dalam peer set (DSSA, CUAN) dan pakai median.
6. Untuk komoditas: **price deck** eksplisit (forecast statistik + harga acuan resmi), **skenario produksi/strip ratio**, **royalti, DMO, reklamasi**, sustaining capex.
7. Sajikan **target price, upside, horizon, kepemilikan, free float** di halaman output — seperti laporan riset broker.
8. **Hapus sheet sisa template** sebelum dibagikan (Under Armour, WMUU, dll.) dan pastikan konsistensi harga saat ini (Rp9.500 vs 9.550 vs 10.650) & target (Rp13.912 vs Rp15.775 vs NAV Rp13.049).
