# dl-transferlearning
# 🐶🐱 Dog vs Cat Image Classification

## Overview
This project classifies images of **dogs and cats** using **transfer learning**.  
A pre-trained deep learning model is fine-tuned for binary image classification.

This project focuses only on **model training and evaluation**.  
No frontend or user interface is implemented.

## Model
- Approach: Transfer Learning  
- Framework: TensorFlow / Keras  
- Task: Binary Classification (Dog / Cat)

## Dataset
- Images of dogs and cats  
- Split into training and validation sets  
- Images are resized and normalized before training  

## Preprocessing
- Image resizing  
- Normalization  
- Basic data augmentation  

## Training
- Pre-trained model loaded without top layers  
- Custom classification layers added  
- Model trained on dog and cat images  

## Evaluation
- Accuracy and loss are used for evaluation  
- Model performs well on validation data  

## Technologies Used
- Python  
- TensorFlow  
- Keras  

## Conclusion
Transfer learning enables efficient and accurate image classification with reduced training time.
