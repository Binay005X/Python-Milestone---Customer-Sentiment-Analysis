# Python-Milestone - Customer-Sentiment-Analysis
This project focuses on analyzing customer reviews using TextBlob for sentiment analysis and Pandas, Matplotlib, and Seaborn for data exploration and visualization. The goal is to understand overall customer sentiment, its relationship with ratings, and patterns in review behavior.

# ⚙️ Tools & Technologies

- Python

- TextBlob (Sentiment Analysis)

- Pandas (Data Wrangling & Analysis)

- Matplotlib & Seaborn (Data Visualization)

- WordCloud (Text Visualization)

# 🚀 Project Workflow

1. Sentiment Analysis

- Applied TextBlob on review text to generate:

- Polarity score (range: 0 → negative to +1 → positive)

- Subjectivity score (range: 0 → objective to 1 → subjective)

- Defined thresholds to classify sentiment:

- Positive: Polarity ≥ 0.6

- Neutral: Polarity < 0.4

- Mixed: Between 0.4 and 0.6

- Stored the sentiment classification for each review in the dataset.

## 2. Data Analysis & Insights

Performed exploratory analysis to derive meaningful insights:

- Sentiment Distribution

- Correlation between Ratings & Sentiment

- Word Cloud of Positive & Negative Reviews

- Review Length Analysis

# 📈 Key Insights

1. Sentiment Distribution

- The average polarity is ~0.52, suggesting an overall positive sentiment.

- Majority of reviews fall under the positive category, as visualized in the sentiment bar chart.

<img width="597" height="447" alt="Screenshot 2025-08-16 232834" src="https://github.com/user-attachments/assets/01da94d7-c3f0-43fc-98d0-62eaacaf8b06" />

2. Ratings vs Sentiment

- Reviews with higher ratings (4-5 stars) show higher polarity scores.

- Confirms that positive sentiment strongly aligns with high ratings.

<img width="610" height="454" alt="Screenshot 2025-08-16 233017" src="https://github.com/user-attachments/assets/c687b805-2d3a-444a-a2fe-ad83b166d1a1" />


3. Review Length vs Sentiment

- Correlation between review length and polarity is -0.35.

- Longer reviews tend to be more neutral or balanced rather than extremely positive/negative.

- Graphical analysis shows polarity remains consistent regardless of review length.

<img width="613" height="465" alt="Screenshot 2025-08-16 233336" src="https://github.com/user-attachments/assets/a3e909aa-5a72-48c3-9a62-d111a7e7fbe6" />


4. Word Cloud Analysis

- Positive reviews frequently mention words such as quality, product, value, love.

- Neutral/Mixed reviews often include words related to delivery, size, issue, suggesting areas of improvement.

<img width="1101" height="297" alt="Screenshot 2025-08-16 233112" src="https://github.com/user-attachments/assets/9d5dc947-251f-4dbc-8360-02bc05a9571d" />


# 📊 Visualizations

- Sentiment Distribution Bar Chart

- Ratings vs Polarity Scatter Plot

- Review Length vs Sentiment Graph

- Word Clouds for Positive & Neutral/Mixed Reviews
  

# ✅ Conclusion

- Customers have a generally positive perception of the product.

- Higher ratings strongly correlate with higher sentiment polarity.

- Neutral/mixed reviews, though fewer, provide valuable feedback for product and service improvement.

- Longer reviews tend to be more balanced, indicating customers provide detailed insights without extreme sentiment.
