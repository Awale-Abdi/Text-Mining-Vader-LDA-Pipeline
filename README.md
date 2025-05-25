<h1 align="center">COVID-19 Twitter Sentiment & Topic Modeling: NLP-Driven Social Media Campaign Analysis</h1>

## 📊 Overview
This solo-developed NLP and machine learning project transforms raw Twitter data into actionable business intelligence. Originally part of a graduate-level **Social Media Analytics** course, I independently built the entire data pipeline; handling data cleaning, sentiment analysis, topic modeling, and visualization. I then walked my MBA teammates through the project’s structure and insights. This allowed them to focus on creating our PowerPoint and final presentation video, where they demonstrated a solid grasp of the technical concepts and contributed insights.

By clearly communicating complex methods and findings, I enabled the team to confidently deliver a polished final presentation and recorded video submission.

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
  - NLP (vectorization, sentiment analysis, topic modeling),
  - Data visualization (matplotlib, seaborn, wordcloud),
  - Communication of technical results to non-technical stakeholders.
- Developed in **Visual Studio Code** using **Jupyter Notebook**, ensuring reproducibility and clean modular code.
- **Trained and briefed MBA teammates** on the full analytical workflow and findings, enabling them to confidently present the project via **PowerPoint and recorded video**.
- Delivered all components—including code, analysis, training, and presentation assets—**within a tight deadline of just 2 days**.

## 📁 Project Structure

- `Datasets/`  
  - `COVID-19 Twitter Data.zip` – compressed archive containing the raw tweet datasets used for all analysis:  
    - `Covid-19 Twitter Dataset (Apr-Jun 2020).csv` – tweets collected between April–June 2020  
    - `Covid-19 Twitter Dataset (Apr-Jun 2021).csv` – tweets collected between August–October 2020  
    - `Covid-19 Twitter Dataset (Aug-Sep 2020).csv` – tweets collected between April–June 2021  

- `Outputs/`  
  - `Social Media Analytics - Team 5 Code by Awale Abdi.ipynb` – solo-coded Jupyter Notebook covering full data pipeline: cleaning, sentiment analysis, topic modeling, and visualization  
  - `Social Media Analytics - Team 5 Presentation.pptx` – final slide deck used for the class presentation  

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
