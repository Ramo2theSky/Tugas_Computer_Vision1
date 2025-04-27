# Face Recognition - Computer Vision Project

Tugas individu mata kuliah Computer Vision: implementasi face recognition menggunakan ekstraksi **Eigenfaces** dan klasifikasi sederhana.

## Author
**Muhammad Yusuf Ramadhan**  
NIM: 23/517172/PA/22158

## Project Overview
Notebook ini melakukan pipeline pengenalan wajah:
- **Data Preparation**: Load dataset lokal berisi gambar wajah.
- **Face Detection**: Deteksi wajah dari gambar.
- **Face Cropping**: Potong area wajah dari gambar.
- **Image Preprocessing**: Resize dan flatten gambar wajah.
- **Train-Test Split**: Membagi data training dan testing.
- **Mean Centering**: Normalisasi data.
- **Feature Extraction**: Ekstraksi eigenfaces via PCA.
- **Classification**: Membuat classifier sederhana.

## How to Run
1. Pastikan dataset gambar wajah tersedia lokal.
2. Jalankan semua cell di `Computer_Vision_1.ipynb` berurutan.
3. Pastikan dependencies berikut tersedia:
   - `numpy`
   - `matplotlib`
   - `scikit-learn`
   - `opencv-python`

## Dependencies Installation
```bash
pip install numpy matplotlib scikit-learn opencv-python
