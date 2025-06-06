# 📩 SMS Spam Detection using Machine Learning
This project focuses on building a classification model to detect spam SMS messages using natural language processing (NLP) techniques and machine learning algorithms. It serves as a practical demonstration of text preprocessing, feature extraction, model training, and evaluation in Python.
##  Tools & Technologies
**Programming Language**: Python  
**Libraries**:
  - Pandas, NumPy – Data manipulation
  - Scikit-learn – Machine learning and evaluation
  - NLTK – Text preprocessing
  - Matplotlib, Seaborn – Data visualization
**Notebook**: Jupyter Notebook
## 🔄 Workflow
1. **Data Loading & Cleaning**
   - Loaded SMS data and handled nulls
   - Renamed columns for clarity
2. **Text Preprocessing**
   - Lowercasing
   - Removing punctuation & stopwords
   - Tokenization and stemming
3. **Feature Extraction**
   - Converted text into numeric features using **TF-IDF Vectorization**
4. **Model Building**
   - Trained classifiers: **Naive Bayes**, **Logistic Regression**, etc.
   - Split dataset into training and testing sets
5. **Model Evaluation**
   - Evaluated models using:
     - Accuracy
     - Confusion Matrix
     - Precision, Recall, F1-Score
## ✅ Results
- Achieved high accuracy (typically >95%) using Multinomial Naive Bayes
- Effective handling of class imbalance and text features
- Demonstrated real-world applicability for detecting spam in communication platforms
