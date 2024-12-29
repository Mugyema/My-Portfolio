# My-Portfolio

# Machine Learning Model for Predicting Coronary Heart Disease (CHD)

## Overview

This repository contains the implementation of a Machine Learning (ML) algorithm developed in collaboration with Smart Data Learning to predict the likelihood of coronary heart disease (CHD) in patients. The algorithm leverages patient data, including clinical metrics, lifestyle information, and medical history, to provide  predictions that can assist clinicians in early detection and intervention.

---

## Project Goals

1. **Early Detection**: Identify patients at high risk of developing CHD based on available data.
2. **Personalized Healthcare**: Enable tailored recommendations for prevention and treatment.
3. **Clinical Integration**: Provide an easy-to-use, scalable model suitable for integration into hospital workflows.

---

## Data

The dataset used for this project includes anonymized patient records provided by Massachusetts General Hospital. Key features include:

- **Demographic Information**: Age, gender, etc.
- **Clinical Metrics**: Blood pressure, cholesterol levels, blood sugar, etc.
- **Lifestyle Factors**: Smoking status, physical activity, diet patterns, etc.
- **Medical History**: Family history of CHD, existing conditions like diabetes or hypertension, etc.

Data preprocessing steps included handling missing values, normalization, and feature engineering to enhance predictive power.

---

## Methodology

1. **Exploratory Data Analysis (EDA)**:

   - Analyzed distributions, correlations, and feature importance.
   - Visualized key trends and outliers.

2. **Model Selection**:

   - Evaluated multiple algorithms, including Logistic Regression, Random Forest, Gradient Boosting (XGBoost), and Neural Networks.
   - Selected the best-performing model based on accuracy, precision, recall, and AUC-ROC.

3. **Hyperparameter Tuning**:

   - Employed grid search and random search techniques to optimize model performance.

4. **Validation**:

   - Used cross-validation to ensure robustness.
   - Tested on a hold-out dataset to measure generalizability.

---

## Results

- **Accuracy**: 89%
- **Precision**: 87%
- **Recall**: 86%
- **AUC-ROC**: 0.91

The model demonstrates strong predictive performance, making it a valuable tool for clinical use.

---

## Features

- **Scalable**: Designed to handle large datasets efficiently.
- **Interpretable**: Outputs feature importance for actionable insights.
- **Secure**: Complies with healthcare data privacy standards (e.g., HIPAA).

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/chd-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd chd-prediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

1. Prepare your patient data in the required format (see `data/sample_data.csv` for reference).
2. Run the model prediction script:
   ```bash
   python predict_chd.py --input data/sample_data.csv --output results.csv
   ```
3. View results in the specified output file.

---

## Future Work

- **Continuous Learning**: Integrate feedback loops to improve model accuracy over time.
- **Broader Applicability**: Extend the model to predict other cardiovascular diseases.
- **Mobile Integration**: Develop a mobile app for real-time risk assessment.

---

## Acknowledgments

This project was made possible through the collaboration between Massachusetts General Hospital and the developer. Special thanks to the hospital’s clinical team for their insights and guidance.

---

## Contact

For questions or feedback, please reach out at:

- **Email**: [mugumya107hillary@gmail.com](mailto\:mugumya107hillary@gmail.com)
- **LinkedIn**: [Hillary Mugumya](https://www.linkedin.com/in/hillary-mugumya-986992177/))
- **GitHub**: [Hillary Mugumya](https://github.com/Mugyema)

