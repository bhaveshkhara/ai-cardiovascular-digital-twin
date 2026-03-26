# AI-Driven Cardiovascular Digital Twin Using Multi-Modal Data for Personalized Risk Prediction and Preventive Healthcare

This project presents a complete AI-driven healthcare system combining:

* Deep Learning-based cardiovascular disease prediction
* Multi-modal clinical data integration
* Digital Twin concept for patient-specific simulation

to enable accurate risk prediction, continuous monitoring, and preventive healthcare decision-making using a heart disease dataset.

---

## Project Highlights

* Deep Learning prediction model
* Logistic Regression baseline comparison
* Feature engineering pipeline
* End-to-end Jupyter notebook workflow
* Training visualization (accuracy and loss)
* Evaluation using confusion matrix and classification report
* Real-time prediction system

---

## Project Structure

```
cardio_digital_twin_project/
│
├── data/
│   ├── raw/
│   │   └── heart.csv
│   ├── processed/
│
├── notebooks/
│   ├── 00_dataset.ipynb
│   ├── 01_data_loading.ipynb
│   ├── 02_preprocessing.ipynb
│   ├── 03_eda_visualization.ipynb
│   ├── 04_feature_engineering.ipynb
│   ├── 05_model_building.ipynb
│   ├── 06_training.ipynb
│   ├── 07_evaluation.ipynb
│   ├── 08_prediction_demo.ipynb
│   └── 09_advanced_metrics.ipynb
│
├── models/
│   ├── lr_model.pkl
│   ├── dl_model.h5
│   └── dl_model_trained.h5
│
├── outputs/
│   ├── plots/
│   ├── metrics/
│
└── README.md
└── requirements.txt
```

---

## Dataset

* Source: UCI Heart Disease Dataset (Kaggle)
* Records: Clinical patient data
* Features include:

  * Age, Sex, Chest Pain Type
  * Blood Pressure, Cholesterol
  * ECG Results, Heart Rate

Target:

* 0 → No Heart Disease
* 1 → Heart Disease

---

## Model Summary

### Deep Learning Model

* Architecture: Dense Neural Network with Dropout
* Input: Multi-feature clinical data
* Output: Binary classification (risk prediction)

### Performance

* Accuracy: ~94 percent
* Balanced Precision and Recall
* Strong classification performance

---

## Training Results

### Accuracy and Loss

* Training accuracy increases consistently across epochs
* Validation accuracy remains stable
* Loss decreases, indicating proper learning

Generated outputs:

* Accuracy vs Epoch graph
* Loss vs Epoch graph

---

## Evaluation Metrics

* Confusion Matrix
* Classification Report
* Accuracy Score

These metrics demonstrate reliable prediction capability and balanced classification performance.

---

## Prediction System

The system allows prediction using new patient data.

Steps:

1. Input patient features
2. Apply scaling
3. Generate prediction
4. Output risk level

Output:

* Low Risk
* High Risk

---

## Digital Twin Concept

This project implements a simplified cardiovascular digital twin approach where:

* Patient data is used to create a virtual representation
* AI continuously predicts risk levels
* Enables simulation of disease progression
* Supports preventive healthcare strategies

---

## Installation

### 1. Clone Repository

```
git clone <your-repo-link>
cd cardio_digital_twin_project
```

### 2. Create Environment

```
conda create -n cardio_env python=3.10 tensorflow=2.13 pandas numpy scikit-learn matplotlib seaborn joblib -y
conda activate cardio_env
```

### 3. Launch Jupyter

```
jupyter lab
```

---

## Execution Flow

Run notebooks in the following order:

1. Data Loading
2. Preprocessing
3. EDA Visualization
4. Feature Engineering
5. Model Building
6. Training
7. Evaluation
8. Prediction

---

## Future Work

* Integration with wearable devices
* Federated learning for privacy
* Explainable AI for model transparency
* Real-time monitoring system
* Multi-disease prediction

---

## Conclusion

This project demonstrates how artificial intelligence combined with digital twin concepts can improve cardiovascular disease prediction. The system provides accurate predictions, supports personalized healthcare, and enables preventive decision-making.

---

## Author

Bhavesh Khara
Computer Engineering Student

---

## License

For academic and research use.
