# Classification for MNIST dataset

Classification is a supervised machine learning process that predicts the class (or group) of input data based on the algorithms training data. Common classification algorithms include logistic regression, support vector machine, naive Bayes classifier, and decision trees.

This mini project is all about exploring different ways to classify handwritten digits. I wanted to build on a previous assignment from school where I learned about categorizing 28x28 pixel images into 10 different classes (0-9). The images are greyscale, with values ranging from 0.0 (white) to 1.0 (black).

Due to the small size of the images (28x28), flattening them results in a manageable number of columns (784). I am exploring both traditional machine learning algorithms and neural networks to determine the best approach for image classification in this scenario.

I'm going to experiment with Linear models (Simple Least Squares) with MASS, TreeDecision with RandomForest, and  Multinomial(Softmax) with Tensorflow.