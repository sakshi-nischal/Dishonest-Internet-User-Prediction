# Dishonest-Internet-User-Prediction

Dishonest internet user identification with Machine Learning is possible because of the ability of machine learning algorithms to learn from historical data patterns and recognize them in future patterns. Machine Learning is a set of method and techniques that let computers recognize patterns and trends and generate predictions based on those. It is all about taking data as input, extracting features from the data, training the algorithm using the data and creating model based on that data. Machine Learning algorithms appear more effective when it comes to the speed of information processing. Also, Machine Learning algorithms can find sophisticated untrustworthy traits that a human simply cannot detect. Rule based detection imply creating exact rules to tell the algorithm which types of operations seem normal and should be permitted and which should not be as they seem suspicious. Detection using Machine Learning come in handy to learn new patterns. Machine Learning methods show better performance along with the growth of dataset to which they are fitted. It implies the more samples they are trained on, the better they make predictions. A data science team should be aware of the risks linked to fast model scaling. If the model did not make predictions accurately, this will lead to false negatives in future. Machines can take over routine tasks and repetitive work of manual analysis, and the specialists will be able to spend time on making more high-level decisions.

The dataset was taken from Kaggle Platform having 322 rows and 5 attributes. 

The tuple of attributes is as follows:

Ctrust- Counting Trust. It is used to count how many trustworthy transactions belonging the specific context occur after the last untrustworthy transaction.

ctrust= {1,2,3,4}


Cuntrust- Counting Untrust. It is used to count how many untrustworthy transactions belonging the specific context occur after the last trustworthy transaction.

cuntrust= {1,2,3,4}


Last- Last time. It is used to consider the date at which the last experience in a specific context took place.

last= {1,2,3,4}


Context- Transaction Context. It is used to identify the type of transaction such as game, e-commerce, social network and others.

context= {sport, game, Ecommerce, holiday}


Score- Trust Score. It is the score that an entity gives to another at the end of each direct interaction.

Score= {trustworthy, untrustworthy}
