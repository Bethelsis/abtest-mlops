# abtest-mlops


### Objective
Test if the ads that the advertising company runs resulted in a significant lift in brand awareness. Our task here, is to design a reliable hypothesis testing algorithm for the Brand Impact Optimiser (BIO), which is a lightweight questionarie served with every campaign to detrmine the impact of the creative, service and to determine whether a recent advertising campaign resulted in a significant lift in their brand awareness.

### Data


The BIO data for this project is a “Yes” and “No” response of online users to the following question

Q: Do you know the brand SmartAd? O Yes O No The users that were presented with the questionnaire above were chosen according to the following rule:

Control: users who have been shown a dummy ad Exposed: users who have been shown a creative, an online interactive ad, with the SmartAd brand. The data is collected from 3-10 jul 2020 from SmartAd advertising agency.
    
The data collected for this challenge has the following columns auction_id: the unique id of the online user who has been presented the BIO. In standard terminologies this is called an impression id. The user may see the BIO questionnaire but choose not to respond. In that case both the yes and no columns are zero. experiment: which group the user belongs to - control or exposed. date: the date in YYYY-MM-DD format hour: the hour of the day in HH format. device_make: the name of the type of device the user has e.g. Samsung platform_os: the id of the OS the user has. browser: the name of the browser the user uses to see the BIO questionnaire.


### Method
A/B Hypothesis Testing is a way to compare two versions of something to figure out which performs better.
The notebooks in this repository contains data exploration and implementation of classical p-value based algorithm,the sequential A/B testing algorithm  and Machine learning based AB testing in Python.  

