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

1. Deskriptif
* Penyajian deskriptif adalah penjelasan naratif atau dalam bentuk teks tentang bagaimana algoritma berfungsi.
* Ini sering digunakan dalam bahasa manusia yang mudah dipahami dan diikuti oleh pengembang atau pembaca algoritma.
* Deskripsi langkah demi langkah algoritma diberikan dalam bahasa alami atau bahasa pemrograman yang mudah dipahami.