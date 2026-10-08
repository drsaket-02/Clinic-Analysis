# Clinic-Analysis

Medical data analysis and machine learning projects built as part of my 
Medicine + Technology learning journey.

**Author:** Saket Gupta | MBBS Student | RNT Medical College, Udaipur

---

## Project 1: Clinic Data Analysis
**File:** Clinical_data_2.0.ipynb

Analysis of 2000 patient records from a clinical dataset.

**What this covers:**
- Data cleaning and preprocessing (missing values, impossible ages, inconsistent categories)
- Patient diagnosis distribution analysis
- Department-wise billing analysis
- Doctor performance comparison
- BMI vs Blood Sugar visualization
- BP category classification using custom function

**Tools:** Python, Pandas, Matplotlib, Google Colab

---

## Project 2: Diabetes Prediction Model
**File:** Diabetes_prdict_model_1.ipynb

Machine learning model to predict diabetes using clinical parameters.

**Dataset:** Pima Indians Diabetes Dataset (768 rows, 9 columns)

**What this covers:**
- Data cleaning (handling disguised missing values as zeros)
- Model 1: Decision Tree Classifier — Accuracy 76.62%
- Model 2: Random Forest Classifier — Accuracy 77.27%
- Confusion Matrix analysis (false negatives, false positives)
- Feature Importance analysis (Glucose 30%, BMI 20%)

**Tools:** Python, Pandas, Scikit-learn, Matplotlib, Google Colab


---

## Project 3: Pulmonary TB Detection from Chest X-rays
**File:** PulmonaryTB_ML_1.ipynb

Deep learning model to detect Tuberculosis from chest X-ray images using CNNs.

**Dataset:** Tuberculosis Chest X-ray Database — Qatar University/Dhaka Medical College (2200 images: 700 TB, 1500 Normal)

**What this covers:**
- Image preprocessing and data augmentation
- Transfer learning with ResNet-18 (fine-tuned on medical images)
- Model accuracy: 99.76% | Sensitivity: 99.4% | Specificity: 100%
- Error analysis: 4 false negatives identified and clinically interpreted
- External image testing with probability output (distribution shift discussed)

**Tools:** Python, fastai, PyTorch, ResNet-18, Jupyter Notebook

## Skills demonstrated
Python | Pandas | Scikit-learn | Data Cleaning | 
Machine Learning | Data Visualization | Clinical Data Analysis | fastai | PyTorch
