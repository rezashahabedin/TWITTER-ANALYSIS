# TWITTER-ANALYSIS
in this approach we recieve a huge amount coments and tweets from twitter api to analyse.

main idea is to find negative and positive quality of service provides in an airport based on people tweets.
first of all we need to specify different topics that has been spoken in the corpus, many other approaches using supervised algorithms which is not an option here,in reall world we can not label people comments with their topics, unless its a review or a clean database
so i had to use unsupervised approache to address at least 20 different topics that people has spoken about. doing that by using tfidf-vectoriser, LDA and NMF algorithms.
relating the found topics to the actual comments is a huge headache to be honest which is provided in the code.
running a sentiment analysis on the corpus and getting grade for each topic was the next but not last step
in the end by visualising the result we can see what servises has the most good reaction by the people and what need more attention, for example i can say restrooms and waiting areas got a pretty low score showing people frustration waiting for their flights.

you need to be a familiar with data science field to be able to run the code and it wont be suggested for beginners

****in the end i have to mention this the academic approach of the project and the actual code will not be desplayed because of costumer privacy****
