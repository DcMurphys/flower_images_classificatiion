# FIVE-CLASSES FLOWER IMAGE CLASSIFICATION
by Dwi Cahaya Dharma

## Dataset
The dataset being used in this project is a collection of several dataset files containing different flower images from Kaggle by referencing to five similar underlying labels (daisy, dandelion, rose, sunflower, tulip). This collection is then compressed into a .zip file and has 15.227 images in total. 

## Model used in Classification 
This project utilizes custom sequential model as the classification model, comprised of two Conv2D layers, 'MobileNetV2' transfer learning base model without any remaining layers inside, three pooling layers, and four dense layers. The transfer learning base model used is the most suitable for this project due to one of its advantages, which is better performance compared to two other tested pretrained models like ResNet50 and VGG16, but still able to maintain its high accuracy rate. 

## Libraries used in this project
TensorFlow and its derivative libraries are used in this project to classify collection of flower images into five classes. The following derivative libraries are Keras, as well as 'MobileNetV2' as a pretrained model without any remaining weights.


