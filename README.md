# ANN-Model
Penjelasan kode:
1.	Baca Dataset:
o	Dataset yang digunakan berasal dari Kaggle.
o	Kolom “diagnosis” pada dataset mengandung nilai 1 (Malignant) atau 0 (Benign).
2.	Preprocessing Data:
o	Kolom-kolom yang tidak relevan seperti “customer name”, “customer e-mail”, “country”, dan “gender” dihapus.
o	Data numerik dinormalisasi menggunakan MinMaxScaler.
3.	Linear Regression:
o	Model regresi linear (LinearRegression) diuji dengan membagi data menjadi train dan test set.
o	Skor akurasi pada data train dan test ditampilkan.
4.	Artificial Neural Network (ANN):
o	Model jaringan saraf tiruan (ANN) dengan dua lapisan (32 neuron pada lapisan pertama dan 1 neuron pada lapisan kedua) dibuat.
o	Fungsi aktivasi yang digunakan adalah ReLU pada lapisan pertama dan linear pada lapisan kedua.
o	Model di-compile dengan optimizer Adam dan loss function mean squared error.
Hasil Linear Regression:
•	Skor pada data train: 0.9999 (hampir sempurna)
•	Skor pada data test: 0.9999 (hampir sempurna)
Hasil ANN:
•	Model ANN telah dievaluasi pada data test.
•	Prediksi harga mobil untuk input [40, 70000.500, 9550, 534000] adalah [0.0001].
5.	Perbandingan Prediksi Linear Regression dan ANN: 
o	Scatter plot menunjukkan perbandingan antara nilai aktual dan nilai prediksi menggunakan regresi linear dan ANN.
o	Garis putus-putus abu-abu menunjukkan nilai aktual dan prediksi yang sama.

Hasil dari kode menunjukkan beberapa hal:
1.	Grafik Training dan Validasi Loss:
o	Grafik ini menggambarkan training loss (garis merah) dan validation loss (garis hijau) selama proses pelatihan model.
o	Titik biru menunjukkan epoch terbaik dengan validation loss terendah.
(Semakin rendah validation loss, semakin baik performa model. Pada titik biru, model memiliki performa optimal)
2.	Grafik Training dan Validasi Akurasi:
o	Grafik ini membandingkan training accuracy (garis merah) dengan validation accuracy (garis hijau) selama proses pelatihan model.
o	Titik biru menunjukkan epoch terbaik dengan validation accuracy tertinggi.
(Semakin tinggi validation accuracy, semakin baik performa model. Pada titik biru, model memiliki akurasi optimal)
3.	Hasil Regresi Linear:
o	Skor R2 pada data test: hampir sempurna (nilai mendekati 1).
(Model regresi linear sangat baik dalam memprediksi harga mobil berdasarkan fitur-fitur yang diberikan)
4.	Hasil Artificial Neural Network (ANN):
o	Model ANN telah dievaluasi pada data test.
o	Prediksi harga mobil untuk input [40, 70000.500, 9550, 534000] adalah [0.0001].
(Model ANN memiliki performa yang baik)
5.	Perbandingan Prediksi Linear Regression dan ANN:
o	Scatter plot menunjukkan perbandingan antara nilai aktual dan nilai prediksi menggunakan regresi linear dan ANN.
o	Garis putus-putus abu-abu menunjukkan nilai aktual dan prediksi yang sama.


