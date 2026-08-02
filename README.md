# Hybrid Crowd Counting using ResNet-50 & CatBoost

A hybrid computer vision project that combines **ResNet-50 Transfer Learning** with **CatBoost Regression** to accurately estimate the number of people in crowded scenes. The model extracts rich visual features from images using a pretrained ResNet-50 network and leverages CatBoost for robust crowd count prediction.

---

# Overview

Crowd counting plays a vital role in surveillance, transportation, public safety, and smart city applications. Detecting individuals in highly congested scenes is challenging due to heavy occlusions and scale variations. This project presents a hybrid approach that combines deep feature extraction with machine learning regression to estimate crowd counts efficiently and accurately.

The complete pipeline includes image preprocessing, feature extraction using ResNet-50, regression with CatBoost, and performance evaluation using standard regression metrics.

---

# Key Features

- Automated crowd counting from images
- Crowd density estimation
- Deep feature extraction using ResNet-50
- Transfer learning for improved performance
- CatBoost regression for crowd count prediction
- Model evaluation using MSE, MAE, and R² Score
- Prediction visualization on validation samples
- Reproducible workflow using Jupyter Notebook

---

# Technology Stack

- Python
- TensorFlow
- Keras
- OpenCV
- ResNet-50
- CatBoost
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook
- Google Colab
- Git
- GitHub

---

# Dataset

The project is trained and evaluated using the Crowd Counting Dataset containing annotated crowd images along with their corresponding crowd counts.

**Dataset**

https://www.kaggle.com/datasets/fmena14/crowd-counting

---

# Methodology

```text
Crowd Counting Dataset
          │
          ▼
Image Preprocessing
          │
          ▼
Image Normalization
          │
          ▼
ResNet-50 Feature Extraction
          │
          ▼
Feature Vector Generation
          │
          ▼
CatBoost Regression
          │
          ▼
Crowd Count Prediction
          │
          ▼
Performance Evaluation
```

---

# Installation

### Clone the Repository

```bash
git clone https://github.com/HimanshuS-arch/Hybrid-Crowd-Counting-using-ResNet-50-CatBoost.git
```

### Navigate to the Project Directory

```bash
cd Hybrid-Crowd-Counting-using-ResNet-50-CatBoost
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Run all notebook cells sequentially to preprocess the dataset, train the model, and evaluate predictions.

---

# Project Structure

```text
Hybrid-Crowd-Counting-using-ResNet-50-CatBoost/
│
├── Hybrid Crowd Counting using ResNet-50 & CatBoost.ipynb
├── README.md
├── requirements.txt
└── dataset/
```

---

# Results

The proposed hybrid model combines deep feature extraction and gradient boosting regression to achieve reliable crowd count estimation on unseen images.

### Evaluation Metrics

```text
+-----------------------------------------------+
|      CatBoost Evaluation (Validation Set)     |
+-----------------------------------------------+
| Mean Squared Error (MSE)       : 8.4562        |
| Mean Absolute Error (MAE)      : 2.2625        |
| R² Score                       : 0.8276        |
+-----------------------------------------------+
```

### Sample Predictions

```text
+--------------------------------------------------+
| Sample Crowd Count Predictions                   |
+--------------------------------------------------+
| Image 1   | Predicted: 31 | Actual: 30           |
| Image 2   | Predicted: 32 | Actual: 34           |
| Image 3   | Predicted: 38 | Actual: 45           |
| Image 4   | Predicted: 39 | Actual: 42           |
| Image 5   | Predicted: 26 | Actual: 25           |
| Image 6   | Predicted: 33 | Actual: 33           |
| Image 7   | Predicted: 33 | Actual: 31           |
| Image 8   | Predicted: 41 | Actual: 44           |
| Image 9   | Predicted: 30 | Actual: 27           |
| Image 10  | Predicted: 31 | Actual: 36           |
+--------------------------------------------------+
```

The model achieved an **R² Score of 0.8276**, demonstrating strong predictive capability while maintaining low prediction error across the validation dataset.

---

# Applications

- Smart Surveillance Systems
- Crowd Density Monitoring
- Traffic Management
- Railway and Metro Stations
- Stadium and Event Management
- Shopping Mall Analytics
- Smart City Infrastructure
- Disaster and Emergency Response

---

# Future Work

- Real-time crowd counting from video streams
- Integration with object detection models
- Deployment as a web application
- Edge-device optimization
- Training on larger benchmark datasets
- Improving performance on extremely dense crowds

---

# References

- Crowd Counting Dataset
- TensorFlow Documentation
- Keras Documentation
- ResNet-50 Documentation
- CatBoost Documentation
- OpenCV Documentation
- Scikit-learn Documentation

---

# Author

**Himanshu Saroj**

B.Tech – Information Technology

Harcourt Butler Technical University, Kanpur

GitHub: https://github.com/HimanshuS-arch

---


---

# Support

If you found this project helpful, consider giving the repository a **star** on GitHub. Contributions, suggestions, and feedback are always welcome.
