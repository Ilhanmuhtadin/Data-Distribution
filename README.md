# Analisis Distribusi Data

## Deskripsi

Proyek ini bertujuan untuk menganalisis apakah sebuah dataset memiliki distribusi normal atau tidak. Distribusi normal sangat penting dalam statistika karena banyak metode statistik yang bergantung pada asumsi bahwa data berasal dari distribusi normal. Oleh karena itu, mengetahui apakah data kita memiliki distribusi normal atau tidak merupakan langkah awal yang penting dalam analisis data.

Analisis dilakukan menggunakan beberapa tes statistik yang umum digunakan dari pustaka `scipy.stats`
-  Shapiro-Wilk Test: Test normalitas yang digunakan untuk menguji apakah sampel data berasal dari distribusi normal.
-  D'Agostino's K-squared Test: Test normalitas yang menguji apakah sampel data berasal dari distribusi normal.
-  Kolmogorov-Smirnov Test: Test yang digunakan untuk membandingkan dua sampel data, atau untuk menguji apakah sampel data berasal dari distribusi tertentu.
-  Jarque-Bera Test: Test yang digunakan untuk menguji apakah sampel data memiliki kemiringan dan kurtosis yang sesuai dengan distribusi normal.
Tes statistik ini digunakan untuk menguji apakah sampel data kita berasal dari distribusi normal.


Selain itu, untuk memberikan gambaran visual tentang distribusi data, proyek ini juga menggunakan beberapa teknik visualisasi, seperti:

- **Boxplot**: Untuk melihat sebaran data, nilai tengah, dan keberadaan outlier.
- **Q-Q plot (Quantile-Quantile plot)**: Untuk membandingkan distribusi data dengan distribusi normal.
- **Histogram dengan Kernel Density Estimation (KDE)**: Untuk melihat bentuk distribusi data secara visual.

Dengan menggunakan tes statistik dan teknik visualisasi ini, diharapkan kita dapat lebih memahami karakteristik distribusi data yang kita miliki.

