[FIVE-CLASSES FLOWER IMAGE CLASSIFICATION]
by Dwi Cahaya Dharma

DATASET
Dataset yang digunakan dalam project ini merupakan gabungan dari beberapa file dataset gambar bunga berbeda yang berhasil dikumpulkan dari Kaggle dan kemudian digabung menjadi satu dataset dengan mereferensikan pada lima label yang serupa di file-file ini (daisy, dandelion, rose, sunflower, tulip) dan dataset ini selanjutnya dikompres ke dalam format .zip. Jumlah keseluruhan gambar dalam dataset gabungan ini adalah 15.227 gambar. 

Referensi masing-masing file dataset: 
- 5 Flower Types Classification Dataset: 
https://www.kaggle.com/datasets/kausthubkannan/5-flower-types-classification-dataset
- 🌸 | Flowers: 
https://www.kaggle.com/datasets/l3llff/flowers/data 
- Floral Diversity: A Collection of Beautiful Blooms:
https://www.kaggle.com/datasets/mansi0123/floral-diversity-a-collection-of-beautiful-blooms
- Flowers "Five Classes":
https://www.kaggle.com/datasets/lara311/flowers-five-classes
- National Flowers:
https://www.kaggle.com/datasets/shahidulugvcse/national-flowers
- Flowers by Joey Lim Zy:
https://www.kaggle.com/datasets/joeylimzy/flowers
- 🌸 Flower Classification by Supriyo Ain: 
https://www.kaggle.com/datasets/supriyoain/flower-classification
- Flowers Dataset by Rahmma Sleam:
https://www.kaggle.com/datasets/rahmasleam/flowers-dataset 

MODEL KLASIFIKASI
Model klasifikasi yang digunakan dalam project ini adalah model sekuensial yang berisikan dua buah Conv2D layer, base model dari transfer learning 'MobileNetV2' tanpa menghidupkan layer apapun yang ada di dalamnya, tiga buah pooling layer, dan empat buah dense layer. 'MobileNetV2' paling sesuai untuk digunakan dalam project ini karena performanya yang ringan apabila dibandingkan dengan ResNet50 dan VGG16 namun tetap mempertahankan akurasinya yang tinggi. 



