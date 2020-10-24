# Machine-Learning
Yang harus di penuhi yaitu :
1. Dataset harus dibagi menjadi train set dan validation set.
2. Ukuran validation set harus 40% dari total dataset (data training memiliki 1314 sampel, dan data validasi sebanyak 874 sampel).
3. Harus mengimplementasikan augmentasi gambar.
4. Menggunakan image data generator.
5. Model harus menggunakan model sequential.
6. Pelatihan model tidak melebihi waktu 30 menit.
7. Akurasi dari model minimal 85%.
8. Dapat memprediksi gambar yang diunggah

Belum menerapkan 3 teknik lain seperti dropout, plot akurasi, callbacks, dan lain-lain. Ketika memprediksi gambar, model akan memberikan hasil prediksi yang baik ketika gambar yang di upload memiliki background green screen tetapi ketika gambar tidak memiliki background greenscreen hasil prediksi sering tidak sesuai. Hal ini dikarenakan dataset yang dipakai untuk training memiliki background yang seragam sehingga model hanya mengenali background green screen
