# Dogs vs Cats Classifier 🐶🐱

This project implements a Convolutional Neural Network (CNN) to classify images of dogs and cats. 
The model is trained on the Kaggle Dogs vs Cats dataset and can predict the class of a given image with a confidence score. 
It also includes an interactive GUI built using Gradio, allowing users to upload images or screenshots for real-time predictions.

## Features
- Binary image classification: Cat vs Dog
- Uses Convolutional Neural Networks (CNN) with Keras and TensorFlow
- Image preprocessing: resizing, normalization
- Interactive Gradio GUI for uploading images and getting predictions
- Shows confidence of prediction
- Trained and validated on Kaggle dataset

## Results
- Training Accuracy: ~99%
- Validation Accuracy: ~76%
- Mild overfitting observed (can be improved with data augmentation or transfer learning)

## Usage
1. Clone the repository
```bash
git clone https://github.com/nabighasafdar/dogs-vs-cats-classifier.git
