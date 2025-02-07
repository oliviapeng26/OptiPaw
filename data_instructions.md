# Data Instructions for OptiPaw Repository

The data files for the OptiPaw project are hosted externally in google drive due to their large size. Follow the steps below to access the data and run the code:

---

## **Step 1: Access the Data**
1. Visit the [OptiPaw Data Google Drive Folder](https://drive.google.com/drive/folders/1qFq_yNHQVVKv-FSYt_zh_r0xRBw3XLaV?usp=sharing).
2. The folder contains two subfolders:
   - **`raw`**: Contains the unprocessed, original datasets used for data cleaning.
   - **`processed`**: Contains cleaned and transformed datasets for use in the visualisations, machine learning models, and recommendation system.

---

## **Step 2: Download the Data**
Download data sets in both the `raw` and `processed` folders to your local machine.

---

## **Step 3: Copy the Data File's Address**
Follow the allocation below to copy and paste the data file's address into the corresponding code files:  

- **OptiPaw Data Folder** → **`raw`** → **All Datasets**  
  Use these file paths in all code files (.ipynb) located in the `OpitPaw/data_cleaning` folder.  

For example:  
```python
data = "data/raw/indiana-animal-data.csv"
```

- **OptiPaw Data Folder** → **`processed`** → **optipaw_FINAL.csv**  
  Use this data file's path in all code files (.Rmd, ipynb) located in the `OpitPaw/eda_visualisations`,  `OpitPaw/feature_engineering`, `OpitPaw/ml_models`, and `OpitPaw/recommendation_system` folders. 

For example:  
```python
data = "data/processed/optipaw_FINAL.csv"
```
---

## **Step 4: Run the Code**
Now you can run any code files in the OptiPaw repository!
