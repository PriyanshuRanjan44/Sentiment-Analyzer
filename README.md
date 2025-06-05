# 🧠 Sentiment Analysis on Twitter Data

This project applies Natural Language Processing (NLP) techniques to analyze and visualize public sentiment from Twitter using a labeled dataset. It aims to provide insights into the emotional tone behind tweets by classifying them as positive, negative, or neutral. This end-to-end pipeline includes data cleaning, feature engineering, exploratory data analysis (EDA), and meaningful data visualizations.

---

## 📌 Project Objectives

- Classify tweets based on sentiment (Positive, Negative, Neutral)
- Clean and preprocess raw tweet text using NLP techniques
- Extract features like tweet length, word count, and presence of hashtags/mentions
- Visualize trends and insights from the sentiment data
- Evaluate model performance through visual tools (confusion matrix, classification report)

---

## 📦 Dataset

- **Source**: [Twitter Entity Sentiment Analysis](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)
- **Format**: CSV with fields — ID, Entity, Sentiment, Tweet
- **Size**: ~7,000 labeled tweets

---

## 🧰 Tech Stack & Tools

| Category       | Tools / Libraries                          |
|----------------|---------------------------------------------|
| Language       | Python 3.x                                  |
| IDE            | Visual Studio Code (VS Code)                |
| Data Handling  | Pandas, NumPy                               |
| NLP            | NLTK                                        |
| Visualization  | Seaborn, Matplotlib, WordCloud, Plotly      |
| Environment    | Jupyter Notebook                            |
| Version Control| Git + GitHub                                |

---

## 🧪 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/PriyanshuRanjan44/Sentiment-Analyzer.git
   cd Sentiment-Analyzer
   ```

2. **Create and activate virtual environment**
   ```bash
   python -m venv venv
   venv\Scripts\activate  # For Windows
   ```

3. **Install the dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the notebooks**
   - Open `notebooks/01_data_preprocessing.ipynb` for data cleaning and feature engineering.
   - Then run `notebooks/02_eda_visualization.ipynb` for visualizations and analysis.

---

## 📊 Features & Engineering

- Removed null/missing tweets
- Cleaned text (lowercase, removed hashtags, mentions, URLs)
- Removed stopwords and punctuation using NLTK
- Engineered features:
  - `text_length`: number of characters
  - `word_count`: number of words
  - `has_mention`: whether `@` was used
  - `has_hashtag`: whether `#` was used

---

## 📈 Exploratory Data Analysis (EDA)

- **Sentiment Distribution**: Bar plots showing number of positive, negative, and neutral tweets
- **Text Length vs Sentiment**: Box plots highlighting differences in average tweet length
- **Word Clouds**: Show most common words per sentiment class
- **Interactive Plots**: Built using Plotly for interactive exploration

---

## 📉 Model Evaluation 

- **Confusion Matrix**: Visualize true vs predicted sentiment labels
- **Classification Report**: Precision, recall, and F1-score breakdown
- **ROC Curve**: Shows trade-off between true/false positive rates

---

## 📁 Project Structure

```
Sentiment-Analyzer/
├── data/
│   ├── twitter_training.csv
│   └── cleaned_data.csv
├── notebooks/
│   ├── 01_data_preprocessing.ipynb
│   └── 02_eda_visualization.ipynb
├── outputs/
│   └── visualizations/
├── requirements.txt
├── .gitignore
└── README.md
```

---

## ✅ Results & Insights

- **Negative tweets** tend to be longer and more expressive
- **Positive tweets** often contain promotional or cheerful words
- **Neutral tweets** are short and to-the-point
- **Hashtags** are more common in positive tweets
- Word clouds give a clear view of dominant emotional keywords

---

## 📌 Future Enhancements

- Add sentiment confidence scores
- Extend analysis to other platforms (e.g., Reddit, YouTube)
- Build a web app using Streamlit or Flask
- Include time-series analysis to show sentiment over time

---

## 🧠 Author

**Priyanshu Ranjan**  
Data Analytics Project | Galgotias University  
2027 Passout | 4th Semester
