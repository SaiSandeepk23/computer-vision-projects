# Traffic Sign Detection and Classification

This repository contains code for traffic sign detection and classification. It includes data preprocessing, feature extraction using Histogram of Oriented Gradients (HOG), training a Random Forest classifier for traffic sign detection, and a deep learning approach using transfer learning and Convolutional Neural Networks (CNNs) for traffic sign classification.

## Data Preprocessing

- Class labels are loaded from CSV files.

- Image data is collected from various classes, and labels are assigned to each image.

- Images are resized and preprocessed for feature extraction and classification.

## Traffic Sign Detection with HOG Features

- Histogram of Oriented Gradients (HOG) features are extracted from each image.

- A Random Forest classifier is trained to detect traffic signs.

- Model performance is evaluated using accuracy and a classification report with class names.

## Data Splitting

- The data is split into training and validation sets for deep learning.

- Data augmentation is applied to the training set for improved model generalization.

## Traffic Sign Classification with Transfer Learning

- Transfer learning is used with the InceptionV3 architecture pre-trained on ImageNet.

- Additional layers are added for traffic sign classification.

- The model is trained and evaluated using the training and validation sets.

## Results

- The Inception based model achieves an accuracy of 97.62%

- The Random Forest classifier achieves an accuracy of 92.07%

## Conclusion

This repository demonstrates a comprehensive workflow for traffic sign detection and classification. It includes traditional machine learning techniques with HOG features and deep learning with transfer learning and CNN models.

## Maintainer

Sai Sandeep Kethiboina
AI and Machine Learning Engineer

Sai Sandeep is an AI/ML Engineer and Data Scientist with over 5 years of experience designing, developing, and deploying scalable Artificial Intelligence, Machine Learning, Deep Learning, and Predictive Analytics solutions. His expertise spans Python, TensorFlow, PyTorch, and Scikit-learn, with a focus on building data-driven products and predictive systems across various industrial domains.

Contact:
- GitHub: https://github.com/saisandeepkethiboina
- LinkedIn: https://www.linkedin.com/in/saisandeepkethiboina