<h1 style=" text-align: center; font-weight: bold;">TEST CODING IMV 2024/2025</h1>

<img title="a title" alt="Alt text" src="display/banner.png">

## ***PERATURAN TES CODING***

1. Tes coding dilakukan secara individu.
2. Dilarang bekerja sama, memberikan bantuan calon asisten lain, serta melakukan kecurangan dalam bentuk dan cara apapun. Jika terbukti melakukan kecurangan, calon asisten akan dikeluarkan dari proses rekruitasi.
3. Tidak diperkenankan keluar ruangan selama tes coding berlangsung.
4. File yang dibutuhkan selama Tes Coding IMV 2024/2025 dapat diakses pada folder `assets` pada repository github ini.
5. Calon asisten diperbolehkan membuka semua sumber seperti dokumentasi, forum, atau sumber lainnya di internet.
6. **Tidak diperkenankan menggunakan ***AI Tools*** dalam bentuk apapun.**
7. Waktu pengerjaan maksimal **100 menit**, bagi yang sudah selesai diperkenankan untuk tetap ditempat dan menunggu arahan dari asisten.
8. Calon asisten diperbolehkan minum selama tes coding berlangsung.
9. Tes coding harus dikumpulkan melalui Google Form yang dapat diakses melalui tautan berikut: **LINK PENGUMPULAN**
10. Berkas yang harus dikumpulkan adalah file `.py` atau `.ipynb` serta `screenshoot` hasil output setiap program sesuai dengan nomor soal. Berkas dikumpulkan dalam bentuk `.rar` atau `.zip` dengan format sebagai berikut: **NAMA_NIM.rar/NAMA_NIM.zip**.

    **Strukur folder yang dikumpulkan**
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

## ***SOAL TES CODING***

### ***Tes Potensi Akademik***

1. Harga sebuah GPU dan sebuah Webcam adalah `Rp5.500.000`. Jika harga GPU lebih besar `Rp5.000.000` dari harga Webcam. Berapakah harga dari masing-masing GPU dan Webcam? Jelaskan sesederhana mungkin!

2. Sebuah kereta cepat berangkat dari stasiun Bandung ke stasiun Jakarta dengan kecepatan konstan. Waktu tempuh kereta cepat adalah `30 menit`. Jika kereta berjalan `50km/jam` lebih cepat, waktu tempuh berkurang `10 menit`. Berapakah jarak antara stasiun Bandung dan Jakarta? Jelaskan sesederhana mungkin!

3. *Pencuri dan Polisi*

    Petunjuk yang diberikan: `polisi selalu berkata jujur` dan `pencuri selalu berkata bohong`. Suatu hari ada suatu kasus pencurian yang melibatkan polisi dan pencuri. 

    Disini kita ditugaskan untuk mencari siapa pencuri dan siapa polisi. Terdapat `3 tersangka` yaitu Hari, Budi dan Lestari. 
    Ketika dilakukan interogasi, masing- masing dari mereka memberikan pernyataan 

    Hari : "Salah satu pernyataan yang saya katakan adalah benar, yaitu Budi adalah pencuri atau saya adalah polisi" 

    Lestari : "Budi bisa saja menuduh bahwa saya adalah pencuri" 

    Budi : "Lestari dan Hari bukanlah seorang polisi" 

    Tentukan siapa yang merupakan polisi dan pencurinya!

### ***Tes Coding : Basic Python***

1. Buatlah program sederhana dengan output seperti dibawah! (Gunakan Looping)

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

2. Terdapat 2 buah list dengan panjang acak. Buatlah sebuah fungsi untuk melakukan operasi [**konvolusi**](https://en.wikipedia.org/wiki/Convolution) dari dua list tersebut! **(dilarangan menggunakan library external)**

    ```python
    # EXAMPLES

    # Two random length lists
    a = [1, 2, 3, 4, 5]
    b = [1, 1, 1]
    # Expected result
    [1, 3, 6, 9, 12, 9, 5]

    # Two random length lists
    x = [1, 2, 3, 4, 5]
    y = [4, 3, 2, 1, 2, 3, 4]
    # Expected result
    [4, 11, 20, 30, 42, 33, 30, 30, 34, 31, 20]
    ```

### ***Tes Coding : Image Processing***

1. Transformasikan gambar dibawah ini ke domain frekuensi lalu kembalikan ke domain 

2. Lakukan *image pre-processing* berupa flip horizontal, flip vertikal, dan transpose pada gambar `emma.jpg` lalu simpan masing-masing hasil *image pre-processing* tersebut dalam file baru (emma_flip_vertikal.jpg, emma_flip_vertikal.jpg, emma_transpose.jpg) 

    ![Emma!](/display/emma_preprocessing.jpg "Emma")

3. Lakukan *image segmentation* pada gambar `ashlyn.jpg` lalu simpan hasil masking dan hasil final tersebut dalam file baru (`ashlyn_mask.jpg`, `ashlyn_final.jpg`)

    ![Ashlyn!](/display/ashlyn_segmentation.jpg "Ashlyn")

### ***SOAL BONUS!***

1. (Denoising Image)