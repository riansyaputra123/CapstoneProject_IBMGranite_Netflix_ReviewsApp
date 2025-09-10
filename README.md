# 📌 Sentiment Analysis and User Feedback Insights on Netflix App Reviews  

## Project Overview  
Proyek ini bertujuan untuk menganalisis ulasan pengguna aplikasi Netflix dengan pendekatan **analisis sentimen** dan **ringkasan berbasis AI**.  
Dataset berisi **9.466 ulasan** dari Google Play Store, yang kemudian diproses untuk:  
- Mengklasifikasikan sentimen ke dalam **Positive, Negative, dan Mixed**.  
- Melakukan **ringkasan bulanan** untuk mengidentifikasi tren permasalahan dan kepuasan pengguna.  
- Memberikan **insight data-driven** untuk rekomendasi peningkatan layanan.  

## Raw Dataset Link  
Dataset dapat diakses melalui Kaggle pada tautan berikut:  
🔗 [Netflix App Reviews Dataset (Kaggle)]([https://www.kaggle.com/](https://www.kaggle.com/datasets/ashishkumarak/netflix-reviews-playstore-daily-updated))  
*(ganti dengan link dataset asli)*  

## Insight & Findings  
Berdasarkan hasil analisis:  
- **Mayoritas sentimen pengguna bersifat negatif**, didominasi keluhan mengenai **kenaikan harga, iklan, penghapusan konten, masalah teknis, dan kebijakan screen-sharing**.  
- **Rata-rata skor aplikasi cenderung menurun** seiring waktu, menunjukkan adanya penurunan kepuasan pengguna.  
- **Positive reviews** masih muncul, terutama terkait dengan kualitas streaming dan pengalaman antarmuka.  
- **Mixed reviews** relatif sedikit, tetapi umumnya terkait pengalaman yang bercampur antara kelebihan (konten menarik) dan kekurangan (bug teknis).  

## AI Explanation  
Analisis ini menggunakan **IBM Granite 13B Instruct**, sebuah model AI yang mampu melakukan:  
- **Klasifikasi Sentimen** → Mengelompokkan ulasan ke dalam kategori **Positive, Negative, dan Mixed**.  
- **Ringkasan Bulanan** → Menghasilkan kesimpulan singkat mengenai masalah utama yang sering dikeluhkan pengguna tiap bulan.  

Penggunaan IBM Granite membantu menghasilkan **analisis yang konsisten, cepat, dan skalabel**, serta mempermudah dalam mengekstraksi **informasi bernilai** dari ribuan ulasan yang tidak terstruktur.  
