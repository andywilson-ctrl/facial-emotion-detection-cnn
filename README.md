# facial-emotion-detection-cnn

## Overview
This project trains a Convolutional Neural Network (CNN) to recognize facial emotions from images.
Classes: Happy, Neutral, Sad, Surprised.

## Dataset
The dataset contains 20,000+ labeled images split into training, validation, and test sets.
Due to file size, the dataset is not included in this repository.

To reproduce:
1. Download the dataset from the original source (Kaggle or course-provided link)
2. Place it inside a local folder named `data/` following the same class subfolders used in the notebook

## Method
- Image preprocessing (grayscale)
- Custom CNN model
- Training monitored with validation set
- Final evaluation on a test set

## Results
- Accuracy: ~76%
- Best performance: Happy and Neutral
- Lower performance: Surprised (fewer examples, class imbalance)

## Project files
- Notebook: `notebook/`
- Slides: `presentation/`
- Images/plots: `images/`

## Future work
- Data augmentation for the Surprised class
- Regularization tuning
- Compare with transfer learning baselines (MobileNet / EfficientNet)
