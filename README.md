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
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
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
  
</ol>
- [x] Add Changelog
- [x] Add back to top links
- [ ] Add Additional Templates w/ Examples
- [ ] Add "components" document to easily copy & paste sections of the readme
- [ ] Multi-language Support
    - [ ] Chinese
    - [ ] Spanish

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
