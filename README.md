# Implementasi-Metode-Preprocessing-untuk-Meningkatkan-Performa-Face-Recognition

Pendekatan Teknikal

Face Detection (Segmentation)
deteksi wajah pada gambar, menggunakan library opencv. metode ini digunakan agar proses ektraksi ciri lebih fokus pada bagian wajah.

Cropping (Basic Operation)
Crop pada wajah yang telah dideteksi pada proses sebelumnya. metode ini digunakan agar proses ektraksi ciri lebih fokus pada bagian wajah

Resizing (Tranformation)
Gambar akan diperkecil sebanyak 0.8 dari gambar asli. metode ini digunakan agar proses ekstraksi lebih cepat. 

Histogram Equalization (enhancement)
Karena tidak semua gambar memiliki kondisi pencahayaan terkontrol mengandung kontras yang seragam, maka membutuhkan pemerataan histogram. pada tahap ini digunakan library opencv.

Image Filtering (Konvolusi)
metode ini dilakukan untuk mengurangi noise dan menghilangkan informasi frekuensi tinggi dan hanya menyimpan informasi frekuensi rendah.  metode ini menggunakan Gaussian Blur sebagai kernel dan dilakukan operasi konvolusi pada gambar.

Lossy (Compressing)
compress bertujuan untuk memperkecil ukuran data. metode ini digunakan untuk menghemat resource yang telah di preprocessing. pada tahap ini digunakan library PIL
