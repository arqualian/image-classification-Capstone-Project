![Poster Kalsifikasi Gambar Resto](https://github.com/arqualian/image-classification-Capstone-Project/assets/60522938/ac1e3405-5575-46bb-b3c9-15adf47d8a35)

# Klasifikasi Gambar Menggunakan EfficientNetV2M untuk Restoran

Projek Capstone Merdeka Belajar Kampus Merdeka (MBKM) Infinite Learning Indonesia

------------------------------------------------------------------------------
# Informasi 

| Point | Informasi | 
|--------------------|------------------------------|
| Nama   | Ghora Laziola |
| Kampus | Universitas Maritim Raja Ali Haji | 
| Mentor | Agistira Lamunde | 
| Project Name         | Image Classification using trained VGG-16 for Restaurant |
| Programing Language  |Python |
| Pattern              | [IBM ASL](https://github.com/IBM/ASL-Pytorch) (American Sign Language) alphabet classifier using pytorch and GPU environments on Watson Studio |
| Ibm Service          | Watson Studio, Watson Cloud Service |
| Early Build          | Visual Studio Code + Jupiter Extention |
| Library              | Keras |
| Model                | EfficientNetV2M |

------------------------------------------------------------------------------
# Rangkuman 
Dalam project ini, kita akan menggunakan pustaka Keras untuk mengklasifikasikan gambar-gambar yang dipilih secara acak dari internet. Keras menyederhanakan proses perancangan dan pelatihan model deep learning dengan menyediakan antarmuka tingkat tinggi. Gambar-gambar dari internet akan diambil menggunakan link URL dan diunduh oleh program ini. kita akan menerapkan metode transfer learning. Transfer learning adalah teknik yang memanfaatkan pengetahuan yang diperoleh dari model yang sudah dilatih sebelumnya pada tugas sebelumnya untuk mengklasifikasikan gambar-gambar baru. Pendekatan ini membantu mengurangi waktu dan sumber daya yang dibutuhkan untuk melatih model dari awal. Kita akan menggunakan model EfficientNetV2M yang sudah dilatih sebelumnya untuk tujuan ini.

Dalam notebook ini kita akan : 
- Menggunakan model EfficientNetV2M untuk klasifikasi
- mengimport Liberary yang dibutuhkan
- Menggunakan link urls gambar yang berkaitan dengan restoran agar di klasifikasi
- Mengunduh gambar dari link urls dan merubahnya ke num array
- preproses data menggunakan model EfficientNetV2M
- Menampilkan hasil prediksi

# Alur 
![Diagram ](https://github.com/arqualian/image-classification-Capstone-Project/assets/60522938/6ac9d586-95fd-4900-b3c4-ab0fce5672d8)

1. Masuk ke akun IBM Cloud
2. Menggunakan watson studio
3. Menggunakan watson cloud storage
4. Menjalankan pemrograman yang terdapat di [link](https://github.com/arqualian/image-classification-Capstone-Project/blob/main/Image_Clasification.ipynb)

# Batasan 
Dalam projek ini memiliki batasan yaitu : 
1. Tingkat akurasi mencapai 73%
2. Gambar harus sesuai format (copy image address)
3. Link harus di letakan secara manual kedalam kodingan
4. Tidak ada batasan dalam jenis gambar (bisa diluar konteks restauran). Namun dianjurkan yang sesuai dengan projek

--------------------------------------------------------------------------------------------------------------
# Saran Objek 
Tabel ini merupakan saranan item yang bisa di telusuri di internet, lalu diambil link address nya dan copy ke dalam kodingan. Mencari diluar tabel ini memungkinkan untuk diproses. 
Perabotan | Makanan / Minuman | Alat-alat | Lainnya 
----------|-------------------|-----------|----------
Kuali     | Es Krim           | Celemek   | Jam Analog  
Bufet | Baguette | Pembuka Kaleng | Balon 
Meja | Pretzel | Tutup Botol | Rak Buku 
Meja Makan | Burger Keju | Sapu | Piano 
Kursi Lipat | Hot Dog | Kaset | Payung 
Penggorengan | Pizza | Telfon genggam | Kendi Wiski 
Kulkas | Burrito | Gesper | Botol Anggur 
Keranjang | Jamur | Botol Air | Sendok 
Pemanggang Roti | Spageti | Kipas | Piring 
Lampu Meja | nanas | botol bir | Menu 

untuk daftar lengkap, silahkan lihat : 
- File Json 1000 label : [Klik disini](https://github.com/anishathalye/imagenet-simple-labels/blob/1a7c0a962e632880e85d48329b06d7848ac20e6d/imagenet-simple-labels.json) 
- file saran lengkap   : [Klik Disini](https://docs.google.com/spreadsheets/d/1XSIWMUKxZBHHYmblfaIZgHq1BGSRMYoC/edit?usp=sharing&ouid=109385220482846132254&rtpof=true&sd=true)

# Pemrosesan 

## Gambar yang di unduh dari URL 
<img width="758" alt="image" src="https://github.com/arqualian/image-classification-Capstone-Project/assets/60522938/ab8a7c17-5f72-4713-b5d7-276b499e7d54">


## Gambar dengan label hasil prediksi
<img width="658" alt="image" src="https://github.com/arqualian/image-classification-Capstone-Project/assets/60522938/17e43666-c463-43b2-b3ce-12083dc05e8f">






