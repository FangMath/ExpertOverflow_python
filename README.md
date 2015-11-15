# ExpertOverflow Python Implementation

This is the ipython implementation of ExpertOverflow. It is used for the
initial model development and test. We use the smaller dataset of 
[**Stats Overflow**](http://stats.stackexchange.com/)(~546M) for the first develpment.

Check out the Heroku app [here](https://experts-overflow.herokuapp.com).

## A brief discription on ExpertOverflow project

Analyze 20G posts data from 2,000,000 users using Spark/Hadoop. Reduce the user knowledge dimension by PCA and find the patten in users by K-Means clustering algorithm. Expert users with distinct expertise are recognized. Information about top experts is presented on our Heroku app https://experts-overflow.herokuapp.com

## Related repos

* [ExpertOverflow_spark](https://github.com/FangMath/ExpertOverflow_spark) ExpertOverflow implementation using Spark(Scala) on the full Stack Overflow dataset

* [ExpertOverflow_flask](https://github.com/FangMath/ExpertOverflow_flask) Heroku app development using flask

A better documentation is needed...

