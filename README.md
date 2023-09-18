# Looking into Seattle Airbnb Open Data

Here I used the data from Seattle Airbnb to get some insight to answer couple of questions as listed below. The data is downloaded from [kaggle open data](https://www.kaggle.com/datasets/airbnb/seattle)

## Questions
1) What are the busiest times of the year to visit seattle? by how much do prices spike?

2) Describe the vibe of each Seattle neighborhood

3) Is there anything about the properties that helps us predict price. For example, can we find negative and positive reviews based on the text?

## Files and folders descriptions

- Udacity_Project1.ipynb is a Jupyter notebook where I have looked at the data and for each question above I did some analysis with plots for visualisation.
- Seattle folder contains 3 csv files that are used in the code as inputs for different analysis.
** Listings, including full descriptions, average review score, and all information regarding each listing id
** Reviews, including unique id for each reviewer and detailed comments
** Calendar, including listing id and the price and availability for that day
- df_review_grouped.pkl is a dataframe which is a result of a preprocess function that works on the text values. As this function takes a long time to run each time on the whole data, I saved the out put and read in later in the code so I do not need to run the function everytime.

## Results
The main findings of the code can be found at the post available [here](https://medium.com/@rojan.saghian/travelling-to-seattle-what-you-need-to-know-f94769265430).

## Acknowledgements
To do this project specially the parts related to topic modelling and sentimental analysis, I used instructions, informations, and in some cases functions proposed in the below linkes that I also have referenced in my code where it applies:
- Topic modelling:
** [Introduction to Natural Language Processing](https://openclassrooms.com/en/courses/6532301-introduction-to-natural-language-processing/8080062-remove-stopwords-from-a-block-of-text)
** [Topic Modeling in Python: Latent Dirichlet Allocation (LDA)](https://towardsdatascience.com/end-to-end-topic-modeling-in-python-latent-dirichlet-allocation-lda-35ce4ed6b3e0)
** [Finding deeper insights with Topic Modeling](https://www.red-gate.com/simple-talk/databases/sql-server/bi-sql-server/deeper-insights-topic-modeling/)
- Sentimental Analysis:
** [text-analytics-beginners-nltk](https://www.datacamp.com/tutorial/text-analytics-beginners-nltk)
** [python-sentiment-analysis-using-vader](https://www.geeksforgeeks.org/python-sentiment-analysis-using-vader/) 

