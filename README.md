**Final Project for NLP course**

Authors: Roman Makarov, Adela Krylova

Project Description:

Email categorizer based on the following NLP methods:
* Text preprocessing
* Vectorizer
* TF-IDF transformer

Our solution can categorize the following types of e-mails:
* Ham - general emails
* Spam emails
* Calendar - notifications or information about added events from calendars such as Google Calendar
* Meeting - e-mails that contain links to zoom etc.
* Working - e-mails related to work, which are not included in two previous categories

Requirements:

    !pip install nltk
    !pip install pandas
    !pip install sklearn
    
How to run the code:

* The code in python notebook is self-explanatory and ready to run, after installing the requirements.
  
* The code should be run in Google Colab, otherwise, you need to replace '!gdown' command with the files that are located in the directory 'data'. One of the files is too big to upload. It can be found by the following link: https://drive.google.com/uc?id=1Ej9AAef7xLi5xhMo5BN-qPQGeYHwTZ6O

* The final dataset (before preprocessing) can be found in a folder 'data' by a name 'complete_dataset.csv'
