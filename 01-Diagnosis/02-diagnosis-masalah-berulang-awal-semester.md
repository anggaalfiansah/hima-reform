# 02 — Diagnosis Masalah Berulang Awal Semester: Onboarding Maba, Drama KRS, dan Kekacauan Grup Kelas

**Program Studi:** PJJ Sistem Informasi  
**Institusi:** Universitas Siber Asia (UNSIA)  
**Status:** Dokumen Diagnosis Resmi (Basis Bukti Empiris)  
**Kategori:** Evaluasi Layanan & Tata Kelola Awal Semester  
**Penyusun:** Tim Reformasi Tata Kelola HIMA Sistem Informasi  
**Tanggal Rilis:** September 2026  

---

## 1. Pendahuluan dan Latar Belakang

Siklus pergantian semester merupakan periode paling krusial sekaligus rentan dalam penyelenggaraan pendidikan jarak jauh (PJJ). Pada perguruan tinggi berbasis daring penuh seperti Universitas Siber Asia (UNSIA), mahasiswa baru (maba) maupun mahasiswa aktif mengandalkan kanal-kanal digital sebagai satu-satunya jembatan interaksi akademik, teknis, dan sosial.

Himpunan Mahasiswa (HIMA) secara ideal mengemban mandat sebagai representasi mahasiswa dan garda terdepan pendampingan civitas. Khusus pada awal semester, ekspektasi mendasar mahasiswa terhadap HIMA mencakup:
1. Menyambut mahasiswa baru, memberikan orientasi teknis, serta panduan adaptasi sistem PJJ (*tips & tricks* perkuliahan).
2. Mengawal proses registrasi administrasi dan pengisian Kartu Rencana Studi (KRS).
3. Mengoordinasikan pembagian dan pengelolaan kanal komunikasi kelas (grup WhatsApp mata kuliah).

Namun, realitas operasional di lapangan menunjukkan bahwa ketiga agenda tersebut secara berulang setiap semester justru menjadi sumber kebingungan massal (*mass confusion*), friksi informasi, dan disorientasi civitas. Dokumen ini disusun untuk mendiagnosis secara komprehensif kegagalan sistemik HIMA dalam menangani tiga masalah tahunan tersebut berbasis bukti empiris percakapan civitas mahasiswa.

> [!IMPORTANT]
> **Batasan Ruang Lingkup Dokumen:**
> Dokumen ini berfokus secara eksklusif pada **diagnosis kondisi faktual** berdasarkan bukti lapangan. Dokumen ini **tidak menetapkan solusi teknis, program kerja, atau keputusan struktural**. Perumusan solusi akan dituangkan pada tahapan desain intervensi selanjutnya (Fase 02 dan seterusnya).

---

## 2. Metodologi dan Sumber Bukti Empiris

Diagnosis ini dibangun di atas metodologi analisis data kualitatif berbasis arsip percakapan riil mahasiswa (*grounded textual analysis*). Demi kepatuhan mutlak terhadap UU Pelindungan Data Pribadi (UU PDP No. 27 Tahun 2022), seluruh berkas log chat berstatus **full ignore** di repositori Git dan hanya disimpan secara lokal/internal untuk kebutuhan audit dan verifikasi. Sumber data mencakup:

1. **Dokumen Sintesis Statistik Bukti:** [`evidence/statistik-chat-evidence.md`](./evidence/statistik-chat-evidence.md) *(Tracked di Git)*  
   - Analisis kuantitatif lonjakan pesan awal semester, frekuensi kata kunci masalah, dan peta beban pimpinan prodi vs mahasiswa tanpa PII.
2. **Berkas Bukti Utama (Arsip Lokal):** [`evidence/chat-civitas-1-si-pjj.txt`](./evidence/chat-civitas-1-si-pjj.txt) *(Full Ignored / Lokal)*  
   - Jumlah Data: 11.987 baris teks  
   - Rentang Waktu: Oktober 2024 hingga September 2026  
   - Karakteristik: Kanal civitas primer yang menampung ribuan mahasiswa SI PJJ lintas angkatan (reguler dan konversi).
3. **Berkas Bukti Pendukung (Arsip Lokal):** [`evidence/chat-civitas-2-si-pjj.txt`](./evidence/chat-civitas-2-si-pjj.txt) *(Full Ignored / Lokal)*  
   - Jumlah Data: 617 baris teks  
   - Rentang Waktu: Oktober 2025 hingga September 2026  
   - Karakteristik: Kanal civitas lanjutan yang menampung interaksi operasional dan semester antara (*short semester*).

Metode identifikasi dilakukan melalui penelusuran kata kunci tematik, analisis garis waktu peristiwa (*timeline reconstruction*), dan kodifikasi permasalahan struktural berulang.

---

## 3. Ringkasan Eksekutif

Hasil penelusuran terhadap lebih dari 12.000 baris rekaman interaksi menunjukkan tiga pola patologi organisasi yang konsisten terjadi di setiap awal semester:

1. **Vakum Panduan Onboarding Maba:** Mahasiswa baru dilepas ke lingkungan perkuliahan siber tanpa bekal panduan navigasi sistem terstruktur. Akibatnya, grup civitas dibanjiri pertanyaan mendasar berulang (SIAKAD vs Edlink, jadwal perkuliahan, kredensial login, skema konversi). Ketiadaan pemandu resmi memaksa pimpinan program studi (Sekretaris Prodi) turun tangan langsung menjawab hal-hal elementer.
2. **Ketiadaan Kanal Informasi Terpadu Terkait KRS:** Transisi pengisian KRS diwarnai kebingungan massal membedakan alur mahasiswa reguler (otomatis) dan konversi (manual). Ketiadaan FAQ terverifikasi dan layanan *helpdesk* terorganisir mengakibatkan kepanikan ketika jadwal kuliah telah berjalan namun status KRS belum muncul di portal pembelajaran.
3. **Anarki Koordinasi Grup Kelas:** Pembagian grup kelas mata kuliah mengalami kekacauan koordinasi terbuka (*open coordination failure*). Tanpa adanya protokol baku atau fasilitasi resmi dari pengurus mahasiswa, mahasiswa secara swadaya membuat tautan grup yang saling bertubrukan, tautan rusak/kedaluwarsa, dan duplikasi ruang kelas. Pihak representasi mahasiswa hanya hadir di grup secara reaktif untuk sosialisasi rekrutmen internal organisasi, bukan menyelesaikan kegentingan logistik akademik mahasiswa.

---

## 4. Analisis Rinci Permasalahan Empiris

### Masalah 1: Ketiadaan Orientasi Terstruktur & Panduan Onboarding Mahasiswa Baru

#### Konteks dan Pola Lapangan
Mahasiswa PJJ UNSIA datang dari berbagai latar belakang: lulusan SMA baru, pekerja profesional, hingga mahasiswa transfer/alih jenjang (konversi). Ketiadaan masa orientasi fungsional dan ketiadaan dokumen *Starter Pack* / *Playbook* resmi mengakibatkan disorientasi massal sesaat setelah mahasiswa dinyatakan diterima.

#### Bukti Empiris Terverifikasi
- **Kebingungan Sistemik Akses Platform Akademik:** Mahasiswa baru tidak memahami ekosistem sistem ganda UNSIA (SIAKAD sebagai portal nilai/administrasi vs Edlink sebagai *Learning Management System* kelas daring). Pertanyaan elementer mengenai kredensial dan aktivasi akun muncul beruntun tanpa ada materi rujukan terpusat:
  - *Bukti chat:* Pertanyaan berulang terkait cara login, kartu ujian, dan akses sistem ([`evidence/chat-civitas-1-si-pjj.txt` Baris 141-143](./evidence/chat-civitas-1-si-pjj.txt#L141-L143)).
  - *Bukti chat:* Ketidaktahuan mekanisme penentuan kelas dan akun kampus ([`evidence/chat-civitas-1-si-pjj.txt` Baris 193](./evidence/chat-civitas-1-si-pjj.txt#L193), [Baris 225](./evidence/chat-civitas-1-si-pjj.txt#L225), [Baris 238](./evidence/chat-civitas-1-si-pjj.txt#L238)).
- **Eskalasi Pertanyaan Sepele ke Tingkat Pimpinan Prodi:** Ketiadaan kurasi informasi oleh HIMA menyebabkan Sekprodi (Ibu Fesa) terpaksa berulang kali masuk ke percakapan grup umum untuk menjelaskan hal-hal administratif mendasar:
  - *Bukti chat:* Penjelasan alur mahasiswa konversi dan penetapan kelas oleh Sekprodi ([`evidence/chat-civitas-1-si-pjj.txt` Baris 283-287](./evidence/chat-civitas-1-si-pjj.txt#L283-L287)).
- **Dependensi pada Solidaritas Informal:** Jawaban atas kebingungan maba bergantung sepenuhnya pada kerelaan mahasiswa senior secara sukarela (*ad-hoc peer answering*), bukan panduan terverifikasi kelembagaan:
  - *Bukti chat:* Mahasiswa saling mengarahkan secara mandiri tanpa acuan resmi ([`evidence/chat-civitas-1-si-pjj.txt` Baris 106-120](./evidence/chat-civitas-1-si-pjj.txt#L106-L120)).

---

### Masalah 2: Drama Pengisian dan Sinkronisasi Rencana Studi (KRS)

#### Konteks dan Pola Lapangan
Pengisian KRS adalah pintu masuk seluruh aktivitas semester. Pada sistem akademik UNSIA, terdapat perbedaan fundamental antara mahasiswa baru reguler (skema paket otomatis dari sistem prodi) dan mahasiswa konversi/lanjutan (pengisian mandiri berbasis mata kuliah ekuivalensi). Ketiadaan mitigasi informasi menyebabkan terulangnya drama ketidakpastian status akademik setiap awal semester ganjil, genap, maupun semester antara.

#### Bukti Empiris Terverifikasi
- **Disinformasi Status Paket vs Mandiri:** Ketidakpahaman massal mengenai apakah mahasiswa harus memilih mata kuliah di SIAKAD atau menunggu paket muncul otomatis:
  - *Bukti chat:* Mahasiswa bingung mengapa tampilan KRS kosong ([`evidence/chat-civitas-1-si-pjj.txt` Baris 106-119](./evidence/chat-civitas-1-si-pjj.txt#L106-L119)).
  - *Bukti chat:* Diskusi panjang membedakan alur mahasiswa konversi yang harus mengajukan secara manual dan reguler yang dipaketkan ([`evidence/chat-civitas-1-si-pjj.txt` Baris 144-176](./evidence/chat-civitas-1-si-pjj.txt#L144-L176)).
- **Friksi Menjelang Hari Pertama Perkuliahan (H-1 Kuliah):** Siklus semester dimulai namun mata kuliah belum tersinkronisasi dari SIAKAD ke Edlink, memicu kepanikan mahasiswa apakah mereka terdaftar di kelas atau mengalami kendala keuangan:
  - *Bukti chat:* Keluhan Edlink masih kosong menjelang kuliah perdana ([`evidence/chat-civitas-1-si-pjj.txt` Baris 127-151](./evidence/chat-civitas-1-si-pjj.txt#L127-L151)).
- **Pengulangan Siklus pada Semester Antara (Agustus 2026):** Pola drama yang sama persis terulang pada tahun-tahun berikutnya, menunjukkan ketiadaan memori institusional:
  - *Bukti chat:* Kebingungan KRS semester antara, status kelas belum muncul, dan pertanyaan teknis berulang di grup civitas 2 ([`evidence/chat-civitas-2-si-pjj.txt` Baris 440-443](./evidence/chat-civitas-2-si-pjj.txt#L440-L443), [Baris 545](./evidence/chat-civitas-2-si-pjj.txt#L545), [Baris 560](./evidence/chat-civitas-2-si-pjj.txt#L560)).

---

### Masalah 3: Kekacauan Koordinasi Pembagian Grup Kelas Mata Kuliah

#### Kronologi Krisis Terbuka: 22 Oktober 2024 (Pukul 14.00 – 17.00 WIB)
Peristiwa pembagian grup kelas pada 22 Oktober 2024 dalam berkas [`evidence/chat-civitas-1-si-pjj.txt`](./evidence/chat-civitas-1-si-pjj.txt) (baris 347 hingga 1.100+) memberikan gambaran paling telanjang mengenai ketiadaan kepemimpinan operasional mahasiswa di ruang siber.

| Rentang Baris Teks | Aktor Lapangan | Peristiwa / Dinamika Percakapan | Makna Diagnosis |
|---|---|---|---|
| **Baris 347 – 420** | Inisiator Mahasiswa Mandiri | Mahasiswa mulai membagikan tautan grup WA mata kuliah satu per satu secara tidak teratur. Tautan berserakan di linimasa obrolan. | Tidak ada wadah repositori tunggal terkurasi dari organisasi mahasiswa. |
| **Baris 421 – 650** | Berbagai Mahasiswa | Format pesan berantai (*copy-paste chain message*) mulai digunakan. Mahasiswa saling menimpa daftar (*list overwriting*) sehingga tautan yang telah ditambahkan sebelumnya terhapus. | Inefisiensi tata kelola informasi berbasis obrolan spontan; ketiadaan platform bersama. |
| **Baris 651 – 740** | Komunitas Civitas | Muncul grup ganda untuk satu mata kuliah yang sama (misal: 2 grup terpisah untuk `SI101 Pengantar Teknologi Informasi`). Mahasiswa bingung menentukan grup resmi. | Fragmentasi kelas; potensi mahasiswa tertinggal informasi tugas dan instruksi dosen. |
| **Baris 745 – 760** | Mahasiswa & Civitas | Mahasiswa mempertanyakan legitimasi grup dan menyuarakan kekhawatiran keamanan (potensi masuknya nomor asing/penipu akibat tautan publik tak terverifikasi). | Kerentanan privasi dan keamanan digital civitas kampus PJJ. |
| **Baris 830 – 850** | Mahasiswa Kritis (Ibrahim, dkk.) | Mahasiswa menyerukan usulan standardisasi nama grup (misal: `2024SI103`) dan melontarkan pertanyaan retoris krusial: *"Siapa yang seharusnya bertanggung jawab mengoordinasikan ini?"* | Frustrasi civitas terhadap ketiadaan koordinator resmi; kerinduan atas kepemimpinan HIMA. |
| **Baris 950 – 1.080** | Pengurus HIMA | Perwakilan HIMA hadir di grup civitas setelah krisis berlangsung berjam-jam, namun **hanya membagikan pengumuman pendaftaran rekrutmen pengurus HIMA**, tanpa memedulikan kepanikan grup kelas yang sedang memuncak. | **Pemisahan total (*total disconnect*)** antara agenda internal organisasi HIMA dengan kebutuhan darurat mahasiswa di lapangan. |

#### Bukti Kutipan Langsung Lapangan
- **Pertanyaan Pertanggungjawaban:**
  - *"Ini siapa yang bikin list? Ada koordinator resminya ngga?"* ([`evidence/chat-civitas-1-si-pjj.txt` Baris 844, 893](./evidence/chat-civitas-1-si-pjj.txt#L844)).
- **Upaya Standardisasi yang Diabaikan:**
  - Inisiatif mahasiswa mengusulkan pola penamaan grup teratur agar mudah dilacak ([`evidence/chat-civitas-1-si-pjj.txt` Baris 836](./evidence/chat-civitas-1-si-pjj.txt#L836)), namun lenyap tertutup arus pesan berantai baru.
- **Ketidakhadiran Empati Organisasi:**
  - Sosialisasi rekrutmen organisasi masuk di tengah kebingungan tanpa respons atas masalah kelas ([`evidence/chat-civitas-1-si-pjj.txt` Baris 961, 1073](./evidence/chat-civitas-1-si-pjj.txt#L961)).

---

## 5. Matriks Temuan Empiris Awal Semester

Berikut rekapitulasi temuan empiris awal semester terintegrasi dengan kode identifikasi:

| Kode Temuan | Deskripsi Temuan Faktual | Dampak Terhadap Civitas | Rujukan Bukti Empiris |
|---|---|---|---|
| **D-SEM-01** | Ketiadaan panduan orientasi resmi (*Student Starter Pack* / FAQ Terpadu) bagi mahasiswa baru SI PJJ. | Maba mengalami disorientasi sistemik; grup civitas dibanjiri pertanyaan mendasar berulang. | [`chat-civitas-1` Baris 141-143, 193](./evidence/chat-civitas-1-si-pjj.txt#L141-L143) |
| **D-SEM-02** | Beban klarifikasi teknis elementer tereskalasi langsung ke pimpinan program studi (Sekprodi). | Waktu strategis pimpinan prodi tersedot untuk menjawab pertanyaan berulang yang seharusnya diselesaikan oleh perangkat mahasiswa. | [`chat-civitas-1` Baris 283-287](./evidence/chat-civitas-1-si-pjj.txt#L283-L287) |
| **D-SEM-03** | Jawaban atas pertanyaan maba bergantung pada inisiatif acak rekan mahasiswa (*ad-hoc peer advice*). | Risiko disinformasi tinggi karena jawaban mahasiswa senior belum tentu terverifikasi regulasi prodi terbaru. | [`chat-civitas-1` Baris 106-120](./evidence/chat-civitas-1-si-pjj.txt#L106-L120) |
| **D-SEM-04** | Kebingungan masif membedakan alur pengisian KRS antara jalur reguler (paket) dan jalur konversi (mandiri). | Mahasiswa panik menghadapi portal SIAKAD kosong dan ketidakjelasan status registrasi mata kuliah. | [`chat-civitas-1` Baris 106-119, 144-176](./evidence/chat-civitas-1-si-pjj.txt#L106-L119) |
| **D-SEM-05** | Keterlambatan sinkronisasi data SIAKAD ke Edlink pada masa kritis H-1 perkuliahan tanpa kanal klarifikasi terpusat. | Mahasiswa cemas tertinggal perkuliahan perdana; spekulasi liar mengenai status pembayaran dan kendala akun. | [`chat-civitas-1` Baris 127-151](./evidence/chat-civitas-1-si-pjj.txt#L127-L151) |
| **D-SEM-06** | Pola kebingungan KRS berulang secara siklikal pada semester ganjil, genap, hingga semester antara. | Menunjukkan ketiadaan memori institusional dan tidak berjalannya fungsi evaluasi tata kelola awal semester. | [`chat-civitas-2` Baris 440-443, 545, 560](./evidence/chat-civitas-2-si-pjj.txt#L440-L443) |
| **D-SEM-07** | Pembagian grup kelas mata kuliah mengandalkan pesan berantai WhatsApp swadaya tanpa kurasi resmi. | Pesan tertimpa (*overwritten*), tautan kedaluwarsa (*expired*), dan hilangnya tautan mata kuliah tertentu. | [`chat-civitas-1` Baris 347-650](./evidence/chat-civitas-1-si-pjj.txt#L347-L650) |
| **D-SEM-08** | Terjadinya duplikasi grup kelas (*split classes*) untuk mata kuliah yang sama akibat inisiatif sporadis. | Mahasiswa terpecah ke dalam ruang komunikasi berbeda; instruksi dosen dan tugas kelompok terfragmentasi. | [`chat-civitas-1` Baris 651-760](./evidence/chat-civitas-1-si-pjj.txt#L651-L760) |
| **D-SEM-09** | Pemisahan (*disconnect*) kepedulian HIMA terhadap krisis logistik akademik mahasiswa di grup civitas. | HIMA hadir mempromosikan rekrutmen internal saat civitas mengalami kebuntuan koordinasi kelas, memicu sinisme publik. | [`chat-civitas-1` Baris 950-1080](./evidence/chat-civitas-1-si-pjj.txt#L950-L1080) |

---

## 6. Hipotesis Akar Penyebab (Root Cause Hypotheses)

Berdasarkan temuan empiris di atas, dirumuskan hipotesis struktural mengenai penyebab mendasar dari kegagalan berulang ini:

| Kode Hipotesis | Aspek Tata Kelola | Rumusan Hipotesis Akar Masalah |
|---|---|---|
| **H-SEM-01** | *Knowledge Management* | HIMA tidak memiliki basis pengetahuan terdokumentasi (*knowledge base*) atau memori institusi antar-periode kepengurusan, sehingga setiap generasi mahasiswa baru dipaksa mengulang siklus kesalahan dan kebingungan yang sama tanpa ada akumulasi perbaikan sistemik. |
| **H-SEM-02** | *Service Mindset & Prioritas* | Terdapat distorsi orientasi nilai kepengurusan organisasi: HIMA memprioritaskan kegiatan seremonial, rekrutmen internal, dan eksistensi struktural di atas tanggung jawab mendasar melayani kebutuhan logistik akademik dan kenyamanan studi civitas mahasiswa (*service over ceremony* belum terwujud). |
| **H-SEM-03** | *Operational Protocols* | Tidak adanya Standar Operasional Prosedur (SOP) atau protokol terpadu antara HIMA, Program Studi, dan Komti (Komisaris Tingkat) dalam mengelola siklus rutin awal semester (SOP Onboarding, SOP Helpdesk KRS, SOP Pembuatan & Verifikasi Direktori Grup Kelas). |
| **H-SEM-04** | *Infrastructure & Tools* | Pengelolaan informasi mahasiswa PJJ masih disandarkan pada pola komunikasi analog/spontan (pesan berantai teks obrolan biasa) dan belum memanfaatkan repositori digital terstruktur (portal tautan tunggal terverifikasi, direktori Notion/Docs/Portal Web resmi). |
| **H-SEM-05** | *Proactive Coordination* | HIMA bersikap pasif-reaktif (menunggu masalah meledak di grup civitas) alih-alih mengambil inisiatif koordinatif terencana H-14 sebelum semester dimulai. |

---

## 7. Pernyataan Diagnosis dan Batasan

### Critical Finding
> **Kondisi Kritis Organisasi:**  
> Tiga pekerjaan rutin awal semester (onboarding mahasiswa baru, mitigasi KRS, dan koordinasi grup kelas) adalah **kebutuhan paling vital sekaligus pengujian paling nyata atas relevansi keberadaan HIMA di mata mahasiswa PJJ**.  
> Kegagalan HIMA hadir mengantisipasi dan memfasilitasi ketiga kebutuhan ini bukan sekadar masalah teknis operasional, melainkan **kegagalan legitimasi kelembagaan**. Ketika mahasiswa merasa berjuang sendirian (*abandoned*) di tengah kebingungan sistem kampus daring, HIMA kehilangan alasan moral dan fungsional keberadaannya.

### Diagnosis Statement
> **Pernyataan Diagnosis:**  
> HIMA Sistem Informasi PJJ UNSIA mengalami **disfungsi layanan operasional awal semester** yang disebabkan oleh ketiadaan sistem *knowledge management*, ketiadaan protokol kemitraan akademik dengan program studi, serta pemisahan (*disconnect*) antara agenda elitis internal organisasi dengan realitas kebutuhan harian mahasiswa. Akibatnya, mahasiswa dibiarkan menanggung biaya kebingungan mental dan akademis secara mandiri pada setiap awal semester.

### Penegasan Batasan (*Non-Solution Disclaimer*)
Dokumen ini secara tegas membatasi diri pada pemetaan realitas empiris lapangan dan formulasi diagnosis akar masalah. Dokumen ini:
- **TIDAK** merancang bentuk panduan maba (*starter pack*).
- **TIDAK** membentuk panitia *helpdesk* KRS.
- **TIDAK** membuat direktori tautan grup kelas.
- **TIDAK** merevisi AD/ART atau struktur kabinet.

Seluruh rancangan intervensi, perbaikan proses bisnis, dan instrumen tata kelola baru akan dirumuskan secara terpisah dan bertahap pada fase berikutnya (Fase 02 dan seterusnya) dengan mengacu pada prinsip-prinsip piagam reformasi.

---
*Dokumen ini merupakan bagian tak terpisahkan dari seri dokumen diagnosis reformasi tata kelola HIMA Sistem Informasi PJJ UNSIA.*
