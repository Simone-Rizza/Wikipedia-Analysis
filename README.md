# Wikipedia Analysis
 
In this project we are going to perform an EDA activity to statistically analyze and evaluate all the information content offered by Wikipedia. The bump you are provided with, has the following categories: 

'culture',
 'economics',
 'energy',
 'engineering',
 'finance',
 'humanities',
 'medicine',
 'pets',
 'politics',
 'research',
 'science',
 'sports',
 'technology',
 'trade',
 'transport'

Specifically, we are going to calculate the following information for each category.

- Number of articles
- Average number of words used
- Maximum number of words present in the longest article
- Minimum number of words present in the shortest article
- For each category, identify the most representative word cloud

After performing the required analysis, we will train and test a text classifier capable of classifying the articles (according to the categories in the dataset) that will be entered in the future.

The dataset consists of 4 columns: 

- title: indicates the title of the article
- summary: contains the introduction of the article
- documents: contains the complete article
- category: contains the category associated with the article

We are going to train the model first using the summary column and then the documents column osso as to compare the results obtained and check which of the two classifiers has greater accuracy in terms of classification.