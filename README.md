# AplikasiPerhitunganDiskon
 
## Identitas
Nama: Ayu Atut Khofifah

NPM: 2210010553

## Penjelasan Program

**Aplikasi Perhitungan Diskon**

Program ini dirancang untuk membantu pengguna menghitung harga akhir suatu barang setelah diskon diberikan. Pengguna dapat memasukkan harga asli barang, memilih persentase diskon, dan mendapatkan hasil akhir berupa harga setelah diskon dan jumlah penghematan yang diperoleh.

### Komponen Program
1. **Komponen GUI**: Aplikasi ini menggunakan komponen GUI (Graphical User Interface) yang terdiri dari JFrame, JPanel, JLabel, JTextField, JComboBox, dan JButton untuk membuat antarmuka yang interaktif bagi pengguna.  
   - **JFrame**: Sebagai wadah utama aplikasi.
   - **JPanel**: Untuk mengatur tata letak komponen di dalam JFrame.
   - **JLabel**: Memberikan label informasi seperti "Harga Asli", "Diskon", dan "Harga Akhir".
   - **JTextField**: Digunakan untuk memasukkan harga asli.
   - **JComboBox**: Digunakan untuk memilih persentase diskon.
   - **JButton**: Tombol untuk melakukan perhitungan diskon.

2. **Logika Program**: Program ini melakukan perhitungan aritmatika sederhana untuk menghitung harga setelah diskon dan menangani kesalahan input menggunakan penanganan pengecualian. Hal ini memastikan program tetap berjalan meskipun terdapat kesalahan input dari pengguna.

3. **Events**:
   - **ActionListener**: Diterapkan pada tombol "Hitung" untuk memicu proses perhitungan saat tombol ditekan.
   - **ItemListener**: Diterapkan pada JComboBox untuk memperbarui persentase diskon saat pengguna memilih opsi yang berbeda.

4. **Variasi Tambahan**:
   - Program ini juga memiliki beberapa variasi tambahan, seperti opsi untuk memasukkan kode kupon diskon tambahan, penggunaan JSlider sebagai alternatif JComboBox untuk memilih persentase diskon, serta fitur riwayat perhitungan diskon yang memungkinkan pengguna melihat perhitungan sebelumnya.

### Cara Kerja Program
Pengguna memasukkan harga asli barang dan memilih persentase diskon melalui JComboBox atau JSlider. Saat tombol "Hitung" ditekan, program akan menghitung harga akhir berdasarkan harga asli dan persentase diskon yang dipilih. Jika ada kode kupon diskon tambahan, nilai diskon tambahan akan diterapkan pada harga yang sudah didiskon. Hasil perhitungan akan ditampilkan berupa harga akhir dan jumlah penghematan yang diperoleh.

## Keunggulan Program

1. **Mudah Digunakan**: Aplikasi ini dirancang dengan antarmuka yang sederhana dan intuitif, sehingga pengguna dapat dengan mudah memasukkan harga asli, memilih persentase diskon, dan mendapatkan hasilnya tanpa kebingungan.

2. **Akurasi Perhitungan**: Program ini memastikan perhitungan diskon dilakukan dengan tepat. Pengguna dapat melihat harga akhir serta jumlah penghematan secara akurat, membantu dalam pengambilan keputusan saat berbelanja.

3. **Fleksibilitas Pilihan Diskon**: Pengguna dapat memilih persentase diskon melalui JComboBox atau JSlider, memberikan fleksibilitas dalam cara pengguna memilih nilai diskon yang diinginkan.

4. **Dukungan Kupon Diskon Tambahan**: Selain persentase diskon biasa, program ini memungkinkan pengguna memasukkan kode kupon diskon tambahan, sehingga memberikan opsi lebih banyak untuk menghitung harga akhir dengan berbagai potongan harga.

5. **Fitur Riwayat Perhitungan**: Program ini menyediakan fitur riwayat perhitungan diskon, yang memungkinkan pengguna melihat hasil perhitungan diskon yang telah dilakukan sebelumnya. Ini berguna untuk perbandingan atau catatan perhitungan diskon.

6. **Penanganan Kesalahan Input**: Dengan adanya penanganan pengecualian, program ini dapat menangani input yang salah atau tidak valid, sehingga tidak mudah crash dan memberikan pengalaman yang lebih aman bagi pengguna.

7. **Interaktif dan Dinamis**: Kombinasi dari ActionListener dan ItemListener membuat aplikasi ini interaktif. Aplikasi merespons setiap kali pengguna menekan tombol "Hitung" atau mengubah pilihan diskon, membuat pengalaman penggunaan lebih dinamis.

8. **Multifungsi untuk Berbagai Kebutuhan**: Aplikasi ini cocok digunakan untuk menghitung diskon pada berbagai situasi, baik untuk penggunaan sehari-hari saat berbelanja maupun untuk perhitungan bisnis sederhana.

Dengan keunggulan-keunggulan ini, aplikasi perhitungan diskon Anda menjadi alat yang bermanfaat dan praktis, baik untuk pengguna individu maupun bisnis kecil yang ingin melakukan perhitungan diskon secara cepat dan akurat.

## Ini dia Screenshot Programnya

**1.** ![ss an AplikasiPerhitunganDiskon](https://github.com/user-attachments/assets/400a33eb-df1b-4d67-90fb-12d41fe6a6d5)


**2.** ![ss an AplikasiPerhitunganDiskon2](https://github.com/user-attachments/assets/8ffe6900-d2a4-4df9-bfe2-3576f2fcf1dd)


**3.** ![ss an APlikasiPerhitunganDiskon3](https://github.com/user-attachments/assets/e0529aa2-171f-49ad-8c7e-d3d1ecdc5013)


