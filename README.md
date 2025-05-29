# MedPredictAI – Predictive Pipeline for Rare Disease Diagnosis

**Domain**: Medical + Data Science + Python (NLP/ML)  
**Goal**: Predict underdiagnosed diseases early by analyzing structured and unstructured EHR data.

## 💡 Project Features
- Use of publicly available EHR datasets (e.g. MIMIC-IV)
- NLP on clinical notes (BERT/ClinicalBERT)
- Feature engineering from lab tests, vitals, symptoms
- ML models to predict ICD-10 codes for rare diseases
- Explainable AI (SHAP, LIME)

## 🛠 How to Run
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Open and run `notebooks/01_data_preprocessing.ipynb`

## 📁 Structure
- `data/`: datasets (or download instructions)
- `notebooks/`: model building and EDA
- `src/`: scripts for preprocessing, training, etc.
- `models/`: saved models
- `images/`: visualizations
