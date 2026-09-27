# 🔢 Handwritten Digit Recognizer

Classifying handwritten digits (0–9) with a Multi-Layer Perceptron neural network in scikit-learn, reaching **98.3% accuracy** on unseen test data.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Lidiyajohnson07/image-classifier/blob/main/imageclassifier.ipynb)

## 📌 Problem
Given a small grayscale image of a handwritten digit, predict which digit (0–9) it shows. This is a **multi-class image classification** task.

## 📂 Dataset
- **scikit-learn Digits** dataset (`sklearn.datasets.load_digits`)
- 1,797 images, 8×8 pixels each (64 features per image)
- 10 classes (digits 0–9)

## ⚙️ Approach
1. Loaded and visualized sample digits
2. Split into 80% training and 20% test data (`random_state=42`)
3. Trained an **MLP classifier** (1 hidden layer, 100 neurons, up to 500 iterations)
4. Evaluated accuracy on the test set
5. Visualized predictions and a confusion matrix to see which digits get confused

## 📊 Results
| Metric | Value |
|---|---|
| Test accuracy | 98.33% |
| Test images | 360 |

The confusion matrix shows almost all predictions on the diagonal, with only a few misclassified digits.

## 🔭 Possible Improvements
- Feature scaling (e.g., `StandardScaler`) and hyperparameter tuning
- Cross-validation for a more reliable accuracy estimate
- A Convolutional Neural Network (CNN) in PyTorch on the full MNIST dataset (28×28 images)

## 🛠️ Tools
Python · scikit-learn · NumPy · matplotlib · seaborn · Google Colab

## ▶️ How to Run
Click the **Open in Colab** badge above and run all cells. No local setup needed.

## 👩‍💻 Author
**Lidiya Johnson**, M.Sc. Computational Engineering, FAU Erlangen-Nürnberg
GitHub: [@Lidiyajohnson07](https://github.com/Lidiyajohnson07)
