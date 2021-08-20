# Vehicle-detection
Computer vision and Machine learning methods based project for vehicle detection in self driving cars

### Key words
Histogram of oriented gradient(HOG),Vehicle Detection,machine learning,self-driving cars

### Abstract
Self-driving cars are slowly becoming the reality of our future. For cars to run autonomously, they first require identifying objects present in their environment and then making appropriate decisions. Electric vehicles have gained massive popularity in recent times due to various reasons. One of them is providing an advanced driving assistance system, which has increased road transport safety by providing vital information of driving environment and suggesting a better decision to user depending on various factors. A precise and robust vehicle detection module is a vital part of such a system. Our project is aimed at addressing this issue. We have used histogram of oriented gradients (HOG) to extract features from dash cam present in front of the car and trained supervised machine learning models to classify the cars and not-cars according to HOG features and use the model to detect the objects present in the driving environment. The primary focus was kept on having maximum precision and accuracy as it is vital to precisely detect the vehicles in front of the car to avoid the collision. The model can take the video file as an input and return the video file with bounding boxes placed on a detected vehicle.

The codes are written using Google Colab IDE and in python programming language.
Most of the datasets and methods are open-sourced information and are used just for learning perspective.

For more details read [Report](https://github.com/sandesh-30/Vehicle-detection/blob/main/Report.pdf)

## Key Highlights 
* Studied and applied Histogram of Oriented Gradients (HOG) feature descriptor for feature engineering
* Reduced total number of features in an image from 12288 to 1764 (by 85.67%) using Histogram of Oriented Gradients feature descriptor
* Reduced total number of features to 1764 (by 85.67%) using Histogram of Oriented Gradients feature descriptor
* Performed hyperparameter tuning and cross-validation using GridSearch for SVC, Adaboost, and Random Forest
* Trained and compared different ML algorithms like SVC, Random Forest, Perceptron, and Adaboost classifier
* Attained ROC-AUC score of 0.9951 for SVC and obtained 8/9 correct classification on the test image set
