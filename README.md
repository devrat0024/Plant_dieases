Plant Disease Classification
Overview
This project focuses on classifying plant diseases using a deep learning model. The model is trained to identify diseases such as Botrytis Blight, Crown Gall, Downy Mildew, Powdery Mildew, and Fire Blight from images of plants. The project uses TensorFlow and Keras for building, training, and evaluating the model.
Features
Dataset: Contains images of plants with five types of diseases.
Model: A Convolutional Neural Network (CNN) is used for classification.
Training: The model is trained on a dataset of labeled images.
Prediction: The trained model can predict the disease class for new images.
Requirements
To run this project, you need the following dependencies:
Python 3.x
TensorFlow 2.x
NumPy
Matplotlib
OpenCV (optional, for image processing)
You can install the required libraries using the following command:
pip install tensorflow numpy matplotlib
Dataset
The dataset should be organized in the following structure:
dataset/
├── Botrytis blight/
├── Crown gall/
├── Downy mildew/
├── Powdery mildew/
└── Fire blight/
Each folder contains images of the respective disease.
