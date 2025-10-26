# 🏥 Health Data Analyzer

Machine learning analysis of clinical biomarkers for diabetes prediction using the Pima Indians Diabetes Database.

## 🎯 Project Overview

This project implements a complete data analysis and classification pipeline for health outcome prediction based on clinical biomarkers.

**Objectives:**
- Exploratory data analysis of clinical biomarkers
- Data preprocessing and quality assessment
- Feature engineering and selection
- Implementation of classification models
- Model evaluation and interpretation

## 📊 Dataset

**Pima Indians Diabetes Database**
- **Source:** UCI Machine Learning Repository / Kaggle
- **Samples:** 768 female patients
- **Features:** 8 clinical measurements
- **Target:** Binary diabetes outcome (0=negative, 1=positive)

### Clinical Features

| Feature | Description | Unit |
|---------|-------------|------|
| Pregnancies | Number of pregnancies | count |
| Glucose | Plasma glucose concentration | mg/dL |
| BloodPressure | Diastolic blood pressure | mm Hg |
| SkinThickness | Triceps skin fold thickness | mm |
| Insulin | 2-Hour serum insulin | mu U/ml |
| BMI | Body mass index | kg/m² |
| DiabetesPedigreeFunction | Diabetes heredity score | score |
| Age | Age | years |

## 📁 Project Structure

```
01-health-data-analyzer/
├── README.md              # Project documentation
├── requirements.txt       # Python dependencies
├── data/
│   └── diabetes.csv       # Dataset
├── src/
│   └── load_data.py       # Data loading module
├── notebooks/
│   └── analysis.ipynb     # Exploratory analysis (planned)
└── results/
    └── figures/           # Output visualizations (planned)
```

## 🚀 Setup & Usage

### Prerequisites
```bash
Python 3.8+
pip or conda
```

### Installation
```bash
# Clone the repository
git clone <repository-url>
cd PROJECTS/01-health-data-analyzer

# Install dependencies
pip install -r requirements.txt
```

### Running the Analysis
```bash
# Load and explore data
python src/load_data.py
```

## 🔬 Methodology

### Phase 1: Data Exploration ✅
- Data loading and validation
- Statistical summary
- Data quality assessment
- Class distribution analysis

### Phase 2: Data Preprocessing (In Progress)
- Handling missing values (zeros)
- Outlier detection and treatment
- Feature scaling and normalization
- Train-test split

### Phase 3: Modeling (Planned)
- Baseline model (Logistic Regression)
- Tree-based models (Decision Tree, Random Forest)
- Model comparison and selection
- Hyperparameter tuning

### Phase 4: Evaluation (Planned)
- Performance metrics (Accuracy, Precision, Recall, F1)
- Confusion matrix analysis
- ROC curve and AUC
- Feature importance analysis

## 📈 Initial Findings

### Data Characteristics
- **Dataset Size:** 768 samples, 9 features
- **Class Distribution:** 65% negative (500), 35% positive (268)
- **Data Quality Issues:**
  - Zero values in Glucose: 5 samples (0.7%)
  - Zero values in BloodPressure: 35 samples (4.6%)
  - Zero values in SkinThickness: 227 samples (29.6%)
  - Zero values in Insulin: 374 samples (48.7%)
  - Zero values in BMI: 11 samples (1.4%)

> **Note:** Zero values in clinical measurements likely represent missing data and require preprocessing.

## 🛠️ Technologies

- **Language:** Python 3.8+
- **Data Processing:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Analysis:** Jupyter Notebook

## 📚 References

1. [Pima Indians Diabetes Database - UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/diabetes)
2. [Kaggle Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
3. Scikit-learn Documentation
4. Clinical diabetes diagnosis guidelines

## 📝 Future Work

- [ ] Complete data preprocessing pipeline
- [ ] Implement visualization dashboard
- [ ] Train and evaluate multiple models
- [ ] Feature importance analysis
- [ ] Model interpretation (SHAP values)
- [ ] Cross-validation strategy
- [ ] Final model selection and documentation

---

**Status:** In Development  
**Last Updated:** January 2025
