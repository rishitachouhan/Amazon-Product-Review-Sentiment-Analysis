Amazon-Product-Reviews - Sentiment-Analysis
Table of Contents
1. Problem Statement
2. My Approach
3. Technologies used
4. Project Objectives
5. Running My Deployed project on your Local Server
6. Data source files

__________________________________________________________________________________________________________________________________________________________________

🔹Problem Statement
It is observed that the maximum number of customers look at product reviews before they make a purchase. Survey results show that positive product reviews are a key factor for purchasing by 57% of Amazon buyers (Statista, 2019).

As product reviews are often the deciding factor for many customers, it’s very important to have a well-automated system for monitoring them.

The traditional manual process of Amazon product reviews is time-consuming and inefficient when millions of reviews are being posted all the time. It doesn’t show any trend or patterns over time. Moreover, it is tough to understand customers’ sentiment towards any product or its delivery.

____________________________________________________________________________________________________________________________________________________________________

🔹My Approach
I will be classifying Amazon customer reviews from the source files mentioned below, into 3 categories of positive, negative and neutral. The techniques used to solve this problem involve Text Classification and Time Series Analysis.

An automated system was developed to analyze and monitor an enormous number of reviews. By monitoring the entire review history of products, we analyzed the tone, language, keywords, and trends over time to provide valuable insights that increase the success rate of existing and new products as well as marketing campaigns.

![image](https://user-images.githubusercontent.com/115287902/221250402-75158fdc-5556-4ff8-be2f-e95a52e7b4d5.png)


Sentiment Analysis is a technique used in Natural Language Processing that converts unstructured text into data that can be analysed. It is an emerging tool that helps businesses differentiate and categorize opinions about their products, services and brand image.

Time Series Analysis helps in highlighting trends to forecast sentiment trends for particular subcategories in the future. Brands can discover many hidden trends in customer sentiments from historical data.

____________________________________________________________________________________________________________________________________________________________________

🔹Technologies used
![image](https://user-images.githubusercontent.com/115287902/221250599-2ccaf15b-af14-4447-aa26-b49c32ca797b.png)



______________________________________________________________________________________________________________________________________________________________________

🔹Project Objectives
➣ Reviews Preprocessing and Cleaning

➣ Story Generation and Visualization from reviews - Tableau

➣ Extracting Features from Cleaned reviews

➣ Model Building: Sentiment Analysis

➣ Model Building: Time Series Analysis

➣ Model Deployment

___________________________________________________________________________________________________________________________________________________________________

🔹Running my Deployed project on your Local Server
Go to your command prompt/terminal, change your directory to the folder that includes all the files in the deploymed_files folder

Then, enter the following codes:

pip install virtualenv
virtualenv ENV

./ENV/Scripts/activate

install all required dependencies listed in requirements.txt


To run our website on your local server, enter the code python app.py


Enter the ip address generated, on your browser's search bar.

_________________________________________________________________________________________________________________________________________________________________

🔹Data Source Files
I would like to deeply thank Julian McAuley for sharing this mass collection of datasets containing Amazon reviews. These files can be accessed from the link below:-

http://jmcauley.ucsd.edu/data/amazon/

4 datasets that I used in this project are (Per-category files):

Home and Kitchen - reviews

Home and Kitchen - metadata

Musical Instruments - reviews

Musical Instruments - metadata
