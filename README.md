# Heart Failure Clinical Data Analysis

## Project Overview

This project explores clinical characteristics associated with recorded mortality outcomes among patients with heart failure using publicly available clinical data. Python is used to perform data cleaning, exploratory data analysis, statistical comparisons, data visualization, and a preliminary machine learning analysis.

The project aims to demonstrate how computational methods can be applied to biomedical datasets to investigate patterns in clinical data.

## Research Question

**Which clinical characteristics are associated with recorded death events among patients with heart failure in the dataset?**

The analysis focuses on variables such as age, ejection fraction, serum creatinine, serum sodium, and follow-up duration.

## Dataset

- **Name:** Heart Failure Clinical Records
- **Source:** UCI Machine Learning Repository
- **Number of patients:** 299 in the original dataset
- **Target variable:** `DEATH_EVENT`
- **Dataset link:** https://archive.ics.uci.edu/dataset/519/heart+failure+clinical+records

The dataset contains clinical characteristics and follow-up information for patients with heart failure. The target variable indicates whether a death event was recorded during the follow-up period.

## Tools and Technologies

- **Python** — data analysis and modeling
- **Pandas** — data manipulation and cleaning
- **NumPy** — numerical computing
- **Matplotlib** — data visualization
- **Seaborn** — statistical graphics
- **SciPy** — statistical hypothesis testing
- **Scikit-learn** — machine learning and model evaluation
- **Statsmodels** — multiple-comparison correction

## Project Workflow

### 1. Data Collection and Quality Assessment
- Load the dataset from the UCI Machine Learning Repository.
- Inspect the dataset structure, variable types, and descriptive statistics.
- Check for missing values and duplicate records.

### 2. Exploratory Data Analysis
- Examine the distribution of clinical variables.
- Analyze the distribution of recorded death events.
- Explore correlations between numerical features.
- Visualize important clinical characteristics using histograms, boxplots, and a correlation heatmap.

### 3. Statistical Analysis
- Compare numerical clinical characteristics between outcome groups using the Mann–Whitney U test.
- Examine associations between categorical variables and the recorded outcome using chi-square tests.
- Apply false discovery rate correction to account for multiple statistical comparisons.

### 4. Machine Learning
- Split the data into training and test sets.
- Build a logistic regression classification pipeline.
- Evaluate model performance using accuracy, precision, recall, F1-score, and ROC-AUC.
- Examine model coefficients to explore the direction and relative magnitude of associations.

### 5. Results
Results will be documented after executing the analysis and reviewing the generated outputs.

Planned outputs include:

Clinical feature distributions

Correlation analysis

Statistical comparisons between outcome groups

Logistic regression evaluation metrics

Visualizations of model coefficients

### Limitations

The dataset contains only 299 patients, limiting the generalizability of findings.

The analysis is observational and cannot establish causal relationships.

Statistical associations do not demonstrate that a clinical characteristic causes a death event.

Model performance on a single train-test split may be unstable and requires further validation.

This exploratory model is not intended for clinical decision-making or individual patient risk assessment.

### Ethical Considerations

This project uses a publicly available dataset for educational and research purposes. No individual patient-identifying information is intentionally used in the analysis.

### Project Status

Status: Initial implementation and exploratory analysis.

Results and interpretations will be added after the code has been executed and the outputs have been reviewed.

### Author

Hatice İLHAN 

### Acknowledgements

The dataset is provided by the UCI Machine Learning Repository. All dataset rights and terms of use remain subject to the original source.
