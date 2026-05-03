# Tic-Tac-Toe Symbol Recognition using CNN

This project is a computer vision image classification task that uses a Convolutional Neural Network (CNN) to recognize individual Tic-Tac-Toe board cells.

The model classifies each cell into one of three classes:

- Blank: empty cell
- Circle: O symbol
- Nought: X symbol

## Dataset

The dataset contains 600 grayscale images with a size of 128x128 pixels.

| Class | Train | Test | Total |
|---|---:|---:|---:|
| Blank | 160 | 40 | 200 |
| Circle | 160 | 40 | 200 |
| Nought | 160 | 40 | 200 |
| Total | 480 | 120 | 600 |

The dataset includes hand-drawn variations, different line weights, and slightly off-center symbols to simulate real-world conditions.

## Model

The project uses a custom CNN architecture built with PyTorch.

Main steps:

1. Load the dataset using ImageFolder
2. Apply image preprocessing
3. Train the CNN model
4. Evaluate the model on the test set

## Tools and Libraries

- Python
- PyTorch
- Torchvision
- Google Colab / Jupyter Notebook

## Project Structure

```text
notebooks/
dataset/
requirements.txt
README.md
