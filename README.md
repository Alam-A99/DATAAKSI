## Daftar Variabel
1. **Government Spending** 
- *Arab Saudi* (K SAR Million, Q1)
- *China* (K Hundred Million)
- *Indonesia* (K IDR Billion, Q1)
- *Iran* (K IRR Billion)
- *Korsel* (K KRW Billion, Q1)
2. **Industrial Production (%)**
3. **GDP Per Capita (K USD)**
4. **GGROWTH (%)**
5. **EDUofGdp (%)**
6. **HEALTHofGDP (%)**
7. **Unemployment (%)**

| Kolom | Kode      | Keterangan                         | Penjelasan Singkat                                                                 |
|:-----:|:----------|:-----------------------------------|:------------------------------------------------------------------------------------|
| A     | CC        | Control of Corruption              | Indeks persepsi korupsi dalam pemerintahan dan sektor publik                       |
| B     | GE        | Government Effectiveness           | Efektivitas kualitas pelayanan publik dan kebijakan pemerintah                     |
| C     | PV        | Political Stability and Violence   | Stabilitas politik dan tidak adanya kekerasan/terorisme                            |
| D     | RL        | Rule of Law                        | Tingkat kepatuhan hukum, kualitas peradilan, dan penegakan hukum                   |
| E     | RQ        | Regulatory Quality                 | Kemampuan pemerintah merumuskan dan menerapkan regulasi yang baik                  |
| F     | VA        | Voice and Accountability           | Tingkat kebebasan warga untuk menyuarakan pendapat dan keterlibatan politik        |
| G     | GSPEND    | Government Spending                | Pengeluaran pemerintah dalam mata uang lokal (dalam miliar atau juta satuan lokal) |
| H     | INDS_PROD | Industrial Production              | Pertumbuhan produksi industri (dalam persen)                                       |
| I     | GDPpp     | GDP per capita (PPP)               | Produk Domestik Bruto per kapita berdasarkan daya beli                            |
| J     | GROWTH    | Economic Growth                    | Pertumbuhan ekonomi tahunan (dalam persen)                                         |
| K     | EDUofGdp  | Education Expenditure (% of GDP)   | Pengeluaran pendidikan sebagai persentase dari PDB                                 |
| L     | HEALTofGDP| Health Expenditure (% of GDP)      | Pengeluaran kesehatan sebagai persentase dari PDB                                  |
| M     | UNEMPL    | Unemployment Rate                  | Tingkat pengangguran (dalam persen)                                                |

## newDATASET
## 📊 Penjelasan Variabel Dataset

| Kolom | Nama Variabel | Deskripsi                                               | Keterangan                                  |
|-------|----------------|----------------------------------------------------------|---------------------------------------------|
| Negara | Negara         | Nama negara dalam observasi                             | Negara yang diamati dalam dataset          |
| Tahun  | Tahun          | Tahun data diambil                                      | Tahun pengumpulan data                     |
| A      | CC             | Control of Corruption                                   | Indikator pengendalian korupsi             |
| B      | GE             | Government Effectiveness                                | Efektivitas pemerintahan                    |
| C      | PV             | Political Stability and Absence of Violence             | Stabilitas politik dan absennya kekerasan   |
| D      | RL             | Rule of Law                                             | Ketaatan terhadap hukum                     |
| E      | RQ             | Regulatory Quality                                      | Kualitas regulasi dan kebijakan            |
| F      | VA             | Voice and Accountability                                | Akses terhadap partisipasi politik         |
| G      | AVR_QI         | Rata-rata indikator kualitas institusi (A-F)            | Rata-rata nilai indikator A-F              |
| H      | EDUofGdp       | Pengeluaran Pendidikan terhadap PDB (%)                 | Rasio pengeluaran pendidikan terhadap PDB  |
| I      | HEALTofGDP     | Pengeluaran Kesehatan terhadap PDB (%)                  | Rasio pengeluaran kesehatan terhadap PDB   |
| J      | GSPEND         | Pengeluaran Pemerintah (dalam mata uang lokal)          | Total pengeluaran pemerintah dalam mata uang lokal |
| K      | GSP (mUSD)     | Pengeluaran Pemerintah dalam juta USD                   | Total pengeluaran pemerintah dalam juta USD|
| L      | INDS_PROD      | Pertumbuhan Produksi Industri                           | Laju pertumbuhan sektor industri           |
| M      | GDPpp          | PDB per kapita dalam Purchasing Power Parity (PPP)      | PDB per kapita disesuaikan dengan PPP      |
| N      | GROWTH         | Laju Pertumbuhan Ekonomi (%)                            | Laju pertumbuhan ekonomi tahunan           |
| O      | UNEMPL         | Tingkat Pengangguran (%)                                | Persentase pengangguran dalam populasi     |
| P      | POV            | Tingkat Kemiskinan (%)                                  | Persentase populasi yang hidup di bawah garis kemiskinan |


## APBD Realisasi Kota Makassar (dalam Miliar)
| AKUN                                                                 | Kode     |
|----------------------------------------------------------------------|----------|
| Pendapatan                                                          | PDtot    |
| PAD                                                                 | PAD      |
| Pajak Daerah                                                        | PjD      |
| Retribusi Daerah                                                    | RtD      |
| Hasil Pengelolaan Kekayaan Daerah yang Dipisahkan                   | HsKD     |
| Lain-Lain PAD yang Sah                                              | LainPAD  |
| TKDD                                                                | TKDD     |
| Pendapatan Transfer Pemerintah Pusat                                | PDTrf    |
| Pendapatan Transfer Antar Daerah                                    | PDtrAD   |
| Dana Perimbangan                                                    | 0        |
| DBH                                                                 | 0        |
| DAU                                                                 | 0        |
| DAK                                                                 | 0        |
| Pendapatan Lainnya                                                  | PDLain1  |
| Hibah                                                               | Hbh      |
| Lain-lain Pendapatan Sesuai dengan Ketentuan Peraturan Perundang-Undangan | PDLain2  |
| Bagi Hasil Provinsi atau Pemda Lain                                 | BgHProv  |
| Dana Penyesuaian dan Otsus                                          | Otsus    |
| Bantuan Keuangan                                                    | BtKeu    |
| Pendapatan Lainnya                                                  | PDLain3  |
| Belanja                                                             | Belanja  |
| Belanja Tidak Langsung                                              | BTL      |
| Belanja Pegawai Tidak Langsung                                      | BPgTL    |
| Belanja Langsung                                                    | BL       |
| Belanja Bunga                                                       | BBung    |
| Belanja Subsidi                                                     | Bsub     |
| Belanja Pegawai Langsung                                            | BPgL     |
| Belanja Barang Jasa                                                 | BBrJasa  |
| Belanja Daerah                                                      | BlDa     |
| Belanja Pegawai                                                     | BPeg     |
| Belanja Modal                                                       | Bmod     |
| Belanja Lainnya                                                     | Blain    |
| Belanja Bagi Hasil                                                  | BBH      |
| Belanja Hibah                                                       | Bhibah   |
| Belanja Bantuan Sosial                                              | BBSos    |
| Belanja Bantuan Keuangan                                            | BBKeu    |
| Belanja Tidak Terduga                                               | BTT      |
| Pembiayaan Daerah                                                   | PebDa    |
| Penerimaan Pembiayaan                                               | PenBy    |
| SiLPA TA Sebelumnya                                                 | SilPA    |
| Pencairan Dana Cadangan                                             | DnCad    |
| Penjualan Kekayaan Daerah yang Dipisahkan                           | JKyD     |
| Penerimaan Pinjaman Daerah                                          | PnPjDa   |
| Penerimaan Kembali Pemberian Pinjaman                               | PeKemP   |
| Penerimaan Pembiayaan Lainnya Sesuai dengan Ketentuan Peraturan Perundang-Undangan | PePbyLain |
| Pengeluaran Pembiayaan                                              | PengBiaya|
| Pembentukan Dana Cadangan                                           | PemDanCad|
| Penyertaan Modal                                                    | PyrtMo   |
| Pembayaran Pokok Utang                                              | PbPoUtang|


## Deskripsi Variabel Dataset

| Kode | Nama Variabel | Satuan |
|-----|--------------|--------|
| Provinsi | Provinsi | - |
| Tahun | Tahun | Tahun |
| IPM | Indeks Pembangunan Manusia | Indeks |
| KMSKN | Tingkat Kemiskinan | % |
| PMSKN | Penduduk Miskin | Ribu Jiwa |
| PEGR | Tingkat Pengangguran | % |
| PEGRjw | Jumlah Pengangguran | Jiwa |
| PE | Pertumbuhan Ekonomi | % |
| PADm | Pendapatan Asli Daerah | Miliar Rupiah |
| TPENDm | Total Pendapatan Daerah | Miliar Rupiah |
| BEKOm | Belanja Ekonomi | Miliar Rupiah |
| BKESm | Belanja Kesehatan | Miliar Rupiah |
| BPENm | Belanja Pendidikan | Miliar Rupiah |


