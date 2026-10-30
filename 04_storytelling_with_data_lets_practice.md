# Storytelling with Data: Let's Practice! — Cole Nussbaumer Knaflic (Wiley, 2020, 448 hal.)

Sumber: `Storytelling with Data _ Let's Practice! ...pdf`. Penulis: founder SWD, ex-Google People Analytics; buku pendamping "storytelling with data" (SWD, 2015). Gene Zelazny & Cole Knaflic juga dirujuk oleh Bulletproof sebagai referensi visual McKinsey. Struktur buku: tiap bab = **recap** pelajaran SWD → **practice with Cole** (soal + solusi bertahap) → **practice on your own** (tanpa solusi) → **practice at work** → **let's discuss**. Bab: 1 Understand the context · 2 Choose an effective visual · 3 Identify & eliminate clutter · 4 Focus attention · 5 Think like a designer · 6 Tell a story · 7 Practice more with Cole (studi kasus lengkap) · 8 Practice more on your own · 9 Practice more at work (tips, panduan fasilitator, rubrik) · 10 Closing words.
- Tidak ada satu jawaban "benar"; ada pendekatan yang lebih baik. Kerjakan dulu sendiri sebelum melihat solusi; gambar, tulis, gunakan tools; minta feedback; tetapkan tujuan spesifik & komunikasikan ke orang lain.
- **Tools:** Excel, Google Sheets, Datawrapper, Flourish, Infogram, Tableau, Power BI, R, Python, D3.js — "tak ada tool yang inherently baik/jahat"; kuasai satu agar tool tak membatasi. Semua solusi Cole dibuat di Excel. **Alat terpenting: pena & kertas.**

---

## BAB 1 — Understand the Context

### Recap SWD Bab 1
- **Exploratory vs Explanatory analysis.** Exploratory = menganalisis & memahami (mencari "mutiara di antara tiram"); **Explanatory** = mengomunikasikan cerita spesifik — **fokus buku**.
- **Mulai dari mana — 3 pertanyaan:**
  1. **WHO** — siapa audiens? *Spesifik!* Apa hubungannya dengan Anda? Apa yang memotivasi mereka? Apa yang membuat mereka terjaga di malam hari?
  2. **WHAT** — apa yang Anda ingin mereka *lakukan* (change, support, create, implement, empower...)? *Eksplisit!* Jangan berasumsi mereka akan menghubungkan titik-titiknya sendiri.
  3. **HOW** — apakah data membantu menegaskan poin? *Diskriminatif!* Data apa yang menjadi bukti?
- **3-minute story:** bila hanya punya 3 menit, apa yang akan Anda katakan? Esensi ("So what?") dari keseluruhan cerita. Mengetahui persis apa yang ingin dikomunikasikan mengurangi ketergantungan pada slide & data.
- **Big Idea** (dari Nancy Duarte, *Resonate*, 2010): "So what?" yang lebih dipadatkan — **satu kalimat** yang (1) mengartikulasikan **point of view** unik Anda, (2) menyampaikan **what's at stake**, (3) **satu kalimat lengkap**.
- **Storyboarding:** perencanaan di depan untuk membuat struktur, dengan **sticky notes** (menghindari keterikatan pada kerja yang sudah dibuat di komputer, memaksa artikulasi ringkas, mudah menata ulang alur). Tiga langkah: **(1) Brainstorm → (2) Edit → (3) Get feedback.**

### Ex 1.1 — Mengenal audiens (kepala HR baru; Anda People Analyst)
Saat tak bisa bertanya langsung: (1) debrief dengan kolega yang sudah bertemu dia (prioritas, minat, apa yang tak berjalan baik); (2) tanyakan manajer (yang makan siang dengannya) apa fokus awal & apa yang menurut manajer penting; (3) gunakan pemahaman data & konteks + desain dokumen cerdas: **ringkasan takeaway tingkat tinggi di depan**, sisanya diorganisir per topik agar pembaca bisa langsung ke area minatnya.

### Ex 1.2 — Mempersempit audiens (survei back-to-school ritel pakaian)
- Jaring luas: senior leadership, buyer, merchandiser, marketing, store manager, sales associate, customer service, pesaing, pelanggan.
- Temuan: kepuasan layanan berbeda antar toko → leadership, store manager, sales associate, CS.
- Rekomendasi: pelatihan sales associate → + HR (siapa membuat/menyampaikan), Finance (anggaran).
- **4 cara mempersempit:** (1) spesifik tentang apa yang dipelajari dari data; (2) jelas tentang aksi yang direkomendasikan; (3) sadari posisi waktu (apa yang harus terjadi *sekarang*: persetujuan); (4) identifikasi **decision maker spesifik** → **kepala retail sales**. Komunikasi ke kelompok lain terjadi "downstream".

### Big Idea Worksheet (template)
- **Who is your audience?** (1) Daftar kelompok/individu utama; (2) jika harus satu orang, siapa?; (3) apa yang mereka pedulikan?; (4) aksi apa yang harus mereka ambil?
- **What is at stake?** Manfaat jika audiens bertindak sesuai keinginan Anda? Risiko jika tidak?
- **Form your Big Idea:** point of view + what's at stake + satu kalimat lengkap.
- **Contoh solusi 1.3 (back-to-school):** audiens = tim eksekutif → kepala retail; peduli: musim back-to-school yang sangat menguntungkan, pelanggan senang (belanja lebih), mengalahkan pesaing; aksi: setuju pelatihan adalah cara tepat menangani level layanan yang tak konsisten & menyetujui sumber daya (biaya, waktu, orang). Manfaat: layanan lebih baik → pelanggan lebih senang, belanja lebih banyak, kembali lebih sering, cerita positif ke teman. Risiko: WOM negatif, pelanggan ke pesaing, risiko reputasi, kehilangan revenue. **Big Idea: "Mari berinvestasi dalam pelatihan sales associate untuk memperbaiki pengalaman belanja di toko dan menjadikan musim back-to-school mendatang yang paling menghasilkan revenue!"**
- **Ex 1.4 refine & reframe:** framing positif (manfaat revenue) vs negatif (kerugian jika tak bertindak) atau ganti apa yang dipertaruhkan (mengalahkan pesaing). Manfaat potensial: pelanggan puas, revenue, mengalahkan pesaing; risiko: pelanggan tak puas, revenue turun, kalah, WOM negatif, kerusakan reputasi. **Asumsi tentang apa yang paling dipedulikan audiens menentukan framing.**
- **Contoh solusi 1.5 (pilot adopsi hewan di toko pet supply):** audiens = panitia acara shelter (voting mayoritas) → Jane Harper (paling berpengaruh); peduli: menaikkan adopsi (target +20%), kemampuan fundraising, sadar biaya; aksi: setujui pilot 3 bulan + sumber daya marketing ($500 cetak + 3 jam relawan/bulan). Manfaat: lebih banyak adopsi (euthanasia lebih rendah), capai target 20%, fundraising masa depan. Risiko: peluang hilang, hewan tak mendapat rumah, euthanasia & biaya lebih besar, gagal target. **Big Idea: "Setujui program pilot berbiaya rendah kami yang berpotensi meningkatkan adopsi secara signifikan dan menghasilkan peluang fundraising yang lebih baik."**
- **Ex 1.6 kritik Big Idea** ("Meski tingkat vaksinasi flu membaik dari tahun lalu, kita harus menaikkan 2% untuk mencapai rata-rata nasional"): tanyakan dulu siapa audiens & apa yang mereka pedulikan. Point of view ada (naikkan vaksinasi); **what's at stake tidak jelas**; satu kalimat ✓ (bisa ditambah). Memberi *what* tapi bukan *why*. Apakah rata-rata nasional memotivasi? Target terlalu agresif/kurang? Alternatif: kompetisi (pusat medis lain, negara bagian), kebaikan bersama (manfaat pasien, kesejahteraan komunitas); positif vs negatif. Dialog memaksa kolega menjelaskan pemikiran & asumsinya.

### Storyboarding
- "Storyboarding adalah hal terpenting yang bisa dilakukan di depan untuk mengurangi iterasi & membuat materi lebih tepat sasaran." Visual outline konten, **low-tech** sebelum membuat konten.
- **Solusi 1.7 (back-to-school) — brainstorm 20 ide:** konteks historis (back-to-school penting), masalah (historis tidak data-driven), cara-cara yang dipertimbangkan, aksi (survei), detail survei (kelompok pelanggan, demografi, response rate, pesaing yang dimasukkan, pertanyaan, tanggal), data (perbandingan antar item, per toko & region, vs pesaing, per toko/region vs pesaing), kabar baik (di mana unggul), kabar buruk (di mana kalah), area perbaikan, remedi potensial, **rekomendasi: investasi pelatihan sales**, sumber daya (orang, anggaran), apa yang diselesaikan, timeline, diskusi/keputusan. **Storyboard (3 baris):** PROBLEM (back-to-school penting [demonstrasikan] · historis tidak data-driven · cara yang dipertimbangkan agar lebih data-driven) → ACTION/ANALYSIS (Survei! · semua detail: siapa ditanya, siapa merespons, pesaing · apa yang dipelajari dari data) → OUTCOME (peluang: inkonsistensi level layanan · rekomendasi: investasi pelatihan karyawan (+detail) · diskusi/persetujuan).
- **Solusi 1.8 (pilot adopsi):** BACKGROUND (tujuan +20% adopsi · konteks: adopsi saat ini · tunjukkan bagaimana adopsi membantu fundraising) → OPPORTUNITY (acara bulan lalu sukses tak terduga · perkenalkan kemungkinan akar penyebab · apa yang bisa didapat jika direplikasi · data keberhasilan di shelter lain) → PROPOSAL (perkenalkan pilot 3 bulan · investasi: $500 + 3 jam · bagaimana mengukur hasil · rekomendasi: setujui program & sumber daya).
- **Ex 1.14 — mengatur komponen** (background, analysis, recommendation, data, problem statement, findings): pertimbangkan di mana asumsi diletakkan; untuk audiens teknis (banyak pertanyaan tentang data) vs saat butuh input konteks dari audiens (di mana mengundang input) vs **senior leadership dengan waktu sangat singkat** (mungkin lebih pendek dari slot) → urutan berubah (pimpin dengan rekomendasi).
- **Ex 1.16 — storyboard kolega (pemilu mahasiswa)** berisi sticky notes acak (timeline pemilu 4 bulan lagi, turnout −30%, turnout beda per asrama & angkatan, "bisa membaik tahun ini", iklan tertarget membantu, 3.000 mahasiswa, flyer $500, Instagram $500, benchmark Smithville 80% & Denbigh 50%, tujuan naikkan turnout, butuh persetujuan hari ini, butuh $1.000, berapa kali bertemu sebelum pemilu) → kritik: urutan (kronologis/Big Idea dulu?), gabung/tambah/buang, revisi; jika audiens (wakil presiden) sibuk & sering memotong rapat → **letakkan call to action di depan**.

### Practice at work (Bab 1)
- **1.17 Get to know your audience:** bisa bicara langsung? orang yang mirip audiens? kolega yang pernah (gagal) berkomunikasi dengannya? Asumsi tentang motivasi, bias, apakah data penting, reaksi. **Audiens campuran** → kelompokkan & kerjakan per kelompok; cari irisan kebutuhan. Uji asumsi dengan kolega; minta jadi **devil's advocate**; antisipasi apa yang bisa salah.
- **1.18 Narrow:** proyek → jaring luas → tambah lagi → persempit: apa yang dipelajari dari data, aksi apa & siapa yang bertindak, posisi waktu, decision maker utama → audiens primer.
- **1.19 Identify the action:** "Setelah membaca deck/mendengar presentasi saya, Anda harus ___." Daftar kata kerja: accept, agree, approve, begin, believe, budget, buy, champion, change, collaborate, commence, consider, continue, contribute, create, debate, decide, defend, desire, determine, devote, differentiate, discuss, distribute, divest, do, empathize, empower, encourage, engage, establish, examine, facilitate, familiarize, form, free, implement, include, increase, influence, invest, invigorate, keep, know, learn, like, maintain, mobilize, move, partner, pay for, persuade, plan, procure, promote, pursue, reallocate, receive, recommend, reconsider, reduce, reflect, remember, report, respond, reuse, reverse, review, secure, share, shift, support, simplify, start, try, understand, validate, verify. Kadang butuh input audiens untuk menentukan aksi, atau ingin mereka menemukan sendiri — tapi **komunikator harus jelas** apa aksinya.
- **1.21 Solicit feedback on Big Idea** (10 menit dengan partner): Apa tujuan & seperti apa sukses? Siapa audiens? Ada jargon/akronim? Aksi jelas? Dibingkai dari sudut Anda atau audiens (ubah ke audiens)? Apa yang dipertaruhkan & apakah memikat ("So what?")? Kata lain yang lebih mudah? Bisakah partner mengulang pesan dengan kata sendiri? **"Why?" adalah pertanyaan terbaik — terus tanyakan.**
- **1.22 Big Idea sebagai tim:** tiap orang mengisi worksheet → tulis semua di whiteboard & bacakan → diskusikan kesamaan & yang tak selaras → buat **master Big Idea** → keselarasan & buy-in.
- **1.23 Brainstorm:** sticky notes, timer 10 menit, keluarkan sebanyak mungkin ide tanpa filter — lakukan **setelah paham data & Big Idea, sebelum membuat konten di komputer**.
- **1.24 Organize:** struktur menyeluruh, buat sticky meta-topik, gabung & eliminasi (**discard pile**: apakah ini membantu Big Idea tersampaikan?). Pertanyaan urutan: presentasi live/telepon/webinar atau dibaca sendiri? mulai dengan aksi atau membangun ke arahnya? konteks esensial — di depan atau nanti? seberapa cepat menjawab "So what?" sudah punya kredibilitas atau perlu dibangun? asumsi — kapan & bagaimana diperkenalkan, apa jika salah? butuh input audiens — di mana? di mana data masuk — mengonfirmasi atau berlawanan ekspektasi? bagaimana menciptakan common ground, buy-in & memicu aksi? Konten yang tak mendukung pesan tapi tak tega dibuang → **appendix** atau de-emphasize.
- **1.25 Feedback storyboard:** bagaimana disajikan (dibaca sendiri vs dipresentasikan)? urutan & alur masuk akal? di mana Big Idea diperkenalkan? apakah audiens peduli semua bagian? bagaimana menjaga perhatian di bagian kurang menarik? di mana bisa salah? transisi antar topik? apa yang bisa dipotong/ditambah/ditata ulang? Minta feedback manajer/stakeholder di titik ini (sebelum investasi waktu besar). Hasil perencanaan depan: materi lebih pendek, lebih banyak waktu untuk slide & grafik berkualitas.

---

## BAB 2 — Choose an Effective Visual

### Recap SWD Bab 2 (jenis visual)
- **Simple text** — "Just because you have numbers doesn't mean you need a graph!" (mis. satu angka besar "91%" + kalimat).
- **Table** — tanya "apa poin utama yang ingin dibuat?"; sering ada cara lebih efisien; **hindari tabel di presentasi live** karena orang berhenti mendengar & mulai membaca.
- **Heatmap** — mata mudah menangkap perbedaan besar intensitas warna, tapi perbedaan kecil tak menonjol; bagus saat mulai eksplorasi untuk menentukan di mana menggali.
- **Scatterplot** — mengodekan data pada dua sumbu sekaligus untuk melihat hubungan.
- **Line** — aturan: garis yang menghubungkan titik harus masuk akal; paling efektif untuk **data kontinu, biasanya waktu**.
- **Slopegraph** — "nama keren untuk line graph dengan hanya 2 titik"; fokus pada perubahan antara 2 titik waktu atau perbedaan antar kelompok.
- **Bar charts** — bagus untuk data kategorikal; mudah bagi mata membandingkan tinggi terhadap baseline konsisten; **ATURAN: harus punya zero baseline, tanpa pengecualian.** Vertikal (kolom); **horizontal** (bagus bila nama kategori panjang); **stacked** (sering disalahgunakan — mudah membandingkan total & seri pertama, tapi segmen lain tak sejajar baseline); **100% stacked** (dua baseline untuk perbandingan).
- **Waterfall** — dari kuantitas awal, penambahan & pengurangan, ke kuantitas akhir; sering di finance (varians vs anggaran).
- **Square area (waffle chart)** — grid penting karena kita cenderung salah menaksir area; bagus untuk angka dengan magnitudo sangat berbeda atau sebagai alternatif pie.

### Ex 2.1 — Memperbaiki tabel (new client tier share)
- **Observasi & pertanyaan:** mayoritas akun di Tier B & C, tapi A & A+ (sedikit akun) menyumbang revenue berarti; urutan tier aneh (A sebelum A+ — sort alfabet?); tak ada baris Total; % Accounts hanya berjumlah 81,16% & % Revenue 95% → ada kategori "Other/All other" yang hilang; terlalu banyak desimal (7,08% vs 7,09% bermakna?) → bulatkan ke bilangan bulat, kecuali revenue ($M) 1 desimal.
- **Desain tabel:** desain harus "memudar ke latar" agar fokus ke angka; **hindari zebra shading**, gunakan white space & border tipis terang; tabel boleh center-align (atau rata kanan/desimal untuk angka); kelompokkan kolom dengan judul bersama (ACCOUNTS: #, % OF TOT; REVENUE: $M, % OF TOT); tambah baris TOTAL; urutkan A+ → A → B → C → D → All other.
- **Zigzagging "z":** tanpa isyarat visual, audiens mulai dari kiri atas lalu zigzag → letakkan data terpenting di atas & kiri (bila masuk akal dalam struktur).
- **Ke mana mata tertarik?** Di tabel standar, mata ke baris header — bukan data! Arahkan perhatian dengan warna hemat, outline sel/kolom, **heatmapping** pada kolom kunci (conditional formatting Excel), atau **embedded bar** dalam tabel (tapi perbandingan antar kolom sulit karena tak sejajar baseline).
- **Iterasi grafik:** sepasang pie (Cole: "satu hal lebih buruk dari satu pie: dua pie!"; pie hanya bagus untuk "satu bagian sangat kecil/besar"; mata buruk membandingkan area; segmen bergeser posisi antar pie) → dua bar horizontal terpisah → **dual-series horizontal bar** (perbandingan % accounts vs % revenue per tier paling mudah: berdekatan & sebaris baseline — "Bingo!") → kolom vertikal → tarik garis antar ujung → hapus bar → **slopegraph** (label langsung): A+ & A hanya 9% akun tapi ~50% revenue; C & All other turun.
- Prinsip: **identifikasi perbandingan utama yang ingin dibuat audiens, letakkan berdekatan secara fisik & sejajarkan pada baseline yang sama.** Tak perlu mencoba semua view; persempit ke perbandingan spesifik.

### Ex 2.2 — Visualisasikan tabel (makanan disajikan 2010–2019)
- Membaca kolom angka butuh banyak tenaga otak. Heatmap 3 warna (putih–hijau muda–hijau) cepat menunjukkan 2010 jauh lebih rendah & 2016 tertinggi, tapi perbedaan medium sulit. **Bar** (perbesar lebar bar, kurangi gap agar mudah membandingkan puncak) — cocok bila program punya awal-akhir jelas per tahun. **Line** tanpa y-axis, hanya label titik awal (40.139) & akhir (232.797); subtitle sebagai judul sumbu; tambah marker untuk titik penting (puncak 2016). Garis lebih baik untuk tren & punya ruang anotasi. Warna tak harus biru.

### Ex 2.3–2.4 — Menggambar di kertas (capacity vs demand jam proyek)
- **Kertas kosong = alat terbaik**: bebas dari batasan tool, tak terikat pada hasil komputer, ruang kosong memicu kreativitas. Timer 10 menit, sketsa sebanyak mungkin.
- 6 opsi: kolom (capacity terisi, demand outline — paling sedikit menarik perhatian ke gap), **line** (bersih; label di ujung garis + nilai: 34K demand, 24K capacity; tebalkan capacity), overlapping bars (capacity semi-transparan; tak biasa → uji feedback), **stacked bars capacity + unmet demand** (hanya bila demand ≥ capacity; unmet demand biru, capacity abu → **pilihan Cole**), dot plot dengan area penghubung (dot = marker garis tanpa garis; "brute force Excel"), grafik selisih saja (kehilangan konteks magnitudo).
- Ingat: grafik selalu terasa intuitif bagi pembuatnya — belum tentu bagi audiens → minta feedback.

### Ex 2.5 — Attrition rate program 1 tahun (2010–2019, rata-rata 7,5%)
- **Simple text dulu:** "Attrition rata-rata 7,5% selama 10 tahun"; atau "bervariasi 1–15%, 9,1% di 2019"; atau "naik dari 4,5% (2017) ke 9,1% (2019)". **Setiap membuat visual, tulis kalimat yang menjawab "So what?" — kadang kalimat itu cukup tanpa grafik.**
- Dot plot + garis rata-rata; **line graph + garis rata-rata putus-putus tipis + marker & label titik terakhir (9,1%) → pilihan Cole** (tren jelas, mudah dibanding rata-rata, sedikit tinta, ruang untuk komentar); line + area teduh untuk rata-rata; area graph (banyak tinta, memberi kesan area penting — jarang dipakai); bar + garis rata-rata. Label rata-rata disesuaikan ruang.

### Ex 2.6 — Cuaca: zero baseline
- Grafik bar suhu dengan sumbu mulai 50°F membuat Minggu tampak 90-an & Rabu 40-an padahal 74 & 58 → **bar wajib zero baseline, tanpa pengecualian** (mata membandingkan ujung bar dengan baseline).
- **Tidak berlaku untuk titik & garis** (scatter, dot plot, line, slopegraph) — fokus pada posisi relatif & kemiringan, yang tetap saat di-zoom; tetapi jangan over-zoom membuat perubahan kecil tampak besar. Bila perubahan kecil memang penting (mis. +2°C iklim global), **jangan potong sumbu bar — ganti ke garis atau grafikkan perubahannya**.

### Ex 2.7 — Kritik dot plot "Bank Index" (Financial Savings vs bank lain)
- Pertanyaan: metrik apa (kepuasan? error teller)? Lebih tinggi lebih baik? Perlu semua titik bank? Rata-rata industri terdiri dari mereka? Apa arti lingkaran merah 2019 (bersaing dengan terlalu banyak warna)? **So what?**
- Makeover: metrik = kepuasan cabang; fokus **Financial Savings vs Industry Average** saja (pertimbangkan konteks yang hilang: sebaran pesaing) → **line graph** (garis memperlihatkan gap & persilangan), label langsung, **judul menjawab "So what?"**. Live: bangun garis demi garis/titik demi titik; dibaca sendiri: anotasi teks penyebab naik-turun.

### Ex 2.8 — NPL vs Loan Loss Reserves (credit risk)
- Masalah: bolak-balik bar–garis–legenda; **dual y-axis** (hindari secara umum); rate tanpa denominator jelas & tak menambah info → buang; **interval waktu tak konsisten** (tahun → kuartal → Desember) — masalah terbesar: satu bar tak boleh mewakili tahun & kuartal.
- Solusi: plot semua kuartal (pakai garis), atau beri lebar sumbu x setara, atau **dua grafik**: tahunan 2014–2019 & kuartalan 2019 (lebih rapat), shading menghubungkan 2019 ke breakout kuartal, **min-max y-axis sama**, label langsung 2 desimal (agar titik beda tinggi tak berlabel sama). Insight: gap NPL vs reserves menyempit; 2019 pertama kali NPL > reserves (Q3 & Q4) → perlu aksi.

### Practice on your own (Bab 2) — soal
- 2.9–2.10: sketsa waktu rata-rata closing deal (direct vs indirect × 4 produk), lalu buat di tool & refleksi manfaat/frustrasi menggambar.
- 2.11: visual dashboard "Successful Opportunities by Center (FLU)" (bar ungu per pusat + garis rata-rata 12,1% + tabel data) — bagaimana diurutkan (alfabet kode pusat) & alternatif (urut nilai), cara menampilkan rata-rata, menambahkan **target** (10% vs 25% mengubah cerita), pro-kontra **tabel data tertanam**, fokus pada peluang (yang belum divaksin).
- 2.12: pilih grafik survei retensi "Saya berencana bekerja di sini 1 tahun lagi" tahun lalu vs ini (pie, bar berkelompok, **divergent stacked bars** [disagree di kiri, agree di kanan dari titik tengah], **slopegraph**) — diskusikan apa mudah/sulit dibandingkan.
- 2.13: grafik response & completion rate kampanye email (bar + garis dengan dua sumbu, kuartal) — daftar 3 masalah & solusinya.
- 2.14: nyeri pasien device ON vs OFF (improved 58/36, unchanged 32/45, worsened 10/19) — daftar & buat ≥4 view.
- 2.15: belajar dari contoh media (baik & buruk) → generalisasi pelajaran. 2.16: ikut **#SWDchallenge** bulanan (participate, emulate, critique, run your own).

### Practice at work (Bab 2)
- **2.17 Draw it!** 10 menit sketsa; tunjukkan ke orang lain; whiteboard dengan kolega kreatif bila buntu.
- **2.18 Iterate in your tool** 30 menit, nilai pro-kontra tiap iterasi.
- **2.19 Pertanyaan setelah membuat grafik:** Apa yang ingin ditunjukkan & perbandingan apa yang termudah/tersulit? Seberapa penting (stakes, tingkat kesempurnaan & akurasi)? Siapa audiens (familiar? menantang keyakinan? ekspektasi format)? Familiar dengan tipe grafik (grafik baru = hambatan; harus ada alasan kuat — insight yang tak mungkin dengan grafik familiar)? Bagaimana disajikan (live vs dibaca sendiri — bila tidak hadir, buat jelas cara membaca & apa yang harus diproses)?
- **2.20 Say it out loud:** jelaskan cara membaca grafik, apa yang ditunjukkan, sumbu, lalu observasi. Bila Anda berkata "ini tak penting/abaikan itu" → dorong ke latar atau hapus; cara Anda mengarahkan perhatian saat bicara → wujudkan secara visual. (Podcast SWD episode 6.)
- **2.21 Solicit feedback:** minta orang (bahkan tanpa konteks) menceritakan proses berpikirnya: apa yang diperhatikan, pertanyaan, observasi; perhatikan **ekspresi wajah mikro** (dahi berkerut, bibir mengerucut). Bila orang kesulitan, jangan salahkan mereka — perjelas judul/label, warna hemat, atau ganti tipe grafik.
- **2.22 Build a data viz library** (per tipe grafik, topik, tool; file bisa diunduh; kompetisi bulanan/kuartalan; sumber inspirasi & standar untuk karyawan baru).
- **2.23 Sumber:** chart chooser — Juice Analytics Chart Chooser, The Chartmaker Directory (Visualising Data), Graphic Continuum (PolicyViz, >90 tipe), Interactive Chart Chooser (Depict Data Studio); inspirasi — Information Is Beautiful Awards, Reddit r/dataisbeautiful, Tableau Public Gallery, R Graph Gallery, Xenographics.
- **2.24 Diskusi:** tabel vs grafik; y-axis berlabel vs label langsung; kapan non-zero baseline boleh (titik/garis); manfaat kertas; kapan iterasi; kapan grafik baru/tak familiar layak.

---

## BAB 3 — Identify & Eliminate Clutter
- Setiap elemen di grafik/slide menambah **beban kognitif**. Buang yang tak menambah nilai informatif cukup untuk "membayar" kehadirannya.

### Recap SWD Bab 3 — "Clutter is your enemy"
- **Clutter** = elemen visual yang memakan ruang tapi tak membantu pemahaman.
- **Cognitive load** = usaha mental untuk mempelajari informasi baru; tiap elemen = beban → jangan masukkan yang tak menambah informasi.
- **Lack of visual order** (clutter jenis lain) → manfaatkan white space & sejajarkan elemen; usahakan elemen horizontal & vertikal bersih, **hindari diagonal** (mis. label kategori miring → ubah jadi bar horizontal).
- **Non-strategic use of contrast** → kontras jelas adalah sinyal ke mana melihat; jangan membuat terlalu banyak hal berbeda, atau poin kunci hilang.
- **Gestalt principles** — cara kita secara bawah sadar menata yang kita lihat:
  - **Proximity** — benda yang berdekatan dianggap satu kelompok.
  - **Similarity** — warna/bentuk/ukuran sama dianggap terkait.
  - **Enclosure** — benda yang terlingkup (mis. shading) dianggap satu kelompok (mis. membedakan actual vs forecast).
  - **Closure** — kita melihat satu kesatuan meski bagian tak lengkap → tak perlu border grafik.
  - **Continuity** — mata mencari jalur paling mulus → bar tanpa garis sumbu tetap terlihat sejajar.
  - **Connection** — benda yang terhubung secara fisik dianggap kelompok (garis menghubungkan titik).

### Ex 3.1 — Gestalt pada grafik market size (aktual & forecast)
- Proximity: judul & label sumbu y; label data dekat marker. Similarity: warna oranye & biru di teks atas mengikat ke titik data. Enclosure: shading abu muda membedakan forecast & menghubungkan ke teks bawah. Closure: tanpa border, grafik tetap terlihat satu kesatuan. Continuity: **garis putus-putus untuk forecast** — tetap terbaca sebagai satu garis (gunakan putus-putus **hanya untuk ketidakpastian**, karena dash menambah clutter). Connection: garis menghubungkan titik bulanan; sumbu menghubungkan nilai.

### Ex 3.2 — Mengikat kata dengan grafik (attrition sukarela bulanan 2019; catatan April reorganisasi, musim panas tinggi karena kembali sekolah, Nov-Des rendah karena liburan)
- Masalah umum slide: grafik di satu sisi, teks di sisi lain → audiens harus mencari sendiri bukti di grafik. **"Jangan buat audiens bekerja — kerjakan untuk mereka!"**
- **Proximity:** teks langsung di samping data (asal tak menghalangi data) + **penekanan** (bar terkait abu tua + teks bold hemat).
- **Similarity (favorit Cole):** teks tetap di kanan, kata kunci & bar diwarnai sama (April merah, Summer oranye, Nov-Dec biru) → mata bolak-balik secara alami; memudahkan presenter ("lihat bar merah...").
- **Enclosure:** shading menghubungkan bar & teks (hati-hati jika data menembus area lain); bisa ditambah warna di area.
- **Connection:** garis tipis & terang dari teks ke bar (hanya bila sedikit & bisa horizontal; garis diagonal berantakan → pakai similarity); tambah similarity untuk kejelasan (favorit kedua).
- Intinya: saat membaca teks, audiens tahu di mana melihat bukti di data, dan sebaliknya.

### Ex 3.3 — Alignment & white space (slopegraph writers Product X per promo, repeat vs new)
- Slide asli terasa "dilempar begitu saja". **Hindari center alignment** (menggantung di ruang, tepi bergerigi bila multi-baris) → **rata kiri/kanan** untuk membuat garis vertikal & horizontal bersih (closure).
- Perbaikan: rata kiri takeaway atas, judul grafik, label sumbu kiri; label data kiri untuk repeat & kanan untuk new; nama Promo A/B/C dipindah ke kanan sejajar label data; teks kanan rata kiri dengan **line break** agar mudah dipindai; beri jarak judul–grafik; sempitkan grafik. Pilihan rata kiri vs kanan tergantung tata letak — hindari "trapped white space" bergerigi.
- "Hal kecil berdampak besar" — rasa terstruktur & perhatian pada detail.

### Ex 3.4 — Declutter (Time to Close Deal, direct vs indirect, 15 langkah)
1. **Hapus garis tebal** (pembatas judul & border bawah) — closure sudah cukup; gunakan white space.
2. **Hapus gridlines** ("gridlines are gratuitous!") & border.
3. **Buang trailing zeros** pada label sumbu y (120.0 → 120); ubah interval sesuai makna (hari → tiap 15); **tambahkan judul sumbu y** ("DAYS TO CLOSE").
4. **Hilangkan teks diagonal** di sumbu x (lebih lambat dibaca; vertikal lebih lambat lagi) → singkatan bulan + tahun sebagai judul/super-kategori.
5. **Tebalkan bar** (gap antar bar tak boleh lebih lebar dari bar).
6. **Tarik label data ke ujung bar** (dua elemen jadi satu → beban kognitif turun), kurangi presisi (bulat), label putih di atas warna.
7. **Hapus label data** — jangan tampilkan sumbu & label sekaligus (redundan). Pilih: **nilai spesifik penting → label langsung & hapus sumbu; bentuk/tren penting → pertahankan sumbu tanpa label.**
8. **Jadikan line graph** (data waktu; 24 bar → 2 garis).
9. **Label data langsung** di ujung garis (proximity) → buang legenda (legenda = kerja mencari).
10. **Warnai label sama dengan datanya** (similarity).
11. **Judul di kiri atas** (zigzag "z": audiens tahu cara membaca sebelum melihat data); hapus italic.
12. **Hapus warna judul** (judul biru menciptakan asosiasi palsu dengan seri biru).
13. **Masukkan goal ke grafik** (garis 90 hari, bukan hanya di subtitle) → bandingkan langsung.
14. **Iterasi format goal**: tipis + putus-putus + huruf kapital "GOAL" (all caps untuk frasa pendek mudah dipindai, bentuk persegi rapi).
15. **Hapus warna** — semua abu (spasi antar garis sudah cukup membedakan) → kembalikan warna hanya untuk memfokuskan perhatian.
- Lalu **focus attention**: judul "Time to close deal: **indirect varies over time**" dengan kata berwarna sama dengan garis Indirect; alternatif "indirect sales **missed goal 3 times**" + marker & label pada 3 titik di atas goal (120, 98, 94) — bisa ditambah **oranye** (Cole menghindari hijau=baik/merah=buruk karena buta warna; oranye punya konotasi negatif mirip merah); atau meta-takeaway "Time to fill: **beating goal the majority of time**" + label akhir (65 Indirect, 46 Direct).

### Practice on your own & at work (Bab 3)
- 3.5: Gestalt pada tabel "Wallet share by growth type" (baris Stable & Dropping disorot + angka besar 69% akun, 81% gain-share opportunity, 74% keep-share opportunity dengan warna & garis penghubung).
- 3.6 temukan visual efektif & identifikasi Gestalt; 3.7 alignment & white space (sentimen konsumen ekstensi lini minuman); 3.8–3.10 declutter (kepuasan pelanggan dari waktu ke waktu; mobil terjual per bulan; % nasabah dengan pembayaran otomatis per produk).
- **3.11 Mulai dengan kertas kosong** — tool adalah biang clutter; saat menggambar, tiap goresan butuh usaha sehingga elemen tak informatif jarang masuk.
- **3.12 "Do you need that?"** — clutter apa yang bisa dihapus (border, gridline, yang terasa seperti kerja)? Informasi redundan (sumbu vs label data; satuan tak perlu di tiap titik; judul efektif)? Semua data perlu (konteks apa yang hilang; time frame tepat; titik pembanding; **agregasi**: harian → mingguan, bulanan → kuartalan untuk tren)? Apa yang bisa didorong ke latar (abu-abu) & kontras strategis? Minta feedback (bila Anda berkata "abaikan ini" → hapus/latar).
- Diskusi: kapan tak perlu declutter; clutter bawaan tool & cara efisien menghapusnya (template); bar vs line untuk data waktu; apakah alignment & white space hanya soal cantik (tidak — soal kredibilitas & kemudahan); kapan clutter diinginkan.

---

## BAB 4 — Focus Attention
- "Ke mana Anda ingin audiens melihat?" — gunakan **preattentive attributes** (warna, ukuran, posisi) secara strategis & hemat agar jelas ke mana melihat & dalam urutan apa.

### Recap SWD Bab 4
- **You see with your brain:** cahaya → mata → otak.
- **3 jenis memori:** **Iconic** (super singkat, sepersekian detik sebelum diteruskan; menangkap preattentive attributes) → **Short-term** (hanya ~**4 potong informasi** sekaligus; hilang atau diteruskan) → **Long-term** (tujuan kita mencapai memori jangka panjang audiens — **story** membantu, Bab 6).
- **Preattentive attributes** (sinyal ke mana melihat & menciptakan visual hierarchy): orientation, shape, line length, line width, size, curvature, added marks, enclosure, hue, intensity, spatial position, motion.
- Atribut kunci: **Size** (ukuran relatif = kepentingan relatif), **Hue/color** (dipakai hemat = alat paling strategis untuk mengarahkan perhatian), **Spatial position** (tanpa isyarat lain, orang mulai dari **kiri atas** & zigzag "z" — letakkan info penting di kiri atas, atau jelaskan urutan secara eksplisit).
- **"Where are your eyes drawn?" test:** tutup mata/berpaling → lihat kembali → catat di mana mata mendarat pertama → evaluasi & ubah bila perlu.

### Ex 4.1 — Foto: ke mana mata tertarik?
- Rambu batas kecepatan: besar, angka hitam tebal di putih, **merah** (dikondisikan sebagai peringatan — tapi buta warna merah-hijau tak menangkapnya → **beri redundansi sinyal**), outline putih memisahkan dari latar → pelajaran: ukuran, tipografi, warna, enclosure — dipakai hemat.
- Matahari & mobil: ketegangan bila **menekankan beberapa hal sekaligus**.
- Rambu jalan "Queens Bronx": tajam vs blur, disinari, lebih besar, lebih sedikit kata (ruang kosong), urutan pertama → jaga elemen kunci tajam & terbaca; sorot satu dari deretan hal serupa; hal penting lebih besar (& hal setara ukurannya konsisten); tata letak menuntun gerak mata.
- Mobil kuning di jalan berliku: mata mengikuti jalan → waspadai mengarahkan perhatian **tanpa sengaja** menjauh dari yang penting.
- Deretan mobil warna-warni: mata tak bisa mendarat → terlalu banyak warna menghilangkan nilai preattentive warna; **warna hemat** = salah satu cara paling efektif (satu mobil merah di antara abu-abu langsung terlihat).

### Ex 4.2 — Fokus bertahap (YoY % perubahan penjualan merek makanan kucing; bar horizontal diurutkan dari turun terbesar ke naik terbesar, nama merek di sisi bar)
- Alat: warna & bold pada data & label, dan **judul berisi takeaway** (detail pindah ke subtitle).
- Lifestyle line → hitam + bold, sisanya abu lebih muda; Feline line → **ungu (warna brand)** + similarity menghubungkan elemen terpisah (tak dipindah posisinya agar urutan tetap bermakna); merek turun → **oranye** (Cole: hindari merah/hijau — buta warna merah-hijau ~**10%** populasi; oranye = negatif, **biru = positif**); dua merek turun terbesar → variasi **intensitas** oranye; merek naik → biru.
- Untuk dokumen yang dibaca sendiri: **2 slide komprehensif** (Lifestyle & Feline; turun & naik) dengan teks penjelas berwarna sama dengan datanya → meniru progresi presentasi live. Judul "Cat food brands: **mixed results in sales year-over-year**".

### Ex 4.3 — 15 cara mengarahkan perhatian ke satu garis (conversion rate per channel; fokus Referral)
1. **Panah** & 2. **Lingkaran** — alat tumpul; tak membawa informasi (clutter), tapi lebih baik daripada tidak sama sekali; lebih baik mengubah aspek data itu sendiri.
3. **Kotak putih transparan** menutupi yang ingin dilatarbelakangkan (berguna untuk screenshot dari tool yang tak bisa diubah desainnya).
4. **Tebalkan garis** (& bold label). 5. **Ubah gaya garis** (putus-putus sangat menarik perhatian tapi memecah elemen → simpan untuk ketidakpastian: forecast, prediksi, target). 6. **Intensitas** (lebih gelap). 7. **Posisi di depan** data lain (urutan seri). 8. **Ubah hue** (satu berwarna, sisanya abu). 9. **Kata di judul** untuk "priming" audiens. 10. **Hapus data lain** (pertimbangkan konteks yang hilang). 11. **Animasi muncul** (motion = atribut paling menarik perhatian; hanya pakai appear/disappear/transparency — tanpa terbang, memantul, fade). 12. **Data markers**. 13. **Data labels** / anotasi teks. 14. **End markers & labels** di tiap garis (memudahkan membandingkan titik terbaru). 15. **Kombinasikan beberapa atribut** — judul "Conversion rate over time: **referral decreasing markedly since 2010**" (merah, sama dengan garis), garis Referral tebal & merah, marker & label (6,3% Total, 3,6% Organic, 2,5% Referral), anotasi penyebab (2010 puncak 5,5% karena kemitraan; masuknya kompetitor ABC; 2016 kampanye baru) → mata: judul → garis → titik akhir → anotasi = **visual hierarchy**.

### Ex 4.4 — Menampilkan SEMUA data tanpa membingungkan (Bank index semua bank)
- **"Kekuatan abu-abu"**: dorong sebagian besar data ke latar — garis bank pesaing abu tipis; Industry avg (hitam) & Financial Savings (biru) tebal. Jika perbandingan dengan pesaing spesifik penting → ganti ke bar horizontal titik terbaru.
- Tambah warna kedua untuk menyorot periode terakhir (segmen 2018–2019 hijau) + judul "**Financial Savings below industry for first time in 5 years**" + teks "FS naik 1% dalam setahun, industri naik rata-rata 3% (1–5% tiap bank)".

### Practice on your own/at work (Bab 4)
- 4.5 where are your eyes drawn (gambar). **4.6 Fokus dalam tabel** (penjualan 4 minggu top 10 akun kopi): sales volume kolom pertama — apa lagi? sorot Account D (volume jauh lebih besar) dengan 3 cara (warna baris, bold, border/enclosure, ukuran); sorot price per pound rendah dalam baris D; fokus pada price per pound (posisi kolom, urutan baris, heatmap). 4.7 market share produk kita (berbagai cara). 4.8 fokus pada pusat medis di atas rata-rata (bar).
- **4.9** uji mata sendiri lalu minta orang lain (Anda bias karena sudah tahu data); minta mereka menceritakan urutan pemrosesan, pertanyaan, observasi.
- **4.10 Kuasai tool:** bold/tebal; semua abu lalu satu seri biru & warna brand; ubah warna satu titik/bar; urutkan bar naik/turun; pindahkan garis ke depan/belakang; garis putus-putus (atau outline bar); intensitas (transparansi/pola/warna kurang intens/kotak transparan); label satu seri, pindahkan posisi, label hanya satu-dua titik (trik seri tak terlihat untuk posisi label).
- **4.11 Menentukan di mana fokus (eksploratif → eksplanatif):** kapan agregasi/disagregasi? time frame yang tepat? breakdown per lini bisnis, region, produk, tenure — di mana mirip/beda & kenapa? sesuai ekspektasi? hubungan antar variabel & apa yang mendorong apa? perbandingan bermakna? konteks yang belum dimiliki & siapa ditanya? pertanyaan orang lain? asumsi & dampaknya bila salah? apa yang hilang (data jarang menceritakan semuanya)? apakah masa lalu sama dengan masa depan?
- Diskusi: penekanan hemat di komunikasi eksplanatif vs **dashboard** (eksploratif — warna dipakai berbeda); visual hierarchy; kenapa penekanan harus hemat ("jika semuanya ditekankan, tak ada yang menonjol").

---

## BAB 5 — Think Like a Designer

### Recap SWD Bab 5
- **Form follows function:** (1) **Function** — apa yang ingin Anda mampukan audiens *lakukan* dengan data? (2) **Form** — bagaimana memvisualisasikannya agar mudah?
- **Affordances** — aspek desain yang membuat jelas cara menggunakannya (pegangan "hold here", parutan "grate here", bar disorot "focus here"). **Sorot hal penting & hapus distraksi** — sorotan maksimal ~**10%** dari keseluruhan desain. Afordansi desain grafis: **bold**, *italics*, underlining, CASE, typeface, size, color, inversing. Antoine de Saint-Exupéry: "Kesempurnaan tercapai bukan ketika tak ada lagi yang bisa ditambahkan, tetapi ketika tak ada lagi yang bisa dibuang."
- **Accessibility** — desain yang bisa dipakai orang dengan kemampuan teknis sangat beragam: (1) legible, (2) clean, (3) bahasa sederhana, (4) hapus kompleksitas tak perlu — "tidak terlalu sederhana, tidak terlalu rumit".
- **Aesthetics** — desain yang lebih menarik dipersepsikan lebih mudah dipakai & lebih diterima. "Perlukah dibuat cantik?" → **YA**: cerdas dengan warna, perhatikan alignment, manfaatkan white space.
- **Acceptance** — agar efektif, desain harus diterima audiens: (1) jelaskan manfaat, (2) tunjukkan side-by-side, (3) beri beberapa opsi & minta masukan, (4) libatkan anggota audiens yang vokal.

### Ex 5.1 — Use words wisely (penjualan 4 merek deterjen)
- Pertanyaan yang muncul tanpa kata: apa sumbu y (unit? ratusan? $ ribuan? £ jutaan)? sumbu x (periode historis/proyeksi)? konteks 4 merek (semua di satu toko/website? merek utama satu produsen? top/bottom 4)? cakupan (global/AS/kota/lini produk/rantai toko)? → asumsi bisa salah.
- Tambahkan judul deskriptif + judul sumbu (y di atas, x di kiri; **sumbu y rata atas dengan label tertinggi, sumbu x rata kiri dengan label paling kiri; all caps; abu**). Kata berbeda → interpretasi berbeda total.
- **Aturan: setiap grafik punya judul; setiap sumbu punya judul** (pengecualian jarang). Cole: judul grafik deskriptif + **judul slide = takeaway**; konsisten dalam satu laporan.

### Ex 5.2 — Do it better (output default tool: penjualan mobil per dealer per kuartal)
- Reaksi terhadap default: membingungkan, kacau, berlebihan, rumit.
- Perbaikan: judul & judul sumbu di kiri atas (y all caps), buang judul sumbu x "Quarter" (jelas), tahun sebagai super-kategori; **visual hierarchy** — Regional Avg hitam tebal, dealer lain abu; buang latar abu, border, gridlines; ganti legenda alfabetis dengan **label langsung berkelompok** di kanan (tertinggi, tengah, terendah).
- **Satu slide untuk manajemen:** judul "Regional car sales: **mixed results**"; kiri: "OVERALL DECLINE IN REGIONAL AVERAGE" (dari >1.000 unit Q1 2017 ke 857 Q3 2019, −17%) + garis; kanan: "MARKED VARIANCE BY DEALERSHIP" (Lakeside, Draper, Filmore terbanyak — biru; Oakley, Pierce, Mare Valley paling sedikit — oranye) + **bar horizontal kuartal terbaru** dengan rata-rata hitam; catatan sumber di bawah. Layout dua sisi dengan white space & alignment. Warna biru/oranye hanya di grafik kanan (di kiri bersaing dengan rata-rata). **Jangan andalkan default tool.**

### Ex 5.3 — Attention to detail & desain intuitif (touchpoints per pelanggan: phone, chat, email)
- Grafik/slide adalah satu-satunya bagian analisis yang dilihat audiens → mereka menilai ketelitian keseluruhan dari situ.
- Feedback detail: **konsistensi** (desimal label sumbu & sel tabel; format tanggal berbeda antara grafik & tabel & di dalam tabel), **alignment** (teks tengah bergerigi; vertikal tabel tak konsisten; elemen tak sejajar; kotak sorotan tak pas), **label sumbu intuitif** (label tiap bulan ke-5 tidak intuitif → harian tiap 7, bulanan tiap 3 atau 6, atau kuartal/tahun; huruf awal bulan + tahun sebagai super-kategori); buang kata redundan "Touchpoints"; label langsung.
- Desain ulang data: terlalu banyak angka (judul, grafik, tabel yang hanya mengulang titik Januari) → total touchpoint cukup sebagai kalimat; **stacked bar hanya mudah membandingkan seri dasar & total** → ubah ke garis per kategori + total → terlihat **musiman** → sumbu x Jan–Des dengan garis per tahun → karena data terakhir Jan 2020, ubah sumbu ke **Jul–Jun** dengan "This year" vs "Last year" → insight: total mengikuti tahun lalu tapi Januari lebih rendah; email & phone turun; **chat konsisten lebih tinggi & meningkat**. Desimal: 1 untuk total & email, 2 untuk phone & chat (agar perbedaan kecil terlihat & tak ada dua titik beda tinggi berlabel sama).
- Slide final: "Total touchpoints flat, **shift toward chat**" + kalimat ringkas (musiman, puncak Januari; email & phone turun YoY, chat naik) + "LET'S DISCUSS: Bagaimana ini memengaruhi strategi & target ke depan?" + anotasi per seri berwarna sama. Live: bangun grafik bertahap.

### Ex 5.4 — Design in style (branding)
- Gaya SWD: Arial, judul kiri atas, judul sumbu all caps, abu + warna hemat (oranye negatif, biru brand positif).
- **United Airlines-inspired:** kata sifat — clean, classic, bold, blue, navigable, open, minimal, simple, serious, structured → biru tua & muda, font Gill Sans (lebih lebar → kotak teks dipindah ke bawah garis, maksimum sumbu y diturunkan), teks center, persegi biru di belakang judul & footnote, border biru, garis data lebih tebal.
- **Coca-Cola-inspired:** red, silver, round, classic, bold, sweet, playful, international, diverse, wet → latar merah, teks putih, hitam hemat, center, bold all caps; **tidak memakai font kursif logo — legibilitas utama** (Montserrat); latar bentuk bulat; versi "Diet Coke" latar abu muda (lebih hemat tinta, cocok dicetak/banyak grafik). **Jika warna brand merah, jangan pakai merah untuk hal negatif** (alternatif: merah = baik/umum, hitam = callout).
- Style guide perusahaan = "lodestar" yang menginspirasi kreativitas & kohesi; untuk klien, riset brand mereka.

### Practice on your own (Bab 5)
- 5.5 examine & emulate visual efektif (nilai affordances, aesthetics, accessibility, acceptance; tiru persis lalu versi perbaikan). 5.6 perubahan kecil berdampak besar (incremental reach per 1.000 impressions kampanye iklan 6 minggu). 5.7 kritik slide market share pesaing (5 perbaikan + beda live vs dokumen). 5.8 brand this! (dua brand kontras, lalu brand perusahaan/sekolah sendiri).

### Practice at work (Bab 5)
- **5.9 Words make data accessible:** wajib judul grafik & judul sumbu; **nyatakan kesimpulan dalam kata** (jangan berasumsi orang akan menarik kesimpulan sama) — besar, bold, di tempat prioritas (atas). **Bagian atas halaman = real estate berharga → gunakan untuk judul aktif/takeaway, bukan deskriptif.** **Footnote** (sumber data, periode/waktu ekstraksi, asumsi, metodologi) — kecil, abu, di bawah — membangun kredibilitas & memudahkan replikasi. Checklist: takeaway dinyatakan menonjol? grafik berjudul cukup deskriptif? semua sumbu berlabel & berjudul? footnote perlu? jumlah kata sesuai mode (live = sedikit; dikirim = lebih banyak).
- **5.10 Visual hierarchy:** **squint test** (picingkan mata — elemen terpenting harus terlihat pertama). Highlight: **bold** (lebih disukai — sedikit noise), italics (kurang menonjol & kurang terbaca), underline (noise — hindari), UPPERCASE untuk urutan kata pendek, jangan pakai font berbeda untuk highlight, warna hemat (dengan bold), **inversing** (menarik perhatian tapi noise), size. Eliminate distractions: tak semua data sama penting; ringkas bila detail tak dibutuhkan; "apakah menghapus ini mengubah sesuatu? Tidak? Hapus!" (jangan simpan karena sudah susah payah membuatnya); dorong yang perlu tapi tak berdampak ke latar (abu).
- **5.11 Attention to detail:** ejaan, tata bahasa, tanda baca, **matematika benar** ("tak ada pembunuh kredibilitas lebih besar dari angka yang tak menjumlah"; trik: baca mundur atau ganti font jelek; minta orang lain memeriksa); align presisi (tabel/gridline/ruler di tool; hindari diagonal); white space strategis (jangan takut/diisi); ikat hal terkait secara visual; konsistensi bila masuk akal (warna sama untuk makna sama); amati "feel" keseluruhan (minta kata sifat dari orang lain).
- **5.12 Design more accessibly (Amy Cesal):** (1) **alt text** bermakna (satu kalimat apa grafiknya termasuk tipe + link CSV data), (2) **takeaway title** (orang membaca judul dulu & cenderung mengulang judul saat ditanya maknanya), (3) **label data langsung** (bukan legenda — sulit bagi buta warna), (4) **cek kontras teks & warna** (buta warna 8% pria & 0,5% wanita keturunan Eropa Utara; WCAG; Color Palette Accessibility Evaluator), (5) **white space** (mis. outline putih antar segmen stacked bar agar tak hanya bergantung warna). Desain aksesibel = lebih baik untuk semua.
- **5.13 Garner acceptance (manajemen perubahan):** jangan bilang "saya baru baca buku, kita selama ini salah". Strategi: jelaskan manfaat desain baru; tunjukkan before-after side-by-side; beri beberapa opsi & minta input (libatkan stakeholder → buy-in); dapatkan anggota audiens vokal/champion (one-on-one); **mulai dari yang familiar lalu transisi** (live); **jangan ganti — augment** (laporan rutin tetap, tambahkan beberapa slide di depan/di email dengan best practice; perlahan kurangi ketergantungan pada semua data). Pikirkan kenapa *mereka* ingin berubah; pilih pertempuran — mulai dari low-hanging fruit, kumpulkan kemenangan kecil & kredibilitas.

---

## BAB 6 — Tell a Story
- Data di spreadsheet & fakta di slide mudah dilupakan; **cerita mudah diingat** — dan bisa diceritakan ulang (audiens ikut menyebarkan pesan). Urutan pelajaran: konteks/audiens/pesan di depan (efisiensi), lalu setelah mengenal data, kembali ke gambaran besar → story.

### Recap SWD Bab 6 — Lessons in storytelling
- **Red Riding Hood** sebagai bukti elemen kunci cerita: **konflik & tensi adalah bagian integral**.
- **Narrative arc** (sumbu tensi): Beginning — **plot** (perkenalkan alur; bangun konteks; jawab "kenapa saya harus memperhatikan?") → **inciting incident** → **rising action** → **climax** (puncak tensi) → **falling action** → **resolution** (End: call to action; jelaskan apa yang audiens harus lakukan dengan pemahaman baru). Middle: kembangkan "what could be" — ilustrasi contoh, data yang menunjukkan masalah, artikulasikan apa yang terjadi bila tak ada aksi.
- **Narrative structure:** kata lisan/tulisan (atau keduanya) yang menceritakan dalam urutan masuk akal & membuat orang memperhatikan.
- **Narrative flow** (urutan = jalur yang Anda tempuh bersama audiens): **Chronological** (masalah → kumpul data → analisis → temuan → rekomendasi) vs **Lead with the ending** (call to action → poin pendukung #1 → #2 ...).
- **Spoken vs written narrative:** **laporan tertulis** — audiens sendiri yang membuat konten relevan → narasi tertulis harus membuat "So what?" jelas; **presentasi live** — "So what?" jelas lewat kata yang Anda ucapkan, visual memperkuat. Artikulasikan peran yang Anda ingin audiens mainkan.
- **Repetition** memindahkan dari short-term ke long-term memory: **Bing (apa yang akan dibahas) → Bang (detail & konten utama) → Bongo (ringkasan & review)** — intro, isi, kesimpulan.

### Ex 6.1 — Takeaway titles (NPS kita vs pesaing teratas)
- **Ruang judul = real estate berharga** — biasanya disia-siakan untuk judul deskriptif. Gunakan **action/takeaway title**; studi menunjukkan judul efektif meningkatkan memorabilitas & recall, dan menyetel ekspektasi untuk sisa halaman.
- Contoh: "NPS is increasing over time" (audiens mencari garis naik) vs "NPS: we rank 4th among competitors" (audiens menghitung urutan). Judul bisa memberi **sentimen**: "Great work! NPS is increasing over time" vs "More work ahead: we still haven't hit top 3". **Gunakan kekuatan kata dengan hati-hati.**
- "What's the story?" biasanya berarti "apa poinnya/So what?" — **tingkat minimum "story"** untuk setiap data eksplanatif.
- Cole memakai **sentence case** untuk judul slide (lebih mudah jadi takeaway; title case cenderung deskriptif "NPS Over Time"); konsisten.

### Ex 6.2 — Put it into words (collections: accounts worked, dials made, penetration rate)
- Menulis kalimat memaksa melihat data & bisa memunculkan cara tampil lain. Tulis beberapa observasi berbeda (1 per seri): accounts worked bervariasi & turun; **dials turun 47% Jan–Des (~250.000 di Desember)**; **penetration rate turun tajam** → fokus ke penetration rate (mencakup dua seri lain); menariknya rate turun meski dials turun (akun "mudah" sudah dikerjakan? — butuh konteks).
- Konteks dials dinyatakan **dengan kata**, sehingga grafik bisa fokus: ubah data menjadi Worked + Not Reached (stack) → **100% stacked bar** → **100% stacked area** (garis pemisah = penetration rate), legenda di kiri atas di bawah judul, label langsung "PENETRATION RATE 27%". Teks di atas: "Total accounts dialed decreased 47% from January to December to 250K. During the same time period, **penetration rate has declined markedly**." Cole mengakui solusi ini mendapat respons campuran (100% membingungkan sebagian) → di dunia nyata minta feedback lebih lanjut; tak apa mencoba di luar norma.

### Ex 6.3 — Identify the tension
- Tensi bukan dibuat-buat; **jika tak ada tensi, tak ada yang perlu dikomunikasikan**. Temukan tensi **bagi audiens** (bukan bagi Anda) — terkait "what's at stake". **Aksi yang diminta = cara audiens menyelesaikan tensi.**
- (1) Back-to-school: tensi = layanan tak konsisten antar toko → resolusi = alokasikan sumber daya untuk pelatihan sales associate. (2) HR: tensi = diproyeksikan kekurangan direktur (attrition naik, promosi internal) → resolusi = diskusikan & putuskan perubahan strategi (kurangi attrition, percepat pengembangan manajer, akuisisi strategis, rekrut eksternal). (3) Kesehatan virtual: tensi = **efisiensi vs kualitas perawatan** (pergeseran ke virtual terjadi, seberapa jauh didorong?) → resolusi = gunakan data + masukan dokter untuk menetapkan target wajar.

### Ex 6.4–6.5 — Komponen story & narrative arc
- Presentasi bisnis tipikal **linear** (pertanyaan → data → analisis → temuan/rekomendasi) — seperti storyboard Bab 1. Keunggulan besar didapat dengan **menata ulang komponen sepanjang narrative arc**.
- **Back-to-school arc:** PLOT — back-to-school ~30% revenue tahunan, historis tak data-driven → RISING ACTION — kami melakukan survei & kini punya data; kami bagus di beberapa area, tapi... → CLIMAX — **kami underperform di area kunci!** (apa yang dipertaruhkan: kalah dari pesaing & akan terus kalah tanpa perubahan) → FALLING ACTION — tak semua area sama penting; kami punya ide solusi & sudah mempersempit ke satu yang berdampak besar → ENDING — investasi pelatihan karyawan untuk memperbaiki pengalaman pelanggan di toko.
- **Pet adoption arc:** PLOT — bayangkan hari indah di taman, acara adopsi biasa → RISING ACTION — hanya sedikit hewan diadopsi; banyak kembali ke shelter; ruang terbatas — hewan baru datang, yang lain harus pergi → CLIMAX — **terlalu banyak hewan di-eutanasia!** → FALLING ACTION — namun saat hujan badai, acara pindah ke toko pet → lebih banyak adopsi, sedikit dikembalikan; perubahan kecil, dampak besar → ENDING — setujui sumber daya untuk pilot di toko pet lokal. Alternatif: **lead with the ending** ("Saya butuh $500 & 3 jam relawan untuk pilot yang saya yakini menaikkan adopsi — mau dengar lebih lanjut?") bila ragu bisa menjaga perhatian hingga akhir.

### Ex 6.6 — Live vs stand-alone ("slideument")
- Satu materi yang dipakai untuk presentasi live & dikirim = **"slideument"** — terlalu padat untuk live, kurang detail untuk dibaca sendiri. **Rekomendasi: bangun bertahap untuk presentasi live, lalu akhiri dengan satu slide beranotasi lengkap untuk dibagikan.**
- Contoh (konsultan untuk steering committee Company X; time to fill internal vs external, goal 60 hari): (1) grafik kerangka hanya sumbu ("sebelum mengganggu Anda dengan data, saya jelaskan cara membacanya") → (2) garis goal 60 hari + konteks → (3) titik pertama External (Jan <45 hari) → (4) external naik hingga Juni (61 hari, seiring jumlah wawancara per kandidat naik) → (5) paruh kedua bervariasi (marker biru = bulan wawancara lebih sedikit; oranye = di atas goal karena wawancara & jadwal liburan) → (6) dorong external ke latar, bangun Internal (48 hari Jan; Mar–Apr <3 minggu "impressively fast"; naik Mei seiring transfer internal meningkat → proses tak efisien menangani volume) → (7) naik-turun, internal akhir tahun di atas external → (8) gambaran penuh & ringkasan + "Let's discuss: apa artinya untuk tahun depan?"
- Slide dibagikan: judul "**Time to fill role discussion needed: where do we go from here?**" + kalimat ringkas + anotasi berwarna per periode + "LET'S DISCUSS: perlukah pedoman jumlah wawancara maksimum? menjaga jadwal liburan? efisiensi proses transfer internal?"

### Ex 6.7 — Dari dashboard ke story (Project dashboard: demand vs capacity jam proyek)
- **Dashboard = alat eksploratif** (lihat rutin di mana sesuai/tidak dengan ekspektasi); setelah menemukan hal menarik, **keluarkan data dari dashboard** & terapkan pelajaran SWD.
- Kalimat per komponen: total demand jauh melebihi capacity; per region gap mirip (kurang menarik); per bulan gap terbesar Juni & menyempit di akhir tahun; per role gap terbesar Developer & Business Analyst; per sponsor department banyak data hilang ("(Empty)").
- Pilih fokus: **waktu & role**; buang yang konsisten/data hilang (kecuali menyimpang dari ekspektasi). Slide tunggal untuk dikirim: judul takeaway yang melampaui data — "**Expect continued progress towards meeting demand**"; **layout dua sisi** (kiri: OVER TIME: GAP DECREASING, BUT PERSISTS — stacked bar capacity + unmet demand; kanan: BY ROLE: BIGGEST GAP IN 2 AREAS — slopegraph capacity→demand per role, Developer & BA disorot). **"Dua visual adalah angka ajaib"** untuk satu slide (masih cukup besar & ada ruang teks; >2 → pecah ke beberapa slide).

### Practice on your own (Bab 6)
- 6.8 tensi & resolusi: CFO (rugi $45 jt → expense control initiative ABC), pemasok medis (single/dual supplier, voting mayoritas), **Craveberry yogurt** (tunda launch untuk perubahan kecil vs launch apa adanya).
- 6.9 ubah storyboard linear pemilu mahasiswa ke arc. 6.10 arc langsung untuk Craveberry (pertahankan sweetness & size; kurangi buah & tambah yogurt agar tak terlalu kental; Head of Product memutuskan menunda). 6.11 dari laporan bulanan tiket (Key Metrics) ke story.

### Practice at work (Bab 6)
- **6.12 Pithy, repeatable phrase** — ubah Big Idea menjadi frasa pendek, catchy, mungkin aliterasi; memorable (tak harus lucu). Live: buka, tutup, dan sisipkan beberapa kali. Dikirim: judul/subtitle deck, takeaway title slide penting, atau slide terakhir.
- **6.13 story (huruf kecil) vs Story (huruf besar):** *story* = untuk setiap grafik/slide tanyakan "apa poin utamanya?", tuliskan, takeaway title, fokuskan perhatian, jelaskan dengan kata — **jangan pernah biarkan audiens bertanya "So what?"**. *Story* = cerita tradisional sepanjang arc (plot, tensi, klimaks, falling action, resolusi) — memaksa mengidentifikasi tensi bagi audiens, memikirkan hubungan antar ide & transisi, dan **berpikir dari perspektif audiens**.
- **6.14 Employ the narrative arc (panduan per komponen):** **Plot** — apa yang perlu diketahui audiens agar berada di kerangka pikir yang tepat (eksplisitkan pengetahuan tacit Anda). **Rising action** — tensi apa yang ada bagi audiens & bagaimana membangunnya (sesuai situasi). **Climax** — puncak tensi bagi audiens (what's at stake, yang mereka pedulikan). **Falling action** — penyangga agar tak melompat dari klimaks ke akhir: detail tambahan/breakdown (per produk/region), opsi yang dipertimbangkan, solusi, diskusi. **Ending** — resolusi/call to action; jarang sesederhana "kami temukan X maka lakukan Y" — bisa percakapan, pilihan opsi, atau input. Urutan tak harus persis (flashback, foreshadowing), tapi **semua komponen harus hadir — terutama tensi & klimaks yang sering hilang di jalur linear**. Storyboard bisa jadi langkah antara.
- Diskusi: takeaway vs descriptive title; peran tensi; komponen arc; urutan; resistensi terhadap story; repetisi; live vs dikirim.

---

## BAB 7 — Practice More with Cole (studi kasus holistik)

### Recap: THE STORYTELLING WITH DATA PROCESS (6 langkah)
1. **Understand the context** — WHO (audiens), WHAT (apa yang harus mereka lakukan), HOW (bagaimana data membantu) → artikulasikan **Big Idea** → buat **storyboard** (brainstorm, edit, get feedback).
2. **Choose an appropriate visual** — **gambar dulu**, lalu buat di tool; iterasi & lihat data dengan berbagai cara; **minta feedback**.
3. **Eliminate clutter** — identifikasi elemen tak perlu & hapus; manfaatkan white space, sejajarkan elemen, hindari elemen diagonal.
4. **Draw attention where you want it** — posisi, ukuran, warna; uji "where are your eyes drawn?".
5. **Think like a designer** — *first function, second form*: pikirkan apa yang ingin audiens lakukan (analisis detail halus vs komunikasi tren kunci), lalu desain mudah: affordances, accessibility, aesthetics, acceptance.
6. **Tell a story** — kembali ke storyboard; susun pada **narrative arc** (set up → tension → act!); di mana & bagaimana data masuk ke cerita; bentuk **pithy, repeatable phrase** agar pesan melekat.

### 7.1 — New advertiser revenue (Feature Z, digital marketing)
- **Selalu mulai feedback dengan yang positif** (takeaway title bagus, sumbu berjudul, anotasi langsung) — panah berantakan & menutupi data.
- Masalah: tabel heatmap terasa seperti kerja; **merah/hijau** (buta warna & bersaing perhatian); alignment campur aduk.
- Iterasi quick & dirty (grafik default tanpa format): sumbu x = kuartal iklan pertama (sulit dijelaskan) vs **sumbu x = usia advertiser, garis = kohort kuartal pertama** (mudah: garis naik ke kanan = sofistikasi naik dengan usia; garis lebih tinggi = sofistikasi lebih cepat) — **"perhatikan betapa lebih mudah menjelaskannya dengan kata"** → sederhanakan dengan **kohort tahunan** (2015–2019) → "Bingo!"
- Tensi: adopsi membaik secara umum, tapi tak tahu untuk advertiser baru — ada masalah? Resolusi: **tidak perlu aksi**; audiens cukup tahu; tim akan memantau & memberi tahu bila berubah. (Biasanya, jika tak bisa mengartikulasikan aksi, tinjau ulang perlu tidaknya komunikasi — tapi pertanyaan audiens tetap layak dijawab.)
- Slide: "**Sophistication increasing with time & age**" — Feature Z % revenue by advertiser age; kohort 2015 abu → 2019 biru; anotasi "Sophistication increases with time" (28% revenue Feature Z pada kuartal pertama untuk advertiser baru 2019 vs 15% untuk 2015) & "with age"; "**No action is needed at this time** — We will continue to monitor and report back if things change"; footnote sumber.

### 7.2 — Sales channel update (stacked bar unit per channel 2012–2020 + bullet teks)
- **Terlalu banyak pertanyaan dijawab satu grafik → tak ada yang terjawab baik.** Stacked bar = **"pisau Swiss Army"** — bisa banyak hal, tak ada yang sebaik alat khusus → **pakai beberapa grafik**.
- Feedback: (1) multiple graphs; (2) **ikat teks ke data** (proximity, connection, similarity); (3) **bedakan forecast** (2020 proyeksi tapi tampak nyata) — **aktual = garis solid & titik terisi; estimasi = garis putus-putus & titik kosong + label "PROJECTED"**.
- Grafik 1 (total unit, line, label beberapa titik saja): **live progression kronologis** — kerangka → 2012 launch 22,5K (target 18K) → 2013 sedikit naik → 2014 masalah produksi, anjlok (18,1K) → 2015 pulih ~24K → 2016–2017 naik → 2017 keputusan geser dari retail ke partner, 2018 dip → 2019 pulih → 2020 diproyeksi naik (27,5K). Versi dikirim: anotasi langsung.
- Grafik 2 (komposisi): **100% stacked bar** — baseline atas & bawah konsisten → dua seri (bawah & atas) mudah dibandingkan bila **urutannya cerdas** (Retail di bawah, Partner di atas); live: fokus bergantian Retail (turun), E-commerce (naik sedikit, stabil), Direct mail ("kecil, selalu kecil, akan tetap kecil"), Partner (naik) → "**The desired shift in channels has happened: success!**"
- Slide untuk distribusi: "**Total sales increasing as channels shift**" — kiri "2020 EXPECT INCREASE IN SALES" (line), kanan "CHANNEL SHIFT OVER TIME" (100% stacked; retail turun dari >60% ke 38% di 2019, partner dari <20% ke 30%).

### 7.3 — Model performance (bank; output SAS: prepayment model vs actual by LTV)
- Pertanyaan: apa arti akronim & sumbu? data mana dibaca ke sumbu kanan? kenapa gaya garis begitu? apa yang disorot kotak merah besar?
- **Bahasa yang mudah dipahami:** "vol_prepay_rt" → *voluntary prepayment rate* (proporsi peminjam melunasi lebih awal); **eja semua akronim** minimal sekali per halaman atau di footnote (orang malu bertanya / salah asumsi) — "bukan menyederhanakan, tapi tak membuat lebih rumit dari perlu". LTV = loan-to-value (makin tinggi makin berisiko); UPB = unpaid principal balance. Detail teknis (sampel out-of-time dll) → footnote untuk audiens senior.
- **Ubah gaya garis secara hemat:** putus-putus hanya untuk ketidakpastian (model = tepat putus-putus; UPB aktual tak boleh putus-putus). Aktual = tebal, solid, terisi; estimasi = tipis, putus-putus, kosong.
- **Hapus sumbu y sekunder** (selalu ada kerja mencocokkan) → sembunyikan & label langsung, atau **pisah jadi dua grafik dengan sumbu x sama**. Satuan "ribuan dari ribuan" → jutaan.
- **Kotak merah menyorot hal yang salah** ("model overpredict di LTV rendah") — tak ada portofolio di LTV rendah (& itu pinjaman paling aman) → bukan masalah. Yang penting: **model underpredict di LTV tinggi, di mana ada saldo pinjaman** → pantau.
- Live: set up sumbu → actual (datar) → model (over di rendah, under di tinggi) → ganti sumbu y dengan distribusi UPB (bar terbesar ~$800 jt) → hapus sumbu, bar ke latar, lapisi kembali garis → sorot over-predict (tak ada portofolio) → sorot under-predict (ada portofolio) → slide dikirim: "**Prepayment model has limitations**" — "Model bekerja baik di rentang LTV tempat sebagian besar pinjaman terkonsentrasi. Namun overestimate di LTV rendah & underpredict di LTV tinggi. **ACTION: hindari konsentrasi portofolio pada pinjaman LTV rendah atau tinggi.**"

### 7.4 — Back-to-school shopping (survei % favorable, toko kita vs pesaing)
- Iterasi: scatterplot (memunculkan lebih banyak pertanyaan) → line (menghubungkan data kategorikal — tak masuk akal) → vertical bars (label diagonal) → **horizontal bars** (alasan paling sering beralih: ruang untuk label kategori) → **urutkan bermakna** (bila tak ada urutan alami): ascending (yang kecil di atas jika itu penting) vs **descending** (mulai dari yang baik lalu peluang — lebih halus untuk alur cerita; Excel memindahkan sumbu x ke atas — bagus) → declutter (hapus border & gridlines, bar lebih tebal, maks sumbu 100%, label sumbu x lebih jarang, hapus garis & tick sumbu y, hapus titik di akhir label, singkat label, legenda di atas berwarna sama) → "where are your eyes drawn?" → tak ke mana-mana → **fokus**: semua abu, "Our Store" biru tua → tambahkan kata (judul grafik & sumbu).
- **Live progression:** (1) pithy phrase/Big Idea dulu: "Saya membuat satu rekomendasi hari ini: **investasi pelatihan karyawan untuk memperbaiki pengalaman pelanggan di toko**" → (2) mundur & set plot (back-to-school hampir 1/3 revenue tahunan; dulu dikendalikan pujian/kritik one-off per toko — tak scalable; survei pelanggan kita & pesaing) → (3) agenda → (4) setup grafik (dimensi & "% favorable") → (5) data kita (variasi) → (6) sorot 3 tertinggi (atmosfer, item tak ada di tempat lain, gaya terbaru; komentar verbatim mendukung) → (7) sorot terendah → (8) tambah bar abu pesaing (di area terendah kita setara pesaing → bukan fokus) → (9) sorot di mana kita di bawah pesaing → (10) **ganti view: selisih vs pesaing** (kiri underperform, kanan outperform) → (11) area unggul = 3 item sama → (12) area kalah → (13) kalah terbesar di **promosi & harga obral** — sengaja dihindari karena **brand dilution** → tak direkomendasikan → (14) **karyawan ramah & membantu, bisa menemukan barang, menemukan ukuran** — "mengkhawatirkan", tapi **dalam kendali sales associate** → (15) ulangi Big Idea.
- Slide dikirim: "**Action needed: invest in employee training**" — diverging bar selisih % favorable vs pesaing + "THE GOOD NEWS" (biru) & "WE CAN IMPROVE" (oranye) & "RECOMMENDATION"; footnote data (2019 Back-to-School survey, n=2.482, dsb.).
- "**Don't just show data: make data a pivotal point in an overarching story!**"

### 7.5 — Diabetes rates (oleh Elizabeth Hardman Ricks)
- Audiens = senior administrator; brainstorm 5 menit kekhawatiran → 5 kelompok: **finansial** (opex, target revenue), **people** (rekrut & retensi), **akreditasi & standar** (benchmark, regulasi), **pemasok** (reimbursement asuransi, kontrak, alat), **kompetitor** (kualitas/biaya). What's at stake: kehilangan revenue (reimbursement) & jatuh di bawah standar akreditasi → minta pertimbangkan **menambah staf**.
- Storyboard kronologis (mengikuti proses analisis) → disusun ulang sepanjang arc dari perspektif audiens.
- 4 opsi grafik (bar per center per tahun; garis terpisah per center; **line standar**; slopegraph) → tulis 1 kalimat observasi per grafik → pilih **line standar** (konteks historis, familiar, bisa sorot garis ALL & proyeksi).
- **Fire drill (akhir hari, tanpa ubah layout) → hanya warna & kata** (<15 menit karena konteks sudah dipikirkan): judul "Diabetes rates have increased" (hitam = garis ALL), subtitle "Do we need additional staff to remain within standards?"; oranye = **CENTERS OF CONCERN** (B tertinggi 12,5%, E naik paling banyak); hitam = **OVERALL** (naik stabil ke 8,6% di 2019; +14.000 pasien diabetes/th 4 th ke depan); biru = **THE GOOD NEWS** (A terendah) + next steps.
- Deck manajer (live + speaker notes): buka dengan **angka mengejutkan "14,000"** & pertanyaan diskusi → setup → overall 7,2% (2015) → 8 center lebih tinggi & 5 lebih rendah → overall 8,6% (2019) → semuanya naik → +0,5 poin/th → proyeksi **10% di 2023 (1 dari 10 pasien)** → +14.000 pasien/th → "Apa yang harus kita lakukan? Rekomendasi awal: pertimbangkan staf tambahan; opsi lain? Let's discuss." + slide beranotasi untuk dikirim: judul "**Rising diabetes rates: do we need additional staff?**"; garis overall hitam aktual 2015–2019 lalu **putus-putus ke titik kosong "10%" (2023)** dengan label sumbu x "ACTUAL | FORECAST"; anotasi oranye (Center B tertinggi 12,5%, Center E naik tajam 8,5%→11,3% — faktor apa?), hitam (7,2%→8,6% → 10% di 2023 = +14.000 pasien/th), biru (kabar baik: pelajari faktor yang membuat Center A terendah & top patient care; next steps: tentukan apakah bisa diterapkan luas). Judul-judul slide live = takeaway ("Increase: low centers", "Consistent increase of 0.5 points per year").

### 7.6 — Net Promoter Score (aplikasi; rapat bulanan 15 menit dengan format tetap: title, data & methodology, analysis, findings)
- NPS = %promoter (5 bintang) − %detractor (1–3 bintang); 4 bintang = passive; dinyatakan sebagai angka.
- **Big Idea:** "Kita akan terus kehilangan pengguna kecuali memperbaiki latensi produk: prioritaskan di rilis fitur berikutnya." **Pithy phrase (tak terlalu "salesy"):** "**Let's learn from our detractors**" (judul deck & call to action).
- Takeaway per grafik: NPS naik ke tertinggi 14 bulan (37; 29 setahun lalu); peringkat 4 dari 15 pesaing (rentang 47–18); **polarisasi** — passive menyusut, promoter & detractor sama-sama naik; banyak detractor berkomentar, keluhan utama latensi.
- Deck live (menggantikan alur linear methodology-analysis-findings): judul → tujuan hari ini (NPS saja tak bercerita lengkap; detractor naik; bingkai diskusi strategi produk) → NPS naik ke 37 → peringkat 4 → "NPS alone doesn't tell the full story" — definisi komponen → setup grafik komponen → **bangun dari tengah**: passive turun → promoter naik → detractor naik (area kosong sudah mengisyaratkan) → angka: detractor 10% (awal 2019) → 13% (pertengahan) → **25% (Feb 2020), hampir dua kali lipat sejak Agustus** → 15% pemberi rating berkomentar; promoter jarang & umum ("It's great!"), **29% detractor berkomentar** → "**1 in 3 detractor comments are about speed or latency**" (tema berikutnya hanya 6%) + baca verbatim komentar → rekomendasi (slide oranye penuh): "**Revisit our product and feature release strategy in light of this feedback and prioritize latency improvements. Let's discuss.**"
- Pelajaran: audiens tak selalu setuju (prioritas bersaing, perbaikan sulit), tapi **membingkai sebagai rekomendasi memberi sesuatu yang spesifik untuk direspons** → memunculkan konteks & debat lebih kaya. Menyajikan data story tak berarti Anda tahu semua jawaban.

---

## BAB 8 — Practice More on Your Own (latihan tanpa solusi; makin kompleks)

### Common myths in data viz (halaman ilustrasi)
| Mitos | Kebenaran |
|---|---|
| **Unbiased data exists** | Kita **membiaskan data di setiap langkah proses**: apa yang dipilih untuk diukur, bagaimana diagregasi & dibandingkan, bagaimana ditampilkan. **Aturan: jangan berbohong dengan data.** |
| **More data is always better** | Sebelum mengejar data lagi, tanya "**Apa yang akan ini bantu kita lakukan/putuskan?**" Audiens & konteks menentukan jumlah data yang tepat. |
| **Averages always work to summarize data** | Pahami **distribusi, sebaran, variabilitas** (tahunan vs bulanan vs harian) — rata-rata bisa menyesatkan dengan menyembunyikan sebaran dalam satu angka. |
| **There is a single right answer when visualizing data** | Selalu pertimbangkan **apa tujuan Anda**: inform, engage, explore, innovate, entertain. |
| **Line graphs are for continuous data only** | Garis yang menghubungkan titik **harus masuk akal** — mis. *slopegraph* data survei (garis dengan 2 titik saja) untuk membandingkan antar kelompok/kategori (overall org vs sales org). |
| **Bars are always better** | Bar = titik mulai yang baik, **tapi tak selalu terbaik** — tanya "apa yang ingin saya audiens lihat?", coba tipe grafik lain. |
| **Graphs must have a zero baseline** | Benar **untuk bar chart** (panjang bar harus proporsional); grafik garis tak wajib. |
| **Pie charts are evil** | Saat memakai pie, **tanya mengapa**. Studi: orang membaca pie & donut dengan **membandingkan luas, bukan sudut**. Jika pie masuk akal untuk data & audiens, **uji**. |

### Daftar latihan (semua bisa dipakai sebagai tugas/ujian; campur & cocokkan instruksi)
- **8.1 Diversity hiring** — slide "2019 ABC Program Hiring Highlights" (tabel padat: hire per LOB & tipe posisi, GPA 3,66; tabel diversity: target 25% terlampaui 26%, target etnis 40% tak tercapai karena 5 kandidat etnis-beragam membatalkan; rasio 1:1). Langkah: yang positif → yang tak ideal → **success story atau call to action?** → **jika dipaksa tetap dalam bentuk tabel**, bagaimana memfokuskan perhatian? → bila bebas, ceritakan data-driven story.
- **8.2 Sales by region** (Sales Manager NW; bar 2018 vs 2019 + titik "annualized growth" pada sumbu y sekunder + kotak teks di bawah) — Skenario 1: offsite besok, **maks 5 menit perubahan** — apa yang dilakukan? Skenario 2: seminggu, Chief of Staff akan redesign — apa yang dipertahankan & diubah?
- **8.3 Revenue forecast** (gross vs net revenue + tabel data) — efektifkah tabel data? perbedaan **live vs email**; coba tool dataviz baru & refleksikan.
- **8.4 Adverse events** (perusahaan alat medis) — positif dulu → daftar pertanyaan untuk kolega → rekomendasi (apa & **mengapa**) → bagaimana jika audiens **non-teknis**?
- **8.5 Reasons for leaving** (Chief of Staff CMO; HRBP mengirim dua bubble matrix "HR Business Partner Input" & "Exit Survey" — sumbu *Ability to impact* × *Frequency*, ukuran bubble = jumlah; alasan: training, conflict, lack of recognition, workload, career advancement, pay, type of work, career change, commute, relocation, illness). Jelaskan cara membaca → apa yang membingungkan + **bagaimana memberi feedback agar HRBP yang sudah bekerja keras tak tersinggung** → **gambar 3 cara berbeda** (kelebihan & kekurangan) → buat & presentasikan ke CMO.
- **8.6 Accounts over time** ("Market model: accts and field coverage" — bar akun aktual s.d. Sep 2019 + forecast s.d. akhir 2020, bintang "77% achieved in 9 mos", kotak teks "Great market & successful launch") — pertanyaan → declutter → **success atau call to action? apa tensinya?** → live vs dikirim.
- **8.7 Errors & complaints** (bank, year-end review portofolio Home Loans — halaman penuh grafik errors (overall, inbound quality, product A/B/C vs goal), complaints (historical, top categories), top error reasons) — pertanyaan & jawab dengan asumsi → takeaway per grafik → cerita mana? data apa yang dibuang? satu slide atau lebih? → **manajer bilang audiens mengharapkan "halaman grafik" seperti biasa — bagaimana merespons?**
- **8.8 Taste test data** (yogurt Craveberry; stacked bar 100% "not enough / just about right / too much" per atribut size, amount of yogurt, amount of fruit, sweetness, creaminess, thickness + lingkaran oval) — positif → feedback & alasan → susun komponen **narrative arc (plot, rising action, climax, falling action, ending)** dengan sticky notes → apa tensi & resolusinya → buat cerita + narasi untuk Head of Product.
- **8.9 Encounters by type** (pusat kesehatan; tabel encounter in-person vs telephone/video/email untuk Primary & Specialty Care) — visualisasikan untuk memahami: (A) total encounter berubah? (B) breakdown per tipe, **apakah pergeseran ke virtual terjadi?** (C) beda Primary vs Specialty? (D) **target** yang direkomendasikan berdasarkan data saja → outline low-tech (bullet, sticky, storyboard, arc) → buat live story + **one-pager** untuk yang absen. (Konteks: minta input dokter agar target tidak terlalu agresif & merusak kualitas layanan.)
- **8.10 Store traffic** (ritel nasional) — traffic turun YoY overall & semua region; paling turun di **Northeast** (toko ditutup → pelanggan pindah ke pesaing); turun lebih tajam untuk segmen terpenting "**Super Shoppers**", gap melebar beberapa bulan terakhir. **Sales = traffic × basket; basket = unit dibeli × harga per item.** Pelanggan membeli item lebih sedikit, tapi **harga rata-rata naik** (promosi tertarget merek mewah) → rekomendasi: **investigasi implikasi finansial promosi Super Shopper tambahan** (uji hipotesis & membalik tren). Grafik eksplorasi (YoY total & Super Shopper per region, weekly traffic/basket components) **tak cocok untuk komunikasi** → Big Idea + pithy phrase → takeaway per grafik → sticky notes → narrative arc → desain → deck + narasi → refleksi.
- **Pelajaran umum:** grafik yang dipakai untuk **menemukan** cerita (exploratory) sering **tidak cocok untuk menyampaikan** cerita (explanatory).

---

## BAB 9 — Practice More at Work

### Mengembangkan tim (halaman ilustrasi "Developing your team")
- **What about me? — Nobody works in a vacuum:** manajer & pemimpin diuntungkan dengan membangun kapasitas tim bercerita dengan data; juga individu yang ingin memengaruhi orang di sekitarnya.
- **Typical team set-ups — cross-functional groups:** technician, designer, manager, analyst. **Sebagian besar tim tak punya spesialis dataviz; ini bagian dari peran analis.**
- **Balancing strategic & technical:** lebih dari "membuat data cantik" — pandangan 10.000 kaki vs informasi teknis mendalam. **Analisis paling brilian pun sia-sia jika tak dikomunikasikan efektif.**
- **Untuk manajer — foster a culture of learning:** jadikan dataviz & komunikasi bagian yang diharapkan dari peran analitis; identifikasi siapa yang punya minat & bakat alami, dukung jadi ahli.
- **Untuk tim kecil — embrace the constraints:** makin kecil tim, makin perlu solusi kreatif → dorong eksperimen pendekatan baru, manfaatkan sumber daya gratis online, cari mentor eksternal.
- **Untuk individu:** kerjakan dengan baik, minta feedback, bagikan tips tanpa menggurui, **keberhasilan kecil membangun kepercayaan diri & kredibilitas**.

### 9.1 Create your plan of attack — daftar latihan "practice at work" yang bisa dikombinasikan per proyek
1.17 get to know your audience · 1.18 narrow your audience · 1.19 identify the action · 1.20 Big Idea worksheet · 1.21 solicit feedback on Big Idea · 1.22 create Big Idea as a team · 1.23 get ideas out of your head · 1.24 organize ideas in a storyboard · 1.25 feedback on storyboard · 2.17 draw it! · 2.18 iterate in your tool · 2.19 consider these questions · 2.20 say it out loud · 2.21 feedback on graph · 2.22 build a data viz library · 2.23 explore resources · 3.11 start with blank paper · 3.12 query "do you need that?" · 4.9 test "where are your eyes drawn?" · 4.10 practice differentiating in your tool · 4.11 figure out where to focus · 5.9 make data accessible with words · 5.10 create visual hierarchy · 5.11 pay attention to detail · 5.12 design more accessibly · 5.13 garner acceptance · 6.12 pithy repeatable phrase · 6.13 answer "what's the story?" · 6.14 employ the narrative arc.

### 9.2 Set good goals — OKR (dipelajari Cole di Google)
- Inti: isolasi skill yang ingin ditingkatkan → daftar aksi spesifik → **beri tenggat (urgensi)** → tempel di tempat terlihat → bagikan ke manajer/kolega (**akuntabilitas**).
- **Objectives** = apa yang ingin dicapai (signifikan, berorientasi aksi). **Key Results** = bagaimana objective dicapai — **agresif tapi realistis, terukur, terbatas jumlahnya, time-bound**. Biasanya **3–5 objective per kuartal, masing-masing 2–3 KR**.
- Contoh — **O:** Integrasikan story ke presentasi pilot program XYZ untuk mendapat persetujuan sumber daya. **KR1:** selesaikan latihan 1.17, 1.20, 1.21, 1.23, 1.24, 6.12, 6.14 untuk dua proyek sebelum 31 Jan. **KR2:** buat materi terpisah untuk live & email summary sebelum 15 Jan; minta & integrasikan feedback Stakeholder A sebelum 31 Jan. **KR3:** 3 presentasi latihan ke kolega kuartal ini & integrasikan feedback (konten, alur, gaya).
- OKR **dipublikasikan** ke tim (transparansi meningkatkan peluang sukses). **Seminggu setelah kuartal: review & grade** skala **0–10** (mis. target 12 grafik, buat 6 → 5). Angka memaksa kejujuran & introspeksi ("kenapa tidak lebih? prioritas berubah — oke? apa penghambatnya?"). Skor objective = rata-rata KR; skor kuartal = rata-rata objective. Review → input OKR kuartal berikut. Manfaat: disiplin berpikir, akuntabilitas resmi, indikator kemajuan, **alignment** tim ke tujuan yang sama.

### 9.3 Give & receive effective feedback
- **Tentukan siapa yang ditanya:** orang **tanpa konteks** = perspektif segar (menemukan bahasa tak terjangkau, asumsi tersembunyi, visual asing) — cocok bila audiens jauh dari pekerjaan Anda; **ahli** bila audiens teknis/akan ada scrutiny.
- **Timing:** **makin awal makin baik** (belum terikat, mudah ganti arah; kurangi iterasi dengan stakeholder beropini kuat); untuk proyek kritis, feedback di beberapa titik. Hormati jadwal pemberi feedback; bila sulit, jadwalkan sesi live. **Berterima kasih.**
- **Jelas fokusnya:** mudah dibaca? poin tersampaikan? Bagikan konteks audiens & kendala. Contoh: "Harus terkirim hari ini jam 5 sore — cari yang tidak jelas atau isu yang cepat diperbaiki" vs "Semua boleh dikritik".
- **Dengarkan, jangan bicara:** jangan membela diri (mematikan percakapan); dengarkan tanpa menghakimi, akui, catat, dorong terus bicara, ajukan pertanyaan probing.
- **Pertanyaan pemicu:** Ke mana mata Anda pertama? Apa pesan utamanya? Bagaimana Anda memproses grafik — pertama, lalu? Apa yang akan Anda lakukan berbeda & mengapa? Ada yang mengganggu pesan? **Sisihkan — bisakah Anda ceritakan poin utama? Apa lagi yang diingat?**
- **Timbang input:** tak semua feedback setara (sumbernya menentukan). Jika ditolak, lepaskan keterikatan emosional. Ragu → minta opini kedua; **bila sama, anggap masalahnya di desain, bukan di pemberi feedback** — cari akar masalah.
- **Memberi feedback yang baik:** hindari dogmatis benar/salah; orang sedang rentan & punya kendala yang tak Anda lihat; tanya feedback apa yang diinginkan; **tentang pekerjaan, bukan orangnya**; **mulai dari yang bagus**. Kerangka: "**I like… / I have questions about… / I'd suggest…**" atau **analyze–discuss–suggest**.
- Input dadakan juga berguna (cetak, minta kolega melihat layar) — "from good to great".

### 9.4 Cultivate a feedback culture
- Taruhan di kerja tinggi → orang enggan mengaku butuh feedback; feedback buruk terasa serangan pribadi.
- **"Present & discuss"** 10 menit di rapat rutin (tiap orang: 1 poin positif + 1 saran; bergilir).
- **"Feedback buddies"** — pasangan dengan ekspektasi kapan/berapa sering (mis. 2x seminggu selama sebulan); manajer menanyakan di 1-on-1; acak ulang tiap bulan/kuartal.
- **Feedback "speed dating"** — bawa cetakan; meja berhadapan; timekeeper bersuara keras; 1 menit tinjau diam + 2 menit saran untuk A + 2 menit untuk B = 5 menit; satu sisi geser satu kursi; ulangi.
- **Sesi formal 1 jam** — kelompok bertiga; tiap orang 5 menit konteks & feedback yang dicari + 10 menit diskusi (3 × 15 menit) → debrief seluruh grup.
- Forum **non-kerja** (low-risk): **"review & critique"** contoh publik dari media (hilangkan ego; contoh bagus juga berguna); **#SWDchallenge bulanan tim** (minggu 1 tetapkan tantangan, data non-kerja; akhir bulan presentasi & feedback; terinspirasi Simon Beaumont, JLL — sesi direkam & dibagikan).

### 9.5 Refer to the SWD process (6 pelajaran + pemantik)
1. **Understand the context** — siapa audiens, apa motivasinya; Big Idea (POV, what's at stake, kalimat lengkap); storyboard; urutan; **minta input klien/stakeholder di titik ini**.
2. **Choose an appropriate visual** — iterasi berbagai cara untuk momen "**ah ha**"; gambar; minta feedback.
3. **Eliminate clutter** — hubungkan yang terkait, white space, alignment, hindari diagonal; kontras secara hemat.
4. **Focus attention** — posisi, ukuran, warna (hemat; tone, brand, buta warna); tes "where are your eyes drawn?".
5. **Think like a designer** — kata membuat data masuk akal; judul & label; **takeaway title menjawab "So what?"**; hierarki visual; **detail (jangan biarkan isu kecil merusak kredibilitas)**; aksesibilitas.
6. **Tell a story** — pithy phrase; storyboard pada narrative arc; tensi & resolusi; posisi data dalam narasi; **live vs dikirim**; tangkap perhatian, dorong diskusi, pengaruhi aksi.

### 9.6 Assessment rubric (Figure 9.6) — skala: "**nailed it! / good / more attention needed / (N/A)**", atau 1–3, atau 1–10
1. Saya paham cara membaca grafik.
2. Pilihan visual masuk akal untuk data & pesan.
3. Konteks data/metodologi/latar memadai.
4. Kata dipakai dengan baik untuk judul, label, anotasi, penjelasan.
5. Clutter minim/tiada.
6. Jelas di mana harus fokus pertama.
7. Warna efektif.
8. **Bebas salah eja, tata bahasa, & kesalahan hitung.**
9. Desain terstruktur: elemen sejajar, white space baik.
10. Urutan konten masuk akal.
11. Pesan utama &/atau call to action jelas.
12. Materi dioptimalkan untuk cara penyampaian.
13. **Overall success: komunikasi menyelesaikan kebutuhan yang dituju.**
(+ baris kosong untuk komponen tambahan.) Cole umumnya menghindari rubrik (orang suka aturan → formulaik). Hal tak berwujud juga penting: **apakah waktu dioptimalkan sesuai kepentingan** — tak perlu menjalankan seluruh proses SWD setiap menyentuh data; efisiensi & prioritisasi patut dihargai.

### 9.7 Facilitate a Big Idea practice session (60 menit)
- Persiapan: pahami panduan & latihan Bab 1; jelaskan Big Idea ke orang lain dulu; cetak worksheet; pena; **laptop ditinggal**.
- Agenda: 00:00–00:10 perkenalkan Big Idea + contoh · 00:10–00:20 isi worksheet · 00:20–00:30 diskusi partner 1 · 00:30–00:40 partner 2 · 00:40–01:00 diskusi grup.
- Contoh skenario (SWD 2015): program belajar sains musim panas untuk kelas 2–3 SD; sebelum program 40% merasa "biasa saja", setelahnya hampir 70% tertarik. **Big Idea untuk komite anggaran:** "*Program pilot musim panas berhasil memperbaiki persepsi siswa terhadap sains; mohon setujui anggaran untuk melanjutkan program penting ini.*" (POV ✓, at stake ✓, satu kalimat lengkap ✓)
- Partner: **pasangkan dulu dengan yang kurang familiar**; penerima bertugas **menghujani pertanyaan** agar jelas & ringkas; cek di menit 5 untuk bergantian; ganti partner.
- Poin diskusi: **meringkas jadi satu kalimat itu sulit** (tulis beberapa kalimat lalu pangkas; worksheet memecah komponen seperti puzzle); **satu kalimat itu penting** — **kejernihan berpikir terjadi lewat wordsmithing**; **ucapkan dengan keras** (tersandung = tanda perlu iterasi); **feedback partner krusial** (tacit knowledge, jargon, asumsi); partner tanpa konteks bagus (pertanyaan "Mengapa?"); **Big Idea = North Star** & **litmus test** untuk setiap konten: "apakah ini membantu menyampaikan Big Idea saya?"

### 9.8 Conduct an SWD working session (3 jam, ideal 8–10 orang; ~6–7 menit/orang untuk present back)
- Persiapan: ruang dengan meja luas & whiteboard; spidol warna, flip chart, **sticky note 6×8 inci (seukuran slide — mock-up seluruh deck)** + ukuran kecil untuk storyboard tingkat tinggi; tunjuk timekeeper (umumkan setengah waktu & sisa 20 menit).
- Agenda: 00:00–00:15 recap & ekspektasi · 00:15–01:30 kerja proyek (low-tech, laptop tertutup; pilih pelajaran 1–6 yang mau dipraktikkan) · 01:30–01:45 istirahat · 01:45–02:45 present back · 02:45–03:00 debrief.
- **Present back (~5 menit):** (1) latar: audiens, tujuan, keputusan kunci, **seperti apa sukses**; (2) bagaimana pelajaran SWD diterapkan (Big Idea, storyboard, ide visual, before/after, fokus, cerita) + **minta feedback spesifik**.
- Debrief: terasa bagaimana? paling membantu? perubahan ke depan? tantangan menerapkan? langkah tambahan? → **publikasikan hasil**, bagikan kisah sukses, **ciptakan champion** → pengakuan & kesabaran organisasi terhadap waktu yang dibutuhkan.

### 9.9 Set yourself up for successful data stories
- **Coba hal baru di tempat berisiko rendah dulu** (jangan buka rapat direksi dengan "hari ini saya akan bercerita"); keberhasilan kecil → kredibilitas.
- **Urutkan dengan cermat** (elemen grafik, objek slide, urutan slide); uji ke orang yang kurang familiar.
- **Optimalkan materi untuk cara komunikasi:** live = bangun visual bertahap; dikirim = 1–2 slide teranotasi penuh.
- **Antisipasi bagaimana bisa salah:** uji asumsi, selidiki **hipotesis alternatif**, minta kolega jadi **devil's advocate / audiens sinis**, siapkan jawaban pertanyaan.
- **Jawab "So what?"** — jangan biarkan audiens menebak; mengapa mereka di sini, apa yang ingin Anda katakan, mengapa harus mendengar.
- **Fleksibel** — kadang perlu cerita "**choose your own adventure**"; kesediaan menyesuaikan diri membangun kredibilitas.
- **Minta feedback setelah presentasi**; **belajar dari sukses & gagal** (yang gagal sering lebih mengajarkan); bagikan.
- Meta-tema: **be thoughtful** — definisikan sukses & posisikan diri untuk mewujudkannya.

### 9.10 Let's discuss (10 pertanyaan refleksi tim)
1) Satu hal yang akan dilakukan berbeda; 2) pelajaran mana paling kritis & mana perlu dikembangkan; 3) di mana bisa salah & cara mencegah; 4) sumber daya tambahan; 5) takeaway terbesar; 6) gap cara kerja sekarang vs ideal; 7) resistensi dari siapa & cara mengatasi; 8) **kendala apa & bagaimana merangkulnya untuk solusi kreatif**; 9) cara membantu orang lain menghargai data storytelling; 10) **tujuan spesifik, akuntabilitas, ukuran sukses**.

---

## BAB 10 — Closing Words
- Komunikasi data seperti **puzzle** dengan kepingan: audiens, konteks, data, asumsi, bias, kredibilitas, cara presentasi, ruang fisik, printer/proyektor, dinamika interpersonal, aksi yang dicari — **kepingannya berbeda setiap kali**. **Bukan jigsaw: tak ada satu cara benar**; banyak pendekatan bisa berhasil.
- **Closing thoughts (ilustrasi):** **Start small — jadikan SWD bagian dari keseharian**: mulai dari ide berisiko rendah & usaha rendah; lama-lama hal kecil menumpuk. **Low-hanging fruit: COLOR dan WORDS** (titles, annotations, labels). **Practice & prioritize — keep at it!** **Learn guidelines — lalu langgar dengan sengaja ketika masuk akal.**
- Latihan tak pernah selesai; terapkan, bagikan, **ceritakan kisah dengan data yang memengaruhi perubahan positif**.

---

## RINGKASAN SUPER PADAT SWD: LET'S PRACTICE (cara berpikir konsultan saat membuat slide data)
1. **Exploratory ≠ explanatory.** Grafik untuk menemukan insight bukan grafik untuk menyampaikan insight.
2. **Konteks dulu, tool belakangan:** WHO (audiens spesifik, motivasi, apa yang membuat mereka tak bisa tidur) → WHAT (aksi yang diminta) → HOW (data apa yang mendukung) → **Big Idea satu kalimat (POV + at stake)** → storyboard sticky notes → minta feedback.
3. **Pilih visual dengan iterasi** (gambar di kertas, coba 3+ cara, "say it out loud" — mana yang paling mudah dijelaskan). Bar horizontal untuk label panjang; urutkan bermakna; line untuk waktu; 100% stacked untuk komposisi (2 seri yang dibandingkan di dasar & puncak); slopegraph untuk 2 titik; diverging bar untuk selisih vs pesaing; hindari pie/3D/sumbu sekunder bila bisa; bar wajib baseline nol.
4. **Declutter** (border, gridline, marker, label berlebih, legenda → label langsung) & **fokus** (abu untuk konteks, satu warna aksen; "where are your eyes drawn?").
5. **Kata adalah bagian dari data:** judul aksi/takeaway ("So what?"), judul sumbu, anotasi langsung yang terhubung secara warna/proximity, footnote sumber & definisi; eja akronim; **forecast dibedakan** (putus-putus, titik kosong, label "projected").
6. **Cerita = narrative arc** (plot → rising action → **tension** → climax → falling action → resolution/**call to action**), bukan urutan methodology-analysis-findings. Gunakan **pithy, repeatable phrase** di awal & akhir ("Let's learn from our detractors").
7. **Live vs dikirim:** live = bangun grafik bertahap (setup sumbu → data → fokus bergantian → ganti view → rekomendasi → ulangi Big Idea); dikirim = 1 slide **teranotasi penuh** yang menceritakan cerita yang sama.
8. **Rekomendasi spesifik + "Let's discuss"** — memberi audiens sesuatu untuk direspons; tak harus punya semua jawaban.
9. Di bawah tekanan waktu: **ubah warna & kata saja** (bila konteks sudah dipikirkan, cukup <15 menit).
10. Kultur: feedback awal & sering ("I like / I have questions / I'd suggest"), OKR untuk skill, rubrik 13 poin sebagai checklist akhir.
