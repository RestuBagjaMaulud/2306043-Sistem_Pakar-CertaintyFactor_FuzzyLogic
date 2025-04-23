# Certainty Factor & Fuzzy Logic
## Certainty Factor (CF)
Certainty Factor adalah metode yang digunakan untuk merepresentasikan tingkat keyakinan (confidence level) terhadap suatu fakta atau aturan dalam sistem pakar. Nilai CF berada dalam rentang -1 hingga 1:
- 1 menunjukkan keyakinan penuh terhadap suatu fakta (benar 100%)
- 0 menunjukkan ketidakpastian (netral/tidak tahu)
- -1 menunjukkan ketidakyakinan penuh (fakta salah 100%)

CF banyak digunakan dalam sistem pakar berbasis aturan (rule-based expert system) untuk menggabungkan berbagai sumber informasi yang tidak pasti.

Contoh: Jika gejala A terdeteksi dan aturan mengatakan "jika A maka kemungkinan penyakit X dengan CF = 0.7", maka sistem akan menganggap ada 70% keyakinan bahwa pasien menderita penyakit X.

## Fuzzy Logic
Fuzzy Logic adalah logika yang digunakan untuk menangani konsep "kabur" atau tidak pasti yang tidak bisa dipecahkan dengan logika biner (true/false). Dalam fuzzy logic, nilai kebenaran dapat berada antara 0 dan 1, mencerminkan derajat keanggotaan suatu nilai dalam sebuah himpunan fuzzy.

Contoh klasik: Dalam logika biner, suhu 29°C bisa dikategorikan sebagai "tidak panas", sedangkan dalam fuzzy logic, suhu 29°C bisa termasuk dalam kategori "sedikit panas" dengan derajat keanggotaan 0.6, misalnya.

Fuzzy Logic sering digunakan dalam sistem kontrol dan kecerdasan buatan (AI), terutama ketika data atau kondisi bersifat subjektif atau tidak pasti.
