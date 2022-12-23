# Analysis-Cifar10-dataset-using-ML-algorithms


## Dataset
using https://www.kaggle.com/competitions/cifar-10/data 

The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

Here are the classes in the dataset, as well as 5 random images from each:

![image](https://user-images.githubusercontent.com/60587913/209399038-340a6b0c-81fd-41ee-86bb-78943a5574c4.png)

## Main topics recovered in methodology
* Dataset
  - Download the dataset
  - Divide the raw data into appropriate training and test sets for both the images and corresponding labels .
  - Visualize five samples of each class by plotting a grid using the matplotlib library.

* Modeling
  -  k-NN Classifier
      * using KNN algorithm from scratch
      * using KNN algorithm from sklearn 
      * Comparing between distances methods to select the best one ['euclidean', 'manhattan','minkowski']
      * select the best number of k
      * Applying best distance method with best k value
  - Logistic Regression
      * using Logistic Regression from sklearn besline model
  - Support Vector Machine (SVM) Classification
      * Create an SVM baseline using the LinearSVC() function
      * Explore the effect of the cost parameter on the accuracy
      * use L1 regularization

* Evaluation

## Conclusion
* k-NN Classifier
  Applying the k_nearest neighbors class, first, compare different distance models and calculate the accuracy, the best distance method was (Manhattan) then take multiple random values to get the best number of neighbors using the best distance method and it equals 15 with accuracy 24%
  
* Logistic Regression
  Implement baesline of logistic regression and achevie the accuracy 39.9%
  using ovr multiclasses and the best model from 10 models was model 1 with an accuracy of 12% and the worst one model 0 with an accuracy of 8%. 
* Support Vector Machine (SVM) Classification
  Apply the baseline for SVM, and calculate the accuracy that equals 32%
  Explore the effect of the cost parameter on the accuracy the best one equal 33% when c_value = 0.0001
  use L1 regularization with different values of c, the best accuracy achieved 40% when c = .1 
* champion model 
  In svm , using a radial basis function when c = 10 and gamma = .01 with an accuracy of 53.7%

## contact 
![image](https://user-images.githubusercontent.com/60587913/209285099-911ab4b9-604a-45e5-8c96-ce618df56870.png)https://www.linkedin.com/in/%D9%90%D9%90alaa-elkhashap/
