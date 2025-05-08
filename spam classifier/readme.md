**Project Title:** Spam or Ham? – Email Classifier Using the Enron Dataset

**Description:**
This project is a binary text classification task that identifies whether an email is **spam** (junk) or **ham** (non-spam). It uses machine learning techniques on the Enron email dataset (renamed to `data/`) and employs TF-IDF vectorization with a Naive Bayes classifier.

**Setup Instructions:**

1. **Create a virtual environment** (optional but recommended):

   ```bash
   python3 -m venv forageenv
   source forageenv/bin/activate  # On Windows: forageenv\\Scripts\\activate
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook:**

   ```bash
   jupyter notebook task3_complete_freshlook.ipynb
   ```

**Data Folder:**

```
data/
├── ham/
└── spam/
```

**Output:**
The notebook includes:

* Data preprocessing
* TF-IDF transformation
* Model training & prediction
* Evaluation (accuracy & confusion matrix)
* Visualizations using updated styles
