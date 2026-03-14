# praktik-OpenCV3-kelompok1

# Praktik OpenCV Part 3: Konversi Gambar & Drawing

Repository ini berisi hasil praktik mandiri Kelompok 3 untuk mata kuliah 
**Praktik Machine Learning / Pengolahan Citra Digital**. Proyek ini mencakup 
teknik konversi ruang warna dan menggambar objek pada gambar menggunakan 
library OpenCV, termasuk interaksi mouse event secara real-time.

## Anggota Kelompok 3
**Informatika – Universitas Teknologi Sumbawa**
- **[Sherly Novia Indriani]** - [231001057]
- **[Dinda Oktavia Pratiwi]** - [231001026]
- **[Ahsanul Ikram]** - [231001077]
- **[Wanda Setya Budi]** - [231001008]

**Dosen Pengampu:** Herfandi, Ph.D.

---

## Alat dan Library
- **Bahasa:** Python 3.x
- **Library:** OpenCV (opencv-python), NumPy, Matplotlib
- **Editor:** Visual Studio Code / Jupyter Notebook

---

## Materi yang Dipraktikkan

### 1. Konversi Gambar
- BGR → Grayscale (`cv2.COLOR_BGR2GRAY`)
- BGR → RGB untuk Matplotlib (`cv2.COLOR_BGR2RGB`)
- BGR → BGRA dengan pengaturan transparansi Alpha

### 2. Pemrosesan Video
- Membaca video frame per frame (`cv2.VideoCapture`)
- Konversi setiap frame menjadi grayscale secara real-time

### 3. Menggambar Objek
- Garis (`cv2.line`) dengan berbagai mode
- Persegi panjang outline & terisi (`cv2.rectangle`)
- Lingkaran outline & terisi (`cv2.circle`)

### 4. Menulis Teks
- Menulis teks pada gambar (`cv2.putText`)
- Mengukur ukuran teks (`cv2.getTextSize`)
- Membuat label box yang pas dengan teks

### 5. Interaksi Mouse Event
- Menggambar garis, persegi, dan lingkaran menggunakan klik mouse
- Crop gambar secara interaktif menggunakan seleksi mouse
- Bounding Box Object Detection dengan label (`draw_ped()`)

---

## Video Presentasi
👉 [https://youtu.be/XX1Im1jui_g?si=h50UhP6PUq5FXQnx]

---

## Cara Menjalankan
1. Clone repository ini:
```bash
   git clone [link repo kalian]
```
2. Install library yang dibutuhkan:
```bash
   pip install opencv-python numpy matplotlib
```
3. Buka file `pertemuan_3.ipynb` di VS Code atau Jupyter Notebook.
4. Pastikan file `lena.jpg` dan `video.mp4` berada di folder yang sama.
