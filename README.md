# Twitter Sentiment Analysis

This project focuses on analyzing and visualizing sentiment patterns in social media data (Twitter) to understand public opinion and attitudes toward specific topics or brands.

## 📁 Dataset

**Dataset Used:** `twitter_training.csv`  
- Each record contains a tweet, associated topic (entity), and sentiment.  
- Sentiment Labels: `Positive`, `Negative`, `Neutral`, `Irrelevant`  
- Source: Provided by Prodigy InfoTech for internship project tasks.

## 🎯 Objective

To perform **exploratory data analysis (EDA)** and generate **visual insights** about sentiment trends across different entities and topics.

## 🔧 Technologies Used

- **Python**
- **Pandas** – Data manipulation
- **Matplotlib / Seaborn** – Data visualization
- **WordCloud** – Generating topic and corpus clouds
- **Jupyter Notebook** – Interactive environment for analysis

## 📊 Key Analyses Performed

- Data cleaning (null & duplicates)
- Topic frequency distribution
- Overall sentiment distribution
- Topic-wise sentiment analysis
- Top 5 topics with most Negative, Positive, Neutral & Irrelevant sentiments
- Specific analysis of entities like **Google** and **Microsoft**
- Message length distribution (overall & by sentiment)
- Heatmap of topics vs sentiment
- WordClouds of topics and tweet text corpus

## 📈 Sample Visualizations

- Bar chart: Count of tweets per topic
- Pie chart: Sentiment proportions
- Boxplot: Message length by sentiment
- Heatmap: Topic vs Sentiment density
- WordCloud: Most mentioned topics & words

## 🧠 Insights (Summary)

- **Most Frequent Topic**: `TomClancyRainbowSix`
- **Dominant Sentiment**: `Negative`
- **Balanced Neutrality**: Topics like `Google` and `Microsoft` show more neutral sentiment.
- **Message Length**: Most tweets are short (under 400 characters), aligning with platform limits.
