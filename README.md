# Student Dropout Prediction Using Machine Learning

This project aims to develop a **Machine Learning** model capable of predicting **student dropout** in higher education, enabling institutions to identify at-risk students and take preventive actions to reduce attrition.

Developed by **Nowa Analytics**, a consulting firm specialized in data-driven solutions for the education sector.


## Background

Student dropout is a major challenge for educational institutions at all levels. Many students abandon their courses, especially during the first few semesters. This has a significant impact on both the institution and the students themselves.

This project proposes the use of **data science** and **machine learning** techniques to **predict dropout before it happens**, enabling early intervention strategies.


## Project Stages

1. **Exploratory Data Analysis (EDA)**

   * Understanding student profiles
   * Detecting patterns, outliers, and correlations
   * Data visualization

2. **Data Preprocessing**

   * Handling missing values
   * Encoding categorical variables
   * Scaling and normalization

3. **Data Balancing**

   * Applying techniques such as **SMOTE** to address class imbalance (dropout vs. retention)

4. **Model Development**

   * Training classification models such as:

     * Random Forest
     * XGBoost
     * Logistic Regression
     * KNN
   * Using Scikit-learn's **Pipeline** and **GridSearchCV** for model validation and tuning

5. **Model Evaluation**

   * Metrics used:

     * Accuracy
     * Precision, Recall, F1-Score
     * Confusion Matrix
     * ROC Curve and AUC (when applicable)

6. **Interpretation of Results**

   * Feature importance analysis
   * Discussion of causes and actionable recommendations for reducing dropout rates


## 📁 Project Structure

```
📦 student-dropout-ml
│
├── data/                # Raw and processed datasets
├── notebooks/           # Jupyter Notebooks for EDA and modeling
├── src/                 # Python scripts
│   ├── preprocessing.py
│   ├── modeling.py
│   └── evaluation.py
├── results/             # Outputs, graphs, and reports
├── README.md            # This file
└── requirements.txt     # Project dependencies
```


## 📊 Technologies and Libraries

* Python 3.9+
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* XGBoost
* Imbalanced-learn (SMOTE)
* Jupyter Notebook


## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/yourusername/student-dropout-ml.git
cd student-dropout-ml
```

2. Install the dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebooks from the `notebooks/` folder or execute the scripts in `src/`.


## Results

The models demonstrated a strong ability to identify students at risk of dropping out, allowing the institution to:

* Take proactive measures
* Reduce student attrition
* Improve engagement and retention


## Key Insights

* Academic performance during the early semesters is a strong predictor of dropout.
* Age, course type, and study mode (e.g., on-campus vs. remote) are important factors.
* Balancing the dataset using **SMOTE** significantly improved model performance.


## About Nowa Analytics

**Nowa Analytics** is a boutique data consulting firm focused on providing advanced analytics and AI solutions to organizations in education, finance, and travel.

📍 Based in São Paulo, Madrid, and London
🌐 [nowaanalytics.com](http://nowaanalytics.com)

## 📬 Contact

For more information or tailored consulting services:

* 📧 [contact@nowaanalytics.com](mailto:contact@nowaanalytics.com)
* 💼 LinkedIn: [Nowa Analytics](https://linkedin.com/company/nowaanalytics)

