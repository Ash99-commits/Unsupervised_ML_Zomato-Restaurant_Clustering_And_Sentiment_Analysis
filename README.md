# ML-NLP Unsupervised_ML_Zomato-Restaurant_Clustering_And_Sentiment_Analysis

#### Objectives :-
  1. **Cluster Restaurants** : Group restaurants into meaningful clusters based on their attributes.
  2. **Analyze Customer Sentiments** : Extract insights from user reviews to classify sentiments as positive or negative, revealing customer satisfaction trends and preferences.

#### Business Context :-

Zomato, a leading restaurant aggregator and food delivery platform in India, has witnessed massive growth in restaurant listings and customer engagement over the years. With the surge in the number and variety of restaurants, deriving actionable insights becomes vital for enhancing user experience and maintaining competitive advantage.

#### Data Utilization:

*   **Data Sources**: Restaurant data from Zomato.
*   **Sentiment Analysis**: Customer reviews will be analyzed to extract sentiment polarity (positive or negative).

#### Methodology:

1.  **Data Preprocessing**: Cleaning and structuring data for analysis.
2.  **Clustering Technique**: Utilizing unsupervised machine learning algorithms (like K-means, hierarchical clustering, DBSCAN) to group restaurants.
3.  **Sentiment Analysis**: Employing NLP techniques to analyze and categorize the sentiments of user reviews.

#### Outcomes:

*   **Visualizations**: Graphical representations of clusters and sentiment analysis results for easier interpretation and decision-making.
*   **Insights for Customers**: Assisting customers in finding the best-suited restaurants based on their preferences.
*   **Business Strategy for Zomato**: Identification of areas for improvement, popular cuisines, and customer preferences to strategize business growth and customer satisfaction.

#### Impact:

*   **For Customers**: Enhanced decision-making in choosing restaurants aligning with their preferences.
*   **For Zomato**: Strategic insights into customer preferences, leading to better service offerings and targeted marketing.

#### Applications:

*   **Customer Segmentation**: Identifying different customer segments for targeted marketing.
*   **Market Analysis**: Understanding popular trends in cuisines and dining experiences.
*   **Operational Improvement**: Identifying gaps in service and areas for improvement.
*   **Critic Analysis**: Using reviewer metadata to identify influential critics in the industry.

#### Models used for Restaurant Clustering:

1. K-Means clustering  (Selected)
2. Hierarchical clustering
3. DBSCAN 

#### Models used for Sentiment Analysis:

1. Logistic Regression :-
  * Accuracy: 86.44% – Strong overall performance.
  * Precision: 86% for both classes – Balanced precision.
  * Recall: 75% (Neg), 93% (Pos) – Better at detecting positive sentiment.
  * F1 Score: 0.80 (Neg), 0.90 (Pos) – Solid overall balance.

2. Random Forest

  * Accuracy: 86.19% – Comparable to Logistic Regression.
  * Precision: 87% (Neg), 86% (Pos) – Good precision balance.
  * Recall: 73% (Neg), 94% (Pos) – Very strong in detecting positive sentiment.
  * F1 Score: 0.80 (Neg), 0.90 (Pos) – Balanced, especially positive class.

3. XGBoost

  * Accuracy: 87.14% – Best accuracy among all models.
  * Precision: 85% (Neg), 88% (Pos) – Good precision.
  * Recall: 79% (Neg), 92% (Pos) – Best negative sentiment detection.
  * F1 Score: 0.82 (Neg), 0.90 (Pos) – Well-balanced performance.

4. Gradient Boosting

  * Accuracy: 82.57% – Lowest among the models.
  * Precision: 87% (Neg), 81% (Pos) – Strong precision for negative class.
  * Recall: 62% (Neg), 95% (Pos) – Weak at negative sentiment, excellent positive detection.
  * F1 Score: 0.72 (Neg), 0.87 (Pos) – Imbalanced performance.

#### 
