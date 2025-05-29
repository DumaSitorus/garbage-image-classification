# Proyek Klasifikasi Gambar: Garbage Classification

Proyek ini bertujuan untuk menghasilkan model yang dapat melakukan klasifikasi terhadap data gambar berdasarkan jenis sampah.


## **Deskripsi Proyek:** 
  
  Proyek ini bertujuan untuk menghasilkan model yang dapat melakukan klasifikasi terhadap data gambar berdasarkan jenis sampah.


---


## **Dataset**

  Dataset yang digunakan merupakan data gambar sampah yang dibagi kedalam beberapa subfolder bernama setiap label berupa jenis sampah tersebut.
  Dataset ini terdiri atas 15,150 gambar dari 12 kelas yang berbeda berdasarkan jenis sampah rumah, antara lain:

1.   battery (sampah baterai)
2.   biological (sampah biologis)
3.   brown-glass (sampah kaca berwarna cokelat)
4.   cardboard (sampah kardus)
5.   clothes (sampah pakaian)
6.   green-glass (sampah kaca berwarna hijau)
7.   metal (sampah berahan metal)
8.   paper (sampah kertas)
9.   plastic (sampah plastik)
10.  shoes (sampah sepatu)
11.  trash (sampah seperti popok, masker, sikat gigi dan lain-lain)
12.  white-glass (sampah kaca berwarna bening)


---


## **Sumber Dataset**
  
  Dataset ini diperoleh dari platform penyedia dataset Kaggle https://www.kaggle.com

  Dataset:  Garbage Classification (12 classes) 
  https://www.kaggle.com/datasets/mostafaabla/garbage-classification



---


## **Teknologi yang Digunakan**  
- **Python** (pandas, numpy, scikit-learn, TensorFlow, Tensorflowjs, kaglehub, pillow, seaborn, keras)  
- **Deep Leanring dan Transfer Leaning**  
  - Arsitektur CNN  
  - Transfer Leaning MobileNetV2 
- **Google Collab** untuk notebook menjalankan kode program
- **Kaggle** (sumber data)
- **Git & GitHub** (sebagai version controll dan penyimpanan serta media kolaborasi)


---


## **Struktur Proyek**  
📁 submission</br>
├───tfjs_model</br>
| ├───group1-shard1of1.bin</br>
| └───model.json</br>
├───tflite</br>
| ├───model.tflite</br>
| └───label.txt</br>
├───saved_model</br>
| ├───saved_model.pb</br>
| └───variables</br>
├───notebook.ipynb</br>
├───README.md</br>
└───requirements.txt</br>


---


## **Cara Menjalankan**  
### 
```sh
1️⃣ Unduh proyek 
2️⃣ Install dependensi:
pip install -r requirements.txt
3️⃣ Jalankan kode program:
Buka file notebook.ipynb dan jalankan untuk menguji model pada gambar.
