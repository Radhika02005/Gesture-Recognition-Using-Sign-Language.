# Gesture-Recognition-Using-Sign-Language

Here's a concise and professional version of your `README.md` without emojis:

---

## American Sign Language (ASL) Gesture Recognition

This project uses deep learning (CNN) to recognize static hand gestures representing the American Sign Language alphabet (A-Y, excluding J).

### Dataset

- **sign_mnist_train.csv**: Training images (28x28 grayscale).
- **sign_mnist_test.csv**: Testing images.
- csv file

### Tools & Libraries

- Python, TensorFlow/Keras
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

### Project Structure

```
├── Gesture_Recognition_Using_Sign_Language.ipynb
├── sign_mnist_train.csv
├── sign_mnist_test.csv
├── images/
└── README.md
```

### How to Run

1. Open the Jupyter notebook.
2. Run all cells to preprocess data, train the model, and evaluate.
3. View training/validation graphs, confusion matrix, and predictions.

### Key Features

- CNN-based image classification
- Accuracy and loss visualization
- Confusion matrix and class-wise metrics
- Sample misclassification analysis

### Results (Example)

| Metric              | Value     |
|---------------------|-----------|
| Training Accuracy   | 98.5%     |
| Validation Accuracy | 97.2%     |
| Test Accuracy       | 96.7%     |

### Notes

- Letters 'J' and 'Z' are excluded as they involve motion.
- All input images are normalized 28x28 grayscale.
