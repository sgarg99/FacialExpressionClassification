# FacialExpressionClassification
A deep learning model using Convolution Neural Networks to classify facial expressions into 7 categories namely-Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral.

# Data
https://www.kaggle.com/deadskull7/fer2013/downloads/fer2013.zip/1
I used the kaggle dataset for facial expression recognition it consists of three sets 
Training
PublicTest
PrivateTest

# Model
I used a keras model consisiting of 4 Convolution layers with Relu activation and 2 Dense layers.Each convolution layer was followed by a batch normalization layer and a max pooling layer. I used categorical-crossentropy as loss and Adam as optimizer.

# Training
I first trained my model on a small portion of training data. Again I trained my model on the full training data.

# Evaluation
My model gave a training accuracy of 62% . Accuracy on private test is 51% and on public test is 50%.
The state of the art accuracy is 65%.
PS:- Still working on my model to get a better accuracy.
