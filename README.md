# 📰 Fake News Detection  

This project builds a **Machine Learning model** to classify news articles as **Fake** or **Real** using Natural Language Processing (NLP).  

---

## 📂 Dataset  
We used the [Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset) from Kaggle.  
It contains two files:  
- `Fake.csv` → Fake news articles  
- `True.csv` → Real news articles  

---

## ⚙️ Requirements  
Install dependencies before running the notebook:  

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

pip install -r requirements.txt

🚀 How to Run

1.Clone this repository:
git clone https://github.com/<your-username>/Fake-News-Detection.git
cd Fake-News-Detection

2.Download the dataset from Kaggle and place Fake.csv and True.csv inside the project folder.

3.Open Jupyter Notebook:
jupyter notebook FakeNewsDetection.ipynb

4.Run all cells to train and test the fake news classifier.


📊 Workflow
Load dataset (Fake.csv, True.csv)
Data cleaning & preprocessing
Feature extraction (Bag of Words / TF-IDF)
Train ML models (Logistic Regression, Naive Bayes, Random Forest, etc.)
Evaluate model performance

🙌 Credits
Dataset: Kaggle - Fake and Real News Dataset
References: Open-source fake news detection notebooks
