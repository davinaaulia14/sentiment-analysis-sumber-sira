# Analisis Sentimen Wisata Sumber Sirah 🌊

Proyek ini menganalisis opini pengunjung terhadap wisata Sumber Sirah menggunakan beberapa algoritma machine learning (SVM, KNN, dan Naive Bayes) dan juga menggunakan TFIDF dan FastText sebagai pembobotan kata.  
Selain itu, hasil analisis divisualisasikan menggunakan Looker Studio untuk memudahkan interpretasi data.

---

## 📂 Isi Repository
- file Jupyter Notebook (`.ipynb`) untuk preprocessing, training, dan evaluasi model.
- `data/` → dataset yang digunakan (contoh atau link ke dataset asli).
- `visualizations/` → hasil grafik dan visualisasi dari Python.
- `report/` → presentasi dan dokumentasi (Canva/Slides).
- `README.md` → deskripsi project ini.

---

## 🛠 Tools yang Digunakan
- Python (pandas, scikit-learn, matplotlib, nltk, sastrawi)
- Jupyter Notebook/Google Colab
- Looker Studio
- Microsoft Excel / Google Sheets
- Canva (untuk presentasi)

---

## 📊 Dashboard Looker Studio
Lihat hasil visualisasi interaktif melalui link berikut:  
👉 [Dashboard Analisis di Looker Studio]([https://lookerstudio.google.com/reporting/1447add9-7a59-4a3b-a3d9-7534bb9ce906])

---

## 🚀 Cara Menjalankan Notebook
Notebook ini secara default menggunakan Google Drive untuk menyimpan dataset, sehingga terdapat perintah:

```python
from google.colab import drive
drive.mount('/content/drive')
Jika menjalankan dengan Google Drive, pastikan dataset diupload ke Drive Anda sesuai path yang digunakan di notebook. Namun, apabila tidak ingin menggunakan Google Drive, Anda juga dapat langsung menggunakan dataset yang sudah diupload pada repository ini.
