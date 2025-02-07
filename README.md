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

## Results

### 1. **Visualisations**
- **Top 3 intake and outcome combinations**: Stray & Adoption, Owner surrender & Adoption, Stray & Return to Owner.  
- **Seasonal trend**: Adoption rates are highest in July and August.  
  - **Conclusion**: Tailor adoption strategies to specific months. For example, advertise adoption more heavily outside of July and August to balance intake and provide adopters with diverse choices year-round.
- **Shelter stay durations**: Shelter time may be related to the type of intake.  
  - **Conclusion**: Allocate care more efficiently by addressing pets with longer stays, such as missing or lost pets, through surveys and improved community engagement.

---

### 2. **Machine Learning Performance**
- **Best model**: XGBoost achieved the highest accuracy (0.8446) with balanced precision (0.8273), recall (0.8467), and F1-Score (0.8352). Log loss was recorded at 0.5406.  
- **PCA impact**: Applying PCA reduced training time for linear models.  
  - **Conclusion**: Pets with health issues often had poor adoption predictions. Boosting the health of these pets or considering humane alternatives like euthanasia could reduce shelter stays, increase chances of adoption, and create space for new intakes.

---

### 3. **Recommendations**
- Generated unique names for pets based on attributes, improving the personal connection between adopters and pets.  
  - **Conclusion**: Use personalised recommendations to enhance adoption appeal and reduce shelter time.

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
