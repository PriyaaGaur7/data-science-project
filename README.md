# 📊 Data Science & AI Mini Projects  
This repository contains three beginner-friendly Data Science and AI projects completed using Python, Pandas, NumPy, Scikit-Learn, and NLP techniques.  
All projects were developed and executed in Google Colab.

---

## 📁 Project List

### 1️⃣ Netflix Data Analysis (EDA + Visualization)
**Notebook:** `netflix_analysis.ipynb`  
- Performed exploratory data analysis on 8,000+ Netflix titles  
- Cleaned missing values, processed categorical columns  
- Analyzed:
  - Movies vs TV Shows distribution
  - Top countries with maximum content
  - Top genres
  - Year-wise content release trend  
- Visualized insights using bar charts and histograms  

**Dataset:**  
🔗 https://www.kaggle.com/datasets/shivamb/netflix-shows

---

### 2️⃣ Student Score Prediction (Machine Learning)
**Notebook:** `student_score_prediction.ipynb`  
- Analyzed student performance dataset  
- Identified correlation between study factors and exam scores  
- Implemented Linear Regression using Scikit-Learn  
- Evaluated model using:
  - R² Score
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)  
- Plotted regression line and predictions  

**Dataset:**  
🔗 https://www.kaggle.com/datasets/spscientist/students-performance-in-exams

---

### 3️⃣ Fake Job Posting Detection (NLP + Classification)
**Notebook:** `fake_job_posting_detection.ipynb`  
- Built an NLP-based text classifier to detect fraudulent job postings  
- Performed text cleaning:
  - Lowercasing
  - Stopword removal
  - Lemmatization  
- Converted text to TF-IDF vectors  
- Trained Logistic Regression classifier  
- Evaluated using:
  - Accuracy
  - F1 Score
  - Confusion Matrix  

**Dataset:**  
🔗 https://www.kaggle.com/datasets/shivkumarganesh/fake-job-postings

---

## 🚀 How to Run the Notebooks

1. Open **Google Colab**  
2. Upload the notebook (`.ipynb`)  
3. Download the dataset from the provided Kaggle links  
4. Upload the CSV inside Colab:
   ```python
   from google.colab import files
   files.upload()
