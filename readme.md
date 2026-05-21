# EduPredict: Academic Success Prediction Using Machine Learning

## Alternative Project Names
1. **EduPredict** *(Recommended)*
2. Student Success Analytics
3. Smart Academic Outcome Predictor
4. Campus Insight ML
5. Academic Performance Intelligence System
6. Student Retention Predictor
7. FuturePath ML
8. Academic Outcome Classification System

---

# EduPredict
### Academic Success Prediction Using Machine Learning

## Project Overview
EduPredict is a machine learning project designed to predict student academic outcomes based on demographic, academic, and socioeconomic factors. The project classifies students into one of three categories:

- **Dropout**
- **Enrolled**
- **Graduate**

The main goal of this project is to help educational institutions identify at-risk students early and improve student retention and academic success.

---

## Problem Statement
Educational institutions often struggle to identify students who may drop out before it is too late. By analyzing student-related data using machine learning techniques, this project aims to:

- Predict academic outcomes accurately
- Discover factors influencing student performance
- Support data-driven educational decisions
- Reduce dropout rates

---

## Dataset Information
The dataset contains:

- Demographic information
- Academic records
- Socioeconomic features
- Student performance indicators

### Target Variable
`Target`

Possible values:
- Dropout
- Enrolled
- Graduate

---

## Project Workflow

### 1. Data Collection
- Imported dataset using Pandas
- Loaded CSV dataset from Google Drive

### 2. Data Preprocessing
- Cleaned column names
- Removed missing values
- Dropped unnamed/empty columns
- Encoded categorical variables using One-Hot Encoding

### 3. Exploratory Data Analysis (EDA)
- Checked target distribution
- Correlation analysis
- Heatmap visualization
- Class imbalance analysis
- Feature type analysis

### 4. Feature Engineering
- Converted categorical features into numerical format
- Selected important features

### 5. Model Building
Machine learning classification models were applied to predict academic outcomes.

Possible models include:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

### 6. Model Evaluation
Evaluation metrics:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-learn | Machine Learning |
| Google Colab | Development Environment |

---

## Project Structure

```bash
EduPredict/
│
├── Academic_Success_Ml_project.ipynb
├── academic_success_dataset.csv
├── README.md
└── requirements.txt
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/EduPredict.git
cd EduPredict
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Usage

Run the Jupyter Notebook:

```bash
jupyter notebook Academic_Success_Ml_project.ipynb
```

Or open directly in Google Colab.

---

## Sample Visualizations
The project includes:

- Correlation Heatmaps
- Class Distribution Charts
- Feature Analysis Graphs
- Model Performance Metrics

---

## Future Improvements
- Hyperparameter tuning
- Deep learning implementation
- Real-time student monitoring dashboard
- Deployment using Flask or Streamlit
- Feature importance interpretation

---

## Expected Impact
This project can help:

- Universities improve retention rates
- Teachers identify struggling students
- Students receive early support
- Educational systems make smarter decisions

---

## Author
Developed as part of an academic machine learning project.

---

## License
This project is for educational and research purposes.

