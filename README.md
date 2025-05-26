# POS Tagging Bahasa Jawa dengan HMM & Algoritma Baum Welch 

### Deskripsi Proyek

Proyek ini merupakan bagian dari skripsi saya yang berfokus pada penerapan Part of Speech (POS) Tagging untuk data teks berbahasa Jawa (Ngoko & Krama) menggunakan algoritma Hidden Markov Model (HMM) dengan Algoritma Baum Welch. Proyek ini bertujuan untuk mengetahui akurasi HMM terhadap performa model POS Tagging.

### Fitur Utama

- **Pra-pemrosesan Data:** Case folding, tokenizing, dan data cleaning.
- **Eksperimen Penghapusan Tag:** Perbandingan akurasi dengan dan tanpa menghapus tag PUNCT dan SYM.
- **Pelatihan Model:** K-Fold Cross Validation (K=5 dan K=10) untuk pelatihan dan evaluasi model.
- **Implementasi Algoritma Baum Welch (Forward-Backward dan EM):** Untuk optimasi parameter HMM.
- **Evaluasi:** Pengukuran akurasi POS Tagging pada data uji.

### Struktur Folder

- `Assets/` : Berisi gambar aplikasi dan ilustrasi terkait proyek.
- `output_with_pos.txt` : Dataset POS Tagging Bahasa Jawa.
- Notebook Jupyter : Berisi seluruh proses eksperimen dan analisis.

### Contoh Tampilan Aplikasi

![Desain Aplikasi](Assets/Desain%20Aplikasi.png)
![Hasil Prediksi](Assets/Hasil%20Prediksi.png)

### Kesimpulan

Berdasarkan hasil eksperimen, model HMM dengan Algoritma Baum Welch pada tugas POS Tagging Bahasa Jawa berhasil mencapai akurasi tertinggi sebesar **74.92%** pada threshold 10^−2 dan 10^−4 dengan nilai K=5 pada K-Fold Cross Validation.

---

# Javanese POS Tagging with HMM & Baum Welch Algorithm

### Project Description

This project is part of my undergraduate thesis, focusing on the implementation of Part-of-Speech (POS) Tagging for Javanese text data (Ngoko & Krama) using the Hidden Markov Model (HMM) with the Baum Welch Algorithm. The goal is to evaluate the accuracy of HMM in POS Tagging tasks.

### Main Features

- **Data Preprocessing:** Case folding, tokenizing, and data cleaning.
- **Tag Removal Experiment:** Accuracy comparison with and without removing PUNCT and SYM tags.
- **Model Training:** K-Fold Cross Validation (K=5 and K=10) for model training and evaluation.
- **Baum Welch Algorithm Implementation (Forward-Backward and EM):** For HMM parameter optimization.
- **Evaluation:** Measuring POS Tagging accuracy on test data.

### Folder Structure

- `Assets/` : Contains application screenshots and project illustrations.
- `output_with_pos.txt` : Javanese POS Tagging dataset.
- Jupyter Notebook : Contains the entire experimental process and analysis.

### Application Example

![Application Design](Assets/Desain%20Aplikasi.png)
![Prediction Result](Assets/Hasil%20Prediksi.png)

### Conclusion

Based on the experimental results, the HMM model with the Baum Welch Algorithm for Javanese POS Tagging achieved the highest accuracy of **74.92%** at thresholds 10^−2 and 10^−4 with K=5 in K-Fold Cross Validation.

