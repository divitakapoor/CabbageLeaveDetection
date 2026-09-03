# 🥬 Cabbage Leaf Disease Detection

An AI-based **Cabbage Leaf Disease Detection System** that uses **Deep Learning and Computer Vision** to identify diseases in cabbage leaves from images.

The project uses a **pre-trained ResNet50 model with Transfer Learning** to classify cabbage leaf images into five categories:

* 🌿 **Healthy Leaves**
* 🍂 **Alternaria Leaf Spot**
* 🦠 **Black Rot**
* 🌱 **Club Root**
* 🍃 **Downy Mildew**

## 🎯 Objective

The main goal of this project is to provide a simple automated approach for detecting common cabbage leaf diseases. Early identification can help farmers and agricultural practitioners recognize potential diseases and take appropriate action sooner.

## 🧠 Model & Approach

The project uses **ResNet50**, a pre-trained convolutional neural network, with **Transfer Learning**.

The general workflow is:

1. Collect and organize cabbage leaf images.
2. Preprocess and resize the images.
3. Apply data augmentation to improve model generalization.
4. Use a pre-trained ResNet50 as the feature extractor.
5. Add custom classification layers for the five disease categories.
6. Train and validate the model.
7. Evaluate the model on unseen test images.
8. Use the trained model to predict the disease category of a new cabbage leaf image.

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* ResNet50
* NumPy
* Pandas
* Matplotlib
* Google Colab

## 📂 Disease Classes

| Class                | Description                                                 |
| -------------------- | ----------------------------------------------------------- |
| Alternaria Leaf Spot | A fungal disease characterized by dark spots on leaves      |
| Black Rot            | A bacterial disease that causes dark lesions and yellowing  |
| Club Root            | A soil-borne disease that affects cabbage roots             |
| Downy Mildew         | A fungal-like disease producing characteristic leaf lesions |
| Healthy Leaves       | Leaves without visible disease symptoms                     |

## 🚀 Future Improvements

* Improve model accuracy and generalization.
* Experiment with other pretrained architectures.
* Add confidence scores to predictions.
* Deploy the model as a web or mobile application.
* Support multiple crop diseases.
* Add multilingual support for easier use by farmers.

## 📌 Project Status

This project is developed as a **deep learning-based image classification project** for exploring the application of AI in agriculture and plant disease detection.
