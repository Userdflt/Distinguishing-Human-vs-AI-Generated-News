# **Mini Project 3 - Distinguishing Human vs AI-Generated News**

## Contents

1. **Data Preprocessing**
    - Loading and combining datasets
    - Text data preprocessing steps
    - [View detailed notebook](./FakeNews_Data_Pre-Processing.ipynb)

2. **Data Analysis**
    - Cleaning the text and title
    - Extracting features from text and titles
    - [View detailed notebook](./FakeNews_EDA_Feature_Eng.ipynb)

3. **ML Modelling**
    - Problem Definition
    - Feature Engineering
    - Model Selection and Implementation
    - Evaluation and Results
    - [View detailed notebook](./FakeNews_Classification_Model.ipynb)

---

# **FakeNews Data Pre-Processing**

### Datasets:

- **True.csv:** Contains true news articles.
- **Fake.csv:** Contains fake news articles.

### Preprocessing Steps:

- **Loading Data:** Combine `True.csv` and `Fake.csv` into a single DataFrame with a target variable indicating whether the news is true or fake.
- **Tokenization:** Splitting text into individual words or tokens.
- **Removing Stop Words:** Removing common words that do not contribute to the meaning (e.g., "and", "the").
- **Stemming/Lemmatization:** Reducing words to their base or root form.

- [View detailed notebook](./FakeNews_Data_Pre-Processing.ipynb)

---

# **FakeNews EDA and Feature Engineering**

### Data Cleaning:

- **Text and Title Cleaning:**
    - Apply text preprocessing steps like tokenization, stop word removal, and lemmatization to clean the text and title.

### Feature Extraction:

- **Feature Engineering:**
    - Extract various features such as word count, character count, word density, etc., from the cleaned text and title.

### Data Analysis:

- **EDA (Exploratory Data Analysis):**
    - Distribution analysis of text and title features.
    - Sentiment analysis of the text and titles using TextBlob and VADER.

### Statistical Testing:

- **Normality Tests:**
    - Apply Shapiro-Wilk test to check for normality.
- **Mann-Whitney U Test:**
    - Conduct hypothesis testing to compare the sentiment distributions between AI-generated and human-written articles.

- [View detailed notebook](./FakeNews_EDA_Feature_Eng.ipynb)

---

# **FakeNews Classification Model**

### Problem Definition:

- **Objective:**
    - Build a predictive model to classify news articles as either "Fake" or "True" using Natural Language Processing (NLP) techniques.

### Feature Engineering:

- **TF-IDF Vectorization:**
    - Convert text and title into numerical features using TF-IDF vectorization.

### Model Selection:

- **Models Implemented:**
    - Logistic Regression, SVM, and Random Forest classifiers.
    - Evaluate the models on accuracy, precision, recall, F1 score, and ROC AUC.

### Evaluation and Results:

- **Model Evaluation:**
    - Detailed evaluation of models using confusion matrices, ROC curves, and classification reports.

- [View detailed notebook](./FakeNews_Classification_Model.ipynb)

---

*For further details, please refer to the following notebooks:*
- [FakeNews Data Pre-Processing](./FakeNews_Data_Pre-Processing.ipynb)
- [FakeNews EDA and Feature Engineering](./FakeNews_EDA_Feature_Eng.ipynb)
- [FakeNews Classification Model](./FakeNews_Classification_Model.ipynb)

---
