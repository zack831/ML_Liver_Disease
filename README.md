##### LIVER DISEASE CLASSIFICATION AND MORTALITY PREDECTION #####
Note : Datasets are obatined from various sources like kaggle(links are provided below)

This notebooks are able to Classify as well as predict the mortality(95% accuracy) of a liver disease aided patient with 99% accuracy

Notebooks are needed to run in specific order as given below to generate the needed datasets for futher computation. Detailed steps are given in their specific folder(if needed).

**1. Cirrhosis Various Train Test**
Contains various Notebooks for various Train and Test Splitted Datasets.

**2. Hepatitis Varios Train Test**
Contains various Notebooks for various Train and Test Splitted Datasets.

**3. HCC Various Train Test**
Contains various Notebooks for various Train and Test Splitted Datasets.

**4. Cleaning,Imputing and Merging**
--Contains various folder as given below.

**I. Cleaning & Merge Part 1**
-- Process of extracting only requied features and renaming columns as per a standard.

**II. Imputing Missing & Partition**
-- Process of Imputing missing values in Cirrhosis and Hepatitis datasets.

**III. Final Merge**
-- Final Merging of all three datasets after imputing all the null values and removing redundancy.

**IV. Cleaning Merge Non Liver**
-- Process of extracting only requied features,renaming columns & extracting only patients who dosen't have liver disease as per a standard from liver patient dataset and merging it with the final merged dataset obtained in previous step.

**V. Mortality**
-- Finding the mortality rate of the patients that have either of the three liver disease

**VI. Classification**
-- Classifing the type of disease the patient have given some specific symptoms.

**VII. Percentage of Disease Mortality**
-- Finding the mortality percentage of each disease.

**Refrences**
1. Liver Patient Dataset: https://www.kaggle.com/datasets/abhi8923shriv/liver-disease-patient-dataset
2. Cirrohis Dataset: https://www.kaggle.com/datasets/fedesoriano/cirrhosis-prediction-dataset
3. Hepatitis Dataset: https://www.kaggle.com/datasets/codebreaker619/hepatitis-data
4. HCC Dataset: https://www.kaggle.com/datasets/mrsantos/hcc-dataset?select=hcc-data-complete-balanced.csv



