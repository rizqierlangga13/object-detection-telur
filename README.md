# 🥚 Deteksi Kebersihan Cangkang Telur Ayam Menggunakan YOLO11

Repository ini berisi implementasi model **YOLO11** untuk mendeteksi kebersihan cangkang telur ayam menggunakan metode *object detection*. Model dikembangkan menggunakan dataset pribadi melalui Roboflow dan mampu mendeteksi telur ke dalam dua kategori, yaitu:

- **Clean Shell (Bersih)**
- **Dirty Shell (Kotor)**

---


## Dataset

Dataset yang digunakan pada penelitian ini disimpan pada Roboflow secara pribadi.


---


## Isi Repository

| Folder         | Deskripsi                                                      |
|----------------|----------------------------------------------------------------|
| **Model**      | Berisi model terbaik (`best.pt`) hasil pelatihan.              |
| **Notebook**   | Berisi notebook untuk proses pelatihan dan inference.          |
| **Inference**  | Berisi gambar-gambar yang digunakan untuk proses inference.    |
| **Output**     | Berisi hasil evaluasi model dan hasil inference.               |

---


## Metrik Evaluasi

Performa model dievaluasi menggunakan metrik berikut:

- Precision
- Recall
- mAP@50
- mAP@50-95

---


## Teknologi yang Digunakan

### Bahasa Pemrograman

- Python

### Library 
- YOLO11 (Ultralytics)
- Roboflow SDK

### Tools

- Roboflow
- Google Colab 

---


## Lisensi

Repository ini dibuat untuk keperluan penelitian dan penyusunan tugas akhir.