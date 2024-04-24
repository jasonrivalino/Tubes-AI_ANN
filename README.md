# Tugas Besar Pembelajaran Mesin - IF3270
> Tugas Besar Bagian A: Implementasi Forward Propagation untuk Feed Forward Neural Network

> Tugas Besar Bagian B: Implementasi Mini-batch Gradient Descent

## Anggota Kelompok
<table>
    <tr>
        <td>No.</td>
        <td>Nama</td>
        <td>NIM</td>
    </tr>
    <tr>
        <td>1.</td>
        <td>Jason Rivalino</td>
        <td>13521008</td>
    </tr>
    <tr>
        <td>2.</td>
        <td>Muhammad Rifko Favian</td>
        <td>13521075</td>
    </tr>
    <tr>
        <td>3.</td>
        <td>Moch. Sofyan Firdaus</td>
        <td>13521083</td>
    </tr>
      <tr>
        <td>4.</td>
        <td>Fazel Ginanda</td>
        <td>13521098</td>
    </tr>
</table>


## Table of Contents
* [Deskripsi Singkat](#deskripsi-singkat)
* [Struktur File](#struktur-file)
* [Requirements](#requirements)
* [Cara Menjalankan Program](#cara-menjalankan-program)
* [Acknowledgements](#acknowledgements)

## Deskripsi Singkat
Pada pengerjaan tugas besar ini, tugas mengimplementasikan untuk membuat algoritma Feed Forward Neural Network (FFNN) dengan memanfaatkan dua metode yaitu Forward Propagation untuk pengerjaan tugas pada Bagian A dan juga implementasi Mini-Batch Gradient Descent dengan Backward Propagation untuk pengerjaan tugas pada Bagian B

## Struktur File
```
📦Tubes-AI_ANN
 ┣ 📂Bagian-A
 ┃ ┣ 📂test-case
 ┃ ┃ ┣ 📜linear.json
 ┃ ┃ ┣ 📜multilayer.json
 ┃ ┃ ┣ 📜multilayer_softmax.json
 ┃ ┃ ┣ 📜README.txt
 ┃ ┃ ┣ 📜reluspek.json
 ┃ ┃ ┣ 📜relutc.json
 ┃ ┃ ┣ 📜sigmoid.json
 ┃ ┃ ┗ 📜softmax.json
 ┃ ┣ 📜model_visual.png
 ┃ ┗ 📜TubesA_13521008.ipynb
 ┣ 📂Bagian-B
 ┃ ┣ 📂test-case
 ┃ ┃ ┣ 📜iris.csv
 ┃ ┃ ┣ 📜linear.json
 ┃ ┃ ┣ 📜linear_small_lr.json
 ┃ ┃ ┣ 📜linear_two_iteration.json
 ┃ ┃ ┣ 📜mlp.json
 ┃ ┃ ┣ 📜README.txt
 ┃ ┃ ┣ 📜relu_b.json
 ┃ ┃ ┣ 📜sigmoid.json
 ┃ ┃ ┣ 📜softmax.json
 ┃ ┃ ┗ 📜softmax_two_layer.json
 ┃ ┗ 📜TubesB_13521008.ipynb
 ┣ 📂docs
 ┃ ┣ 📜Laporan Tugas Besar 1 ML.pdf
 ┃ ┗ 📜Laporan Tugas Besar 2 ML.pdf
 ┣ 📂zip
 ┃ ┣ 📜TubesA_13521008.zip
 ┃ ┗ 📜TubesB_13521008.zip
 ┣ 📜README.md
 ┗ 📜requirements.txt
```
 
## Requirements
1. Visual Studio Code
2. Library (numpy==1.26.4, ipykernel==6.29.4, graphviz==0.20.3)

## Cara Menjalankan Program
Langkah-langkah proses setup program adalah sebagai berikut:
1. Clone repository ini
2. Jalankan program dengan klik Run All pada ipykernel di Visual Studio Code
3. Masukkan nama file JSON yang ingin diproses

## Visualisasi Graf
![model_visual](https://github.com/Mifkiyan/Tubes-AI_ANN/assets/91790457/d4f7d0ad-72c7-4e34-a33d-c28701189998)

## Acknowledgements
- Tuhan Yang Maha Esa
- Dosen Mata Kuliah Pembelajaran Mesin IF3270
- Kakak-Kakak Asisten Mata Kuliah Pembelajaran Mesin IF3270
