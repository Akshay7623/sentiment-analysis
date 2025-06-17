# 📘 Sentiment Analysis using Traditional Machine Learning

This notebook demonstrates a traditional machine learning pipeline for sentiment analysis using multiple datasets sourced from Reddit and Twitter. The workflow includes data collection, cleaning, preprocessing, visualization, modeling, and evaluation.

---

## 1. 📥 Data Collection and Data Cleaning

### Datasets Used:
- Reddit comments dataset  
- Multiple Twitter datasets (from five different sources)  
- **Total Rows**: Over **3.8 million** combined entries

### Initial Steps:
- Import required libraries: `NumPy`, `pandas`, `scikit-learn`, `matplotlib`, `seaborn`, `re`
- Load datasets from CSV files hosted online

---

## 2. 🧹 Cleaning Each Dataset

### Reddit Data:
- Cleaned for text normalization and label consistency

### Twitter Data:
- Each dataset is cleaned individually
- Handle missing values and normalize text
- Ensure consistent sentiment labels

### General Cleaning Tasks:
- Remove duplicates and irrelevant entries  
- Normalize text (lowercasing, removing special characters)  
- Tokenization and lemmatization for further processing

---

## 3. 📊 Data Visualization

Visualizations created using `matplotlib` and `seaborn` to understand:
- Sentiment class distribution  
- Text length and other characteristics

---

## 4. ⚙️ Data Preprocessing

- **Tokenization**: Split sentences into words  
- **Lemmatization**: Reduce words to base forms  
- **Feature Engineering**: Prepare text features for ML models

---

## 5. 🤖 Model Training

### Algorithms Used:
- **Logistic Regression**
- **Linear Support Vector Classifier (LinearSVC)**

### Training Steps:
- Split cleaned data into training and test sets  
- Train models using `scikit-learn`  
- Tune hyperparameters as needed

---

## 6. 🧽 Data Filtering / Pruning

- Purpose: Improve model performance  
- Remove noisy or irrelevant data using prebuilt models for filtering

---

## 7. 🧪 Final Model Training and Evaluation

- Retrain models on cleaned and pruned datasets  
- Evaluate using:
  - **Accuracy score**
  - **Classification report**
  - **Confusion matrix**

---

## 8. ✅ Finalizing the Model

- Best-performing model is selected based on evaluation metrics  
- Finalized model is ready for:
  - Deployment  
  - Further analysis or integration


## 📋 Summary Table

| Step              | Description                                       |
|-------------------|---------------------------------------------------|
| Data Collection   | Load Reddit and Twitter datasets                  |
| Data Cleaning     | Normalize, tokenize, lemmatize, and filter data   |
| Visualization     | Use matplotlib/seaborn for data exploration       |
| Preprocessing     | Prepare features for ML models                    |
| Model Training    | Train Logistic Regression and LinearSVC models    |
| Data Pruning      | Filter data to improve model accuracy             |
| Final Evaluation  | Assess models using standard metrics              |
| Model Finalization| Select and save the best model                    |
