# IT Support Ticket Classification & Priority Automation

An end-to-end NLP (Natural Language Processing) pipeline designed to optimize and automate IT service desk workflows. This project automatically classifies incoming support tickets into specialized IT categories and applies rule-based priority tagging to critical requests.

## 🚀 Key Achievements
* **High Predictive Accuracy:** Reached an overall classification accuracy of **85.98%** using a multi-class machine learning approach.
* **Balanced Class Handling:** Implemented `class_weight='balanced'` to ensure smaller, critical support categories (like *Purchase* and *Storage*) are predicted accurately despite heavy data imbalance.
* **Automated Priority Assignment:** Built a clean text-splitting algorithm to analyze urgent keywords and automatically flag tickets as High, Medium, or Low priority without false substring matching.

## 🛠️ Tech Stack & Methods
* **Language:** Python (Jupyter Notebook)
* **Text Preprocessing:** Regular expressions (Regex) for text cleaning, tokenization, stop-word removal, and Lemmatization via `nltk`.
* **Feature Engineering:** TF-IDF Vectorization (`TfidfVectorizer` with n-grams and minimum document frequency tuning).
* **Machine Learning:** Multi-class Logistic Regression via `scikit-learn`.
* **Evaluation:** Confusion Matrix heatmaps (`seaborn`/`matplotlib`) and comprehensive Classification Reports (Precision, Recall, F1-Score).

## 📁 Repository Contents
* `support_ticket_classification.ipynb` - The full Jupyter Notebook containing data cleaning, model training, evaluation, and pipeline testing.
* `all_tickets_processed_improved_v3.csv` - The original IT support ticket dataset.
* `all_tickets_task2_final_submission.zip` - The final model predictions containing over 47,000 processed tickets with their predicted categories and priority levels.
<img width="926" height="693" alt="image" src="https://github.com/user-attachments/assets/09fc5604-b3b2-4ba6-afea-904bc94d2c80" />
