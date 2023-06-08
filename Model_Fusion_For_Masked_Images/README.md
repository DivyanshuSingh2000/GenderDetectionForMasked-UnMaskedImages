# Model-fusion-and-ML-classifer-used-for-Gender-Detection-on-masked-Images
The dataset we used :https://www.kaggle.com/datasets/itsshuvra/gender-classified-dataset-with-masked-face

This is experimental project to see can fusing more than one model for feature extraction can lead upto better classification.
We use DenseNet for feature extraction in scenario 1 and in another secnario DenseNet121 and Xception Net.

Feature Extractor notebook cover the code of extracted features combining DenseNet121 and Xception Net and saved the data for training and testing.

In the multiclassifier notebook the saved data is used to train ML algo like RF, SVM, KNN, Logistic Regression and noted their performance.
Same thing repeated in single classifier but the change is the feature extracted is done by only Dense Net 121.

We compare their results.
![image](https://user-images.githubusercontent.com/78965726/236618906-3d10f94f-83c0-47c6-a195-5a6b350802c9.png)
