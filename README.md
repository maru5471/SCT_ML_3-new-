Cat vs Dog Classifier using SVM
A simple classifier to distinguish between cats and dogs using Histogram of Oriented Gradients (HOG) features and a Linear SVM (Support Vector Machine).

How it works
Load images (grayscale, resized to 128x128).
Extract HOG features.
Train a Linear SVM (wrapped with CalibratedClassifierCV).
Evaluate on test set.
Results
Accuracy: ~69%
Precision/Recall/F1: ~0.69 for both classes
Test size: 5000 images
Dataset
Dog and Cat Classification Dataset (Kaggle)

Dependencies
pip install numpy opencv-python scikit-learn scikit-image
