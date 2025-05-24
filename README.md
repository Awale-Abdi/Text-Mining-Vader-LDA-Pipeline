<h1 align="center">COVID-19 Twitter Sentiment & Topic Modeling: NLP-Driven Social Media Campaign Analysis</h1>

## 📊 Overview
This solo project uses Natural Language Processing (NLP) and machine learning techniques to extract actionable insights from a COVID-19 Twitter dataset. Though originally a group assignment in a **Social Media Analytics** course, I independently completed all Python coding, text preprocessing, sentiment scoring, and topic modeling tasks. The final deliverables include a strategic analysis of public sentiment and engagement trends, visualized in Python and structured for real-world application in digital marketing and public health communication.

The dataset analyzed contains over 226,000 COVID-related tweets scraped during the pandemic. I applied advanced **text mining** and **NLP workflows** to generate insights that can improve future public service messaging on social platforms like Twitter (X), Facebook, and Instagram.

## 📌 Key Business Questions Answered
- **What was the public sentiment during the early COVID-19 pandemic?**
- **Which themes and topics dominated online discourse?**
- **What content types or keywords increased engagement?**
- **How can organizations optimize their future digital campaigns based on these insights?**

## 🧠 Tools & Technologies Used
- **Languages**: Python (Jupyter Notebook via Visual Studio Code)
- **Libraries**:
  - **NLP & Text Mining**: `nltk`, `gensim`, `re`, `string`, `sklearn`
  - **Vectorization**: `TfidfVectorizer`, `CountVectorizer`
  - **Sentiment Analysis**: `VADER` from `nltk.sentiment.vader`
  - **Topic Modeling**: `Latent Dirichlet Allocation (LDA)` via `gensim`
  - **Visualization**: `matplotlib`, `seaborn`, `wordcloud`, `squarify`
  - **Data Handling**: `pandas`, `numpy`

## 🔍 Methodology

### 1. **Data Import & Preprocessing**
- Cleaned raw CSV data (tweets, usernames, hashtags, engagement metrics).
- Tokenized text, removed stopwords, punctuation, emojis, URLs, and special characters.
- Normalized case and applied **lemmatization** for better topic coherence.

### 2. **Exploratory Data Analysis (EDA)**
- Visualized tweet volume, language distribution, top hashtags, and user behavior patterns.
- Detected spikes in engagement and their correlation with major world events.

### 3. **Sentiment Analysis**
- Applied VADER sentiment scoring to classify tweets into **positive**, **neutral**, and **negative**.
- Generated sentiment distribution charts and retweet/like patterns by sentiment class.

### 4. **Topic Modeling**
- Applied **LDA (Latent Dirichlet Allocation)** to identify dominant conversation topics.
- Visualized results with **WordClouds**, bar plots, and squarify treemaps.

### 5. **Recommendations**
- Proposed improvements for **public sector social media strategy** based on sentiment-topic overlap and engagement triggers.

## ⚙️ Project Highlights
- **Sole analyst and coder** on a project meant for group collaboration.
- Built an end-to-end **NLP pipeline** from data ingestion to model interpretation.
- Demonstrated **cross-functional data science capabilities** including:
  - Data engineering (cleaning & ETL),
  - NLP (vectorization, topic modeling),
  - Data visualization (matplotlib, seaborn, wordcloud),
  - Communication of technical results to non-technical stakeholders.
- Developed in **Visual Studio Code** using **Jupyter Notebook**, ensuring reproducibility and clean modular code.

## 📁 Project Structure


## 📈 Key Insights

- **Sentiment Breakdown**:
  - Negative: ~53%
  - Neutral: ~39%
  - Positive: ~8%
  - *Conclusion:* Fear, frustration, and uncertainty dominated online discourse.

- **Top Topics (LDA)**:
  - Government action and policy debates
  - Lockdown and quarantine stress
  - Vaccine discussions and conspiracy theories
  - Economic anxiety and job loss
  - Health advice and symptoms

- **Engagement Insights**:
  - Tweets with **negative or controversial content** had higher retweet rates.
  - **Neutral sentiment tweets** received more replies than likes.
  - Engagement spikes corresponded to global COVID policy shifts.

## 🧩 Challenges & Solutions

| Challenge | Solution |
|----------|----------|
| No labeled demographics | Focused on content-based insights instead |
| Noisy social media text | Used regex and NLP libraries to normalize and clean |
| Topic overlap in LDA | Tuned hyperparameters and vectorizers for optimal topic coherence |
| Visualizing results for non-technical users | Used intuitive graphics (bar charts, word clouds, treemaps) |

## 🔗 Dataset Source
- Kaggle: [COVID-19 Twitter Dataset (by Arunava Chakraborty)](https://www.kaggle.com/datasets/arunavakrchakraborty/covid19-twitter-dataset)

---

## 📢 Contact Me

If you're interested in collaborating, have questions, or want to discuss similar NLP projects:

- 📧 Email: [Awaleiabdi@outlook.com](mailto:Awaleiabdi@outlook.com)  
- 💼 LinkedIn: [linkedin.com/in/awale-abdi](https://www.linkedin.com/in/awale-abdi/)  
- 💻 GitHub Portfolio: [github.com/yourusername](https://github.com/yourusername)  

---

_**Keywords for SEO**: Python NLP Project, Sentiment Analysis, Topic Modeling, COVID-19 Twitter Analytics, Data Science Portfolio, Social Media Campaign Strategy, Text Mining, Jupyter Notebook, GitHub NLP Projects, LDA Topic Modeling, VADER Sentiment, Twitter Data Analysis_
