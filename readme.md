<h1>Capstone Project Module 3 <h1>
<h3>Machine Learning<h3>
<h3>By Nabil Rakha Dwitya<h3>

<h4> <b> Context </b> </h4>

Deposito berjangka menjadi produk keuangan yang diminati karena menawarkan imbal hasil tetap. Di tengah persaingan ketat, bank perlu strategi efektif untuk menarik nasabah baru. Kampanye pemasaran menjadi salah satu cara. Dengan memanfaatkan data kampanye sebelumnya, bank ingin mengidentifikasi calon nasabah yang berpotensi menempatkan dana di deposito berjangka. Analisis data ini bertujuan untuk memahami karakteristik nasabah yang tertarik pada deposito. Informasi ini akan digunakan untuk meningkatkan efektivitas kampanye pemasaran, sehingga bank dapat lebih efisien dalam menjangkau target pasar dan meningkatkan jumlah nasabah deposito.

<h4> <b> Problem Statement </b> </h4>

Bank perlu menyeleksi calon nasabah sebelum kampanye untuk menghemat biaya dan waktu, dengan hanya menargetkan mereka yang berpotensi tertarik deposito berjangka

<h4> <b> Goals </b> </h4>

Dengan memprediksi nasabah yang berpotensi deposito dan mengidentifikasi faktor pendorongnya, bank dapat meningkatkan efektivitas kampanye dan merancang pendekatan yang lebih personal.

<h4> <b> Analytic Approach </b> </h4>

Dengan menganalisis data untuk menemukan pola nasabah deposito, model klasifikasi machine learning akan dibuat untuk memprediksi potensi deposito nasabah baru

<h4> <b> Metric Evaluation </b> </h4>

Type 1 error : False Positive <br>
Nasabah terprediksi akan mendeposit tetapi ternyata tidak <br>
Sumber daya seperti biaya dan waktu akan terbuang sia-sia

Type 1 error : False Negative <br>
Nasabah terprediksi tidak akan mendeposit tetapi ternyata mendeposit <br>
Bank akan kehilangan calon nasabah yang berpotensi mendeposit uang

Untuk meminimalkan biaya kampanye dengan mengurangi kesalahan prediksi nasabah yang tidak deposito (False Positive) dan tetap memperhatikan prediksi nasabah potensial, model akan dievaluasi menggunakan ROC AUC dan confusion matrix.