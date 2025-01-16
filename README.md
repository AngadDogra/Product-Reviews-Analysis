# Sentiment and Review Analysis with Multi-Modal Feature Engineering

## Project Overview

This project involves analyzing product reviews using a combination of text processing and metadata to predict product ratings and extract key insights. The analysis is performed through sentiment analysis, topic modeling, and key phrase extraction, leveraging both **textual data** (from reviews) and **numerical data** (from metadata such as ratings and helpfulness scores).

## Key Features

- **Text Preprocessing**: Cleaned and preprocessed review text by removing special characters, URLs, and normalizing the text.
- **Sentiment Analysis**: Used a pre-trained sentiment model to generate sentiment labels and sentiment scores for each review.
- **Topic Modeling**: Applied the BERTopic model to identify and extract relevant topics from the review text.
- **Key Phrase Extraction**: Extracted key phrases (noun chunks) using spaCy to capture important themes in the reviews.
- **Data Integration**: Combined textual features (sentiment, topics, key phrases) with numerical features (helpfulness score, ratings) for a comprehensive analysis.

## Usage

1. Preprocess the review text and clean the data.
2. Perform sentiment analysis on the review text to generate sentiment labels and scores.
3. Extract key phrases and perform topic modeling on the reviews to identify key themes.
4. Visualize the sentiment distribution and the relationship between sentiment and helpfulness scores.
5. Integrate the features from both text and metadata to analyze product reviews and ratings.

## Visualizations

- **Sentiment Distribution**: A bar plot showing the distribution of positive, negative, and neutral sentiment labels.
- **Sentiment vs Helpfulness**: A scatter plot visualizing the relationship between sentiment scores and helpfulness scores.
- **Feature Importance**: A bar plot showing the importance of different features in predicting the product ratings.

## Conclusion

This project utilizes multi-modal feature engineering by combining textual data (e.g., sentiment, topics, key phrases) with structured numerical data (e.g., ratings, helpfulness scores) to better understand and predict product ratings. The analysis helps uncover insights from both product review text and metadata, creating a richer feature set for analysis or predictive modeling.

## License

This project is licensed under the MIT License.
