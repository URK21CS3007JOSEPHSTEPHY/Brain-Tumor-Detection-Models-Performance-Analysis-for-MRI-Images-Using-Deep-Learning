# Brain-Tumor-Detection-Models-Performance-Analysis-for-MRI-Images-Using-Deep-Learning
"Automated brain tumor detection using deep learning models (VGG16, VGG19, InceptionV3, ResNet50) trained on MRI scans. Achieves high accuracy and utilizes image augmentation. Code for predictions included."
# Brain Tumor Detection using Deep Learning

This project focuses on automating the detection of brain tumors from MRI scans using deep learning models. It employs popular architectures such as VGG16, VGG19, InceptionV3, and ResNet50, trained on a dataset consisting of 155 tumor-containing and 98 tumor-free MRI images.

## Key Features

- **Deep Learning Models:** Implementations of VGG16, VGG19, InceptionV3, and ResNet50 architectures for brain tumor detection.
- **Image Augmentation:** Techniques such as rotation, flipping, and zooming are used to augment the dataset, enhancing model generalization.
- **Evaluation Metrics:** Assess model performance using standard metrics including accuracy, precision, recall, and F1-score.
- **Ensemble Learning:** Ensemble predictions from multiple models to improve overall performance and reliability.
- **Prediction Script:** Python script provided for making predictions on new MRI images using trained models.

## Dataset

The dataset comprises MRI scans sourced from medical imaging repositories, including 155 images with brain tumors and 98 tumor-free images. It is divided into "yes" and "no" folders, each containing images corresponding to the presence or absence of tumors.

## Dependencies

- TensorFlow
- Keras
- NumPy
- Matplotlib
