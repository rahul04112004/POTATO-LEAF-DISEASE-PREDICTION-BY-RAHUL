# POTATO-LEAF-DISEASE-PREDICTION-BY-RAHUL
This project focuses on developing a deep learning model for image classification using TensorFlow and Keras. The primary objective is to classify images into different categories based on a dataset of potato plant images. 
Potato Leaf Disease Classification Using Convolutional Neural Networks
Overview
This project utilizes Convolutional Neural Networks (CNNs) to classify potato leaf images into three categories: Early Blight, Late Blight, and Healthy. The model is designed to aid early intervention and reduce crop loss by providing accurate and robust disease detection.

Dataset
The dataset used for this project is the Plant Village dataset from Kaggle, which includes labeled images for various plant diseases, including potato blight. This dataset is available within the repository.

Project Structure
The project consists of the following key components:

Data Collection and Preparation: The dataset is loaded and preprocessed, with images resized to 256x256 pixels. Data is split into training, validation, and test sets.
Data Augmentation: Techniques like random flipping and rotation are applied to introduce variability, preventing overfitting.
Model Architecture: The CNN model has six convolutional layers with ReLU activations, max-pooling layers, a fully connected layer, and a softmax output for multiclass classification.
Training and Optimization: The model is trained using the Adam optimizer and Sparse Categorical Crossentropy loss over 100 epochs, leveraging data pipeline optimizations for efficiency.
Model Evaluation: Includes accuracy, loss tracking, and confusion matrix analysis for detailed performance metrics.
Performance
The model achieves high accuracy across training, validation, and test splits. Performance metrics, including accuracy and confusion matrix visualizations, provide insight into the model’s ability to generalize to unseen data.

Actual vs. Predicted labels for potato leaf disease classification
![image](https://github.com/user-attachments/assets/7b46e7c2-2f30-4250-8aac-8c52d23fbf63)

