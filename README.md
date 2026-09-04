# 🎓 Student Placement Prediction Using Machine Learning

## 📌 Project Overview

This repository contains the complete six-week development journey of a
Machine Learning project focused on **Student Placement Prediction**.

The project was developed progressively, starting from the initial
project proposal and data exploration, followed by model development,
advanced tuning, evaluation and interpretability, and finally an
integrated deployment simulation.

The objective is to build a Machine Learning system that predicts whether
a student is likely to be placed based on academic performance,
internships, projects, aptitude, soft skills, training, and other
placement-related attributes.

---

# 🗓️ Project Development Timeline

## 🔹 Week 1 — Strategic Project Proposal

### Objective

The first week focused on planning and designing the Machine Learning
project before implementation.

### Work Completed

- Identified the real-world problem of student placement prediction
- Defined the problem statement
- Studied the significance and potential impact of the problem
- Identified relevant stakeholders
- Planned the Machine Learning approach
- Identified possible data sources
- Proposed preprocessing and feature selection techniques
- Identified suitable Machine Learning algorithms
- Defined evaluation metrics
- Prepared the project timeline and milestones
- Identified expected challenges and computational requirements

### Deliverable

📄 **Project Proposal**

The proposal established the foundation and roadmap for the complete
Student Placement Prediction project.

---

# 🔹 Week 2 — Data Exploration and Preprocessing

### Objective

Week 2 focused on preparing the dataset for Machine Learning through
exploratory data analysis and preprocessing.

### Work Completed

- Selected a publicly available Student Placement dataset
- Loaded and explored the dataset
- Examined dataset structure and attributes
- Performed Exploratory Data Analysis (EDA)
- Identified missing values and data-quality issues
- Checked duplicate records
- Analysed numerical and categorical variables
- Cleaned and prepared the dataset
- Performed required feature transformations
- Prepared the target variable for classification
- Created visualizations to understand patterns in the data

### Deliverable

📄 **Student Placement Prediction – Data Exploration and Preprocessing Report**

The cleaned and prepared dataset became the foundation for the model
development stage.

---

# 🔹 Week 3 — Initial Model Development

### Objective

Week 3 focused on building the first Machine Learning model and
establishing a baseline for future improvements.

### Work Completed

- Prepared input features and target variable
- Created training and testing datasets
- Applied preprocessing techniques
- Built the initial Logistic Regression model
- Trained the model using the prepared dataset
- Generated predictions
- Evaluated model performance
- Calculated:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
- Analysed the initial model results
- Established the baseline model for future experiments

### Deliverable

📄 **Initial Model Development Report**

The Week 3 Logistic Regression model became the baseline against which
the Week 4 experiments were compared.

---

# 🔹 Week 4 — Advanced Model Tuning and Feature Engineering

### Objective

Week 4 focused on improving the baseline through feature engineering,
hyperparameter tuning, and comparison of multiple Machine Learning
algorithms.

### Work Completed

- Revisited the Week 3 Logistic Regression baseline
- Applied numerical feature scaling
- Applied categorical feature encoding
- Explored interaction-based feature engineering
- Used `ColumnTransformer` and Machine Learning pipelines
- Performed hyperparameter tuning using GridSearchCV
- Used 5-fold cross-validation during tuning
- Experimented with:
  - Logistic Regression
  - Random Forest
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
- Compared default and tuned models
- Evaluated models using accuracy, precision, recall and F1 score
- Selected the final model based on experimental results

### Model Comparison

| Rank | Model | Accuracy | Precision | Recall | F1 |
|---|---|---:|---:|---:|---:|
| 1 | Week 3 Baseline Logistic Regression | 80.85% | 76.95% | 77.59% | **77.27%** |
| 2 | Default SVM | 80.65% | 77.83% | 75.33% | 76.56% |
| 3 | Feature Engineered Logistic Regression | 80.25% | 77.14% | 75.21% | 76.16% |
| 4 | Tuned Logistic Regression | 80.20% | 77.05% | 75.21% | 76.12% |
| 5 | Tuned SVM | 80.15% | 77.15% | 74.85% | 75.98% |
| 6 | Tuned Random Forest | 79.95% | 77.31% | 73.90% | 75.56% |
| 7 | Tuned KNN | 79.35% | 75.24% | 75.69% | 75.46% |
| 8 | Default Random Forest | 79.45% | 76.88% | 72.94% | 74.86% |
| 9 | Default KNN | 77.60% | 74.29% | 71.28% | 72.75% |

### Final Model Selection

The **Week 3 Logistic Regression baseline** remained the strongest
overall model.

It achieved:

- **Accuracy:** 80.85%
- **Precision:** 76.95%
- **Recall:** 77.59%
- **F1 Score:** 77.27%

The experiments demonstrated that increasing model complexity or
performing hyperparameter tuning does not necessarily improve
generalization performance.

### Deliverable

📄 **Week 4 Advanced Model Tuning and Feature Engineering Report**

---

# 🔹 Week 5 — Model Evaluation, Validation and Interpretability

### Objective

Week 5 focused on evaluating the selected model more deeply and
understanding its predictions.

### Work Completed

- Reviewed the enhanced model from Week 4
- Performed extensive model validation
- Evaluated model robustness
- Analysed advanced performance metrics
- Generated confusion matrix
- Analysed ROC curve and ROC-AUC
- Examined prediction probabilities
- Applied model interpretation techniques
- Created visualizations for model performance
- Analysed strengths and limitations
- Identified possible improvements for future versions

### Key Evaluation Areas

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix
- ROC Curve
- Feature/model interpretation
- Prediction analysis

### Deliverable

📄 **Week 5 Model Evaluation and Interpretability Report**

This stage helped establish whether the selected model was reliable and
understandable enough to move toward deployment.

---

# 🔹 Week 6 — Integrated Project Simulation and Deployment

### Objective

Week 6 represents the final stage of the project by integrating all
previous work into a cohesive Machine Learning pipeline and simulating
its deployment.

### Work Completed

- Integrated data processing and preprocessing
- Created the final Machine Learning pipeline
- Integrated:
  - Data input
  - Preprocessing
  - Prediction
  - Probability estimation
  - Post-processing
- Saved the trained model using Joblib
- Loaded the saved model
- Tested the saved model
- Implemented new-student prediction
- Added input validation
- Tested valid and invalid inputs
- Performed integration testing
- Tested prediction consistency
- Measured inference performance
- Created a simulated deployment workflow
- Documented deployment requirements
- Planned scalability and monitoring
- Prepared user and technical documentation

### Final Pipeline

```text
Student Input
      ↓
Input Validation
      ↓
Data Preprocessing
      ↓
Feature Transformation
      ↓
Logistic Regression Model
      ↓
Prediction Probability
      ↓
Post-Processing
      ↓
Placed / Not Placed
