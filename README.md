# Analysis of the Boston and Seattle Airbnb Open Data.
This project  is part of the DataScience NanoDegree.
Analysis of the Boston and Seattle Airbnb Open Data.

Link to the Article in Medium [You need to look this before your vacation!](https://medium.com/@jose.lima.4616/you-need-to-look-this-before-your-vacation-1d57ec7a02ef)

Installation
------------

Dependencies
~~~~~~~~~~~~
- Python
- Pandas
- Sklearn
- Matplotlib
- Spacy
- SpacyTextBlob
- Nltk
- WordCloud
~~~~~~~~~~~~

Motivation
----------
Many people want to rent a good place to spend their vacations, but not all of them have experience in it, so an analysis is needed to know what kind of place is ideal for vacations, after all, no one likes to waste money and time in something you dislike.

Data
----
The data used in **Part I** and **Part II** is from [Kaggle Seattle Airbnb Open Data](https://www.kaggle.com/airbnb/seattle/data) and [Kaggle Boston Airbnb Open Data](https://www.kaggle.com/airbnb/boston?select=listings.csv)

The data used in **Part III** is only from [Kaggle Boston Airbnb Open Data](https://www.kaggle.com/airbnb/boston?select=listings.csv)

Files
-----
~~~~~~~~~~~~
- Boston_seattle_opendata_analysis.ipynb -> The notebook
- listings.csv -> listings of Boston Dataset
- listings_2.csv -> listings of Seattle Dataset
- cheap_overview.png -> Overview of houses with a value below 200USD
- general_overview.png -> General Overview of houses
- positive_words.png -> positive keywords of the reviews data
- negative_words.png -> negative keywords of the reviews data
- reviews.csv -> Boston reviews daa
~~~~~~~~~~~~

Results
-------
1 - There is no silver bullet to say if a place is perfect, it is necessary to analyze several factors, usually the price is the biggest one.

2 - If a location have reviews, is possible to use sentimenty analysis to see the strengths and weaknesses of that place.

3 - Is not possible to have a 100% accuracy prediction if a place good or not, but is possible to have good estimatives.
