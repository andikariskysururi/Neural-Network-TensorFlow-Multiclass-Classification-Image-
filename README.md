# Neural Network Multiclass Classification Image - TensorFlow

### _Final Project ID Camp_
source code : 

[![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/114m5z7lv6fTw3VCGd-Kvsf6YKfr2wvVA?usp=sharing)


## Deskripsi 
Project ini bertujuan untuk membangun model neural network dengan menggunakan tensorflow guna melakukan klasifikasi citra. Dataset yang digunakan merupakan citra yang terdiri dari tiga buah label (paper, scissors, rock).

### Dependencies 
- Tensorflow 
- splitfolders 
- numpy 
- matplotlib 

## Metodologi 
- Data Collecting 
Di data collecting dilakukan proses pengunduhan dataset yang kemudian dilakukan proses ekstraksi dan juga splitting data menggunakan splitfolders. splitting data ini bertujuan untuk menyiapkan data citra ke dalam folder train dan validation sesuai dengan kelasnya
- Data Augmentation 
Pada tahap ini data citra dikenakan beberapa perlakukan, diantaranya normalisasi, rotasi, flip , dan fill mode setelah dilakukan shear. Perlakukan ini dilakukan pada data citra train. Sedangkan pada data citra validation hanya dilakukan proses normalisasi 
- Data Preparation 
Pada tahap ini dilakukan proses persiapan pada data training dan data validation yang akan digunakan dalam proses training model 

- Builiding Model 
Setelah data siap, selanjutnya dilakukan proses building model dengan tahapan diantaranya melalui 4 layer konvolusi dan max pooling serta 1 input layer, 1 hidden layer dan 1 output layer

- Training Model
Setelah arsitektur telah ditentukan, dilakukanlah proses training hingga sebanyak 100 epochs