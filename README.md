# Rock Paper Scissors Classification - Machine Learning Project

This project is a Rock-Paper-Scissors image classification using a convolutional neural network (CNN) built with TensorFlow and Keras. The model is trained to classify images into three categories: rock, paper, or scissors. The dataset used for this project is sourced from [this link](https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip). 

## Project Structure

The notebook includes the following steps:
1. Data loading and preparation
2. Training and validation data splitting (60:40 ratio)
3. Data augmentation using `ImageDataGenerator`
4. Building the CNN model using TensorFlow and Keras
5. Training the model over 10 epochs
6. Model evaluation

## Requirements

To run this project, the following Python packages are required:

```bash
keras
matplotlib
numpy
pandas
sklearn
tensorflow
tf-keras
```

## Results

After 10 epochs, the model achieves a training accuracy of ~95.6% and a validation accuracy of ~96.4%. Further fine-tuning or additional epochs could improve these results.

## Conclusion

This project demonstrates a simple approach to image classification using a CNN. Data augmentation and a well-structured CNN help the model to achieve high accuracy in predicting rock, paper, or scissors hand gestures.