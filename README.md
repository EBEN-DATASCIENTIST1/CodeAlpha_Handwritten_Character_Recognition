# Handwritten Digit Recognition Using CNN

**CodeAlpha Machine Learning Internship — Task 3**

## Overview

This project uses a Convolutional Neural Network (CNN) to recognize handwritten digits from images. The model is trained and evaluated using the MNIST dataset, which contains grayscale images of digits from 0 to 9.

## Dataset

- **Dataset:** MNIST
- **Training images:** 60,000
- **Testing images:** 10,000
- **Image dimensions:** 28 × 28 pixels
- **Number of classes:** 10

## Methodology

1. Load and explore the MNIST dataset.
2. Visualize sample handwritten digits.
3. Normalize pixel values to the range 0–1.
4. Prepare image dimensions for CNN input.
5. Build a CNN with convolutional, pooling, dense, and dropout layers.
6. Train the model using early stopping.
7. Evaluate test accuracy and loss.
8. Analyze the classification report and confusion matrix.
9. Visualize training curves and sample predictions.
10. Save the trained model.

## Model Architecture

The CNN includes:

- A convolutional layer with 32 filters and max pooling
- A convolutional layer with 64 filters and max pooling
- A flattening layer
- A dense layer with 128 units
- A dropout layer with a rate of 0.3
- A softmax output layer with 10 units

The model contains 225,034 parameters.

## Results

| Metric                   |     Result |
| ------------------------ | ---------: |
| Test Accuracy            | **99.21%** |
| Test Loss                |     0.0250 |
| Best Validation Accuracy |     99.35% |
| Lowest Validation Loss   |     0.0288 |

The model achieved consistently strong classification performance across all ten digit classes. Most test images were correctly classified.

## Saved Model

The trained model is saved as:

`models/handwritten_digit_cnn.keras`

## Technologies Used

- Python
- TensorFlow/Keras
- NumPy and Pandas
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Repository Structure

- `models/` — Saved CNN model
- `notebook/` — Jupyter Notebook containing preprocessing, training, and evaluation
- `README.md` — Project documentation

## Conclusion

This project demonstrates the use of CNNs for image classification. The model achieved **99.21% test accuracy** on MNIST, showing excellent performance on this handwritten digit recognition benchmark.

**Internship:** CodeAlpha — Machine Learning
