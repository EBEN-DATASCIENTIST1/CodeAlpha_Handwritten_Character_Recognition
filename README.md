# Handwritten Character Recognition using CNN

## CodeAlpha Machine Learning Internship — Task 3

### Project Overview

This project uses a Convolutional Neural Network (CNN) to recognize handwritten digits from the MNIST dataset. The model classifies grayscale images into ten digit classes, from 0 to 9.

### Dataset

- **Dataset:** MNIST
- **Training images:** 60,000
- **Testing images:** 10,000
- **Image dimensions:** 28 × 28 pixels
- **Classes:** 10 digits (0–9)

### Technologies Used

- Python
- TensorFlow and Keras
- NumPy and Pandas
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

### Project Workflow

1. Load and explore the MNIST dataset.
2. Visualize sample handwritten digits and class distribution.
3. Normalize pixel values to the range 0–1.
4. Reshape images for CNN input.
5. Build and train a CNN using convolutional, pooling, dense, and dropout layers.
6. Evaluate the model using test accuracy, classification report, and confusion matrix.
7. Visualize training and validation accuracy and loss.
8. Display sample predictions.
9. Save the trained model.

### Model Performance

- **Test accuracy:** 99.21%
- **Test loss:** 0.0250

The model achieved high classification performance across the ten digit classes. Sample predictions and the confusion matrix demonstrate that most handwritten digits are correctly recognized.

### Saved Model

The trained model is saved at:

`models/handwritten_digit_cnn.keras`

### How to Run

1. Install the required Python packages: TensorFlow, NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn.
2. Open `notebook/Handwritten_Character_Recognition.ipynb` in Jupyter Notebook.
3. Run the notebook cells sequentially to reproduce the workflow.

### Conclusion

This project demonstrates how a CNN can learn visual features from handwritten digit images and achieve approximately 99% test accuracy on MNIST.

**Internship:** CodeAlpha — Machine Learning
