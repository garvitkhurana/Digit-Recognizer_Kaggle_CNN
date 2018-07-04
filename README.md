# Digit-Recognizer_Kaggle_CNN
This is a tutorial for Kaggle competition, Digit Recognizer,Learn computer vision fundamentals with the famous MNIST data

## Goal:
The goal of this repository is to provide an example of a competitive analysis for those interested in getting into the field of data analytics or using python for Kaggle's Data Science competitions .

```
For Kaggle Competition this code results in over 99.5 % percent accuracy
Top 34% result for Kaggle
```
## CNN architechture followed is: Input -> [[Conv2D->relu]*2 -> MaxPool2D -> Dropout]*2 -> Flatten -> Dense -> Dropout -> Output


The steps followed are:

* Preprocessing the pixel image data to suitable format for CNN
* This code is implemented in **Keras using Tensorflow**
* Various implmentations of CNN improvement are done using, Pooling and Dropout and strides.
* Using the optimizer with **"Adam Optimizer" of Keras** 
* Tuning the CNN
