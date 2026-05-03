# Handwritten-Digits

Handwritten digit recognition system not only detects scanned images of handwritten digits.Handwritten digit recognition using MNIST dataset is a major project made with the help of Neural Network. It basically detects the scanned images of handwritten digits. The MNIST handwritten digit classification problem is a standard dataset used in computer vision and deep learning. Although the dataset is effectively solved, it can be used as the basis for learning and practicing how to develop, evaluate, and use convolutional deep learning neural networks for image classification from scratch.

Here we have used 2 data sets named 'train.csv' and 'test'csv' along with original dataset inbuilt in Keras datasets Module. You can find the datasets in kaagle.

train data = https://www.kaggle.com/competitions/digit-recognizer/data?select=train.csv

test data = https://www.kaggle.com/competitions/digit-recognizer/data?select=test.csv

The train data is used as a validation set to estimate validation accuracy and loss that helps to optimize the model. The test data is used to generate predictions.

Inorder to develop CNN model we need certain libraries and essential a High GPU thus here I have used 'Google Colab' which is an online environment to develop ML models. you can create your colab notebook from your google account and you need to mount your 'Google Drive' and load data sets in your drive.

link to colab = https://colab.research.google.com/

The modules and libraries used are:

Keras
Tensorflow
Pandas
Numpy
Sklearn
Matplotlib
These are already available in colab environment
