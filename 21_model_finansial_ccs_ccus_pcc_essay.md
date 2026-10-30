# 21 — Model Finansial "financial analysis essay.xlsx" (proyek CCS/CCUS + PCC + MRV — kasus Pertamina × industri pulp & paper)

> Sumber: *financial analysis essay.xlsx* (7 sheet: constraint and rules · ✅List of Equipment · ✅Financial Analysis · Assumptions · Notes & Sources · Project Cash Flow 2030–2045 · Indicators). Model ini adalah **lampiran finansial proposal esai lomba** untuk kasus **Pertamina CCS/CCUS di industri pulp & paper** (selaras dengan contoh "#CIRCLE Strategy" di file 13). Catatan tim dalam Bahasa Indonesia tertanam di sel.
> Nilai pelajaran: **template model techno-economic lengkap** (capex bottom-up dari daftar peralatan → indirect cost → TCI → opex → revenue berlapis → WACC → DCF dengan terminal value → indikator), dengan skenario ramp-up.

---

## 1. Constraint & rules (dari kasus)
- Volume penangkapan CO₂ **300.000 ton/tahun**; sumber: flue gas recovery boiler (konsentrasi CO₂ 6,9%); capture rate **90%**.
- Inflasi **2,2%/tahun** (IMF 2025); umur proyek **15 tahun** (praktik kontrak 10–15 tahun); harga karbon **US$30/ton**; transport CO₂ via pipa 8–9 km dari pabrik pulp; harga gas alam **US$7/MMBtu** (2025, lalu inflasi). Kurs Rp16.500/US$ (sebagian Rp16.825).

## 2. Capex bottom-up (List of Equipment, US$ → Rp)
- **A. Flue gas liquefaction hubs (4,5 jt ton flue gas/tahun):** 4 scrubber pre-treatment $8 jt; 4 unit dehidrasi $4,4 jt; 4 kompresor multi-stage $13 jt; 4 sistem liquefaction kriogenik $22 jt; 4 paket refrigerasi $7 jt; 8 tangki penyimpanan gas cair $9 jt; 4 sistem loading truk/kapal $3,2 jt; utilitas & listrik $5,5 jt.
- **B. Armada transport:** 60 truk tangki kriogenik $7,92 jt; 2 kapal pengangkut CO₂ kecil $21 jt.
- **C. Central CO₂ processing plant:** kolom absorpsi $6 jt; kolom regenerator $3,8 jt; unit pengering $1,8 jt; kompresor $5 jt; tangki $2,8 jt.
- **D. Pipa ke lokasi injeksi:** pipa 40 km 10–12" $30 jt; booster station $4 jt.
- **G. Platform digital MRV:** software $1,1 jt; server & cloud $0,6 jt; integrasi sensor IoT $0,9 jt; cybersecurity $0,4 jt.
- Subtotal CCS/CCUS + MRV ≈ **Rp2,597 T**.
- **E. Pabrik PCC (precipitated calcium carbonate):** reaktor karbonasi $5 jt; lime slaker $2 jt; separator padat-cair $2 jt; pengering $3 jt; milling & packaging $1,5 jt; utilitas & penyimpanan $3,5 jt; **F.** 15 truk tangki CO₂ ke pabrik PCC → subtotal ≈ Rp280,5 M.
- **Total direct cost ≈ Rp2,878 T.**
- **Land & building:** bangunan 47.500 m² × Rp5 jt/m² = Rp237,5 M (lahan tidak dihitung).
- **Indirect costs (persen dari direct cost):** EPCC 8% (Rp230,2 M) · izin & kepatuhan 1% · training & pre-operating 0,6% · **contingency desain & proyek 6%** → total Rp449 M.
- **Fixed Capital Investment (FCI)** = direct + indirect ≈ **Rp3,327 T**; hibah JCM/JETP (baris tersedia, diisi 0); **working capital = 13% FCI** (Rp432,5 M) → **Total CAPEX ≈ Rp3,997 T**.
- Jadwal belanja FCI: **3 tahun — 60% tahun pertama, sisanya 40%** (model tabel: −60%, −20%, −20%); IDC (interest during construction) dikapitalisasi.

## 3. Opex
- **Bahan baku:** gas alam 588.000 MMBtu × (US$7 × kurs) ≈ Rp69,3 M/tahun.
- **General support (persen dari nilai peralatan):** asuransi 1%, maintenance & repair 1% (variabel), CSR 0,03%, keamanan/umum 0,1%, training 0,01%, administrasi 0,01%, komunikasi 0,01% → ≈ Rp53,2 M; PCC: maintenance 1% → Rp2,9 M.
- **Tenaga kerja (51 orang, gaji dalam US$ × kurs):** 1 factory manager (~Rp32,7 jt/bulan), 4 department manager (~Rp21,8 jt), 5 operation leader (~Rp16,3 jt), 21 staff (~Rp10,9 jt), 20 operator (~Rp6,5 jt) → ≈ Rp114,9 M/tahun.
- **Total biaya operasi ≈ Rp240 M/tahun** (COMd + opex fixed + variable).
- **Depresiasi garis lurus:** (FCI + IDC) Rp3,83 T, umur 15 tahun, nilai sisa 10% → **Rp229,8 M/tahun**.

## 4. Revenue (berlapis — "revenue stacking")
- **Sebelum PCC (2030–2034):** **CCS service fee** 300.000 t × US$87/t ≈ Rp439,1 M; **EOR premium** 250.000 t × US$65 ≈ Rp273,4 M (catatan: gross = tambahan barel × harga minyak; premi biasanya 15–25% setelah pajak); **ekspor CO₂ cair** 50.000 t × US$200 ≈ Rp158,3 M; **cost recovery PSC** (production sharing contract) 47.290 × US$100 ≈ Rp79,6 M → **≈ Rp950,4 M/tahun** + carbon credit + MRV → **≈ Rp973 M**.
- **Carbon credits:** 60.000 t × US$30 ÷ 2 (**50% untuk kemitraan JCM**) ≈ Rp15,1 M; pertumbuhan 4%/tahun (pasar karbon tumbuh low-single-digit — EM, World Bank, MSCI).
- **MRV subscription:** 300.000 × US$1,5 ≈ Rp7,6 M; pertumbuhan 6%/tahun (biaya MRV tumbuh lebih cepat karena regulasi/audit — LSE, WRI).
- **Setelah PCC (2035–2045):** EOR turun ke 165.000 t (sebagian CO₂ dialihkan ke PCC); **PCC & CO₂ cair utilitas** 65.000 t × US$120 ≈ Rp131,2 M; **nano-PCC** 20.000 t × US$400 ≈ Rp134,6 M (PCC Rp265,8 M @100% kapasitas) → total ≈ **Rp1,146 T/tahun**. Alokasi CO₂: EOR 50%, CCS 35%, PCC 15%.
- Pabrik PCC dibangun 2030, selesai 2035.

## 5. Struktur pendanaan & WACC
- **DER 2,33** → debt 70% (≈Rp2,80 T), equity 30% (≈Rp1,20 T); cost of debt = **YTM obligasi 7,47%** (rating Pefindo; BI rate + floating); cost of equity = **ICC 10,5%** (benchmark PGEO — Pertamina Geothermal); pajak 22%; pelunasan utang 12 tahun (≈Rp233 M/tahun).
- **WACC = (D/V)·Kd·(1−T) + (E/V)·Ke = 0,70×7,47%×0,78 + 0,30×10,5% ≈ 7,23%.**

## 6. Skenario & asumsi (sheet Assumptions)
- **Load factor PCC:** Skenario A (optimis) 2035 50% → 2036 75% → 2037+ 100%; Skenario B 40% → 70% → 90% → 100%. Dipilih A karena "**Pertamina bukan bisnis/perusahaan baru**, diasumsikan bisa mengikuti skenario lebih optimis".
- **Cost ramp:** *Method 1 – Follow load* (biaya mengikuti load factor tanpa penalti efisiensi) vs *Method 2 – Efficiency* (biaya mengikuti load + penyesuaian efisiensi ramp-up → lebih tinggi di awal; 2035 70%, 2036 90%, 2037 100%). Literatur ramp-up manufaktur: operasi awal tidak stabil.
- **Terminal value (perpetuity growth):** TV = FCF(n+1)/(WACC − g); g default 2,5% (alt 2% & 3%), titik tengah inflasi & PDB Indonesia (5,3–5,6% 2026).
- Revenue CCS sebelum/sesudah PCC dianggap konstan (tanpa growth); PCC growth hanya dari load factor.

## 7. Laporan arus kas proyek 2027–2045
- Seksi A **Capital investment** (land & building, FCI, IDC kapitalisasi, initial WC, dikurangi hibah JCM/JETP) → **TCI 2027 Rp2,36 T, 2028 Rp0,83 T, 2029 Rp1,31 T**.
- Seksi B **Revenue & opex** (revenue PCC, carbon credits, MRV, CCS before/after PCC; COMd; opex; gross profit & margin) → revenue Rp973 M (2030) → Rp1,169 T (2045).
- Seksi C **Profit & tax** (depresiasi → EBIT → bunga → EBT → pajak 22% → EBIT(1−T) → **NIAT** ≈ Rp406 M (2030) → Rp540 M (2045); dip 2035 saat transisi PCC); catatan **tax holiday** dipertimbangkan.
- Seksi D **Cash flows**: add-back depresiasi, ΔWC, capex penggantian, pelunasan pokok, utang baru → **FCFF** + **terminal value di 2045** → diskonto WACC.
- Tabel lain (sheet Financial Analysis): TCI, CoM, revenue, gross profit, depresiasi, taxable income, pajak, NIAT, cash flow, discount factor, discounted & cumulative cash flow (sebagian sel #REF! — model belum dibersihkan).

## 8. Indikator
- **Discount rate (WACC) 7,23%**; **Project IRR 16,1%**; **PI 1,30** (NPV/TCI; aturan: PI > 1 terima, < 1 tolak, = 1 impas); **payback proyek 7 tahun** (dari investasi pertama 2027) / **payback operasional 6 tahun** (dari operasi 2030); horizon DCF 2027–2045 (umur operasi 16 tahun); **rata-rata revenue ≈ Rp1,09 T/tahun**; **rata-rata net profit margin ≈ 43%**; **ROI proyek ≈ 167%** (Σ NIAT / Σ TCI).
- Penjelasan tim: IRR = return tahunan (angka sedang); ROI = return total jangka panjang (angka besar); NPV = nilai sekarang; payback = tahun balik modal.

---

## 9. Pelajaran membangun model finansial lomba (dari file ini)
1. **Capex bottom-up dari daftar peralatan** (kuantitas × harga, bersumber) lebih kredibel daripada angka bulat.
2. Tambahkan **indirect cost standar** (EPC ~8%, izin ~1%, pre-operating ~0,6%, **contingency 5–10%**) dan **working capital** (~10–15% FCI).
3. **Revenue stacking**: pisahkan aliran (service fee, EOR, ekspor produk, cost recovery PSC, carbon credit, MRV, produk turunan) — tiap aliran punya volume × harga × asumsi pertumbuhan bersumber.
4. **WACC dari struktur modal nyata** (DER, YTM obligasi sesuai rating, cost of equity benchmark perusahaan sejenis) — bukan angka asumsi.
5. **Skenario & sensitivitas** eksplisit (load factor, cost ramp, terminal growth) dengan alasan pemilihan base case.
6. Laporkan **NPV, IRR, PI, payback (proyek vs operasional, nominal vs terdiskonto), ROI, margin** — dan pahami bedanya.
7. **Bersihkan model sebelum diserahkan** (hindari #REF!, kurs ganda 16.500 vs 16.825 vs 15.825, catatan informal) — juri bisa membuka appendix spreadsheet.
