<div id="top"></div>
  <h3 align="center">Visualisasi Data Kemiskinan pada Provinsi di Indonesia 2018-2021 Menggunakan Peta Interaktif</h3>
  <p align="center">Nurul Azizah (221911049, 3SD2)</p><br/>

</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Daftar Isi</summary>
  <ol>
    <li>
      <a href="#latar-belakang">Latar Belakang</a>
    </li>
    <li>
      <a href="#tujuan-penelitian">Tujuan Penelitian</a>
    </li>
    <li><a href="#metode-penelitian">Metode Penelitian</a></li>
    <ul>
      <li><a href="#data-dan-sumber-data">Data dan Sumber Data</a></li>
      <li><a href="#tahapan-penelitian">Tahapan Penelitian</a></li>
    </ul>
    <li><a href="#hasil-dan-pembahasan">Hasil dan Pembahasan</a></li>
    <li><a href="#daftar-pustaka">Daftar Pustaka</a></li>
    <li><a href="#lisensi">Lisensi</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- LATAR BELAKANG -->
## Latar Belakang

<p>Berdasarkan hasil Sensus Penduduk 2020, Indonesia memiliki luas sebesar 1,9 juta km2 dengan jumlah penduduk sebanyak 270,20 juta jiwa. Laju pertumbuhan penduduk per tahun selama 2010-2020 rata-rata sebesar 1,25 persen, melambat dibandingkan periode 2000-2010 yang sebesar 1,49 persen [1]. Permasalahan besar yang terjadi terkait dengan pembangunan hingga saat ini adalah terdapat kesenjangan antar wilayah yang tidak sejalan dengan tujuan utama Pembangunan Indonesia, yaitu pembangunan yang adil dan merata [2]. Pembangunan yang tidak merata inilah yang menjadi salah satu faktor munculnya kemiskinan di wilayah-wilayah Indonesia. Salah satu fokus pemerintahan Indonesia periode ini adalah menyetarakan kesenjangan antar daerah di seluruh wilayah Indonesia.</p>
<p>Adanya permasalahan ini, pemerintah memerlukan waktu yang lama untuk menentukan daerah-daerah yang menjadi prioritas pembangunan. Hal ini dikarenakan perlunya koordinasi antar pemerintah pusat dengan pemerintah daerah. Pemerintah pusat membutuhkan informasi dari setiap pemerintah daerah mengenai tingkat kemiskinan atau kondisi sosial ekonomi pada setiap daerah.</p>
<p>Dengan kemajuan teknologi informasi saat ini, sangat mudah untuk mendapatkan data maupun informasi terkait tingkat kemiskinan di seluruh daerah di Indonesia karena data-data telah bersifat terbuka untuk umum. Dengan adanya data yang terbuka, seharusnya informasi akan jauh lebih mudah didapatkan dan digunakan dengan cepat untuk mengatasi problem kemiskinan yang ada. Akan tetapi, data-data tersebut masih berupa publikasi statistik dan hanya dapat menjadi informasi yang berguna apabila diolah dengan baik, salah satu cara yang bisa digunakan agar informasi tersebut tersampaikan dengan baik adalah menggunakan Teknik visualisasi data.</p><br/>


<p align="right">(<a href="#top">back to top</a>)</p>


<!-- TUJUAN PENELITIAN -->
## Tujuan Penelitian

Penelitian ini bertujuan untuk :
* Menampilkan visualisasi data kemiskinan tiap provinsi di Indonesia.
* Mengetahui tingkat kemiskinan tiap provinsi di Indonesia tahun 2018-2021.
* Mengetahui perubahan tingkat kemiskinan tiap provinsi di Indonesia

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- METODE PENELITIAN -->
## Metode Penelitian

### Data dan Sumber Data
<p>Pada penelitian ini menggunakan data kemiskinan yang bersumber dari publikasi Data dan Informasi Kabupaten/Kota Tahun 2019-2021 oleh Badan Pusat Statistik serta data <i>longitude</i> dan <i>latitude</i> yang bersumber dari <i>website</i> GADM.</p>
Variabel yang digunakan pada penelitian ini meliputi:
<ol>
  <li>Provinsi berupa kode wilayah dan nama</li>
  <li>Jumlah Penduduk Miskin (000)</li>
  <li>Persentase Penduduk Miskin</li>
  <li>P1</li>
  <li>P2</li>
  <li>Garis Kemiskinan (Rp/Kap/Bulan)</li>
</ol>

### Tahapan Penelitian
<ol>
  <li><i>Data prepocessing</i></li>
    Menurut Ham dan Kamber[3], <i>data prepocessing</i> meliputi:
  <ul>
    <li>Pembersihan data</li>
    <ul>
      <li>mengisi nilai yang hilang,</li>
      <li>memperbaiki kesalahan data,</li>
      <li>mengidentifikasi atau menghapus outlier,</li>
      <li>memperbaiki data yang tidak konsisten</li>
    </ul>
    <li>Integrasi data</li>
    Menggabungkan variabel terkait dari tabel atau database
    <li>Pemilihan Data</li>
    Memilih data yang hanya berkaitan dengan proses analisis.
  </ul>
  <li>Memilih jumlah klaster</li>
  Penentuan jumlah klaster optimum akan menggunakan penelitan terdahulu yang terkait dengan klasterisasi provinsi berdasarkan data dan informasi kemiskinan.
  <li>Melakukan klasterisasi</li>
  Pada penelitian ini, klasterisasi dilakukan menggunakan fitur <i>cluster</i> yang telah terdapat pada <i>tableau</i>.
  <li>Visualisasi data</li>
  Pada penelitian ini, visualisasi data yang digunakan berupa peta map interaktif.
</ol>

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- HASIL DAN PEMBAHASAN -->
## Hasil dan Pembahasan
<ol>
  <li>Jumlah klaster</li>
  Menurut beberapa penelitian, klasterisasi yang dilakukan menggunakan klaster optimum sebanyak 5 klaster. Oleh karena itu, pada penelitian ini akan menggunakan 5 klaster.
  <li>Hasil klasterisasi dan visualisasi</li>
  Berikut merupakan tampilan dari dashboard visualisasi data kemiskinan per provinsi di Indonesia.
  
![Screenshot (1088)](https://user-images.githubusercontent.com/107758816/174447698-bc1a3db2-9679-4f7a-8c2f-453b2461380d.png)
![Screenshot (1089)](https://user-images.githubusercontent.com/107758816/174447700-c0fc67f3-4931-4ee9-b873-440cc0d82f68.png)  
![Screenshot (1091)](https://user-images.githubusercontent.com/107758816/174447692-35358446-db08-4163-8d7f-5113acf26886.png)
![Screenshot (1092)](https://user-images.githubusercontent.com/107758816/174447697-742d13ff-1993-4d6a-b64e-6d3dac0b954a.png)

</ol>

<!-- DAFTAR PUSTAKA -->
## Daftar Pustaka
[1] 	Badan Pusat Statistik, “Hasil Sensus Penduduk 2020,” Badan Pusat Statistik, Jakarta, 2021.<br/>
[2] 	Direktorat Jenderal Pembangunan Daerah Tertinggal, “Laporan Kinerja Instansi Pemerintah Tahun 2017,” Kemendesa, Jakarta, 2018.<br/>
[3]   J. Han dan M. Kamber, "Data mining concepts and techniques. Third Edition. Waltham, USA, 2012.<br/>

<!-- LISENSI -->
## Lisensi

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

NURUL AZIZAH - 221911049(3SD2) - 221911049@stis.ac.id

Project Link: [Visualisasi Tingkat Kemiskinan per Provinsi di Indonesia](https://public.tableau.com/app/profile/nurul.azizah1070/viz/VisualisasiTingkatKemiskinanperProvinsidiIndonesia/Dashboard1)

<p align="right">(<a href="#top">back to top</a>)</p>
