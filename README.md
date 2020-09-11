# Sentiment_Analysis_Sekolah_Daring
Berisi kode - kode dan dataset untuk melakukan sentimen analisis terhadap kebijakan sekolah daring yang ditetapkan oleh Pemerintah

Beberapa dataset yang dapat digunakan adalah
1. cobaaja.csv ---> Berisikan dataset yang sudah dipilih sesuai konteks berjumlah 600 dan sentimennya sudah balance
2. data_total.csv ---> Berisikan data - data crawling yang baru selesai di cleaning tahap 1 dan sudah dilabeli (3000-an data)
3. datatest.csv ---> Berisikan data - data komentar twitter yang mengomentari mengenai kebijakan sekolah daring (300 data)
4. liatduludeh.csv ---> data total yang sudah mengalami pembersihan tingkat lanjut dan sudah dilabeli , berjumlah 3000-an
5. liatduludeh4.csv ---> berisikan data yang sudah dicleaning untuk model, hanya berisikan kata - kata yang mendukung sentimen tertentu (600 data)

Beberapa code IPYNB yang dapat digunakan adalah
AnalisaPersebaranKata.ipynb ---> berisikan code untuk melakukan analisa persebaran kata pada data cobaaja.csv
PemodelandanPenggunaan.ipynb ---> berisikan code untuk menganalisis akurasi model terbaik menggunakan dataset lihatduludeh4.csv dan mengaplikasikannya
pada dataset datatest.csv 
preprocessing_data.ipynb ---> berisikan code yang berfungsi untuk cleaning data_total.csv menjadi liatduludeh.csv
preprocessing_data(cont).ipynb ---> berisikan code yang berfungsi untuk cleaning dari liatduludeh.csv menjadi cobaaja.csv
