# 🖑 Garbage Classification with CNN

This project classifies garbage into:

* 🔋 Battery waste
* 🌿 Biological waste

## 📁 Project Structure

```
Garbage-Classification/
├── garbage_model.ipynb                 # Jupyter notebook for training & testing
├── garbage_classifier_model.keras      # (Link provided below)
├── garbage_classifier_model.h5         # (Link provided below)
├── garbage_classification/             # Dataset folder with images
└── requirements.txt                    # Required Python packages
```

## 🧠 Model Overview

* Built using **Convolutional Neural Networks (CNN)**
* Implemented with **TensorFlow / Keras**
* Trained on a 2-class dataset: `biological` and `battery`
* Achieved over **95% accuracy** on validation set

## 💡 Features

* Image preprocessing and normalization
* Train-test split using scikit-learn
* Model evaluation with accuracy & loss plots
* Real-time image prediction

## 🔧 Installation

1. Clone this repository:

```bash
git clone https://github.com/your-username/garbage-classification.git
```

2. Navigate to the project folder:

```bash
cd garbage-classification
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

## 🚀 Run the Project

Open the notebook in Jupyter and run all cells:

```bash
jupyter notebook garbage_model.ipynb
```

## 📦 Model Downloads

Due to GitHub size limitations, download the trained models from Google Drive:

* 🧠 [Download `.keras` Model](https://drive.google.com/file/d/1s-G00cywzE4tdAWiULhUvXuX0ufZ6do-/view?usp=sharing)
* 🧠 [Download `.h5` Model](https://drive.google.com/file/d/1Zi_h5xx1sl7aCop3nwI4A5t_3qFgzOJi/view?usp=sharing)

## 📊 Sample Results

* Validation accuracy: **\~95%**
* Smooth convergence in training loss
* Correct predictions on unseen test images

## 🌐 Credits

Created as part of an academic project on image classification using CNNs.

