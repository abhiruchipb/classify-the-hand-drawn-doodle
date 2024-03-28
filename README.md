The hand-drawn doodle recognition is a AI system tries to classify the hand-drawn doodle into a predetermined category. By this project we are trying to achieve the same using different feature extraction techniques like HOG, LBP, SIFT, SURF, pixel values with feature reduction techniques PCA, LDA and applying various classifiers such as Naive Bayes, Random Forest, SVM, XGBoost, Bagging, ADA-boost, KNN and CNN to compare their performance on different evaluation metric such as Accuracy, MAP@3, CMC Curve and Confusion Matrix.

Problem Usecase:

It is a challenge in Computer Vision & Machine Learning to handle noisy data and dataset with many different representations of the same class. The hand-drawn Doodle Recognition is a good example of these issues because different users may draw the same object differently or the doodles could be incomplete which is similar to noisy data.
This application can be used as a fast prototyping tool for designers or artists by suggesting them the accurate templates on the basis of the rough doodles made by them.
It can be extended by replacing the doodles with doodles of alphabets and then convert the hand-written text into digital text format.

Dataset:
https://console.cloud.google.com/storage/browser/quickdraw_dataset/full/numpy_bitmap;tab=objects?prefix=&forceOnObjectsSortingFiltering=false

The Quick Draw dataset is a collection of millions of doodle drawings of 300+ categories. The drawings draw by the players were captured as 28 x 28 grayscale images in .npy format with respect to each category.
The complete dataset is huge (~73GB) and so we have used only a subset of the complete data (20 categories).
The dataset is split in training and test set with 80-20 ratio, the training set is further split into train and validation with 70-30 ratio.
Fig above shows a doodle image of each class in our sampled dataset.

![image](https://github.com/abhiruchipatilbhagat/classify-the-hand-drawn-doodle/assets/121765345/a2365a68-410e-4047-8467-3794d25324b2)
