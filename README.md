**Emotion Detection Through Text**

This project aims to detect emotions from textual data using machine learning techniques. It includes data preprocessing, model training, and a simple web application to demonstrate the model's capabilities. The model achieves an accuracy of 89% using a Random Tree Classifier.

**Directory Structure:**

**Dataset**

train.txt: Training dataset.

val.txt: Validation dataset.

test.txt: Test dataset.

**Implementation**

Project.ipynb: Jupyter Notebook containing the project implementation and model training process.

app.py: Flask web application for demonstrating the emotion detection model.

EmotionDetection.py: Python script for training the emotion detection model.

EmotionDetection.pkl: Serialized model file.



**Prerequisites**

Python 3.6 or above

Jupyter Notebook

Flask

**Models**

The project explores multiple machine learning models, including:

Random Tree Classifier (89% accuracy)

Logistic Regression(87% accuracy)

Support Vector Classifier(87% accuracy)

Decision Tree Classifier(86% accuracy)

The model is trained using the script EmotionDetection.py and saved as EmotionDetection.pkl. The Jupyter Notebook Project.ipynb provides a detailed walkthrough of the training process and model comparisons.

**Web Application**

The web application is built using Flask and allows users to input text and receive the detected emotion as output. The application runs the trained model to predict the emotion.
