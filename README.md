# Wine-Reviews-NLP

In this repository I have attached three kernals :

1)Wine Descriptions with NLP and kMeans: As the name suggests we will be using NLP to understand the sentiment then will be using unsupervised learning(kmeans) to get the wines which are similar to each other.

2)Wine reviews:- This kernal has details EDA and feature engineering of all the features. Helps to understand what the dataset is actually about. Finally we have built a recommendation system for us where we find the wines which are similar to a given wine.

3)Spacy Wine reviews:- Spacy has been used to understand wine reviews.


Context
After watching Somm (a documentary on master sommeliers) I wondered how I could create a predictive model to identify wines through blind tasting like a master sommelier would. The first step in this journey was gathering some data to train a model. I plan to use deep learning to predict the wine variety using words in the description/review. The model still won't be able to taste the wine, but theoretically it could identify the wine based on a description that a sommelier could give. If anyone has any ideas on how to accomplish this, please post them!

Content
This dataset contains three files:

winemag-data-130k-v2.csv contains 10 columns and 130k rows of wine reviews.

winemag-data_first150k.csv contains 10 columns and 150k rows of wine reviews.

winemag-data-130k-v2.json contains 6919 nodes of wine reviews.

Click on the data tab to see individual file descriptions, column-level metadata and summary statistics.

Acknowledgements
The data was scraped from WineEnthusiast during the week of June 15th, 2017. The code for the scraper can be found here if you have any more specific questions about data collection that I didn't address.

UPDATE 11/24/2017
After feedback from users of the dataset I scraped the reviews again on November 22nd, 2017. This time around I collected the title of each review, which you can parse the year out of, the tasters name, and the taster's Twitter handle. This should also fix the duplicate entry issue.

Inspiration
I think that this dataset offers some great opportunities for sentiment analysis and other text related predictive models. My overall goal is to create a model that can identify the variety, winery, and location of a wine based on a description. If anyone has any ideas, breakthroughs, or other interesting insights/models please post them.
