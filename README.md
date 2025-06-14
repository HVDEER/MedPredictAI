# MedPredictAI – Predictive Pipeline for Rare Disease Diagnosis

**Domain**: Medical + Data Science + Python (NLP/ML)  
**Goal**: Predict underdiagnosed diseases early by analyzing structured and unstructured EHR data.

##  Project Features
- Use of publicly available EHR datasets (e.g. MIMIC-IV)
- NLP on clinical notes (BERT/ClinicalBERT)
- Feature engineering from lab tests, vitals, symptoms
- ML models to predict ICD-10 codes for rare diseases
- Explainable AI (SHAP, LIME)

##  How to Run
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Open and run `notebooks/01_data_preprocessing.ipynb`

##  Structure
- `data/`: datasets (or download instructions)
- `notebooks/`: model building and EDA
- `src/`: scripts for preprocessing, training, etc.
- `models/`: saved models
- `images/`: visualizations

## Dataset

This project uses **synthetic Electronic Health Records (EHR) data** generated by [Synthea](https://github.com/synthetichealth/synthea), an open-source synthetic patient generator. Synthea creates realistic but **non-identifiable** patient data that mimics real-world clinical records without using any real patient information.

The synthetic dataset used here contains **10,000 simulated patients** from Massachusetts and includes demographics, diagnoses, lab tests, and vital signs.

### Key Data Files

- `patients.csv`: Patient demographics such as age, gender, race, and death status.
- `conditions.csv`: Patient diagnoses mapped to ICD-10 codes.
- `observations.csv`: Lab tests and vital signs data (e.g., blood pressure, glucose).
- `encounters.csv`: Hospital visits and encounter details.

All files are in CSV format and stored in the `data/raw/` directory of this project.

---

*Note:* The dataset is synthetic and intended for research, development, and testing purposes only.
