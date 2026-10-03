# 2418048_DataCleansing
Beberapa tahapan utama yang saya lakukan: 

1. Standardisasi Format ID & Nama: Menyeragamkan format ID pasien secara berurutan dan unik (misal: P-001) serta merapikan penulisan nama. 
2. Penanganan Missing Values: Melakukan imputasi usia berdasarkan kecocokan nama pasien serta mengisi kolom kategori dengan nilai modus/median yang relevan.
3. Validasi & Transformasi Rentang Nilai: Memperbaiki batas skor Tingkat Stres Awal dan Skor Kecemasan Akhir ke skala valid (0–100) serta mengonversinya ke dalam kategori (Rendah, Sedang, Tinggi). 
4. Pembersihan Data Teks & Biaya: Menghilangkan karakter khusus pada persentase kehadiran dan menyeragamkan satuan mata uang (Rupiah/IDR).
5. Logika Bisnis & Pemetaan Rekomendasi: Memprediksi Status Kelulusan yang kosong dan memetakan Rekomendasi Lanjutan (Pemulihan, Konseling Lanjutan, atau Rujukan Psikiater) secara otomatis. 
