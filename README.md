# PRODIGY_DS_04 

- Sentiment Analysis on Twitter Data

## 🔍 Overview
This project is part of my Data Science internship with **Prodigy Infotech**. The goal of this task is to analyze and visualize **sentiment patterns in social media (Twitter) data** to understand public opinion and attitudes towards specific topics or brands.

## 📁 Dataset
- The dataset is sourced from **Kaggle** and consists of two CSV files: `twitter_training.csv` and `twitter_validation.csv`.
- Each record contains:
  - `ID`: Unique identifier
  - `Topic`: The subject or brand mentioned (e.g., Amazon, Google, etc.)
  - `Sentiment`: The expressed sentiment (`Positive`, `Negative`, `Neutral`, or `Irrelevant`)
  - `Tweet`: The tweet text

## 🎯 Objective
To perform **Sentiment Analysis** and identify:
- Which **topics/brands** are discussed most frequently
- The **dominant sentiment** for each topic
- General **public opinion trends** on Twitter for various entities

## 🧠 Steps Involved
1. **Data Cleaning:**
   - Removed duplicates
   - Checked for null values
2. **Exploratory Data Analysis (EDA):**
   - Counted total sentiments
   - Counted topics and their frequencies
3. **Visualization:**
   - Stacked bar charts to compare sentiments across topics
   - Highlighted which brand has the highest positive, negative, or neutral sentiment
4. **Insights:**
   - **Assassin’s Creed** has the highest **positive** sentiment
   - **Amazon** has the highest **neutral** sentiment
   - **MaddenNFL** has the highest **negative** sentiment

## 📊 Final Visualization
A grouped bar chart showing the **top sentiment-topic pairs**, summarizing public emotion linked to each brand.

## 🛠️ Tech Stack
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- GitHub

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/YugalSoni/PRODIGY_DS_04.git

---

## Install the required libraries
pip install pandas matplotlib seaborn

---

## 🙌 Acknowledgement

Thanks to Prodigy Infotech for providing this opportunity.
Dataset credit: Kaggle - Twitter Sentiment Dataset

