🧠 CIFAR10 Image Classification with TensorFlow

Proyek ini menggunakan TensorFlow dan Keras untuk membangun model Convolutional Neural Network (CNN) sederhana yang mampu mengenali gambar dari dataset CIFAR-10. Dataset ini berisi 60.000 gambar berwarna berukuran 32x32 piksel dalam 10 kelas berbeda seperti pesawat, mobil, kucing, anjing, dan lainnya.

📦 Dataset

Dataset: CIFAR-10
Sumber: https://www.cs.toronto.edu/~kriz/cifar.html

⚙️ Instalasi

Pastikan kamu sudah menginstal Python 3.8+ dan jalankan perintah berikut di terminal:

# Buat virtual environment (opsional)
python -m venv env
source env/bin/activate   # (Linux/Mac)
env\Scripts\activate      # (Windows)

# Install dependencies
pip install tensorflow matplotlib

🚀 Menjalankan Proyek

Clone repository ini:

git clone https://github.com/username/CIFAR10-Image-Classification-with-TensorFlow.git
cd CIFAR10-Image-Classification-with-TensorFlow


Jalankan notebook atau file Python:

python main.py


Output awal akan menampilkan:

Versi TensorFlow

Informasi dataset CIFAR-10 (jumlah data train/test)

Visualisasi beberapa gambar sampel

🧩 Struktur Proyek
📂 CIFAR10-Image-Classification-with-TensorFlow
 ┣ 📜 main.py
 ┣ 📜 README.md
 ┗ 📂 saved_model (opsional)

📊 Contoh Output
TensorFlow version: 2.19.0
x_train shape: (50000, 32, 32, 3), y_train shape: (50000, 1)
x_test shape: (10000, 32, 32, 3), y_test shape: (10000, 1)
Classes: ['airplane', 'automobile', 'bird', 'cat', 'deer', 
          'dog', 'frog', 'horse', 'ship', 'truck']

🧠 Teknologi yang Digunakan

TensorFlow / Keras

Python 3

Matplotlib (visualisasi data)

💡 Tujuan Proyek

Proyek ini dibuat untuk mempelajari:

Cara memuat dan memproses dataset gambar

Normalisasi data gambar

Arsitektur dasar CNN

Klasifikasi multi-kelas menggunakan TensorFlow

📚 Referensi

TensorFlow Documentation

CIFAR-10 Dataset
