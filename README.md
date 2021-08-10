# Spam-Email-Detection



### Abstract:
We all know how annoying is to see spam emails in our inbox which are repeatedly used for the purposes of advertising and brand promotions. Some major categories of spam emails that are causing great risk to security, such as fraudulent e-mails, identify theft, hacking, viruses, and malware. So to deal with this we thought of building a robust real-time email spam classifier for flagging the incoming spam emails. There is a huge scope of building e-mail spam classifiers as the private companies run their own email servers and want them to be more secure because of the confidential data, in such cases email spam classifier solutions can be provided to such companies. In this project we will be focusing on mainly the subject and the content of the email and if time permits also the header. The models which we will be using in the project are SVM and Naive Bayes.
As of now, we have also thought of building plots on the following.Plotting histogram for email text length of spam vs ham,bar graph depicting the percentage of Ham and Spam emails in the given dataset,plotting histogram for email text length of spam vs ham,word cloud for ham emails, word cloud for spam emails,distribution of the number of words:,Exploring mean word length,most Frequent word analysis using stop words,Most Frequent word analysis without using stop words
We will be using the following steps for data preparation:-
+ Identifying Missing values.
+ Converting all text to lower case.
+ Performing tokenization.
+ Removing Stop words.
+ Labelling classes: ham/spam: {0;1}
+ Splitting Train and Test Data: 80% and 20%.
