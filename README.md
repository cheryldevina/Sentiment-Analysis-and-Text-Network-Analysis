# Sentiment-Analysis-and-Text-Network-Analysis
A text-web-process mining project where we scrape reviews from the internet and try to predict their sentiment with multiple machine learning models (XGBoost, SVM, Decision Tree, Random Forest) then create a text network analysis to see the frequency of correlation between words.

## Dataset
Dataset comprises of two columns, a 'text' column and a 'recommendation' column. The 'recommendation' column consists of 3 labels:
- Recommended
- Not recommended
- Mixed Feelings

## Preprocessing
Since some of the text are not in English, a Python library called spacy is used to detect the language and only keep data that is in English. 
The labels are then mapped to 0, 1, and 2 respectively.
The data is then oversampled to have an equal amounts of each class label.

## Model Training
The models used were:
- Support Vector Machine (SVM)
- Random Forest
- XGBoost
- Decision Tree

## Results
A result of words that are highly correlated with certain class labels are achieved. As well as a text-network diagram with thick edges with words that are used frequently together.
