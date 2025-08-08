# Portfolio
Hi! This is Farha. Welcome to my Data Science portfolio! This space showcases a curated collection of real-world and project-based work that reflects my ability to turn data into actionable insights. My projects span various domains—from finance and cryptocurrency to fake news detection—demonstrating skills across the entire data pipeline.

🔍 What You’ll Find:
* End-to-End Projects: Complete workflows including data collection, cleaning, analysis, visualization, and modeling.

* Real-World Datasets: Applied to publicly available or scraped data that mimics practical business challenges.

* Machine Learning Models: Built for classification, regression, and NLP, evaluated using appropriate metrics.

* Interactive Visualizations: Used for storytelling and communicating insights to technical and non-technical stakeholders.

* Code and Documentation: Clean, well-commented code with Jupyter notebooks, GitHub repositories, and final presentations.

🛠️ Skills Demonstrated
* Languages & Libraries: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, NLTK

* Data Handling: Cleaning messy data, handling missing values, feature engineering, and EDA

* Machine Learning: Logistic Regression, Decision Trees, Word2Vec, and more

* Visualization & Reporting: Dashboard-ready plots and business-oriented summaries

📌 Featured Projects:
* Trader Performance Analysis: Studied how emotions like fear and greed influence trading behavior.

* Fake News Detection: Developed an NLP model using Word2Vec and Logistic Regression to detect misinformation.

* Airbnb Price Range Prediction and Customer Segmentation: Explored key factors that impact listing prices using regression models.

* Banking Churn Prediction: Predicted customer churn with classification models and model interpretation techniques.

👩‍💻 Let’s Connect!
If you're interested in collaborating or hiring for data-driven roles, feel free to reach out!





## Trader Performance Analysis
This project explores the relationship between market sentiment and cryptocurrency trading performance. By integrating Fear & Greed Index data with real trading records, it uncovers behavioral patterns in decision-making, profitability, and trade direction under different sentiment conditions such as Fear, Greed, Extreme Greed, and Neutral.

📌 Key Highlights:

* Data Integration: Merged public sentiment data (Fear & Greed Index) with real-world trade logs based on timestamps.

* Data Cleaning & Processing: Handled inconsistent formats, parsed dates, managed missing classifications, and standardized features for analysis.

🔍 Exploratory Data Analysis (EDA):

* Distribution of trades under each sentiment.

* Win rate and average PnL per sentiment.

* BUY vs SELL behavior across market conditions.

📊 Visualizations:

* PnL distribution under fear vs greed (bar chart)

* PnL distribution by sentiment (Box Plot)

* PnL over time by sentiment (Line chart)

* Number of trades per sentiment (Bar chart)

* Buy vs Sell comparison (Pie chart)  

✅ Insights Derived:

* Lower win rates and higher volatility during periods of Fear.

* Greed-driven trades showed higher average profitability but also risk.

* BUY trades were more frequent during Greed, while SELL trades increased under Fear.

🛠️ Tools & Technologies:

* Python, Pandas, Matplotlib, Seaborn

* Data wrangling, datetime handling, and group-based analysis






## Fake News Detection System
This project focuses on detecting misleading or false information in news articles using Natural Language Processing (NLP) and supervised learning techniques. With misinformation being a growing threat, especially across digital platforms, the goal was to build a robust classification model that can distinguish between real and fake news.

🔍 Key Objectives
* Classify news headlines/articles as real or fake

* Apply text preprocessing techniques (tokenization, stopword removal, lemmatization)

* Generate semantic meaning using Word2Vec embeddings

* Train a Logistic Regression model for binary classification

* Evaluate model performance using accuracy, confusion matrix, and ROC curve

🛠️ Tech Stack
* Language: Python

* Libraries: Pandas, NumPy, Scikit-learn, NLTK, Gensim, Matplotlib, Seaborn

* Modeling: Word2Vec + Logistic Regression

* Data: Sourced from a labeled dataset of fake and real news headlines/articles

📊 Approach
* Data Cleaning: Removed noise such as punctuation, special characters, and stopwords.

* Tokenization & Lemmatization: Prepared the text for embedding.

* Vectorization: Used Word2Vec to convert text into numerical vectors by averaging word embeddings.

* Model Training: Trained a logistic regression model to classify the articles.

* Evaluation: Achieved good accuracy with balanced results across both classes.

✅ Outcome
* Developed a scalable pipeline for text-based classification.

* Gained deeper understanding of NLP preprocessing and word embeddings.

* Demonstrated how classical ML methods can perform well when combined with strong feature engineering.


## AirBNB Price Range Prediction and Customer Segmentation

This project applies machine learning techniques to predict price categories of Airbnb listings and identify natural segments of accommodations for targeted marketing.

🔍 Problem Statement
* Predict the price range of Airbnb accommodations using key listing features.

* Use clustering to group similar listings for better market targeting and customer segmentation.

🔧 Methods & Tools
* Classification Model: Decision Tree Classifier (pruned for optimization)

* Clustering: K-Means on dimensionally reduced data (PCA/TSNE)

🛠️ Tech Stack: Python, Pandas, Scikit-learn, Matplotlib, Seaborn

📈 Classification Highlights
* Trained a Decision Tree Classifier to predict price range.

* After pruning (max depth = 8), achieved:

Accuracy: 66%

Precision: 0.49

Recall: 0.31

F1 Score: 0.33

* Prioritized precision over recall to ensure correct marketplace placement for listings, improving customer targeting.

📊 Clustering Insights
* Applied K-Means clustering after dimensionality reduction to 2D.

* Observed clearly separated clusters of listings, suggesting distinct groups with similar features.

* Insights from clustering aid in segment-specific marketing strategies.

💡 Key Insights & Business Recommendations
* Room Type, Accommodates, Bedrooms, and Beds are the most influential features for price prediction.

* Promote Entire Home/Apt and Private Room listings for higher revenue.

* Optimize listings by increasing accommodation capacity (beds and bedrooms) to improve appeal and pricing potential.

✅ Outcome
* Successfully combined predictive modeling with unsupervised learning to offer:

* Accurate price category predictions.

* Actionable segmentation insights.

* Data-driven recommendations for optimizing listings and revenue.

