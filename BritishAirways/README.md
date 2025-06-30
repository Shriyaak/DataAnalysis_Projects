## Certificate of Completion 
![cetf](https://github.com/Shriyaak/Sentiment-Analysis-of-British-Airways-Reviews/blob/a7fadf97aee2e81fef2fcdb687f201cc10e69b0f/certi.png) 

## Task 1: Sentiment Analysis & Word Cloud Visualization
This task involves performing sentiment analysis on customer reviews of British Airways using natural language processing techniques. The goal is to extract and visualize insights about customer perceptions through:

Text Preprocessing: Cleaning and preparing review text for analysis.

Sentiment Scoring: Using TextBlob to assign polarity scores and classify each review as Positive, Neutral, or Negative.

KPI Calculation: Aggregating sentiment results into percentage-based KPIs for quick insight into customer satisfaction levels.
<br/> 
<br/> 
![sub1_img1](https://github.com/Shriyaak/-Sentiment-Analysis-of-British-Airways-Reviews/blob/c6b40e3ea839c0be8eec8030926ec0679c596939/sentiment_kpis.png)

Word Cloud Generation: Creating a visual representation of commonly used words in the reviews, where:
<br/> 
<br/> 
![sub1_img2](https://github.com/Shriyaak/-Sentiment-Analysis-of-British-Airways-Reviews/blob/c6b40e3ea839c0be8eec8030926ec0679c596939/wordcloud.png)

Bigger words appear in dark green (high frequency)

Smaller words fade into grey (lower frequency)

These steps provide a clear, visual, and quantitative understanding of how passengers feel about their experience with British Airways.

## Task 2: Predicting Booking Completion
Goal
Predict whether a customer will complete a booking based on their search and preferences.

### Key Steps
#### Data Cleaning: Handled outliers, converted categorical variables using get_dummies

#### Feature Engineering: Scaled numerical columns, mapped day-of-week

#### Modeling:
- Used RandomForestClassifier with class_weight='balanced' <br/> 
- Optimized threshold using Precision-Recall Curve and F1 score <br/> 
- Tuned hyperparameters via GridSearchCV <br/> 

#### Evaluation: 
- Accuracy: ~85% <br/> 
- Recall for bookings: Increased from 13% to 69% with threshold tuning <br/> 

#### Visualizations: 
- Feature Importance Bar Chart <br/> 
- Confusion Matrix <br/> 
- Precision-Recall Curve <br/> 


## Key Results: 
| Metric                      | Value   |
| --------------------------- | ------- |
| Accuracy                    | \~85.5% |
| F1 Score (custom threshold) | 0.45    |
| ROC AUC                     | 0.78    |
| Booking Recall              | **69%** |


## Skills Demonstrated
Natural Language Processing (TextBlob, WordCloud)

Supervised ML (Random Forest, Threshold Tuning)

Feature Engineering & Preprocessing

Model Evaluation (Precision, Recall, F1, PR AUC)

Data Visualization (Matplotlib, Seaborn)

Business Insight Communication
