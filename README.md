# 🐱🐶 SVM Cat vs Dog Image Classifier

A simple and efficient image classifier using **Support Vector Machines (SVM)** to distinguish between cats and dogs using grayscale image features.

![Cats vs Dogs Banner](https://i.imgur.com/p0Iuw2H.jpg)

---

## 📂 Dataset

This project uses the **Dogs vs Cats dataset** from Kaggle:  
🔗 [Kaggle Dataset Link](https://www.kaggle.com/competitions/dogs-vs-cats/data)

> **Note:** Due to Kaggle's terms, the dataset is not included here.  
Download it manually and extract the `train` folder into:  
## 🚀 Features

- Uses **OpenCV** for image processing
- Images resized to `64x64` and converted to **grayscale**
- Flattened and normalized before feeding into SVM
- **Linear SVM classifier** using `scikit-learn`
- Model trained on a **sample of 2000 images**
- Shows **accuracy and classification report**
- Visualizes predictions with matplotlib

---

## 🧠 Model

- Model: `sklearn.svm.SVC` with `linear` kernel
- Accuracy: ~80% on resized grayscale data
- Input: Flattened `64x64` grayscale image (4096-dim vector)

---

## 📒 Notebook Preview

| Cell | Description |
|------|-------------|
| 1    | Install & import libraries |
| 2    | Set paths and parameters |
| 3    | Load and preprocess images |
| 4    | Train/test split |
| 5    | Train SVM model |
| 6    | Evaluate performance |
| 7    | Visualize predictions |

---