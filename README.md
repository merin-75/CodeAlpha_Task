# CodeAlpha_Task:1
All tasks completed for Code Alpha Data Analyst Internship
## Task 2: Exploratory Data Analysis (EDA)

### ✅ Description:
Performed EDA on Titanic dataset to:
- Ask meaningful questions
- Explore structure, types, and missing values
- Identify patterns, trends, and anomalies
- Test hypotheses using visualization
- Detect potential data issues

### 📂 Files Included:
- `titanic_sample.csv` — sample dataset
- `titanic_EDA_CodeAlpha.ipynb` — Python code for full EDA

### 📊 Tools Used:
- Python
- Pandas
- Seaborn
- Matplotlib



# CodeAlpha_Task:2
📂 Task 1: Web Scraping – Spotify Charts

Overview: 
This project scrapes the Spotify Top Charts to collect song rankings, artist names, and stream counts.

Reasoning / Approach:  
1. Identify Data Source:* Spotify Charts webpage was chosen because it provides publicly visible top songs data.  
2. Select Tools:
   - Requests: To fetch HTML content.  
   - BeautifulSoup: To parse and extract song details.  
   - Pandas: To store the data in a structured DataFrame.  
3. Data Extraction: Located HTML elements for rank, song, artist, and streams by inspecting the webpage source.  
4. Data Storage: Exported the data to spotify_charts.csv for further analysis.  
5. Verification: Printed sample data to confirm correctness before saving.

Technologies Used:
- Python  
- Requests  
- BeautifulSoup  
- Pandas  

# CodeAlpha_Task:3
Task 4: Sentimental Analysis 

This project performs **Sentiment Analysis** on customer reviews using Natural Language Processing (NLP) techniques. The goal is to classify text into **Positive**, **Negative**, or **Neutral** sentiments and extract public opinion patterns that can be used for decision-making in marketing, product development, or user engagement.

---

## 📌 Project Objectives

- Classify text data as **positive**, **negative**, or **neutral**
- Use NLP tools like **TextBlob** and **VADER Sentiment Analyzer**
- Apply sentiment analysis to real-world reviews (Amazon, social media, or news)
- Understand **public sentiment patterns** from the dataset
- Generate insights for product, marketing, or social research

---

## 🛠️ Tools & Technologies Used

- **Python**
- **Google Colab**
- **TextBlob** – for polarity-based sentiment classification
- **VADER (NLTK)** – for rule-based sentiment scoring
- **Pandas** – for data manipulation
- **Matplotlib** – for sentiment distribution visualization

---

## 📂 Dataset

A sample dataset of customer reviews was used. It can be replaced with real datasets from:
- [Kaggle - Amazon Product Reviews](https://www.kaggle.com/datasets/datafiniti/consumer-reviews-of-amazon-products)
- Twitter API data
- News headlines/comments

### Sample Reviews Used:
```text
"I love this product, it's fantastic!"
"Terrible experience. Would not recommend."
"It's okay, not bad but not great either."
"Absolutely amazing! Highly recommend it."
"Worst purchase I've ever made."

