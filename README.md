# ChatGPT-Review-Sentiment-Analyzer

# 1. Introduction 

AI-Powered Review Analyzer for ChatGPT Feedback is an intelligent sentiment analysis system designed to evaluate user feedback on a ChatGPT-based application. Using the power of Natural Language Processing (NLP), Machine Learning (ML), and Deep Learning (DL), this project classifies user reviews into Positive, Neutral, or Negative sentiments. By doing so, it provides actionable insights to enhance customer experience, refine product features, and optimize support and marketing strategies.

# 2. Purpose

The primary objective of this project is to analyze user reviews of a conversational AI application and extract meaningful insights regarding customer satisfaction. Through sentiment classification, we aim to:

- Understand user opinions

- Identify potential areas for improvement

- Monitor brand perception

- Drive product decisions using data

# 3. Tech Stack

- Languages: Python

- Libraries/Frameworks: Pandas, NLTK, Scikit-learn, Matplotlib, Seaborn, Plotly

- Models: Naive Bayes, Logistic Regression, Random Forest, LSTM, BERT

- Deployment: Streamlit, Flask, AWS (optional)

- Tools: Jupyter Notebook, GitHub**




# 4. Project Scope

This project focuses on analyzing customer reviews submitted for ChatGPT versions across different platforms (Web/Mobile). The sentiment classification model categorizes reviews, identifies major themes and concerns, and provides visual insights into user experience trends.



# 5. Features

- Clean and preprocess user review data

- Perform EDA to discover patterns and outliers

- Train and evaluate sentiment classification models

- Deploy web dashboard for interactive sentiment exploration

- Predict sentiment from new reviews

- Visualize sentiment by time, location, platform, and other factors



6. Dataset

- Source: ChatGPT Reviews Dataset (link: chatgpt_reviews)

- Fields:

- date: Review submission date

- title: Headline of the review

- review: Full review text

- rating: Numeric rating (1 to 5)

- username: Reviewer alias

- helpful_votes: Count of helpful votes

- review_length: Character length of the review

- platform: Web or Mobile

- language: Review language (e.g., 'en')

- location: Country of origin

- version: ChatGPT version

- verified_purchase: Indicates if the user is a paid subscriber


# 6. EDA Visualizations

We conducted Exploratory Data Analysis (EDA) to extract key insights from user reviews. A bar chart of review ratings (1–5 stars) revealed overall satisfaction, while a pie chart highlighted the most helpful reviews. Word clouds showcased frequent terms in both positive and negative feedback. Trends over time were visualized using a line chart, and location-based differences were analyzed through maps and bar charts. We compared sentiment across platforms (Web vs. Mobile), and between verified and non-verified users. A box plot showed the relationship between review length and rating, while a negative word cloud focused on 1-star reviews. Finally, we assessed ratings by ChatGPT version using bar charts. These visualizations guided our modeling and interpretation steps.























































# 7. Result:- 


<img width="1440" alt="Screenshot 2025-06-12 at 21 57 01" src="https://github.com/user-attachments/assets/ae6d255b-3001-4fba-8b3d-66896c408da8" />

<img width="1440" alt="Screenshot 2025-06-12 at 21 55 45" src="https://github.com/user-attachments/assets/7ae3d6f9-0964-41e6-92fa-ed392991f0b1" />

# Dashboard:
- Sentiment Distribution: Clear breakdown of sentiment categories

- Feature Importance: Key terms driving classification

- Model Metrics: Accuracy, precision, recall, F1-score, AUC-ROC

- Insights: Negative themes, satisfaction trends, improvement suggestions

 - Interactive visualization using Streamlit 
<img width="1440" alt="Screenshot 2025-06-12 at 21 57 31" src="https://github.com/user-attachments/assets/7e0a3fcb-72c9-4bd2-904e-46fd14cb0a3a" />
<img width="1440" alt="Screenshot 2025-06-12 at 21 57 52" src="https://github.com/user-attachments/assets/ec70403a-a249-4378-9297-6397db9ef7ab" />





# 8. Conclusion

AI-Powered Review Analyzer for ChatGPT Feedback delivers a powerful, data-driven perspective on user feedback, enabling smarter decisions in customer experience, marketing, and product design. With robust preprocessing, effective modeling, and actionable visualizations, this project showcases the impact of AI in sentiment-driven analytics.

# 9. Acknowledgments

- Special thanks to: The course instructors and mentors for guidance and project resources

- OpenAI and HuggingFace for pre-trained NLP models

- All reviewers whose data enabled this analysis



# Created By :- @2025 Prashant Kumar
