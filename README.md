# Machine-Learning-Projects

ACCURACY, RECALL, PRECISION, AND F1 SCORE
Accuracy
After creating a machine learning algorithm capable of making classifications, the next step in the process is to calculate its predictive power. In order to calculate these statistics, we’ll need to split our data into a training set and validation set.

Let’s say you’re using a machine learning algorithm to try to predict whether or not you will get above a B on a test. The features of your data could be something like:

The number of hours you studied this week.
The number of hours you watched Netflix this week.
The time you went to bed the night before the test.
Your average in the class before taking the test.
The simplest way of reporting the effectiveness of an algorithm is by calculating its accuracy. Accuracy is calculated by finding the total number of correctly classified points and dividing by the total number of points.

In other words, accuracy can be defined as:

(True Positives + True Negatives) / (True Positives + True Negatives + False Positives + False Negatives)

Let’s define those terms in the context of our grade example :

True Positive: The algorithm predicted you would get above a B, and you did.
True Negative: The algorithm predicted you would get below a B, and you did.
False Positive: The algorithm predicted you would get above a B, and you didn’t.
False Negative: The algorithm predicted you would get below a B, and you didn’t.
Let’s calculate the accuracy of a classification algorithm!

