# 📊 Sentiment Analysis Mobile JKN Reviews

Analisis sentimen ulasan pengguna aplikasi **Mobile JKN** di Google Play Store. Proyek ini bertujuan mengukur perasaan pengguna—positif, negatif, atau netral—terhadap pengalaman mereka menggunakan aplikasi Mobile JKN. Proyek ini dibuat untuk memenuhi tugas jurnal SNATIA.

## 📝 Deskripsi Proyek

Dalam proyek ini, kami membangun pipeline NLP yang meliputi:

* **Teknik *text preprocessing*** (lowercasing, stopword removal, stemming).
* **Ekstraksi fitur** menggunakan **TF-IDF Vectorizer**.
* **Penanganan imbalanced data** dengan **SMOTE**.
* **Klasifikasi sentimen** dengan tiga model:

  * Multinomial Naive Bayes
  * Logistic Regression
  * Support Vector Machine (SVM)
* **Optimasi** setiap model menggunakan **GridSearchCV** untuk menemukan kombinasi parameter terbaik.

## 📁 Dataset

* **Sumber:** [Kaggle – 10K Dataset Sentiment Mobile JKN](https://www.kaggle.com/datasets/diahmariatululya/10k-dataset-sentiment-mobile-jkn)
* **Total sampel:** 10.000 ulasan
* **Label sentimen:** `positive`, `negative`, `neutral`
* **File CSV:** `sentimen_mobileJKN.csv`

## 🛠️ Metodologi

1. **Preprocessing teks**
2. **Vectorization**
3. **SMOTE**
4. **GridSearchCV**
5. **Pelatihan & Evaluasi**

## 📊 Hasil & Visualisasi

* **Confusion Matrix**
* **Pie Chart**

## 📚 Teknologi & Library

* Python 3
* Pandas
* Scikit-learn
* Imbalanced-learn (SMOTE)
* Matplotlib & Seaborn
* scikit-learn TF-IDF Vectorizer

## 🙋‍♀️ Author
Rahelita Pasaribu - Mahasiswa Informatika, Universitas Udayana  
Proyek ini disusun untuk Seminar Nasional Teknologi dan Informatika (SNATIA) 2025


> This project was created to fulfill one of the requirements for graduation from the computer science major.
