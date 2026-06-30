# 🖼️ MNIST Image Classification using Deep Learning

A Deep Learning project that classifies handwritten digits (0–9) using the **MNIST dataset**. This project demonstrates the complete machine learning workflow, including data preprocessing, visualization, model building, training, evaluation, and prediction using TensorFlow and Keras.

---

## 📖 Project Overview

The objective of this project is to develop an image classification model capable of recognizing handwritten digits from grayscale images.

The project utilizes the **MNIST dataset**, one of the most widely used benchmark datasets in computer vision and deep learning. A neural network is trained to accurately classify handwritten digits into one of ten classes (0–9).

---

## 🎯 Objectives

- Load and explore the MNIST dataset
- Visualize handwritten digit images using Matplotlib
- Preprocess image data for model training
- Build a Deep Learning model using TensorFlow/Keras
- Train and evaluate the model
- Predict handwritten digits from test images
- Visualize model performance

---

## 📂 Dataset Information

**Dataset:** MNIST Handwritten Digits

- Training Images: **60,000**
- Testing Images: **10,000**
- Image Size: **28 × 28 pixels**
- Number of Classes: **10**
- Labels: **Digits 0–9**

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📊 Project Workflow

1. Import Required Libraries
2. Load the MNIST Dataset
3. Explore Dataset Information
4. Visualize Sample Images
5. Data Preprocessing
   - Normalize pixel values
   - Reshape images (if required)
6. Build Deep Learning Model
7. Compile the Model
8. Train the Model
9. Evaluate Model Performance
10. Predict Test Images
11. Visualize Results

---

## 📈 Results

The trained model successfully classifies handwritten digits with high accuracy on the test dataset.

### Performance Highlights

- ✔️ Image Classification
- ✔️ Model Training
- ✔️ Test Evaluation
- ✔️ Prediction on New Images
- ✔️ Data Visualization using Matplotlib

---

## 📸 Sample Outputs

The project includes visualizations such as:

- Sample handwritten digit images
- Training accuracy graph
- Training loss graph
- Model predictions
- Confusion Matrix (optional)

> Store screenshots inside the **images/** folder and display them here.

Example:

```text
images/
├── sample_digits.png
├── accuracy_graph.png
├── loss_graph.png
├── prediction.png
└── confusion_matrix.png
```

---

## 📁 Project Structure

```
MNIST-Image-Classification/
│
├── MNIST_Image_Classification.ipynb
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
├── images/
│   ├── sample_digits.png
│   ├── accuracy_graph.png
│   ├── loss_graph.png
│   ├── prediction.png
│   └── confusion_matrix.png
└── model/
    └── mnist_model.keras
```

---

## ⚙️ Installation

Clone this repository:

```bash
git clone https://github.com/your-username/MNIST-Image-Classification.git
```

Navigate to the project directory:

```bash
cd MNIST-Image-Classification
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## 📦 Requirements

```
tensorflow
numpy
matplotlib
scikit-learn
jupyter
```

---

## 🚀 Future Enhancements

- Improve model accuracy using Convolutional Neural Networks (CNN)
- Implement data augmentation
- Deploy the model using Flask or Streamlit
- Add a web interface for real-time digit prediction
- Save and load trained models

---

## 👩‍💻 Authors

**S. Lakshmi Abhishiktha**

**V. Mohana**

---

## 📜 License

This project is licensed under the MIT License.

---

## ⭐ Acknowledgements

- TensorFlow
- Keras
- MNIST Dataset
- NumPy
- Matplotlib

---

### If you found this project useful, consider giving it a ⭐ on GitHub!