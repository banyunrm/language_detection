<h2> 🌐 Deteksi Bahasa Otomatis Menggunakan Deep Learning </h2>

<h3>📌 Latar Belakang</h3>
<p>Di era digital yang semakin terhubung, teks multibahasa tersebar luas di berbagai platform seperti media sosial, forum daring, hingga sistem layanan pelanggan. Kemampuan untuk mengidentifikasi bahasa secara otomatis merupakan langkah awal penting dalam pemrosesan bahasa alami (NLP), karena memungkinkan sistem untuk memilih model linguistik yang tepat untuk setiap bahasa.</p>

<p>Proyek ini bertujuan untuk membangun model deteksi bahasa otomatis menggunakan pendekatan deep learning. Model ini dilatih pada kumpulan data teks dari 17 bahasa berbeda, menangani kompleksitas linguistik dari berbagai belahan dunia.</p>

<h3>🎯 Tujuan Proyek</h3>
<p>Membangun dan mengevaluasi model deep learning yang mampu mendeteksi bahasa dari teks masukan secara akurat.</p>

<p>Mengklasifikasikan teks ke dalam salah satu dari 17 bahasa:</p>

- Inggris

- Malayalam

- Hindi

- Tamil

- Kannada

- Prancis

- Spanyol

- Portugis

- Italia

- Rusia

- Swedia

- Belanda

- Arab

- Turki

- Jerman

- Denmark

- Yunani

- Mencapai tingkat akurasi deteksi bahasa yang tinggi.

<h3>📊 Dataset</h3>
<p>Judul: Language Detection</p>
<p>Deskripsi: Dataset berukuran kecil yang digunakan untuk membangun model klasifikasi bahasa. Dataset ini mencakup teks dalam 17 bahasa, sehingga dapat digunakan untuk melatih model NLP yang mendeteksi berbagai bahasa.</p>
<p>Sumber: Kaggle - Language Detection Dataset</p>

<h3>🧰 Teknologi yang Digunakan</h3>

- Python (Pandas, NumPy, Scikit-learn, TensorFlow, Keras)

- Natural Language Processing (NLP)

- Deep Learning (CNN & LSTM)

- Google Colab

<h3>📁 Struktur Proyek</h3>
├── index.ipynb</br>
├── data_inference.ipynb</br>
├── tokenizer.pkl</br>
├── eda_language_detection.png</br>
├── label_encoder.pkl</br>
├── cnn_model.h5</br>
├── text_vectorizer_vocab.txt</br>
├── text_vectorizer_config.json</br>
├── text_vectorization_config.json</br>
├── automatic_language_detection.csv

<h3>📈 Output yang Diharapkan</h3>
- Model deep learning yang mampu mendeteksi 17 bahasa secara akurat dari teks masukan.

Evaluasi model menggunakan metrik seperti:

- Akurasi

- Confusion Matrix

- Classification Report

<h3>💡 Catatan Tambahan</h3>
<p>Proyek ini diharapkan dapat membantu berbagai aplikasi dunia nyata seperti deteksi bahasa dalam sistem chatbot multibahasa, filter konten otomatis, hingga sistem klasifikasi dokumen. Model diunggah di GitHub dan dapat diakses secara publik.</p>
