# Python_Sentiment_Analysis
# Sentiment Analysis of Netflix Reviews

This project aims to analyze the sentiments expressed in Netflix app reviews using advanced Natural Language Processing (NLP) tools such as NLTK, VADER, and TextBlob. An in-depth analysis of user reviews has been conducted to identify key emotions (positive, negative, and neutral) and gain valuable insights into users' experiences with the app.

We use the dataset extracted from the following repository: https://www.kaggle.com/code/darrylljk/netflix-reviews-with-nlp/input.

## Objective
To understand how Netflix users perceive the app, identifying not only positive and negative aspects but also the emotional intensity and subjectivity of their comments. This analysis provides valuable information that can be used to improve the user experience and guide product development decisions.

## Methodology
1. **Data Preparation**  
   - Load and clean review data, addressing missing values and ensuring data consistency.

2. **Sentiment Analysis**  
   - Use **VADER** and **NLTK** to analyze the polarity of comments:
     - Tokenization
     - Part-of-speech tagging
     - Named entity recognition
   - Calculate sentiment scores (positive, negative, and neutral) and visualize sentiment distributions through bar charts.

3. **Frequent Bigrams Analysis**  
   - Analyze the most frequent bigrams in negative reviews to uncover common patterns in user criticisms.

4. **Detailed Sentiment Analysis**  
   - Use **TextBlob** to compute polarity and subjectivity scores for each review.
   - Combine these metrics with review ratings to analyze both overall sentiment and the emotional intensity and subjectivity of comments.

5. **Visualization**  
   - Visualize the results of sentiment analysis (positive, neutral, negative) to explore how sentiments vary according to review ratings.

## Results
- The results from VADER and TextBlob are integrated into a single DataFrame, where sentiment scores are displayed alongside the original reviews.
- Detailed analysis of how review ratings correlate with detected sentiments, providing a comprehensive view of user perceptions.
- Specific focus on negative reviews to identify the most critical aspects of the app based on user feedback.

## Applications
- Provides insights for improving the user experience of the Netflix app.
- Supports decision-making in product development by highlighting areas for improvement based on user sentiment.
