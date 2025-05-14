# 🎯 Social Media Sentiment Analysis (FIFA Tweets)

This project analyzes public sentiment around FIFA using real-world Twitter data.  
It uses NLP techniques to classify tweets as Positive, Negative, or Neutral, and provides visual insights into public opinion.

---

## 📊 Project Overview

- **Goal**: Understand public sentiment towards "FIFA"
- **Dataset**: Twitter training data (filtered to FIFA-related tweets)
- **Techniques**: Data cleaning, NLP (VADER), stopword removal, sentiment scoring
- **Tools**: Python, Pandas, NLTK, Matplotlib, Seaborn, WordCloud

---

## 🛠️ Steps Performed

1. **Data Import & Filtering**
   - Loaded full dataset and filtered it to include only tweets related to FIFA

2. **Data Cleaning**
   - Dropped irrelevant columns (`Sentiment`)
   - Removed nulls and duplicates
   - Cleaned tweet text: lowercasing, removing links, punctuation, mentions, etc.

3. **Text Preprocessing**
   - Removed stopwords using NLTK
   - Generated filtered text column

4. **Sentiment Analysis**
   - Used `VADER` sentiment analyzer to score tweets
   - Classified tweets into: `Positive`, `Negative`, and `Neutral`

5. **Visualizations**
   - Bar chart and pie chart of sentiment distribution
   - Word clouds for most frequent words in positive and negative tweets

6. **Exported Cleaned Data**
   - Saved final DataFrame to CSV for further use or dashboarding

---

## 🧰 Tech Stack

- Python (Pandas, Numpy)
- NLP: NLTK, VADER
- Visualization: Matplotlib, Seaborn, WordCloud
- Environment: Jupyter Notebook

---

## 📂 Files

- `Social Media Sentiment Analysis.ipynb`: Full analysis notebook
- `Cleaned_Tweets.csv`: Final dataset with sentiment scores 
- `Visualizatins Screnshots

---


## 📌 Notes

This is part of a personal portfolio project and was also submitted as a task for a training program at Brainwave Matrix Solutions.
