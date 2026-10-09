# Machine Learning Lab 6 – Artificial Neural Network

## Student Details

| Details | Information |
|---|---|
| **Name** | Daksh khandelwal|
| **Roll No.** | 45 |
| **Batch** | B_B3 |
| **Experiment** | Lab 6 |
| **Topic** | Artificial Neural Network (ANN) |

---

## 📌 Aim

To implement an **Artificial Neural Network (ANN)** model for classification of seed varieties using the Seeds dataset and evaluate its performance using different classification metrics.

---

## 📖 About the Experiment

In this experiment, an Artificial Neural Network is developed to classify different varieties of seeds based on their physical and geometric characteristics.

The dataset contains **210 samples** belonging to **3 different classes**.

The model uses the following features:

- Area
- Perimeter
- Compactness
- Length of kernel
- Width of kernel
- Asymmetry coefficient
- Length of kernel groove

The data is preprocessed, split into training and testing sets, scaled, and then given to the ANN model for classification.

---

## 📊 Dataset

**Dataset:** `seeds_new.csv`

### Dataset Information

- **Total Samples:** 210
- **Number of Classes:** 3
- **Target:** Class (1, 2, 3)
- **Features:** 7 numerical features

### Classes

The model predicts one of the following three seed classes:

- Class 1
- Class 2
- Class 3

---

## 🧠 ANN Model Architecture

The Artificial Neural Network consists of the following layers:

```text
Input Layer
     ↓
Dense Layer – 16 Neurons
Activation: ReLU
     ↓
Dense Layer – 8 Neurons
Activation: ReLU
     ↓
Output Layer – 3 Neurons
Activation: Softmax
