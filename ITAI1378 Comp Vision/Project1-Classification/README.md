Problem Statement

This project solves the problem of distinguishing between images of Chihuahuas and muffins. Since both can look visually similar, especially in certain images, this is a good example of how computer vision models can learn subtle visual differences.

Approach

I used a Convolutional Neural Network (CNN) to classify images into two categories: Chihuahua or Muffin. The model was trained on labeled image data and learned patterns such as texture, shape, and color.

Steps included:

Loading and preprocessing image data
Normalizing pixel values
Building a CNN model with convolutional and pooling layers
Training the model using labeled data
Evaluating performance on test data
Results
The model was able to correctly classify most images after training.
Accuracy improved over epochs as the model learned key features.
Performance may vary depending on dataset size and image quality.

Key Findings
CNNs are effective at identifying subtle differences in images.
More training data generally improves model performance.
Image quality and variety significantly impact accuracy.
Overfitting can happen if the dataset is too small.
Technologies Used
Python
TensorFlow / Keras
NumPy
Matplotlib
OpenCV (if used)

How to Run
Open the notebook in Google Colab or Jupyter Notebook
Run all cells in order
Make sure images/dataset are properly loaded
