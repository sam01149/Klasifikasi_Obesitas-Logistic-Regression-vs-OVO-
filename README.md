# Model Prediksi Level Obesitas

## Objektif
1. Membangun model klasifikasi untuk memprediksi level obesitas berdasarkan fitur demografis dan gaya hidup.
2. Membandingkan performa pendekatan klasifikasi Logistic Regression dengan strategi One-vs-All (OVA) dan One-vs-One (OVO).
3. Menentukan pendekatan model yang memberikan akurasi terbaik pada data uji.

Dataset diambil dari: [Obesity-level-prediction-dataset.csv](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/GkDzb7bWrtvGXdPOfk6CIg/Obesity-level-prediction-dataset.csv)

## Kesimpulan

1. Model Logistic Regression berhasil digunakan untuk klasifikasi level obesitas pada dataset ini.
2. Berdasarkan hasil evaluasi, strategi **OVO** menunjukkan akurasi yang lebih tinggi dibandingkan **OVA**.
3. Dengan demikian, untuk kasus pada notebook ini, pendekatan **One-vs-One (OVO)** lebih direkomendasikan sebagai model akhir.

Catatan: performa model masih bisa ditingkatkan melalui tuning hyperparameter, validasi silang, dan eksplorasi model klasifikasi lain.
