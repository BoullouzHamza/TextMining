# Youtube_comments_prediction
In this project, I will be creating a spam filter using multinomial naive bayes algorithm learn, to filter out spam comments from Youtube videos. We have data of labelled youtube comments in five seperate files. So we'll train our model with four of them and use the fifth file for prediction and testing for accuracy. The data set used in this notebook can be found here https://www.kaggle.com/lakshmi25npathi/images

The table below lists the datasets, the YouTube video ID, the amount of samples in each class and the total number of samples per dataset.

Dataset --- YouTube ID -- # Spam - # Ham - Total /n
Psy ------- 9bZkp7q19f0 --- 175 --- 175 --- 350
KatyPerry - CevxZvSJLk8 --- 175 --- 175 --- 350
LMFAO ----- KQ6zr6kCPj8 --- 236 --- 202 --- 438
Eminem ---- uelHwf8o7_U --- 245 --- 203 --- 448
Shakira --- pRpeEdMmmQ0 --- 174 --- 196 --- 370 

## Attribute Information:
The collection is composed by one CSV file per dataset, where each line has the following attributes:
COMMENT_ID--> the ID of each comments
AUTHOR--> the name of the writer of comment
DATE--> the date of the comment 
CONTENT-->the comment content
TAG --> 1: spam  0: not spam 
