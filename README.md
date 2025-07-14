# 🧠 Handwritten Digit Recognizer using CNN (MNIST)

This project uses a Convolutional Neural Network (CNN) built with TensorFlow and Keras to classify handwritten digits from the MNIST dataset.  
The model achieves an impressive **99.10% validation accuracy** by applying dropout regularization and data augmentation.

---

## 📌 Features

- Preprocessing and reshaping of raw MNIST data
- CNN architecture with Conv2D, MaxPooling, and Dropout
- Data augmentation using `ImageDataGenerator`
- EarlyStopping to prevent overfitting
- Accuracy visualization and prediction samples

---

## 📊 Final Model Performance

- **Training Accuracy:** 98.98%  
- **Validation Accuracy:** **99.10%**  
- **Loss:** 0.0249  

---

## 🧠 Tools & Libraries Used

- Python
- TensorFlow / Keras
- Pandas
- NumPy
- scikit-learn
- Matplotlib

---

## 📦 Dataset

The project uses the [MNIST Digit Recognizer Dataset](https://www.kaggle.com/competitions/digit-recognizer/data) from Kaggle.

> 🔔 **Note:**  
> Please download `train.csv` and `test.csv` from the Kaggle link above and place them in the root folder or inside a `data/` directory before running the notebook.
