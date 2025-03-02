# Brain-Tumor-Detection-Using-2D-CNN
This project is an AI-based Brain Tumor Detection system using Convolutional Neural Networks (CNN). The model is trained to classify brain MRI images into four categories:1.Glioma  2.Meningioma  3.No Tumor  4.Pituitary The model achieved high accuracy during training and testing, making it effective for detecting brain tumors in MRI scans.

Model Architecture
The CNN model architecture includes:
Convolutional Layers
Max Pooling Layers
Dropout Layers
Fully Connected Layers
Softmax Activation

Performance Metrics:
Training Accuracy: 96.73%
Test Accuracy: 96.72%
Test Loss: 0.0836
Model Validation Accuracy: 97.71%

Results Visualization:
The detected tumor regions are highlighted in the output MRI images using bounding circles. The model classifies the image and displays the result along with the confidence score.

Git Clone:
git clone https://github.com/ujwalreddybattu04/Brain-Tumor-Detection.git

Dataset Source:
The dataset was obtained from the Kaggle Brain Tumor MRI Dataset which contains MRI images of brain scans labeled with four categories.

Dataset Preprocessing:
Image Resizing to 255x255 pixels
Data Augmentation:
Rotation
Flipping
Zooming

Prerequisites:
pip install tensorflow opencv-python matplotlib numpy scikit-learn keras

Dataset link:
https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset

Reference:
https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-023-02114-6
https://ieeexplore.ieee.org/document/8934561
https://pmc.ncbi.nlm.nih.gov/articles/PMC10527911/
