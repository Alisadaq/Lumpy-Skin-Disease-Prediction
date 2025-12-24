# Lumpy-Skin-Disease-Prediction
This repository contains the research work, analysis, and implementation from my Bachelor’s thesis in Mathematics at COMSATS University Islamabad. The project investigates the use of classical machine‑learning methods to predict Lumpy Skin Disease (LSD) in cattle using environmental, climatic, and clinical features.
The goal of this repository is to present a clean, reproducible, research‑oriented workflow that demonstrates my understanding of supervised learning, data preprocessing, class imbalance handling, and model evaluation.

Project Overview
Lumpy Skin Disease is a viral infection affecting cattle and causing significant economic losses. Traditional diagnostic methods rely on laboratory testing, which can be slow or inaccessible in many regions. This project explores whether machine‑learning models can support early detection using structured data.
The study includes:
- Exploratory Data Analysis (EDA)
- Data preprocessing
- Handling missing values
- Encoding categorical variables
- Outlier removal
- Feature scaling
- Baseline model training
- Class imbalance handling (SMOTE, ADASYN, NearMiss)
- Ensemble learning (Hard Voting Classifier)
- Evaluation using standard metrics
- thesis/ contains the full thesis PDF and presentation slides.


Dataset
- Source: Kaggle
- Type: Structured tabular data
- Features: Environmental variables (temperature, humidity, etc.), Clinical indicators (skin lesions, fever, lactation status), Categorical attributes (breed, location, country)
- Target variable: Lumpy (0 = No disease, 1 = Disease present)
- Nature: Imbalanced, requiring resampling techniques

Methodology
1. Exploratory Data Analysis
- Summary statistics
- Missing value inspection
- Distribution plots
- Target imbalance visualization
2. Preprocessing
- Mean/median/mode imputation
- Label Encoding for binary categories
- One‑Hot Encoding for multi‑class categories
- Z‑score based outlier removal
- Standardization of numerical features
3. Baseline Models
- Logistic Regression
- Support Vector Machine (Linear Kernel)
- Linear Discriminant Analysis
- Gaussian Naive Bayes
- Decision Tree
- SGD Classifier
4. Class Imbalance Handling
- SMOTE (oversampling)
- ADASYN (oversampling)
- NearMiss (undersampling)
5. Ensemble Learning
- Hard Voting Classifier combining:
- Logistic Regression
- SVM
- Decision Tree

Results Summary
The study compares:
- Baseline performance
- Performance after resampling
- Ensemble performance
General findings:
- Oversampling improved recall for minority class
- Undersampling improved precision but reduced recall
- The Voting Classifier provided the most balanced performance
- Class imbalance significantly affected all models
- Preprocessing steps had a measurable impact on model stability
(Exact numerical results are available in the notebook and thesis.)

Key Skills Demonstrated
- Applied machine learning
- Statistical reasoning
- Data preprocessing and cleaning
- Handling imbalanced datasets
- Model evaluation and comparison
- Ensemble methods
- Reproducible research workflow
- Clear academic documentation


📚 Thesis & Presentation
Full documentation of the research is available in the thesis/ folder:
- Lumpy_Skin_Disease_Prediction_Thesis.pdf
- LSD_Prediction_Presentation.pdf
These files provide detailed explanations, figures, and academic context.

📬 Contact
If you are a researcher, professor, or recruiter interested in discussing this work or potential collaborations, feel free to reach out.
