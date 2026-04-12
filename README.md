# Recipe-Review-And-Feedback-Classification-Model



## Detecting receipe star reviews dataset

This project applies **data science and machine learning** techniques to predict patient survival outcomes based on receipes and reviews data.
It includes **EDA, preprocessing, outlier handling, feature encoding, model training, and evaluation** using multiple algorithms.

---

###  Project Workflow

1. **Data Preprocessing**

   * Missing value handling using `SimpleImputer`
   * Outlier capping with the **IQR method**
   * Label/One-Hot Encoding of categorical variables
   * Class balancing using undersampling / SMOTE

2. **Exploratory Data Analysis (EDA)**

   * Statistical summary
   * Visualizations (class balance, boxplots, histograms, correlation heatmap, etc.)

3. **Model Building**

   * Trained multiple models:

     * Logistic Regression
     * Random Forest
     * Gradient Boosting
     * Support Vector Machine
     * XGBoost

4. **Evaluation Metrics**

   * Accuracy, Precision, Recall, F1-score, ROC-AUC
   * ROC curve visualization
   * Model comparison table


### Technical Stack

* **Python**
* **Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib**
* **XGBoost (optional)**
* **Jupyter Notebook**


###  Files

| File                            | Description                                         |
| ------------------------------- | --------------------------------------------------- |
| `recipe+reviews+and+user+feedback+dataset.csv`  | Review feedback dataset                             |
| `Review dataset.ipynb` | Main notebook with EDA, model building & evaluation |
| `README.md`                     | Project overview                                    |

---

###  Key Insights

* The dataset required extensive preprocessing and balancing due to class imbalance.
* Tree-based models (Random Forest, Gradient Boosting, XGBoost) performed best.
* The workflow ensures full reproducibility and scalability for healthcare prediction use cases.

---
