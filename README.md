<h1 style="text-align: center; font-weight: bold;">TES CODING IMV 2024/2025</h1>

<img title="Banner" alt="IMV Laboratory Open Recruitment" src="display/banner.png">

<br>

## ***PERATURAN TES CODING***

1. Tes coding dilakukan secara individu.
2. Dilarang bekerja sama, memberikan bantuan calon asisten lain, serta melakukan kecurangan dalam bentuk dan cara apapun. Jika terbukti melakukan kecurangan, calon asisten akan dikeluarkan dari proses rekruitasi.
3. Calon asisten tidak diperkenankan keluar ruangan selama tes coding berlangsung.
4. File yang dibutuhkan selama Tes Coding IMV 2024/2025 dapat diakses pada folder `assets` di repository GitHub ini.
5. Calon asisten diperbolehkan membuka semua sumber seperti dokumentasi, forum, atau sumber lainnya di internet.
6. **Tidak diperkenankan menggunakan ***AI Tools*** dalam bentuk apapun.**
7. Waktu pengerjaan maksimal **100 menit**, bagi yang sudah selesai diperkenankan untuk tetap ditempat dan menunggu arahan dari asisten.
8. Calon asisten diperbolehkan minum selama tes coding berlangsung.
9. Hasil coding dikumpulkan dengan cara membuat repository pada akun GitHub pribadi calon asisten dengan format nama repository `tes-coding-imv-2024_nama_nim`. Pastikan repository bersifat **public**. Kemudian kumpulkan link repository tersebut pada [**FORM PENGUMPULAN JAWABAN**](https://forms.gle/rZRz5SJ7YC4qFnZWA). 
10. Berkas yang dikumpulkan berupa file `.py` atau `.ipynb` serta `screenshoots` hasil output setiap program sesuai dengan nomor soal.

    **Contoh strukur folder yang dikumpulkan**
    ```
        NAMA_NIM
        │
        ├── Nomor 1
        │   └── jawaban.txt
        │
        ├── Nomor 2
        │   ├── jawaban.py
        │   └── output.jpg
        │
        ├── Nomor 3
        │   ├── jawaban.ipnyb
        │   ├── output1.png
        │   └── output2.png
        │
        └── dst...
    ```

<br>

## ***SOAL TES CODING***

### ***BAGIAN I***

1. Harga sebuah GPU dan sebuah Webcam adalah `Rp5.500.000`. Jika harga GPU lebih besar `Rp5.000.000` dari harga Webcam. Berapakah harga dari masing-masing GPU dan Webcam? Jelaskan sesederhana mungkin! **[5 POINTS]**

2. Sebuah kereta cepat berangkat dari stasiun Bandung ke stasiun Jakarta dengan kecepatan konstan. Waktu tempuh kereta cepat adalah `30 menit`. Jika kereta berjalan `50km/jam` lebih cepat, waktu tempuh berkurang `10 menit`. Berapakah jarak antara stasiun Bandung dan Jakarta? Jelaskan sesederhana mungkin! **[5 POINTS]**

3. **Pencuri dan Polisi**

    Petunjuk yang diberikan: `polisi selalu berkata jujur` dan `pencuri selalu berkata bohong`.
    
    Suatu hari ada suatu kasus pencurian yang melibatkan polisi dan pencuri. Disini kita ditugaskan untuk mencari siapa pencuri dan siapa polisi. Terdapat `3 tersangka` yaitu Hari, Budi dan Lestari. Ketika dilakukan interogasi, masing- masing dari mereka memberikan pernyataan:

    > **Hari** : "Salah satu pernyataan yang saya katakan adalah benar, yaitu Budi adalah pencuri atau saya adalah polisi" 
    >
    > **Lestari** : "Hari bisa saja menuduh bahwa saya adalah pencuri" 
    >
    > **Budi** : "Lestari dan Hari bukanlah seorang polisi"

    Tentukan siapa yang merupakan polisi dan pencurinya! **[5 POINTS]**

4. Suatu hari ada lima orang yang sedang memakan apel. Sebut mereka Ari, Bani, Cia, Danny, dan Elang. Ari menghabiskan apelnya sebelum Elang tetapi setelah Cia. Bani menghabiskannya setelah Danny. Cia menghabiskan apelnya setelah Danny sebelum Bani. 

    Siapakah yang berada di urutan no 3 dalam memakan apel tersebut? **[5 POINTS]**

5. Perhatikan premis-premis berikut ini untuk menjawab pertanyaan berikut :
    - Chaca lebih bahagia daripada Rey, meskipun tugasnya tidak sebanyak Rey
    - Prita tidak sebahagia Rey dan tugasnya tidak sebanyak Rey maupun Chaca
    - Yunjin lebih bahagia daripada Chaca, tetapi tugasnya lebih banyak dari Chaca

    Dari premis tersebut, siapakah orang yang paling bahagia? **[5 POINTS]**

6. Dengan premis di pertanyaan sebelumnya, siapa orang yang paling sedikit tugasnya? **[5 POINTS]**

<br>

### ***BAGIAN II***

1. Buatlah program untuk memeriksa apakah sebuah bilangan ganjil atau genap! **[5 POINTS]**

    ```python
    # EXAMPLES

    # Input
    Masukkan angka : 68
    # Expected result
    Angka 68 adalah bilangan genap

    # Input
    Masukkan angka : 21
    # Expected result
    Angka 21 adalah bilangan ganjil
    ```

2. Buatlah program yang dapat mengecek sebuah input adalah angka Fibonnaci atau bukan! **[10 POINTS]**

    ```python
    # EXAMPLES

    # Input
    Masukkan angka : 377
    # Expected result
    Angka 377 merupakan angka fibonnaci

    # Input
    Masukkan angka : 9
    # Expected result
    Angka 9 bukan angka fibonnaci
    ```

3. Buatlah program dengan output seperti dibawah! (Gunakan Looping) **10 POINTS**

    ```python
                        *   
                      *   *   
                    *   *   *   
                  *   *   *   *   
                *   *   *   *   *   
              *   *   *   *   *   *   
            *   *   *   *   *   *   *   
              *   *   *   *   *   *   
                *   *   *   *   *   
                  *   *   *   *   
                    *   *   *   
                      *   *   
                        *   
    ```

4. Basic Python 
Lakukanlah operasi transpose pada matriks dengan ukuran minimal 3 x 3! **(dilarangan menggunakan library external)** **[10 POINTS]**
    ```python
    # Example
    matriks = [[98, 88, 78],
               [77, 78, 79],
               [66, 67, 68],
               [32, 33, 31]]

    # Expected result
    matriks_transpose = [[98, 77, 66, 32],
                         [88, 78, 67, 68],
                         [78, 79, 68, 31]]
    ```

5. Terdapat 2 buah list dengan panjang acak. Buatlah sebuah fungsi untuk melakukan operasi [**konvolusi**](https://en.wikipedia.org/wiki/Convolution) dari dua list tersebut! **(dilarangan menggunakan library external)** **[10 POINTS]**

    ```python
    # EXAMPLES

    # Two random length lists
    a = [1, 2, 3, 4, 5]
    b = [1, 1, 1]
    # Expected result
    [1, 3, 6, 9, 12, 9, 5]

    # Two Random lenght lists
    x = [1, 2, 3, 4, 5]
    y = [4, 3, 2, 1, 2, 3, 4]
    # Expected result
    [4, 11, 20, 30, 42, 33, 30,  30, 34, 31, 20]
    ```

6. Buatlah program yang dapat mengecek input kata pertama merupakan anagram untuk input kata kedua! **[10 POINTS]**

    ```python
    # EXAMPLES

    # Input
    Masukkan kata pertama : alur
    Masukkan kata kedua   : ular
    # Expected result
    alur dan ular adalah anagram

    # Input
    Masukkan kata pertama : alur
    Masukkan kata kedua   : liar
    # Expected result
    alur dan liar bukan anagram
    ```

<br>

### ***BAGIAN III***

1. Lakukan *Preprocessing* berupa *Flip Horizontal*, *Flip Vertikal*, dan *Transpose* pada gambar `emma.jpg` lalu simpan masing-masing hasil *Preprocessing* tersebut dalam file baru yaitu `emma_flip_vertikal.jpg`, `emma_flip_vertikal.jpg`, `emma_transpose.jpg`. **[10 POINTS]**

    ![emma!](/display/emma_preprocessing.jpg "Emma")

2. Lakukan *Preprocessing* pada gambar `ayon.jpeg` dengan mengubah gambar menjadi *Grayscale* dan *BnW*. Simpan hasilnya dalam file baru yaitu `ayon_grayscale.jpeg` dan `ayon_bnw.jpeg`. **[10 POINTS]**

   ![ayon!](/display/result_ahyeon.png "Ayon")

3. Lakukan transformasi fourier pada gambar `ayon.jpeg` lalu simpan hasilnya dalam file baru yaitu `ayon_fft.jpeg`. **[10 POINTS]**

    ![ayon!](/display/FFT_AHYEON.png "Ayon")

4. Lakukan *Image Preprocessing* berupa Image Rescaling dan Noise Reduction pada gambar `haku.jpg` dengan ketentuan berikut: **[15 POINTS]**
    - Image Rescaling menjadi 2 kali lipat gambar aslinya. Simpan hasilnya dalam file baru yaitu `haku_scaled.jpg`.
    - Noise Reduction menggunakan Gaussian Blur. Simpan hasilnya dalam file baru yaitu `haku_blur.jpg`. 

   ![haku!](/display/haku_preprocessing.png "Haku")

5. Lakukan *Image Segmentation* pada gambar `ashlyn.jpg` lalu simpan hasil masking dan hasil final tersebut dalam file baru yaitu `ashlyn_mask.jpg` dan `ashlyn_final.jpg`. **[10 POINTS]**

    ![ashlyn!](/display/ashlyn_segmentation.jpg "Ashlyn")

6. Lakukan *Image Segmentation* menggunakan *K-means Clustering* yang akan menghasilkan superpixel dari gambar `ponyo.jpg`. Simpan hasil *Image Segmentation* dalam file baru yaitu `ponyo_clustering.jpg`. **[10 POINTS]**

   ![ponyo!](/display/ponyo_segmentation.png "Ponyo")

<br>

### ***SOAL BONUS!***

1. Buatlah Program *Text Detection* pada `text.jpg` yang dapat memberikan bonding box dan hasil deteksi dari gambar input-annya dengan ketentuan-ketentuan berikut: **[30 POINTS]**
    - Library yang digunakan tidak ditentukan/dibebaskan oleh masing-masing peserta
    - Bounding box hasil deteksi kata berwarna merah
    - Font hasil deteksi memakai hershey duplex dan warna font harus abu-abu.

   ![text](/display/text_detection.png "Pure Text")

3. Buatlah contoh program untuk mengenali huruf. **[40 POINTS]**

    ![hasil](/display/hasil_recognition.png "Hasil")
    
    Dataset dapat diunduh melalui [**Handwritten Recognition Model**](https://www.kaggle.com/code/mohamedsherif444/handwritten-recognition-model/input)

    Ketentuan yang harus diikuti adalah berikut :
    - Hasil akhir memiliki akurasi > 70%.
    - Epoch <= 20
    - Diperbolehkan menggunakan berbagai pemrosesan gambar untuk hasil yang lebih optimal (arsitektur yang digunakan bebas, boleh melakukan augmentasi dataset)

2. Buatlah arsitektur *Convolutional Neural Network* untuk klasifikasi paru-paru normal dan paru-paru pneumonia. **[50 POINTS]**

   ![cnn](https://miro.medium.com/v2/resize:fit:828/format:webp/1*7_BCJFzekmPXmJQVRdDgwg.png "CNN")

   Dataset dapat diunduh pada [**Chest Xray Classification**](https://huggingface.co/datasets/keremberke/chest-xray-classification)

   Kriteria model yang harus dibuat:
    - Gunakan arsitektur CNN rancangan sendiri! (dilarang menggunakan *Transfer Learning*).
    - Dataset dibagi menjadi `70% training`, `20% validation` dan `10% test`.
    - Diperbolehkan untuk augmentasi dataset untuk mendapat akurasi yang lebih baik.
    - Hasil akhir memiliki akurasi > 70%.
    - Epoch <= 10.