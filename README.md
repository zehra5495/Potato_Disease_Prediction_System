# Potato_Disease_Prediction_System
## Project Overview

This repository presents a Potato Disease Prediction system powered by deep learning techniques. The model is built using TensorFlow and Convolutional Neural Networks (CNN) for accurate classification of potato diseases, including early blight, late blight, and healthy states.

### Technologies Used:

- **TensorFlow:** The core framework for building and training the deep learning model.
- **FastAPI:** Utilized for creating a robust backend server to handle model predictions, ensuring efficient communication with the frontend.
- **TensorFlow Serving:** Implemented for model deployment, enabling scalable and on-demand predictions through a dedicated serving system.

### Directory Structure:

- **PlantVillage:** Dataset directory containing images of potato leaves for model training.
- **models:** Directory for storing saved model versions.

### Workflow:

1. **Data Preprocessing:** Images are loaded and preprocessed using TensorFlow Dataset and Data Augmentation.
2. **Model Building:** A CNN architecture is employed with additional layers for resizing, normalization, and data augmentation.
3. **Training:** The model is trained on the processed dataset with 50 epochs.
4. **Deployment:** TensorFlow Serving and FastAPI are integrated for efficient model deployment.
5. **User Interface:** A user-friendly interface is developed using ReactJS for the website and React Native for the mobile application.
