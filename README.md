<img src="pic.jpg" alt="image">

# Amazon Fine Food Reviews Analysis

This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories


Data Source: https://www.kaggle.com/snap/amazon-fine-food-reviews <br>

EDA: https://nycdatascience.com/blog/student-works/amazon-fine-foods-visualization/


The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.<br>

Number of reviews: 568,454<br>
Number of users: 256,059<br>
Number of products: 74,258<br>
Timespan: Oct 1999 - Oct 2012<br>
Number of Attributes/Columns in data: 10 

Attribute Information:

1. Id
2. ProductId - unique identifier for the product
3. UserId - unqiue identifier for the user
4. ProfileName
5. HelpfulnessNumerator - number of users who found the review helpful
6. HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not
7. Score - rating between 1 and 5
8. Time - timestamp for the review
9. Summary - brief summary of the review
10. Text - text of the review


### Objective:
Given a review, determine whether the review is POSITIVE OR NEGATIVE


### It is very important to note that deep neural networks can easily fall in the trap of overfitting. This can be easily identified when the validation loss stops reducing for few continuous iterations but the loss keeps reducing. It is then that the model start to overfit and learns the input data exceptionally well resulting in poor performance on unseen data. This can be very well seen in the 17th epoch in ANN, where as LSTM keeps fluctuating. We can run more epochs to improve on the model. 
<img src="img.jpg" alt="image">

#### The data set needed preprocessing and cleaning. Sequential ANN and LSTM  are used with ADAM optimiser to achieve the task. Dive into code for detailed solution.

