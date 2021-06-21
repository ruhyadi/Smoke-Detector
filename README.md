# Smoke Detector

##### Original Author: Abhishek Ghosh, Moumita Mukherjee
For cite this project, please refer to original author 

##### Editied by : Didi Ruhyadi (428644)

#### Proyek Akhir Komunikasi Data Kelompok 03
## *Early Warning System* Pendeteksi Kebakaran Hutan
*Early warning system* yang diusung mengangkat topik kebakaran hutan. Dalam proses kebakaran hutan, fenomena pertama yang dapat dideteksi dari kejauhan adalah munculnya asap. Berdasarkan hal tersebut, kelompok kami menggagas teknologi yang dapat mendeteksi keberadaan asap berbasis citra digital (ditangkap oleh kamera) menggunakan metode *deep learning object detection*.  

Model *object detection* yang digunakan adalah EficientDet yang dilatih pada *datasets* yang sudah dibuat oleh *original author* sebelumnya. Framework yang digunakan dalam proses pelatihan menggunakan Tensorflow. 

## Dataset

Dataset terdiri dari 733 citra (gambar) asap yang sudah di anotasi. Data training, validation dan testting menggunakan rasio 7:2:1 atau 513 citra untuk training, 147 citra untuk validation, dan 73 citra untuk testing. Kami sangat berterimakasih pada [AIforMankind](https://github.com/aiformankind/wildfire-smoke-detection-camera) yang telah menyediakan dataset.

Original author menggunakan [Roboflow](https://roboflow.com) untuk *labeling data, image processing, data augmentation*, dan generating TFRecord. 

## Implementasi

Pada repository ini hanya ditampilkan pendeteksi asap yang digunakan sebagai indikator kebakaran hutan. Fenomena lain yang kelompok kami deteksi adalah api, yang dapat diaksis pada repository ini. 

#### Testing Model
![smokey](https://user-images.githubusercontent.com/61203589/90588540-79f05800-e1a1-11ea-8fd1-54dbe8170a68.gif)
![smokey5](https://user-images.githubusercontent.com/61203589/90666480-156de100-e213-11ea-856c-fcf7ee1fae4b.gif)
![smokey6](https://user-images.githubusercontent.com/61203589/90666481-156de100-e213-11ea-98f1-de6949c99536.gif)

