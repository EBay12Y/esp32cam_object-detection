# Deteksi Objek Menggunakan YOLOv3 dan ESP32-CAM

#### Proyek ini bertujuan untuk mendeteksi berbagai objek dalam gambar yang diambil oleh kamera ESP32-CAM. Proses deteksi dilakukan dengan menggunakan model YOLOv3 yang telah dilatih sebelumnya. Gambar yang diambil oleh ESP32-CAM akan diproses menggunakan OpenCV di Python, di mana gambar tersebut akan mengalami flip horizontal dan vertikal sebelum dilakukan deteksi objek. Objek yang terdeteksi akan ditampilkan dengan bounding box dan label di sekitar objek tersebut.

Langkah-langkah Penggunaan

1. Download atau Clone GitHub Repository Ini

2. Extract File yang Telah Di-download Menjadi Folder

3. Download 3 File Berikut Ini

- [coco.names](https://github.com/pjreddie/darknet/blob/master/data/coco.names)
- [yolov3.cfg](https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg)
- [yolov3.weights](https://pjreddie.com/media/files/yolov3.weights)

4. Masukkan Ketiga File Tersebut dalam Folder Hasil Ekstrak Tadi
   Pindahkan ketiga file yang telah di-download ke dalam folder tempat Anda mengekstrak repository.

5. Compile atau Upload File INO ke ESP32-CAM
   Compile dan upload file INO (kode Arduino) ke perangkat ESP32-CAM Anda. Pastikan perangkat ESP32-CAM sudah terhubung ke jaringan WiFi yang sesuai dengan yang telah dikonfigurasi dalam kode.

6. Buka File detection.py dan Sesuaikan Alamat IP
   Buka file detection.py di editor teks atau IDE favorit Anda dan sesuaikan alamat IP pada variabel url dengan alamat IP ESP32-CAM Anda.

7. Jalankan atau Run File detection.py
   Jalankan script Python detection.py untuk mendeteksi objek dari gambar yang diambil oleh ESP32-CAM

#### Untuk tutorial dalam bentuk video dapat dilihat di video berikut ini

[![ESP32 Cam Tutorial](https://img.youtube.com/vi/llEWoaSOo_U/0.jpg)](https://youtu.be/llEWoaSOo_U "Click to Watch!")
