# Clustering & Classification Project - BMLP Submission

## Deskripsi Proyek
Proyek ini merupakan submission akhir untuk program **BMLP (Belajar Machine Learning Pemula)**. Proyek mencakup dua tugas utama yaitu **Clustering** dan **Klasifikasi** dengan menggunakan dataset terkait analisis pelanggan perbankan.

## Struktur Proyek
- **[Clustering]_Submission_Akhir_BMLP_Davi_Sulaiman.ipynb**  
  Notebook ini berisi analisis clustering untuk mengelompokkan data pelanggan berdasarkan berbagai fitur yang tersedia dalam dataset.

- **[Klasifikasi]_Submission_Akhir_BMLP_Davi_Sulaiman.ipynb**  
  Notebook ini berisi model klasifikasi yang bertujuan untuk memprediksi apakah seorang pelanggan akan churn (berhenti menggunakan layanan bank) atau tidak.

- **data_science_job.csv**  
  Dataset utama yang digunakan untuk tugas clustering. Dataset ini berisi informasi pelanggan bank tanpa label churn.

- **Dataset_inisiasi.csv**  
  Dataset tambahan yang digunakan dalam analisis klasifikasi.

## Teknologi yang Digunakan
- Python 3
- Pandas untuk manipulasi data
- NumPy untuk operasi numerik
- Scikit-learn untuk implementasi algoritma Machine Learning
- Matplotlib & Seaborn untuk visualisasi data

## Cara Penggunaan

### Menjalankan Virtual Environment (venv)
1. Buat virtual environment baru:
   ```bash
   python -m venv venv
   ```
2. Aktifkan virtual environment:
   - **Windows**:
     ```bash
     venv\Scripts\activate
     ```
   - **Mac/Linux**:
     ```bash
     source venv/bin/activate
     ```

3. Install dependensi yang dibutuhkan:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```

### Menjalankan Jupyter Notebook
1. Jalankan perintah berikut untuk membuka Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Buka file `.ipynb` yang sesuai dengan kebutuhan.
3. Eksplorasi dan jalankan sel notebook secara berurutan untuk melihat hasil analisis clustering dan klasifikasi.
