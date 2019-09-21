# Image Classifier (MobileNet Image Classifier Using TensorFlow.js)
This is a simple machine learning web application using TensorFlow.js. by using a pretrained MobileNet model for classifying images from webcam which classify images into three custom categories.

This is a simple demonstration of how to use TensorFlow.js to deploy a pre-trained model to classify images in a web browser.

This image classifier uses the MobileNet model, which is "An architecture which is more suitable for mobile and embedded based vision applications where there is lack of compute power. This architecture was proposed by Google". This project makes use of tensorflow.js , an open-source library you can use to define, train, and run machine learning models entirely in the browser.

This model has not been re-trained, it uses the pre-trained weights to make predictions. All images are resized to 224x224 pixels (due to the input shape). The predictions are returned with the class names and respective probabilities.

MobileNet Model Architecture


![](/MobileNetArchitecture.png)
