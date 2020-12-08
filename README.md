# indonesian-news-classifier

Sastrawi pada projek ini digunakan pada tahap preprocessing untuk menghilangkan "stop words" dalam Bahasa Indonesia. Untuk memasang Sastrawi:

pip install Sastrawi

Klasifikasi berita dilakukan dengan membuat model sequential keras yang juga mengimplementasikan LSTM. Model menerapkan callbacks EarlyStopping dari keras dengan memonitor akurasi dari data validasi (mode maksimum dengan aptience = 0). 

Dataset untuk pelatihan (training) dan testing diperoleh dari https://drive.google.com/drive/folders/1sCF0gNg5sFseZFD5LGJzdh5qzaMIv7Ip
