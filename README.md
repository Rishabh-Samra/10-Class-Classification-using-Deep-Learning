# 10-Class-Classification-using-Deep-Learning

We solve a 10 class classification problem using the method of deep learning where we used resnet pre-trained model and finetuned the network using a few images. To improve the generalization ability of the classifier, we had further augmented images using Albumentation library.

After getting the final trained model, we further tried to improve the accuracy by using the pre-trained model to obtain the confidence score for each training data point. 
We removed the data from the training data having lower confidence scores and had retrained the model to get a better classifier.
