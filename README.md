# Comparison of Gradient Boosting and Random Forest in Predicting Significant Wave Height

This repository contains the files of my project (college thesis) titled "Comparison of Gradient Boosting and Random Forest in Predicting Significant Wave Height". This project compares some aspects in random forest and gradient boosting (XGBoost) when predicting significant wave height using oceanographic data from NDBC Station 51004 Southeast Hawai'i.
IDN:
**Perbandingan Gradient Boosting dan Random Forest dalam Memprediksi Gelombang Laut Signifikan**
Repository ini memuat file dari skripsi saya yang berjudul "Perbandingan Gradient Boosting dan Random Forest dalam Memprediksi Gelombang Laut Signifikan.

## Thesis Abstract
Significant wave height is a crucial parameter in oceanographic studies as it directly affects safety, operations, and the planning of maritime activities, thereby requiring accurate and reliable prediction methods. This study aims to compare the performance of two machine learning algorithms, namely gradient boosting (XGBoost) and random forest, in predicting significant wave height using oceanographic data from Southeast Hawai’i. The research stages included data collection and processing, model training and implementation, and evaluation of prediction results for both models. The gradient boosting algorithm achieved an MAE of 0,110604, RMSE of 0,153243, R2 of 0,921567, bias of -0,005159, and Pearson’s correlation coefficient of 0,960166, with a computation time of 1 minute 53,4 seconds. In comparison, random forest obtained an MAE of 0,111459, RMSE of 0,154747, R2 of 0,920020, bias of -0,004722, and Pearson’s correlation coefficient of 0,959282, with a computation time of 38 minutes 24,3 seconds. Gradient boosting demonstrated superior performance in capturing fluctuation patterns and variations of significant wave height, as well as in minimizing errors, particularly large errors, whereas random forest showed an advantage in producing more neutral bias.
IDN:
Gelombang laut signifikan merupakan parameter penting dalam kajian kelautan karena berpengaruh langsung terhadap keselamatan, operasional, dan perencanaan aktivitas maritim, sehingga diperlukan metode prediksi yang akurat dan reliabel. Penelitian ini bertujuan membandingkan kinerja dua algoritma machine learning, yaitu gradient boosting (XGBoost) dan random forest, dalam memprediksi gelombang laut signifikan menggunakan data perairan Southeast Hawai’i. Tahapan penelitian meliputi pengumpulan dan pengolahan data, pelatihan serta penerapan model machine learning, hingga evaluasi terhadap hasil prediksi kedua model. Algoritma gradient boosting memperoleh skor MAE 0,110604, RMSE 0,153243, R2 0,921567, bias -0,005159, dan koefisien korelasi Pearson 0,960166, dengan waktu komputasi 1 menit 53,4 detik. Sementara itu, random forest memperoleh skor MAE 0,111459, RMSE 0,154747, R2 0,920020, bias -0,004722, dan koefisien korelasi Pearson 0,959282, dengan waktu komputasi 38 menit 24,3 detik. Gradient boosting memiliki kinerja yang lebih baik dalam memahami pola fluktuasi dan variasi gelombang laut signifikan, serta meminimalkan galat, terutama galat besar. Sedangkan, random forest memiliki keunggulan pada bias yang lebih netral.

## Tools Used
While working in this project I used Visual Studio Code as the main app to run Jupyter Notebook files containing all Python scripts for the analysis, processing, modelling, and evaluation processes. Here are the list of all apps, tools, and libraries used:
IDN:
Dalam mengerjakan projek ini saya menggunakan Visual Studio Code sebagai aplikasi utama untuk menjalankan file Jupyter Notebook yang memuat seluruh script Python untuk proses analisis, processing, modelling, dan evaluasi. Berikut adalah daftar aplikasi, alat, dan library yang digunakan:

- Visual Studio Code
- Jupyter Notebook
- Pandas
- Numpy
- Seaborn
- Matplotlib
- SKLearn
- XGBoost
