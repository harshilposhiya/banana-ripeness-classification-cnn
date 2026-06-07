# Banana Ripeness Classification using CNN

## Project Overview
This project uses a Convolutional Neural Network (CNN) to classify banana images into different ripeness categories. The model is trained using image data and predicts the ripeness level of bananas.

## Dataset
Dataset Name: Banana Classification

Dataset Link:
(https://www.kaggle.com/datasets/koukazu/banana-ripness-level)
Notebook link -https://www.kaggle.com/code/harshilposhiya/notebookb1756468d3

## Classes
- Overripe
- Ripe
- Rotten
- Unripe

## Dataset Statistics
- Training Images: 11793
- Validation Images: 1123
- Test Images: 562
- Total Classes: 4

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Methodology
1. Load dataset using ImageDataGenerator.
2. Resize images to 224×224 pixels.
3. Normalize pixel values.
4. Apply data augmentation.
5. Build CNN model with convolution and pooling layers.
6. Train model using Adam optimizer.
7. Evaluate model using accuracy, loss, confusion matrix, and classification report.

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Results
The CNN model successfully classified banana images into four ripeness categories with good accuracy.

## Output Files
- accuracy_curve.png
- loss_curve.png
- confusion_matrix.png
- classification_report.png
- sample_dataset_images.png
- banana_cnn_model.h5

## How to Run

1. Open the Kaggle notebook.
2. Attach the Banana Classification dataset.
3. Run all notebook cells.
4. The model will train and generate output figures.
5. Download the generated files from the Output section.

## Author
Harshil Poshiya

## Course
Pattern Recognition
