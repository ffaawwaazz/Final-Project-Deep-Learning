# Final-Project-Deep-Learning
LINK DEPLOYMENT

Noise image generator :

Denoising Autoencoder + Image Classifier :

# 🔍 Sistem Klasifikasi Tomat Menggunakan DAE dan CNN

## 📌 Deskripsi Singkat

Sistem ini bekerja dengan cara membersihkan gambar yang terkena noise menggunakan **DAE**, kemudian hasil gambar bersih tersebut diklasifikasikan menggunakan **CNN**. Tujuannya adalah meningkatkan akurasi klasifikasi dengan memastikan input yang lebih bersih dan jelas.

### 💡 Fitur Utama
- Menambahkan berbagai jenis noise ke gambar (Gaussian, Salt & Pepper, dll)
- Membersihkan gambar menggunakan Denoising Autoencoder (DAE)
- Mengklasifikasikan gambar bersih dengan CNN
- Evaluasi hasil menggunakan MSE, PSNR, SSIM, dan akurasi klasifikasi

### 🛠️ Teknologi yang Digunakan
- Python
- TensorFlow / Keras
- NumPy, Matplotlib, scikit-learn
- OpenCV & skimage (untuk simulasi noise)

## 🧪 Ringkasan Evaluasi
- **SSIM DAE**: 0.9056
- **Akurasi Klasifikasi**: 88%
- Performa sangat baik dalam membersihkan gambar dan mengenali kelas objek.


## 📸 Alur Sistem
Gambar Input → Tambah Noise → DAE (denoise) → CNN (klasifikasi) → Output Label


