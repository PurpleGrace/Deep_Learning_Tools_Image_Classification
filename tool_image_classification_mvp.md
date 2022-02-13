# Deep Learning project
## Initial for a platform of mechanical tools sharing  -- Tools Image Classification
The goal of the project is to classify mechanical tools with image downloaded from [Kaggle](https://www.kaggle.com/salmaneunus/mechanical-tools-dataset?select=hammer.csv.csv).

My first model is convolutional neural network(CNN) with an accuracy of .516.The plot blow shows the change of accuracy score along with training epochs.

![image](https://github.com/PurpleGrace/Deep_Learning_Tools_Image_Classification/blob/main/plot/cnn%20accuracy%20plot.png)


I also tried transfer learning model with Xception. When disable top layer and trainable parameters, the accuracy for test dataset is .749


For the next step, I will try to use other transfer learning models like VGG16. Will also try to tune hyper-parameters to improve model performance.
