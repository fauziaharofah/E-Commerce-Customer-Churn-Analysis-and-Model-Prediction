This project aimed to identify high-risk customers likely to discontinue using the service by analyzing the factors influencing their decisions. By utilizing machine learning models, effective retention strategies were designed to enhance customer loyalty. The analysis provided valuable insights for the company, helping to optimize services and reduce churn rates. 

📖 Pendahuluan

Di era digital yang terus berkembang, e-commerce telah menjadi bagian integral dari cara bisnis beroperasi. Namun, dengan pertumbuhan pesat ini, tantangan dalam memahami dan mempertahankan konsumen semakin kompleks. Churn, atau kehilangan konsumen, menjadi isu krusial yang harus diatasi oleh setiap perusahaan e-commerce. Dokumentasi ini bertujuan untuk menjelaskan tujuan, pendekatan, dan metrik yang digunakan dalam analisis churn konsumen.

🌐 Apa itu E-commerce?

E-commerce adalah proses jual beli barang dan layanan melalui internet, yang memanfaatkan platform digital untuk memudahkan transaksi antara individu dan perusahaan. Pertumbuhan pesat dalam sektor ini menjadikannya peluang usaha yang menguntungkan.

📊 Latar Belakang

Menurut IBM, e-commerce telah mengalami transformasi signifikan sejak tahun 1990, menjadi ekosistem kompleks yang mendorong pertumbuhan ekonomi global. Dengan pemanfaatan teknologi, khususnya machine learning, perusahaan berkomitmen untuk menganalisis perilaku konsumen dan mengidentifikasi pola-pola churn.

📊 Gambaran Proyek

Proyek ini berfokus pada analisis churn konsumen menggunakan teknik machine learning. Dengan mengidentifikasi faktor-faktor yang berkontribusi pada churn, kami bertujuan untuk membantu bisnis e-commerce meningkatkan strategi retensi.

🎯 Tujuan Analisis

Identifikasi konsumen berisiko churn:m data untuk mengetahui faktor-faktor yang mempengaruhi konsumen yang memiliki risiko tinggi untuk berhenti menggunakan layanan.

Optimalkan strategi retensi: merancang model machine learning yang efektif untuk mempertahankan konsumen.

🛠️ Pendekatan Analisis

Pengumpulan data: mengumpulkan data relevan, termasuk demografi, preferensi, dan aktivitas transaksi konsumen.

Model klasifikasi: menggunakan algoritma machine learning untuk membangun model yang memprediksi kemungkinan churn berdasarkan pola perilaku konsumen.

Evaluasi metrik:

Churn Rate: menghitung tingkat churn untuk memahami proporsi konsumen yang berhenti menggunakan layanan.

F2-Score: mengoptimalkan pengelolaan churn dengan fokus pada recall, memastikan identifikasi konsumen berisiko tinggi yang lebih akurat.

📈 Metrik Evaluasi

Biaya churn:

Cost of Acquisition (CAC): biaya untuk mendapatkan konsumen baru.

Cost of Retention (CRC): biaya untuk mempertahankan konsumen yang ada. Penelitian menunjukkan bahwa mempertahankan konsumen lebih efisien dibandingkan akuisisi.

Jenis kesalahan dalam analisis:

Type 1 Error (False Positive): mengklasifikasikan konsumen loyal sebagai churn.

Type 2 Error (False Negative): gagal mengidentifikasi konsumen yang churn, yang lebih berdampak pada profitabilitas.

📊 Analisis Data

Kami mengumpulkan dan menganalisis data, termasuk demografi konsumen, riwayat transaksi, dan umpan balik. Faktor-faktor kunci yang mempengaruhi churn diidentifikasi melalui analisis statistik, dan model prediktif dikembangkan untuk meramalkan kemungkinan churn.

📈 Hasil

image
📝 Kesimpulan dan Rekomendasi

Kesimpulan definisi churn:

Analisis menunjukkan bahwa churn tidak hanya dipengaruhi oleh demografi, preferensi, atau keterlibatan, tetapi dapat dilacak melalui indikator perilaku tertentu seperti:

• Perubahan status akun

• Logout dari aplikasi

• Uninstall aplikasi

• Berhenti dari keanggotaan

Rekomendasi untuk bisnis:

Untuk menangani faktor-faktor churn yang teridentifikasi dan meningkatkan retensi, kami merekomendasikan hal-hal berikut:

Program pelatihan: pelatihan rutin untuk semua tim tentang analisis data dan machine learning.

Pelaporan terintegrasi: mengembangkan sistem pelaporan yang lebih kohesif dengan Business Intelligence (BI) untuk visualisasi data secara real-time.

Model machine learning yang lebih lanjut: memperluas cakupan aplikasi machine learning ke area bisnis lain seperti perkiraan penjualan dan manajemen inventaris.

Kemitraan: bekerjasama dengan perusahaan analisis data untuk mendapatkan informasi yang lebih mendalam tentang perilaku konsumen.

🛠️ Performa Model

Langkah-langkah yang diambil:

• Fitur engineering: mengatasi missing value, menggunakan OneHotEncoder untuk fitur kategorikal, dan menerapkan Random Over Sampling (ROS) untuk imbalanced data.

• Evaluasi model: melakukan tuning hyperparameter, memastikan kinerja yang kuat melalui teknik cross-validation.

Model terbaik:

Model LightGBM menunjukkan kemampuan prediksi yang sangat baik, dengan F2 Score meningkat dari 0.93 menjadi 0.94 setelah proses tuning. Biaya kesalahan klasifikasi model adalah yang terendah di antara model lainnya, menunjukkan efisiensi tinggi dalam mendeteksi konsumen yang berisiko churn.

🔮 Rekomendasi Modeling Selanjutnya

Beberapa langkah yang dapat dilakukan untuk pengembangan lebih lanjut meliputi:

• Eksplorasi hyperparameter: menggunakan teknik seperti Bayesian Optimization untuk menemukan parameter terbaik.

• Cross validation yang kompleks: menerapkan stratified k-fold untuk mengurangi kemungkinan overfitting.

• Fitur baru: mempertimbangkan fitur tambahan yang dapat memberikan informasi lebih tentang perilaku konsumen.

• Pemantauan kinerja model: mengimplementasikan sistem untuk memantau kinerja model secara berkala dan mendeteksi penurunan kinerja dengan cepat.

Streamlit:

Dalam konteks e-commerce, memahami perilaku konsumen dan memprediksi kemungkinan churn merupakan langkah penting untuk meningkatkan retensi. Dengan menggunakan Streamlit, penyusun membuat aplikasi sederhana namun cukup efektif, yang memungkinkan user untuk melakukan prediksi churn untuk satu konsumen dengan memasukkan data secara manual. Selain itu, aplikasi ini juga mendukung pengunggahan file CSV, sehingga user dapat menganalisis data churn dari banyak konsumen sekaligus. Dengan demikian, streamlit ini dapat menjadi alat yang berguna untuk membantu perusahaan dalam merumuskan strategi pencegahan churn dengan lebih baik. Streamlit dapat diakses pada file "streamlit_finpro.rar" pada GitHub. Data dummy untuk mencoba bulk prediction dan juga data dari hasul bulk prediction dapat diakses pada file "data_streamlit.rar".

Visualisasi Interaktif:

Visualisasi menggunakan Tableau dapat diakses melalui tautan berikut: [Lihat visualisasi di Tableau.](https://public.tableau.com/app/profile/elisa.hariyanti/viz/E-CommerceCustomerChurn-BetaGroup/Home?publish=yes)
