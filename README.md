<h1>Kelompok 3 A1 Kecerdasan Buatan</h1>
<ul>
  <li>2009106012 - Fathia Nuq Qamarina</li>
	<li>2009106020 - Rausyanfikr Adi Karmayoga</li>
	<li>2009106029 - Muhamad Rizky Nilzamyahya</li>
</ul>

**Table of Contents**
- [Jobs Desk](#jobs-desk--)
- [Mengklasifikasi Jumlah Angka Pada Jari Tangan Kanan dan Kiri](#mengklasifikasi-jumlah-angka-pada-jari-tangan-kanan-dan-kiri)
- [Dataset](#dataset)
- [Labels](#labels)
- [Tahap - Tahap Pengerjaan](#tahap---tahap-pengerjaan-)
  - [Data Collecting](#1-data-collecting)
  - [Data Preprocessing - Data Augmentasi](#2-data-preprocessing---data-augmentasi)
  - [Data Modelling](#3-data-modelling)
  - [Prediksi Gambar Menggunakan Model](#4-prediksi-gambar-menggunakan-model)

<h2>Jobs Desk : </h2>
<ul>
	<li>Rausyanfikr Adi Karmayoga : Ketua Kelompok, Data Augmentasi(preprocessing)</li>
  <li>Fathia Nuq Qamarina : Data Collecting, Data Visualisasi</li>
	<li>Muhamad Rizky Nilzamyahya : Data Modelling</li>
</ul>

<h2>Mengklasifikasi Jumlah Angka Pada Jari Tangan Kanan dan Kiri</h2>

Tujuan Akhir:
<br>
<p>Setelah memasukkan data berupa banyak model gambar jari, mulai dari 0 sampai 5 sebelah kiri dan 0 sampai 5 jari kanan, mesin akan mempelajari foto foto tersebut sehingga dapat membedakan mana jari yang berangka 0 maupun berjumlah lainnya, apakah itu menggunakan tangan kiri ataupun kanan</p>
<p>Training Data menggunakan Data Train dan Data Validation</p>
<p>Melakukan Prediksi menggunakan Data Test</p>

<h2>Dataset</h2>

<p>Kami mengambil salah satu dataset yang kami temukan di internet.
Kaggle Dataset URL: https://www.kaggle.com/datasets/koryakinp/fingers</p>
<p>BY : PAVEL KORYAKIN</p>
<br>
	<p>Dataset terdiri dari 21600 gambar jari-jari tangan kanan dan kiri.</p>
	<p>Semua Gambar berukurang 128 x 128 pixels</p>
	<ul>
		<li>Gambar Data Train Terdiri dari 18000</li>
		<li>Gambar Data Test Terdiri dari 3600</li>
		<li>Gambar Data Validation diambil dari Data Train dan Test</li>
	</ul>
	<p>Jumlah Dataset menjadi :</p>
	<ul>
		<li>Gambar Data Train : 15120</li>
		<li>Gambar Data Test : 2160</li>
		<li>Gambar Data Validation : 4320</li>
		<p>Dengan Target Ukuran 50x50 pixels</p>
	</ul>
	<p>Spliting dengan rasio : </p>
	<p> Train : Val : Test = 70% : 20% : 10% </p>

<h2>Labels</h2>

<p>Label data diambil dari 2 karakter akhir nama file</p>
<ul>
		<li>L/R : menunjukkan tangan kanan atau kiri</li>
		<li>0,1,2,3,4,5 : menunjukkan angka </li>
	</ul>

<h2>Tahap - Tahap Pengerjaan :</h2>

### 1. Data Collecting
<p> Membuat Folder Data Validation, dari Data Train & Test</p>
<p> Mengetahui Jumlah data perfolder, label,dan dimensinya</p>
<p> Visualisasi 1 Gambar setiap folder : train,test,val</p>
<p> Visualisasi Data Sampel dari Data Train</p>

### 2. Data Preprocessing - Data Augmentasi
<p>Membuat Data Gambar Augmentasi dan Visualisasi Data Augmentasi</p>
<p>Membuat Normalisasi dan Encoding dari Folder Data Test</p>

### 3. Data Modelling
<p>Membuat Model Sequential dan Visualisasi : Accuracy & Loss Model</p>
<p>Evaluasi Model dan Save Model</p>

### 4. Prediksi Gambar Menggunakan Model
<p>Membuat Model Prediksi dengan Folder Data Test</p>
<p>Visualisasi Hasil Prediksi dengan menampilkan label aktual dan label prediksi</p>
<br>


![dataset-cover](https://user-images.githubusercontent.com/74334625/205540490-c7a620d3-0e3b-4f01-ae7c-4489e2c24305.jpg)
