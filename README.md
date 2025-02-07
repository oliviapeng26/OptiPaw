# OptiPaw: Data-Driven Outcomes for Shelter Animals 🐾

This repository contains the **OptiPaw Project**, a data science initiative aimed at improving animal shelter outcomes. By analysing shelter data, we provide pet trends, predict adoption outcomes, and recommend tailored pet names.

---

## Problem
Every year, **7.6 million animals** enter U.S. shelters, and resources are often strained. This project addresses:
1. Efficient allocation of care.
2. Tailored adoption strategies.
3. Improved public engagement with data-driven insights.

---

## Features
- **Exploratory Data Analysis (EDA):**
  - Trends in adoption and shelter stay duration.
  - Seasonal and regional adoption variations.

- **Machine Learning Models:**
  - Logistic Regression, kNN, Random Forest, XGBoost, SVM, Neural Networks.
  - Dimensionality reduction using PCA.
  - Evaluative metrics: Accuracy, Precision, Recall, F1-Score, Log Loss.

- **Pet Name Recommendation System:**
  - Implements kNN with TF-IDF encoding and various distance metrics.
  - Generate 5 names for user to choose.

---

## Repository Structure
- **code/**:
  - data_cleaning/
  - eda_visualisations/
  - feature_engineering/
  - ml_models/
  - recommendation_system/
- **docs/**:
  - timeline.docx
  - OptiPaw Presentation.pdf
  - Research Project Proposal.docx
  - Research Project Report 2.docx
- LICENSE
- README.md
- **data_instructions.md**

---

## How to Run

1. **Clone Repository**:
  ```
  git clone https://github.com/yourusername/OptiPaw.git
  ```

3. **Install Requirements**:
  ```
  pip install -r requirements.txt
  ```
4. **Run Scripts**:
- Data Cleaning:
  ```
  python src/data_cleaning/clean_data.py
  ```
- Train Models:
  ```
  python src/models/train_model.py
  ```
- Generate Recommendations:
  ```
  python src/recommendation/recommend.py
  ```

---

## Results
1. **Visualizations**:
- Seasonal adoption trends.
- Shelter stay durations by intake type.
2. **Machine Learning Performance**:
- Best model: XGBoost (F1-Score: 0.87).
- PCA impact: Reduced training time for linear models.
3. **Recommendations**:
- Unique names generated for pets based on attributes.

---

## Contributors
- Lijia (PhD leader)
- Olivia
- YeeCheng
- Chloe

---

## Acknowledgments
Special thanks to SUDATA and SPDSC for giving us this mentoring opportunity, and to our team leader and members for their commitment. We acknowledge the use of public Kaggle datasets from **Austin, California, and Indiana** animal shelters.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Contact
Created by **Olivia Peng**. Feel free to reach out :)
