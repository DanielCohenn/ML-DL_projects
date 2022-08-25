# ML/DL_projects
Various mini projects in the machine and deep learning fields using python. 
All the projects will be uploaded with jupyter notebook or Google Colab notebook 

## Project #1: Detecting pneumonia part 1

### Detection of Pneumonia in patients using X-ray images

In this project I used Google Colab notebook for its ease of use and beacuse I do not own an Nvidia GPU (Tensorflow supports only Nvidia GPUs),
I downloaded the data to Google Colab enviroment using kaggle library and kaggle api token.

### Set-up phase:

1. please follow and exexcute all the commands in part 1 for uploading kaggle dataset to google colab enviroment.

2. make sure to downlaod kaggle.jason token api from kaggle website (second row) and upload it to google colab.

### Notes:

1. For checking if our model is overfitting or underfitting the data we ploted Loss curve and Accuracy curve.

## Project #2: Detecting pneumonia part 2 (testing different model architectures and data augmentation)

### Detection of Pneumonia in patients using X-ray images 

In this project we will use data augmentation and different model architectures.

For evaluation of model preformance we are using Loss and Accuracy curves as well as confusion matrix with precision and recall.

## Project #3: Detecting pneumonia part 2 (transfer learning)

### Detection of Pneumonia in patients using X-ray images 

In this project we will use transfer learning with VGG16 and RESNET50 with trainable weights.

## Project #4: Benign or Malignant tumor (with sklearn library)
In this small project I built a machine learning classifier using SVM algorithm with a polynomial kernel for the prevention of underfitting a data with multi dimensional 
features that can not be represented in a linear way.
* First after downloading the dataset to our local machine we saparate the dataset to 2 different pandas dataframe for features and labels. 
* Second we visualize our features and preprocessed our data and end up with numpy array of features and labels as well as 0.2 ratio of test and train data.
* Third we built our model using SVC with polynomial kernel and trained our model on the training data and tested it on the test data.

