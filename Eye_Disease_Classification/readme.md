# Eye Disease Classification

## Overview
This repository contains code for a deep learning project focused on the classification of eye diseases using Convolutional Neural Networks (CNNs). The project utilizes transfer learning with the InceptionResNetV2 architecture and includes implementations of custom CNNs, including one with a Parallel Convolution Architecture.


## Code Structure

- **Data Preparation**: The dataset is loaded, and dataframes are created to organize file paths and labels. Data distribution is visualized using a count plot.

- **Data Augmentation**: ImageDataGenerator is used for data augmentation during training to improve model generalization.

- **Model Architecture**: The InceptionResNetV2 model is used for transfer learning. Custom CNNs, including one with a parallel convolutional architecture, are also implemented and trained.

- **Model Training**: The model is compiled using the Adamax optimizer and categorical cross-entropy loss. Training and validation results are visualized using accuracy and loss plots.

- **Model Evaluation**: The trained model is evaluated on the test set, and metrics such as accuracy, loss, classification report, and confusion matrix are displayed.

- **Activation Maps**: Activation maps and Grad-CAM (Gradient-weighted Class Activation Mapping) are visualized to understand which parts of the image the model focuses on during predictions.

## Requirements
- Python 
- TensorFlow
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- OpenCV

## Results
The project achieved promising results in terms of accuracy and provides visualizations to aid in model interpretation.

|  Model | Accuracy |
|----------|----------|
| Transfer Learning | 94.31% |
| Custom CNN | 89.81% |
| CNN with Parallel Convolution | 93.36% |

## About the Maintainer

This project is maintained by Sai Sandeep Kethiboina, an AI/ML Engineer and Data Scientist with 5+ years of experience designing, developing, and deploying scalable Artificial Intelligence, Machine Learning, Deep Learning, Predictive Analytics, and Generative AI solutions across Telecommunications, Banking, and Healthcare domains. His expertise includes Python, SQL, TensorFlow, PyTorch, Scikit-learn, and other tools for building data-driven products and predictive systems.

For inquiries or contributions, please refer to Sai Sandeep Kethiboina's professional profiles:
- **GitHub:** Sai Sandeep Kethiboina
- **LinkedIn:** Sai Sandeep Kethiboina