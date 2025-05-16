# Youtube Sentimen Analisis "Generasi muda, Bonus Demografi dan Masa Depan Indonesia" oleh Channel: `Gibran Rakabuming Raka`

Repository ini mengandung projek python untuk analisa sentimen komentar youtube/Menggunakan classify_sentiment dari Tranformers, mengklasifikasikan komentar menjadi netral, negatif, dan positif. Hasil juga menyertakan visualisasi berupa bar chart dan wordcloud untuk memudahkan melihat insight dari opini publik.

Dataset di ambil dari forum kaggle menertakan kolom username dan text. Project ini mendemonstrasikan data cleaning, data preprocessing, sentimen labeling, dan visualisasi data yang cocok untuk tugas akademik maupun portofilio data sains unutk pemula

## Fitur
- Membaca dataset csv dari komputer lokal.
- Labeling sentimen dengan `Transformers`.
- Mengklasifikasikan komentar menjadi Netral, Negatif, dan Positif.
- Visualisasi distribusi sentimen dengan barchart.
- Visualisasi kata dengan `Wordcloud`.

## Struktur Repository
- `data/` : menyimpan dataset original.
- `Sentimen_analisis.ipynb` : berisi kode yang mengolah dataset.
- `requirements.txt` : list library yang perlu di install.

## Instalasi
1. Clone Repository ini.
2. Install semua dependensi:`pip install -r requirements.txt`.
3. Run Jupyter Notebook  `Sentimen_analisis.ipynb` di kode editor.

## Penggunaan 
1. Siapkan dataset `Youtube_Comment_Gibran.csv` yang terdiri dari 2 kolom: 
  * Kolom A: Username
  * Kolom B: Text

2. Run Jupyter Notebook `Sentimen_analisis.ipynb` secara urut.

3. Script ini akan menghasilkan:
  * Dataframe dengan kolom `Label`
  * visualisai yang simple untuk melihat insight dari dataset


## Sumber Dataset

Dataset dalam project ini berasal dari: [Kaggle](https://www.kaggle.com/datasets/faiqkhoirulmuna/indonesias-vice-president-youtube-comment). Mohon gunakan data secara bijak.

---

Made with ❤️ by Rizqy Mubarok