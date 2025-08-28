# Emotion Detection

Emotion Detection adalah proyek machine learning yang dapat mengenali emosi wajah manusia secara real-time menggunakan webcam. Model ini dilatih dengan dataset gambar wajah yang dikategorikan ke dalam 7 emosi: Angry, Disgusted, Fearful, Happy, Neutral, Sad, dan Surprised.

## Fitur
- Deteksi wajah secara otomatis menggunakan OpenCV
- Klasifikasi emosi wajah secara real-time
- Visualisasi hasil prediksi pada frame video
- Model deep learning berbasis CNN (Convolutional Neural Network)

## Struktur Folder
```
├── kel13_latihan.ipynb      # Notebook utama (training & prediksi)
├── model_emosi.h5           # Model hasil training
├── train/                   # Data training (7 folder emosi)
├── test/                    # Data testing (7 folder emosi)
```

## Cara Menjalankan
1. **Clone repository ini**
   ```bash
   git clone https://github.com/arielyosua/Emotion-Detection.git
   cd Emotion-Detection
   ```
2. **Install dependencies**
   Pastikan Python 3.x sudah terinstall. Install library yang dibutuhkan:
   ```bash
   pip install -r requirements.txt
   ```
   Atau install manual:
   ```bash
   pip install tensorflow opencv-python matplotlib numpy
   ```
3. **Jalankan notebook**
   Buka `kel13_latihan.ipynb` di Jupyter Notebook atau VS Code, lalu jalankan sel-selnya secara berurutan.

4. **Prediksi Emosi Real-Time**
   Setelah model dilatih/di-load, jalankan sel prediksi webcam. Tekan `q` untuk keluar dari mode webcam.

## Contoh Hasil
![Alt Text](https://github.com/user-attachments/assets/2f4edf09-4e04-4dc3-8b7a-e41987cdf23c)

## Kontributor
- Ariel Yosua Hasibuan (105222004)
- Haekal Putra Alharis (105222028)
- Bintang Akbar Alim (105222037)


## Lisensi
Proyek ini menggunakan lisensi MIT. Silakan gunakan, modifikasi, dan distribusikan sesuai kebutuhan.

---
> "Mendeteksi emosi, memahami ekspresi."
