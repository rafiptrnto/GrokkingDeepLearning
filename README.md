# Grokking Deep Learning

Repository ini dibuat untuk memenuhi tugas mata kuliah **Deep Learning** dengan melakukan reproduksi kode dan pembahasan materi dari buku:

**Grokking Deep Learning** — Andrew W. Trask (Manning Publications, 2019)

Setiap notebook berisi reproduksi kode dari buku (bersumber dari repository resmi penulis, `iamtrask/Grokking-Deep-Learning`), penjelasan konsep dalam bahasa Indonesia, *Key Ideas*, dan kesimpulan chapter. Notebook dirancang untuk dijalankan di **Google Colab**.

---

## 📂 Struktur Repository

```text
GrokkingDeepLearning
│
├── README.md
├── Chapter_01_Introducing_Deep_Learning.ipynb
├── Chapter_02_Fundamental_Concepts.ipynb
├── Chapter_03_Forward_Propagation.ipynb
├── Chapter_04_Gradient_Descent.ipynb
├── Chapter_05_Generalizing_Gradient_Descent.ipynb
├── Chapter_06_Backpropagation.ipynb
├── Chapter_07_How_to_Picture_Neural_Networks.ipynb
├── Chapter_08_Regularization.ipynb
├── Chapter_09_Activation_Functions.ipynb
├── Chapter_10_Convolutional_Neural_Networks.ipynb
├── Chapter_11_Word_Embeddings.ipynb
├── Chapter_12_Recurrent_Neural_Networks.ipynb
├── Chapter_13_Automatic_Differentiation.ipynb
├── Chapter_14_LSTM.ipynb
└── Chapter_15_Federated_Learning.ipynb
```

---

# 📖 Ringkasan Chapter

| Chapter | Topik | Ringkasan |
|---|---|---|
| 1 | Introducing Deep Learning | Alasan mempelajari deep learning, kebutuhan awal (Jupyter, NumPy, Python), dan pendekatan buku yang berbasis proyek tanpa matematika lanjut. |
| 2 | Fundamental Concepts | Deep learning sebagai bagian machine learning; supervised vs unsupervised; parametrik vs nonparametrik; siklus predict, compare, learn. |
| 3 | Forward Propagation | Neural network pertama: weighted sum (dot product) dengan satu atau banyak input dan output, serta jaringan bertumpuk. |
| 4 | Gradient Descent | Mengukur error, hot and cold learning, gradient descent dengan derivatif, dan peran alpha (learning rate). |
| 5 | Generalizing Gradient Descent | Gradient descent untuk banyak weight: banyak input, banyak output, atau keduanya. |
| 6 | Backpropagation | Deep neural network pertama, korelasi, hidden layer, nonlinearitas (ReLU), dan backpropagation. |
| 7 | How to Picture Neural Networks | Visualisasi ringkas jaringan sebagai vektor (layer) dan matriks (weights), serta notasi dengan huruf. |
| 8 | Regularization | Overfitting, early stopping, dropout, dan batch gradient descent pada MNIST. |
| 9 | Activation Functions | Sigmoid, tanh, softmax, dan penerapan turunan activation saat backpropagation. |
| 10 | Convolutional Neural Networks | Menggunakan kembali weights (structure trick) dan lapisan konvolusi untuk fitur tepi dan sudut. |
| 11 | Word Embeddings | NLP dengan IMDB, embedding layer, makna dari loss function, dan analogi kata. |
| 12 | Recurrent Neural Networks | Data berpanjang variabel, matriks transisi, vektor kalimat, dan backpropagation melalui waktu. |
| 13 | Automatic Differentiation | Membangun deep learning framework mini: tensor, autograd, optimizer, dan berbagai layer. |
| 14 | LSTM | Model bahasa karakter, truncated backpropagation, vanishing/exploding gradients, dan LSTM gate. |
| 15 | Federated Learning | Privasi pada deep learning, federated learning, secure aggregation, dan homomorphic encryption. |

---

# 🛠️ Tools and Libraries

- Python
- NumPy
- Matplotlib
- Keras (hanya untuk memuat dataset MNIST pada Chapter 8-10)

---

# ▶️ Cara Menjalankan

1. Buka notebook di Google Colab (File → Open notebook → GitHub).
2. Pada chapter yang memerlukan data (Chapter 11, 12, 13, 14, 15), sel pertama mengunduh file data dari repository resmi buku.
3. Jalankan seluruh sel (Runtime → Run all).

---

# 📌 Reference

Trask, A. W. (2019). *Grokking Deep Learning*. Manning Publications.

Kode bersumber dari repository pendamping resmi: https://github.com/iamtrask/Grokking-Deep-Learning

---

## 👤 Author

**Nama:** Herpratama Rafi Putranto  
**NIM:** 101032300076  
**Mata Kuliah:** Deep Learning
