# 💳 Analisis Transaksi & Deteksi Penipuan

Aplikasi berbasis **Machine Learning** untuk menganalisis transaksi keuangan dan mendeteksi potensi penipuan.  
Dibangun menggunakan **Streamlit**, **Scikit-learn**, dan **Yellowbrick**, aplikasi ini mencakup seluruh alur analisis — mulai dari *data cleaning* hingga *web deployment*.

---

## 🚀 Alur Sistem
1. **Dataset** → Mengambil data transaksi mentah.
2. **Cleaning** → Menghapus duplikasi dan nilai kosong.
3. **Encoding** → Mengubah data kategorikal menjadi numerik.
4. **Outlier Removal** → Menyaring data ekstrem.
5. **Scaling** → Menyamakan skala antar variabel.
6. **K-Means** → Mengelompokkan transaksi (Normal / Mencurigakan).
7. **PCA** → Reduksi dimensi untuk visualisasi cluster.
8. **Decision Tree** → Model klasifikasi awal.
9. **Random Forest** → Model ensemble untuk akurasi tinggi.
10. **Hyperparameter Tuning** → Optimasi parameter model.
11. **Web Application** → Antarmuka interaktif berbasis Streamlit.

---

## 🧠 Teknologi yang Digunakan
| Komponen | Library / Framework |
|-----------|--------------------|
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn, Yellowbrick |
| Machine Learning | Scikit-learn |
| Deployment | Streamlit |
| Model Storage | Joblib |

---

## ⚙️ Instalasi
```bash
git clone https://github.com/<username>/<repo-name>.git
cd <repo-name>
pip install -r requirements.txt
streamlit run app_analisis_transaksi.py
