# 1. Konsep Dasar Algoritma dan Pemrograman

## 1.1 Pengertian Algoritma
Komputer hanyalah suatu alat yang diinstruksikan oleh manusia untuk menyelesaikan masalah dengan cepat, akurat, dan berulang-ulang tanpa bosan dan lelah, pandangan bahwa komputer adalah mesin yang "pintar" adalah salah. Nama "program" mengacu pada sekumpulan arahan yang dimaksudkan untuk menyelesaikan masalah tersebut. Program harus ditulis dalam bahasa yang komputer dapat memahami agar dapat digunakan. Bahasa pemrograman adalah bahasa komputer yang digunakan untuk menulis program. Algoritma adalah urutan langkah-langkah yang sistematis yang digunakan untuk menyelesaikan sebuah masalah. Di bidang pemrograman, algoritma berarti solusi, dan ketika seseorang berbicara tentang algoritma dalam bidang ini, mereka bermaksud untuk menemukan solusi untuk suatu masalah yang perlu diselesaikan menggunakan komputer. Agar algoritma dapat dipahami dan dilaksanakan oleh komputer, algoritma harus dibuat secara runut. Dalam pembuatan algoritma, analisis kasus sangat penting. Ini menunjukkan proses apa yang diperlukan untuk menyelesaikan masalah yang harus diselesaikan.

Kata algoris dan ritmis pertama kali diungkapkan oleh **Abu Ja'far Mohammad Ibn Musa Al Khowarizmi ** (825M) dalam buku Al-Jabr Wa-al Muqobla. Istilah "algoritma" berasal dari kata "algoris". Berarti dalam pemrograman algortima suatu metode khusus yang tepat yang terdiri dari sejumlah langkah yang terstruktur dan ditulis secara sistematis yang akan dikerjakan untuk menyelesaikan masalah dengan bantuan komputer.

![Abu Ja'far Mohammad Ibn Musa Al Khowarizmi]
![image](https://github.com/regitapermata30/Modul-Algoritma-Pemrograman/assets/46920825/6b3847f4-daac-43fa-a234-b0d6328439cd)

Seiring waktu berjalankata“algorism” berubah menjadi “algorithm” yang artinya metode perhitungan(komputasi) secara umum
Algoritma adalah Tindakan prosedur untuk memecahkan masalah dalam hal Tindakan yang dieksekusi, dan urutan Tindakan ini akan dieksekusi (Binus University, 2013) 

Algoritma dapat ditemukan dalam banyak aspek kehidupan sehari-hari. Berikut adalah beberapa contoh:

1. **Resep Masakan**: Mengikuti resep masakan adalah contoh yang sederhana dari algoritma. Resep memberikan instruksi langkah demi langkah tentang bagaimana memasak suatu hidangan. Anda mengikuti langkah-langkah ini secara berurutan untuk mencapai hasil yang diinginkan.

2. **Navigasi GPS**: Ketika Anda menggunakan aplikasi navigasi GPS di smartphone Anda, algoritma bekerja di belakang layar untuk menghitung rute tercepat atau terpendek ke tujuan Anda. Algoritma ini memperhitungkan data lalu lintas, jarak, dan kecepatan untuk memberikan arahan kepada pengemudi.

3. **Mesin Cuci**: Mesin cuci juga menggunakan algoritma untuk mengatur siklus pencucian. Algoritma ini mengatur waktu, suhu air, putaran, dan proses pencucian lainnya untuk memastikan pakaian dicuci dengan efisien.

4. **Pengurutan Barang di Supermarket**: Ketika Anda mengunjungi supermarket, barang-barang sering diatur berdasarkan algoritma tertentu. Misalnya, produk-produk makanan dapat dikelompokkan berdasarkan jenisnya, sehingga memudahkan pelanggan untuk menemukan yang mereka butuhkan.

5. **Pengenalan Wajah di Perangkat Elektronik**: Banyak perangkat elektronik seperti ponsel pintar menggunakan algoritma pengenalan wajah untuk membuka kunci perangkat. Algoritma ini membandingkan ciri-ciri wajah yang ada dengan data wajah yang telah disimpan untuk memberikan akses.

6. **Pencarian di Mesin Pencari**: Ketika Anda menggunakan mesin pencari seperti Google, algoritma kompleks digunakan untuk menentukan urutan hasil pencarian yang paling relevan. Algoritma ini mempertimbangkan berbagai faktor, seperti kata kunci, kualitas situs web, dan sejarah pencarian pengguna.

7. **Rute Transportasi Umum**: Ketika Anda mencari rute menggunakan transportasi umum, seperti bus atau kereta, algoritma perencanaan rute akan menghitung kombinasi yang paling efisien dari angkutan umum yang tersedia untuk mencapai tujuan Anda.

8. **Pengaturan Jadwal**: Penggunaan algoritma dalam perangkat lunak pengaturan jadwal membantu Anda mengatur waktu dan tugas dengan efisien, memprioritaskan pekerjaan yang harus diselesaikan, dan menghindari tumpang tindih dalam jadwal.

Algoritma adalah bagian integral dari teknologi dan kehidupan sehari-hari kita, membantu kita menjalani kehidupan yang lebih teratur, efisien, dan nyaman.

* Secara umum, definisi algoritma berarti: Langkah-langkah yang sistematis dan logis untuk menyelesaikan masalah (INPUT) sehingga menghasilkan penyelesaian (OUTPUT) yang diinginkan.
* Urutan Langkah Langkah yang disusun secara logis dan sistematis untuk memcahkan suatumasalah. Algoritma haruslah logis atau benar, artinya algoritma harus memberikankeluaran yang dikehendaki dari sejumlah masukan yang diberikan.
 
![image](https://github.com/regitapermata30/Modul-Algoritma-Pemrograman/assets/46920825/1d027663-a91f-413c-b12f-b50866c5e636)

Contoh algoritma di kehidupan sehari-hari adalah **mesin penjual otomatis (vending machine)**:

**Input**:
- Pengguna memasukkan uang atau koin ke dalam mesin.
- Pengguna memilih produk yang ingin dibeli dengan menekan tombol yang sesuai.

**Proses**:
- Mesin menerima uang atau koin dan memeriksa apakah jumlahnya cukup untuk membeli produk yang dipilih.
- Jika jumlah uang cukup, mesin mengeluarkan produk yang dipilih.
- Jika jumlah uang kurang, mesin menolak transaksi dan mengembalikan uang yang dimasukkan oleh pengguna.
- Mesin juga dapat memberikan kembalian jika jumlah uang yang dimasukkan lebih besar dari harga produk.

**Output**:
- Jika uang cukup, pengguna menerima produk yang dipilih.
- Jika uang tidak cukup, pengguna menerima kembalian atau peringatan bahwa uangnya kurang.

Algoritma mesin penjual otomatis ini adalah contoh sederhana dari bagaimana input (uang/koin dan pilihan produk), proses (pengecekan uang, pemilihan produk, dan pengeluaran produk), dan output (produk atau kembalian) bekerja bersama untuk menyediakan layanan yang diinginkan oleh pengguna.

Ciri-ciri algoritma yang baik adalah:

1. **Ketepatan (Precision)**: Algoritma harus memberikan hasil yang akurat dan sesuai dengan yang diharapkan. Hasilnya harus benar dan relevan dengan masalah yang sedang dipecahkan.

2. **Efisiensi (Efficiency)**: Algoritma harus dirancang untuk bekerja dengan cepat dan menggunakan sumber daya yang efisien, seperti waktu dan memori. Ini penting untuk menangani masalah dengan efisien bahkan pada skala besar.

3. **Kemudahan dipahami (Clarity)**: Algoritma harus ditulis dengan cara yang mudah dimengerti oleh manusia. Ini membantu dalam pemahaman, pemeliharaan, dan debugging algoritma oleh pengembang atau orang lain yang bekerja dengannya.

4. **Reusabilitas (Reusability)**: Algoritma yang baik dapat digunakan kembali dalam berbagai konteks atau dapat diintegrasikan ke dalam berbagai program. Ini meningkatkan efisiensi pengembangan perangkat lunak.

5. **Fleksibilitas (Flexibility)**: Algoritma sebaiknya dapat mengatasi berbagai situasi dan masalah yang berbeda. Mereka harus dapat diadaptasi dengan mudah jika perubahan diperlukan.

6. **Terbukti (Proven)**: Algoritma yang baik memiliki dasar matematis atau pengujian empiris yang mendukung keandalannya. Ini berarti telah dibuktikan bahwa algoritma tersebut akan memberikan hasil yang benar dalam semua situasi yang sesuai.

7. **Memiliki langkah-langkah terdefinisi (Well-Defined Steps)**: Algoritma harus memiliki langkah-langkah yang jelas dan terdefinisi dengan baik, sehingga tidak ada ambiguitas dalam pelaksanaan mereka.

8. **Efisien dalam Penggunaan Memori (Memory Efficiency)**: Algoritma sebaiknya tidak menghabiskan terlalu banyak memori yang tidak perlu. Mereka harus mengelola penggunaan memori dengan baik.

9. **Terstruktur (Structured)**: Algoritma yang baik memiliki struktur yang baik dan terorganisir dengan baik. Ini membantu dalam pemahaman algoritma dan memungkinkan untuk mengidentifikasi bagian-bagian yang dapat dioptimalkan atau diperbaiki.

10. **Dapat diimplementasikan (Implementable)**: Algoritma harus dapat diimplementasikan dalam bahasa pemrograman yang sesuai dengan sumber daya yang tersedia.

11. **Dapat Diuji (Testable)**: Algoritma harus dapat diuji dengan mudah untuk memverifikasi kebenaran hasilnya dan untuk mendeteksi kesalahan atau masalah potensial.

12. **Sederhana (Simplicity)**: Kekompleksan yang tidak perlu harus dihindari. Algoritma yang sederhana lebih mudah dipahami, dipelihara, dan diperbaiki.

Memiliki algoritma yang memenuhi ciri-ciri ini sangat penting dalam pengembangan perangkat lunak yang efektif dan handal.

## 1.2 Penyajian Algoritma

Penyajian algoritma terbagi menjadi 
* Deskriptif
* Flowchart
* Pseudocode
* Syntac

**1. Deskriptif**
* Penyajian deskriptif adalah penjelasan naratif atau dalam bentuk teks tentang bagaimana algoritma berfungsi.
* Ini sering digunakan dalam bahasa manusia yang mudah dipahami dan diikuti oleh pengembang atau pembaca algoritma.
* Deskripsi langkah demi langkah algoritma diberikan dalam bahasa alami atau bahasa pemrograman yang mudah dipahami.

Sebagai contoh misalnya algoritma menentukan bilangan terbesar dari 3 bilangan berikut ini:
Algoritma Menentukan_bilangan_terbesar_dari_3_bilangan :

1. Meminta input 3 bilangan dari user, misalkan bilangan a, b, dan c.
2. Apabila bilangan a lebih besar dari b maupun c, maka bilangan a
merupakan bilangan terbesar
3. Jika tidak (bilangan a tidak lebih besar dari b atau c) berarti bilangan a
sudah pasti bukan bilangan terbesar. Kemungkinannya tinggal bilangan b
atau c. Apabila bilangan b lebih besar dari c, maka b merupakan bilangan
terbesar. Sebaliknya apabila bilangan b tidak lebih besar dari c, maka
bilangan c merupakan yang terbesar.
4. Selesai.

Sebagai contoh lain:

CONTOH:
menemukan bilangan terbesar dalam sebuah deretan angka (tak berurut). Solusinya membutuhkan pemeriksaan setiap angka dalam deret, tapi hanya sekali. 
Penyelesaian:
Input 		: Deret angka (list)
Output       : Angka terbesar dari elemen list
Proses;
1. Asumsikan angka pertama pada list adalah terbesar.
2. lakukan iterasi untuk mengecek angka selanjutnya.
3. apabila angka ke-n > ke-(n+1), maka angka terbesar adalah ke-n. apabila angka ke-n < ke-(n+1), maka angka terbesar adalah ke-(n+1). 
4. Bila tidak ada lagi angka tersisa pada deret, angka terbesar sekarang adalah angka terbesar.

**2. Flowchart**
* Flowchart adalah representasi visual dari algoritma dalam bentuk diagram yang terdiri dari simbol-simbol geometris seperti kotak, panah, dan berlian.
* Setiap simbol mewakili langkah-langkah atau keputusan dalam algoritma, dan panah menghubungkannya untuk menunjukkan alur eksekusi.
* Flowchart membantu pengguna untuk secara visual melihat aliran logika dan cabang keputusan dalam algoritma.

Berikut gambar
![image](https://github.com/regitapermata30/Modul-Algoritma-Pemrograman/assets/46920825/84f45787-4b8e-45d6-8586-c2eaef7fef72)

Aturan dalam membuat Flowchart:
* Flowchart digambarkan dari halaman atas ke bawah dan dari kiri kekanan.
* Aktivitas yang digambarkan harus didefinisikan secara hati-hati dan definisi ini harus dapat di mengerti oleh pembacanya
* Kapan aktivitas dimulai dan berakhir harus ditentukan secara jelas.
* Setiap langkah dari aktivitas harus diuraikan dengan menggunakan deskripsi kata kerja
* Setiap langkah dari aktivitas harus berada pada urutan yang benar.
*  Lingkup dan range dari aktifitas yang sedang digambarkan harusditelusuri dengan hati-hati. Percabangan-percabangan yang memotong aktivitas yang sedang digambarkan tidak perlu digambarkan pada flowchart yang sama. Simbol konektor harus digunakan dan percabangannya diletakan pada halaman yang terpisah atau hilangkan seluruhnya bila percabangannya tidak berkaitan dengan sistem.
* Gunakan simbol-simbol flowchart yang standar.



Contoh flowchart:
1. FLowchart Berurutan:
<img width="207" alt="image" src="https://github.com/regitapermata30/Modul-Algoritma-Pemrograman/assets/46920825/fe43f9a1-4f07-425e-be5b-49a5e75a1190">

2. Flowchart Bercabang
Dalam flowchart ini biasanya membutuhkan decision.
![image](https://github.com/regitapermata30/Modul-Algoritma-Pemrograman/assets/46920825/ee6490fa-bafb-47a2-931e-2f5a8bda820b)
![image](https://github.com/regitapermata30/Modul-Algoritma-Pemrograman/assets/46920825/67472304-251e-40c0-9948-b03314becd49)

3. Flowchart Looping
![image](https://github.com/regitapermata30/Modul-Algoritma-Pemrograman/assets/46920825/9f964d05-225d-4e4d-be44-09f4d0ac5715)
![image](https://github.com/regitapermata30/Modul-Algoritma-Pemrograman/assets/46920825/a638898c-dc3c-4863-9acb-f6e84aa99406)


![image](https://github.com/regitapermata30/Modul-Algoritma-Pemrograman/assets/46920825/eaf37493-3cdb-47f3-8cfb-aae041ce2f18)

**3. Pseudocode**
Pseudocode adalah sebuah metode penulisan menggunakan bahasa sederhana untuk mengekspresikan desain algoritma. Pseudocode bermanfaat untuk mempermudah manusia untuk memahami algoritma karena lebih mudah dipahami dibandingkan dengan bahasa pemrograman. Penulisan pseudocode tidak memiliki aturan pasti namun harus logis. Berikut saran untuk penulisan pseudocode:

* Menggunakan huruf kapital untuk kode perintah (misalnya IF, ELSE, dan THEN)
* Setiap pernyataan (statement) ditulis dalam satu baris
* Menggunakan indentasi
* Spesifik
* Simpel

Umumnya dalam penulisan pseudocode dibagi kedalam tiga bagian:
1. Bagian Judul, umumnya pada bagian judul diawali dengan penulisan “PROGRAM” yang kemudian diikuti oleh nama algoritma.
2. Bagian Deklarasi, bagian ini variabel yang dimiliki algoritma dideklarasikan. Variabel ini dapat beruba bilangat bulat, bilangan pecahan, karakter, boolean, dan lain sebagainya.
3. Bagian Algoritma, yaitu bagian yang berisikan sekumpulan perintah algoritma. Perintah algoritma dapat berupa perulangan, kondisional ataupun runtutan.

***
ALGORITMA Mencari Nilai Maksimum
1. Masukkan dua angka, Angka1 dan Angka2
2. Jika Angka1 lebih besar dari Angka2, maka:
     a. Maksimum adalah Angka1
   Jika tidak, maka:
     a. Maksimum adalah Angka2
3. Tampilkan Maksimum
4. Selesai
***

Pseudocode yang ditulis di dalam buku ini akan menyerupai (meniru) syntaxsyntax dalam bahasa Pascal atau C . Namun dibuat sesederhana mungkin sehingga
tidak akan ada kesulitan bagi pembaca untuk memahami algoritma-algoritma dalam buku ini. Contoh algoritma menentukan bilangan terbesar dari tiga bilangan yang ditulis dalam bentuk pseudocode :
<img width="266" alt="image" src="https://github.com/regitapermata30/Modul-Algoritma-Pemrograman/assets/46920825/a14f62e4-262f-42b3-89a7-28678ece4534">
<img width="275" alt="image" src="https://github.com/regitapermata30/Modul-Algoritma-Pemrograman/assets/46920825/a92415ad-6347-44cd-bed4-6d4fd1d42956">




