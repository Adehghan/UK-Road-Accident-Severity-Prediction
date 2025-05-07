
# UK Road Accident Severity Prediction

This project performs machine learning analysis on UK road accident data to predict accident severity. It involves clustering, association rule mining, and classification modeling to help understand and reduce the impact of severe traffic incidents.

---

## Dataset

The dataset used is the [UK Road Accident Data 2020](https://data.gov.uk/dataset/road-accidents-safety-data). It contains over 220,000 accident records with attributes related to location, weather, road conditions, vehicle types, and accident severity.

**Note:** Due to file size, the dataset is not included in this repository. Please place your copy of `accident_data_v1.0.0_2023.db` in the root folder.

---

## Objectives

- Clean and preprocess road accident data
- Explore accident patterns by time, location, and conditions
- Detect outliers and investigate unusual accident scenarios
- Apply the Apriori algorithm for association rule mining
- Perform clustering with KMeans, KMedoids, and DBSCAN
- Build classification models (Random Forest, Decision Tree, Gradient Boosting)
- Address class imbalance using SMOTE and undersampling

---

## Technologies Used

- **Python**
- **pandas**, **numpy**, **seaborn**, **matplotlib**
- **scikit-learn** (ML models, GridSearchCV)
- **imblearn** (for SMOTE)
- **mlxtend** (Apriori algorithm)
- **sqlite3** (for loading `.db` file)

---

## Project Structure

```
📦 uk-road-accident-severity-prediction
 ┣ 📄 001_CWRK_Project_Report.ipynb
 ┣ 📄 requirements.txt
 ┗ 📄 README.md
