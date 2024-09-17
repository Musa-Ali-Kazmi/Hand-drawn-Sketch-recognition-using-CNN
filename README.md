# Hand-Drawn Sketch Recognition Using ResNet50

This project applies Convolutional Neural Networks (CNN), specifically the ResNet50 architecture pre-trained on ImageNet, to recognize and classify hand-drawn sketches. The dataset used consists of images of sketches, categorized into 250 different classes. The project leverages data augmentation techniques to improve model performance.

## Project Overview

The key components of this project include:

- **Model Architecture**: A pre-trained ResNet50 model (without the top classification layer) is fine-tuned for sketch classification.
- **Data Augmentation**: Techniques like random rotations, shifting, and horizontal flipping are used to increase the diversity of the training data.
- **Training**: The model is trained on 10,000 training images and validated on 5,000 images, with labels provided in CSV files.

## Dataset Structure

- **Train Folder**: Contains images for training, organized in the format expected by `ImageDataGenerator`.
- **Validation Folder**: Contains images for validation.
- **CSV Files**: `Train.csv` and `Validation.csv` contain the filenames and corresponding class labels for the images.
