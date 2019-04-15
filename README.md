# final-year-projrct
AUTOMATED TYPE CLASSIFICATION OF DIABETIC RETINOPATHY AND GLAUCOMA DETECTION USING DEEP LEARNING

We developd a network with Convolutional Neural Network(CNN) architecture and data augmentation which can identify the intricate features involved in the classification task such as micro aneurysms, exudate and haemorrhages on the retina. We train this network using a high-end graphics processor unit (GPU). An open source Kaggle dataset is used as an input for DR and RIGA dataset is used as an input for Glaucoma. Total number of 25000 images are used for diabetic retinopathy and the testing accuracy for DR is 86%. Total number of 2664 images are used in glaucoma and the testing accuracy for glaucoma is 94%.

### The architecture consists of

* Data Pre-processing
* Data Augmentation
* Model trained using CNN
* Class Prediction

###Datasets

##Diabetic Retinopathy

The dataset for diabetic retinopathy contains 5 classes. Each class contains 5000 images. A total number of 25000 images are used for training the model.

* class 0 for Normal
* class 1 for Aneurysm(Mild)
* class 2 for Hemorrhage(Moderate)
* class 3 for Hard exudate(Severe)
* class 4 for Proliferative Diabetic Retinopathy(Very Severe) 

The Dataset for Glaucoma contains 2 classes. A total number of 2664 images are used for glaucoma.

* class 0 for Non Glaucoma ( 1488 images )
* class 1 for Glaucoma ( 1176 images )

Data Pre-processing : Conversion of RGB images to Grayscale images. Conversion to grayscale images are done to improvement in testing accuracy.

Data Augmentation : Rotation, Zooming, Shearing, Horizontal and Vertical Flip are done on images of all classes. Data augmentation is done for balancing the classes with equal number of images .

Training the model by using CNN layers. We have used 3 convolutoinal & max pooling layer, A dropout, Dense and a Fully Connected Layer.

The program runs in Google Colab. 

1. Upload the source file and the datasets to the Google Drive.
2. Open the project.ipynb file using Google Colab web app.
3. Run all the cells in the given order.

Output for Diabetic Retinopathy wil be displayed in a .csv file (DRresults.csv)
Glaucoma is a binary classification. Output will be either glaucoma or Not glaucoma. 
. 
