Deteksi Objek dan Penghitungan Jumlah Menggunakan TensorFlow Hub
Proyek ini merupakan implementasi deteksi objek dari gambar atau video menggunakan model pre-trained dari TensorFlow Hub. Proyek ini mendukung input berupa gambar dan video, serta dilengkapi fitur opsional untuk menghitung jumlah objek berdasarkan kategori.

🔧 Fitur Utama
🔍 Deteksi objek otomatis menggunakan:
Faster R-CNN untuk gambar
SSD MobileNet untuk video
📥 Input dari URL atau upload file langsung
📊 Penghitungan jumlah objek berdasarkan kategori (bisa dipilih semua atau manual)
🖼️ Visualisasi bounding box dan label deteksi
🎞️ Output video dengan anotasi objek
🗂️ Label dalam Bahasa Indonesia sesuai COCO Dataset

📁 Struktur Proyek
bash
.
├── object_detection_notebook.ipynb    # Notebook utama
├── output_detected_video.mp4          # (Hasil output video setelah diproses)
├── README.md                          # Dokumentasi ini
└── Makalah Objek Detection.docx       # Laporan/penjelasan eksperimen

🛠️ Teknologi
1. Python 3.x
2. TensorFlow 2.x
3. TensorFlow Hub
4. OpenCV
5. NumPy
6. Matplotlib
7. PIL
8. Google Colab

🚀 Cara Menggunakan
1. Buka dan jalankan notebook object_detection_notebook.ipynb di Google Colab.
2. Pilih metode input: upload file atau masukkan URL gambar/video.
3. Tentukan apakah ingin menghitung jumlah objek.
4. Pilih kategori objek yang ingin dihitung (semua atau pilih manual).

Hasil:
Gambar: ditampilkan dengan bounding box dan informasi deteksi.
Video: diproses frame-by-frame, disimpan sebagai output_detected_video.mp4.

📌 Contoh Kategori Objek
manusia
mobil
kucing
anjing
sepeda
gajah
pizza
laptop
dan lainnya (total 81 label)

📄 Referensi Akademik
Implementasi ini dikembangkan sebagai bagian dari makalah bertema Object Detection menggunakan TensorFlow Hub yang mengacu pada referensi berikut:
Prayogo & Nugroho (2023). Object Detection Menggunakan TensorFlow dan Dataset COCO.
Yuliana & Hakim (2021). Analisis Kinerja Deteksi Objek pada Berbagai Model Deep Learning.

📝 Lisensi
Proyek ini digunakan untuk keperluan pembelajaran dan penelitian. Silakan modifikasi sesuai kebutuhan.

