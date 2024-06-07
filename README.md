# **Deep Fake Detection Using VGG-19 Model**
## **Overview**
This project aims to detect deep fake videos using a VGG-19 convolutional neural network (CNN). Deep fake videos, which use artificial intelligence to create realistic but fake videos, pose significant ethical and security challenges. Our model leverages the VGG-19 architecture to identify and classify these fraudulent videos effectively.

## **Project Motivation**
This project was developed as part of my final year project. The increasing prevalence of deep fake technology and its potential misuse prompted the need for a robust detection mechanism. This project demonstrates how advanced neural networks can be applied to mitigate the risks associated with deep fake videos.

## **Features**
- **Deep Learning Model:** Utilizes the VGG-19 architecture, pre-trained on ImageNet, for feature extraction.
- **Dataset:** Trained and tested on a curated dataset of real and deep fake videos.
- **Performance Metrics:** Provides accuracy, precision, recall, and F1-score for model evaluation.
- **Visualization:** Includes visualization of training progress and performance metrics.

## **Getting Started**
To get a copy of this project up and running on your local machine, follow these steps:

### **Prerequisites**
- Python 3.9
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib

## **Installation**
### **Clone the Repository:**
```
git clone https://github.com/your-username/deep-fake-detection.git
cd deep-fake-detection
```
### **Install Dependencies:**
```
pip install tensorflow keras opencv-python numpy matplotlib
```
### **Prepare the Dataset:**
Download a dataset of real and deep fake videos.
Extract frames from videos and organize them into appropriate directories (e.g., real/ and fake/).

##**Running the Model**
### **Preprocess the Data:**
Load and preprocess the data, including resizing images and splitting into training and testing sets.

### **Define and Train the Model:**
Use the VGG-19 architecture, freeze its layers, and add custom dense layers for classification.

## **Train the model on the preprocessed dataset.**
### **Evaluate the Model:**
Evaluate the model's performance using metrics like accuracy, precision, recall, and F1-score.
Visualize training and validation accuracy and loss.
Usage
Run 

### **the Preprocessing Script:**
Prepare your dataset and preprocess it using the provided scripts.

### **Train the Model:**
Train the VGG-19 based model on the preprocessed dataset.

### **Evaluate and Visualize:**
Evaluate the model on the test set and visualize the results.

## **Contributing**
We welcome contributions to enhance the functionality and features of this project. Please follow these steps to contribute:

Fork the repository.
```
Create a new branch (git checkout -b feature/YourFeature).
Commit your changes (git commit -m 'Add new feature').
Push to the branch (git push origin feature/YourFeature).
Open a Pull Request.
```
## **Model Result**
![Screenshot 2024-06-07 192751](https://github.com/rahul9903/Deepfake/assets/130080777/bf6b10e2-2523-40d4-a8f6-c2677563c9f0)

## **Acknowledgements**
Special thanks to the open-source community and the developers of TensorFlow, Keras, and OpenCV for their invaluable tools and libraries.
This project was completed as part of my final year project, and I appreciate the support from my professors and peers.
