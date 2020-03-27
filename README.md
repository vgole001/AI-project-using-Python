# AI-project-using-Python
AI to predict whether online shopping customers will complete a purchase.
The task in this problem is to build a nearest-neighbor classifier to solve the problem. 
Given information about a user — how many pages they’ve visited, 
whether they’re shopping on a weekend, what web browser they’re using, etc. — our classifier 
will predict whether or not the user will make a purchase. Our classifier won’t be
perfectly accurate — perfectly modeling human behavior is a task well beyond the 
scope of this class — but it should be better than guessing randomly. 
To train our classifier, we’ll provide it with some data from a shopping 
website from about 12,000 users sessions written in a csv file.
We’ll measure two values: sensitivity (also known as the “true positive rate”) 
and specificity (also known as the “true negative rate”). Sensitivity refers to 
the proportion of positive examples that were correctly identified: in other words, 
the proportion of users who did go through with a purchase who were correctly identified. 
Specificity refers to the proportion of negative examples that were correctly 
identified: in this case, the proportion of users who did not go through with 
a purchase who were correctly identified. So our “always guess no” classifier from 
before would have perfect specificity (1.0) but no sensitivity (0.0). 
Our goal is to build a classifier that performs reasonably on both metrics.
