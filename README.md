# Age Prediction with Deep Learning

Predict a person's age from facial images using Convolutional Neural Networks (CNNs).

##  Project Overview
This project trains a CNN model to estimate age based on facial features. The model processes labeled images, learns patterns, and predicts ages for new inputs.

### Key Features
- Image preprocessing (resizing, normalization, augmentation)
- CNN-based architecture for feature extraction
- Applications in healthcare, marketing, and user personalization

##  Dataset
- Contains facial images labeled with ages
- **Download link**: [Dataset](https://www.kaggle.com/competitions/applications-of-deep-learning-wustl-spring-2024/data)

##  Model Architecture
Built with **TensorFlow/Keras**, the pipeline includes:
1. **Preprocessing**: OpenCV for image adjustments
2. **CNN Layers**: Feature extraction (convolution, pooling)
3. **Dense Layers**: Final age regression output

##  Results
- Achieved **Mean Absolute Error (MAE)** of ~5.2 years on test data

##  Live Demo
- [Huggingface](https://huggingface.co/spaces/ArifKemall/Age-Predicion-with-Deep-Learning)

##  Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/ArifKemal/Age-Prediction-with-Deep-Learning.git
