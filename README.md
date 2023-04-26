# article-recommendation-system-cs547-IR-Project-spring2023

Article Recommendation System
By
Supreeth Bandi
Adityavikram Gurao
Sree Likhith Dasari
Snehith Varma Datla
Under the Guidance of Prof. Kyumen Lee

We have our code in Jupyter Notebook file called 'final_ir.ipynb'. In order to run the code you need a our dataset called 'Final_c.csv', it contains 3037 rows and 21 Columns. We have used NewsCatcherAPI for collecting the artcile data online.We've also added requirements.txt file. In order to collect articles online, you have to create an account on https://newscatcherapi.com/ and generate API key. API has some limitations: 10,000 calls, 1 API call/second, 4 weeks old articles, First 250 char of article body.
However, 10,000 calls are applicable for only first month after that you get 500 Requests per month.
We have also added 'datacollection.ipynb', so that you'll only need to put API Key and make few changes in query to collect data.
