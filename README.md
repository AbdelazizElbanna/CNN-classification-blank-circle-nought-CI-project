# Tic-Tac-Toe Symbol Recognition using CNN 

A Computer Vision project that uses a Convolutional Neural Network (CNN) to classify individual Tic-Tac-Toe cells into three categories:<br>
**🔲 Blank**, **⭕**, or **❌**.

---

## 📌 Project Overview

This project focuses on building an image classification model that can recognize the content of a single Tic-Tac-Toe cell.

The model predicts one of the following:
* 🟩 **Blank** → Empty cell
* ⭕ **Circle** → 'O' symbol
* ❌ **Nought** → 'X' symbol

---

## 🗂 Dataset

The dataset consists of **600 grayscale images** (128x128 pixels), equally distributed across three classes:

| Class | Train | Test | Total |
| :--- | :---: | :---: | :---: |
| Blank | 160 | 40 | 200 |
| Circle | 160 | 40 | 200 |
| Nought | 160 | 40 | 200 |
| **Total** | **480** | **120** | **600** |

**📌 Features:**
* Hand-drawn variations.
* Different line thickness.
* Slightly off-centered symbols.

---

## 🧠 Model Architecture

A Convolutional Neural Network (CNN) is used to extract features from images and classify them.

### Main Steps:
1. Load dataset using `ImageFolder`.
2. Apply preprocessing & normalization.
3. Train CNN model.
4. Evaluate on test set.

---

## 📁 Project Structure

```text
tic-tac-toe-symbol-recognition/
│
├── dataset/
│   ├── train/
│   └── test/
|
├── notebooks/
│   └── CNN_classification_blanck_circle_nought.ipynb
│   
├── requirements.txt
└── README.md
```
## ⚙️ Installation & Requirements

Make sure you have Python installed, then install the required libraries by running:

```bash
pip install -r requirements.txt
```

### 📦 Libraries Used

The project uses the following libraries:

- torch
- torchvision
- numpy
- matplotlib
- pillow
- jupyter

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
```

### 2. Navigate to the project folder

```bash
cd tic-tac-toe-symbol-recognition
```

### 3. Open the main notebook

```text
notebooks/CNN_classification_blanck_circle_nought.ipynb
```

### 4. Run all cells

Run the notebook cells to train and test the CNN model.

---

## 💡 Future Improvements

- Improve model accuracy
- Add real-time detection using camera input
- Deploy the model as a web or mobile application

---

## 👥 Credits

- **@AbdelazizElbanna** — Project author and CNN developer  
- **@Jana-Hazem101** — Repository setup, structure, and documentation

---
⭐ If you find this repository useful, feel free to star it.
