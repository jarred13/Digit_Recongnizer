# Digit Recongnizer

# Overview
Kaggle has a competition that you have to use computer vision to correctly classify thousands of hand written digits. There are two notebooks in this repository, the first one was my first CNN model. I was able to achieve a 98% accuracy on the competition. The second notebook, builds and improves on the first CNN model and achieves a 99% accuracy.

# Purpose of the Project
The purpose of this project was to challenge myself by submitting my predictions for Kaggle's hand written digits competition. I wanted to use this competition as a way to learn and improve my understanding of convolutional neural networks.

# What Did I Learn
I learned how to create a convolutional neural network using the python library Keras. I learned how adding different layers can improve your model's accuracy, in this case adding a batch normalization layer and a dropout layer improved the moedel. I learned a little bit about processing images in python as well.

# Dataset User
The data files train.csv and test.csv contain gray-scale images of hand-drawn digits, from zero through nine.Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.The training data set, (train.csv), has 785 columns. The first column, called "label", is the digit that was drawn by the user. The rest of the columns contain the pixel-values of the associated image.Each pixel column in the training set has a name like pixelx, where x is an integer between 0 and 783, inclusive. To locate this pixel on the image, suppose that we have decomposed x as x = i * 28 + j, where i and j are integers between 0 and 27, inclusive. Then pixelx is located on row i and column j of a 28 x 28 matrix, (indexing by zero). The test data set, (test.csv), is the same as the training set, except that it does not contain the "label" column.

# Files Used
sample_submission.csv - file showing how the submission should look  
train.csv - the training data  
test.csv - the test data  
my-first-cnn.ipynb - python notebook first submission  
2nd-attempt-mnist-accuracy-99.ipynb
