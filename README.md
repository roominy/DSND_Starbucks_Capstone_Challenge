# DSND_Starbucks_Capstone_Challenge
Data Science Nanodegree Starbucks Capstone Challenge.


### Table of Contents
1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## 1. Installation <a name="installation"></a>

To be able to run and view this project. It's recommended to have the latest versions of the followings:
* [Python 3](https://www.python.org/downloads/)
* [Jupyter Notebook](https://jupyter.org/index.html)
* [Pandas](https://pandas.pydata.org)
* [Matplotlib](https://matplotlib.org)
* [sklearn](https://pypi.org/project/sklearn/)
* [Seaborn](https://seaborn.pydata.org)
* [NumPy](https://numpy.org/)
* [datetime](https://pypi.org/project/DateTime/)


## 2. Project Motivation <a name="motivation"></a>

The problem statements I am trying to answer are here are: 
   * What are the distributions of gender, age, and income of customers in general?
   * What are the distributions offer types alone and based on gender, age, and income of customers that completed the offers?
   * Will a customer respond to an offer?

## 3. File Descriptions <a name="files"></a>
 
Starbucks_Capstone_notebook.ipynb contains the Python code for this project. 

The data is contained in three files:

* portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
* profile.json - demographic data for each customer
* transcript.json - records for transactions, offers received, offers viewed, and offers completed

Here is the schema and explanation of each variable in the files:

1- portfolio.json:
* id (string) - offer id
* offer_type (string) - type of offer ie BOGO, discount, informational
* difficulty (int) - minimum required spend to complete an offer
* reward (int) - reward given for completing an offer
* duration (int) - time for offer to be open, in days
* channels (list of strings)

2- profile.json:
* age (int) - age of the customer 
* became_member_on (int) - date when customer created an app account
* gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
* id (str) - customer id
* income (float) - customer's income

3- transcript.json:
* event (str) - record description (ie transaction, offer received, offer viewed, etc.)
* person (str) - customer id
* time (int) - time in hours since start of test. The data begins at time t=0
* value - (dict of strings) - either an offer id or transaction amount depending on the record


## 4. Results <a name="results"></a>

The findings of the anslysis can be found at my post [here](https://medium.com/@roominy/starbucks-offers-data-science-approach-b0e6a0bdfb79).


## 5. Licensing, Authors, and Acknowledgements <a name="licensing"></a>

Credit given to Udacity courses for some of code ideas, and to Starbucks for the data.

Author: NYRoomi
