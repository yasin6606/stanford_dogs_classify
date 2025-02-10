# Stanford Dogs Classifier
# Overview
The Stanford Dogs Classifier is a computer vision project aimed at classifying images of dogs into 120 distinct breeds using a modified ResNet50 architecture. This project employs transfer learning techniques to fine-tune a pre-trained model on a custom dataset of 20,000 samples. The model is implemented using PyTorch and optimized for GPU usage.
# Dataset
[Download Stanford Dogs Classifier Dataset](http://vision.stanford.edu/aditya86/ImageNetDogs/)
# Custom Dataset:
The dataset contains __20,000 samples__ across __120 distinct breeds of dogs__. A custom dataset implementation reads samples from directories and prepares them based on three .mat files that define the annotations, as well as the training and test sets. Additionally, appropriate transformations are applied to the samples to enhance the dataset’s suitability for training.
# Architecture:
A __custom-modified ResNet50__ architecture has been implemented to adapt the output layer for classification across 120 distinct dog breeds. The __fine-tuning method__ is employed to specifically train only the output layer, which comprises __245,880 parameters__. This approach allows for efficient training while leveraging the pre-trained features of the ResNet50 model.
# Result:
After training, the model achieved the following performance on __8580 Test samples__:
  * Test Cross-Entropy Loss: 0.38
  * Test Accuracy: 88.76%
## GPU Information:
  * NVIDIA GEFORCE GTX-960M
  * 4GB Memory
  * 640 CUDA Cores
# Contact:
  Thank you for your interest in this project! If you have any questions or suggestions, feel free to reach out.
  
  Email: [yassingourkani@outlook.com](yassingourkani@outlook.com)
  
  LinkedIn: [Yasin LinkedIn](https://www.linkedin.com/in/yassingourkani/)
