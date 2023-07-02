# Covid-19-Tweet-Sentiment-Analysis

![download](https://github.com/kuldeep-sngh/Covid-19-Tweet-Sentiment-Analysis/assets/112714096/51a1bad1-a90e-457a-b017-d37505b26349)

# 1. INTRODUCTION:
This is an Almabetter's capstone project on ML-Classification problem, sentiment analysis of Tweets related to the Covid-19 pandemic, which is a multi-label classification task. Since the outbreak of coronavirus, it has affected more than 180 countries where massive losses in the economy and jobs globally and confining about 58% of the global population are caused. The research on people’s feelings is essential for keeping mental health and informed about Covid-19.

The tweets have been pulled from Twitter and manual tagging has been done then. the names and usernames have been given codes to avoid any privacy concerns.

### Dataset Description:
![image](https://github.com/kuldeep-sngh/Covid-19-Tweet-Sentiment-Analysis/assets/112714096/3f85933d-3aab-4677-a9ce-84825699112a)

### Objective: 
The objective of this project is build a Classification ML model to predict the sentiment of covid-19 tweets.

### Workflow in this Project:
![image](https://github.com/kuldeep-sngh/Covid-19-Tweet-Sentiment-Analysis/assets/112714096/dccb050d-b4c6-4b63-88a2-22ae47920ab2)

# 2. Exploratory Data Analysis:
* The original dataset has 6 columns and 41157 rows.
* Target variable ('Sentiment') has 5 different classes. **'Neutral', 'Positive', 'Extremely Negative', 'Negative', 'Extremely Positive'**

![image](https://github.com/kuldeep-sngh/Covid-19-Tweet-Sentiment-Analysis/assets/112714096/7c9b10ce-f53b-43d9-964e-aada556233a7)

# 3. NLP-based data preprocessing:
For NLP-based data preprocessing in COVID-19 tweet sentiment analysis, the text was cleaned by removing noise like URLs, hashtags, special characters, and mentions. The text was tokenized, stop words were removed, and it was converted to lowercase. Stemming was applied and Text Vectorization using TfidfVectorizer was done. These NLP techniques ensured that the text data was cleaned, normalized, and suitable for sentiment analysis using machine learning models.

![image](https://github.com/kuldeep-sngh/Covid-19-Tweet-Sentiment-Analysis/assets/112714096/7143ee5c-38d8-4ce4-9177-80435b7ed51c)

# 4. Model Implementation and Evaluation
Implemented 6 different algorithms: 
1. Logistic Regression
2. Multinomial Naive Bayes Classifier
3. Passive Aggresive Classifier
4. Random Forest
5. SVM
6. Neural Networks

  
   ![Screenshot (4)](https://github.com/kuldeep-sngh/Covid-19-Tweet-Sentiment-Analysis/assets/112714096/227c3458-1375-43bf-ae75-5793746d2a42)


# Conclusion:
Selected Passive Aggresive Classifier as our final prediction model having accuracy score of 80%. Also tested the selected model on some new tweet and the results were fairly accurate.

