# Deep Learning project
## Initial for a platform of mechanical tools sharing  -- Tools Image Classification

### Abstract

May DIY fans face very similar dilemmas related with cost and space. For a new project, there are often needs of new tools, which means both money and storage spaces. Many DIY fans may share same dream: It would be awesome I can just borrow from someone nearby who has this tool for a few days!And I would love to share with others my tool who loves DIYs too. My husband is one of those DIY fan, he has been hoping that there is a platform exists from which can borrow tool to save money and also share his tools with others. Upon his request, I am using this deep learning project opportunity to accomplish a basic functionality of a tool sharing platform: mechanical tool image classification. After trying with several models.for this project, the transfer learning model of MObilnetV2 is the one with best performance


### Design
The project will use deep learning techniques to build convolutional neural network to do image classification. I build a basic convolutional neural network, also did three transfer learning models: Xception, Vgg16 and Mobelnetv2.

### Data
The Image dataset can be obtained from [Kaggle](https://www.kaggle.com/salmaneunus/mechanical-tools-dataset?select=hammer.csv.csv). During the checking data precess, there are some image obviously classified with wrong label. However, there are nearly seven thousands images and it will be time consuming to check every image. After initial cleanning, there are 6916 images with 8 categories: Gasoline can, hammer, pebbles, rope, screw driver, tool box, wrench, pliers. Also, the dataset is imbalance which we can solve through data augmentation. At last, we split the dataset into train, validation and test folders for model purposes.

### Tools
- **Preprocessing**  :pands,numpy,random
- **Dataset split into folders**: os
- **Model and metric** :Tensorflow, sklean, keras
- **visualization**  :Matplotlib,seaborn

### Algorithms
- Use os package to split dataset into three folders: train, validation and test;
- Transfering image data into array as inputs of neural networks;
- Use ImageDataGenerator to do data augmentation;
- Use Tensorflow and keras to build neural network models
- Basic convolutional neural network;
- Transfering models: Xception, Vgg16 and MobilnetV2


### Result
After comparing four aforementioned models,MObilnetV2 has vary good accuracy and f1 score, meanwhile fast and efficient.

![image](https://github.com/PurpleGrace/Deep_Learning_Tools_Image_Classification/blob/main/plot/deep%20learning%20model%20result.png)


![image](https://github.com/PurpleGrace/Deep_Learning_Tools_Image_Classification/blob/main/plot/mobilnetv2%20confusion%20matrix.png)


### Communications
A PPT presentation will be presented.
