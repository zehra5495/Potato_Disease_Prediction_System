# Potato_Disease_Prediction_System
## Project Overview
## PATATA - A Potato Disease Prediction System Using Deep Learning

## Major Project by Zehra Zaidi, Mohd Akbar Zaidi
## Group -25

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

## Performance Metrics

### Validation Accuracy

- **First 20 epochs:** 96.24%
- **First 40 epochs:** 98.96%
- **First 50 epochs:** 99.42%


### Training Time

- **Average time per epoch:** 2 seconds

## Conclusion

This research work successfully demonstrates the applicability of Convolutional Neural Networks in effectively classifying potato leaf conditions. The integration of FastAPI and TensorFlow Serving enhances the system's efficiency and scalability, ensuring farmers have timely access to disease predictions. The user-friendly interfaces developed using ReactJS and React Native contribute to the practical implementation and usability of the system.

Explore the code, contribute to its enhancement, and join in the advancement of potato disease prediction using deep learning techniques.
