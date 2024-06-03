
# Personal Hiking model 
Final project for the Building AI course
Building AI course project

## Summary
This project will seek to create a model that will work together with already existing training apps. It will match data from the apps on fitness level to find out whether a given mountain route will be suitable for the user’s physical ability. It should also be able to suggest the best suited routes nearby. And incorporate the user's experience and update this concurrently to ensure that the users will not be suggested routes out of experience requirements.

## Background
The program will deliver well suited routed nearby matching the user’s fitness level and mountain experience. 
Hiking is becoming more and more popular. Many wish to hike in untouched landscapes. However, many people underestimate what it takes to do a hike, especially mountain routes. This can be dangerous for some. And costly task for the local rescue workers. 
My own experience is that it can sometimes be difficult to determine whether or not to go on a specific hike because a have no comparable data to the route description. 
This model seeks to solve these problems:
* avoiding users going on a higher leveled route compared to the users experience and physical form
* reduce the number of times local rescue times should take action
* avoid the user having to choose a route out of doubt
*providing data to become a better hiker 

## How is it used?

The program should be used as a part of different apps who provides fitness data for hikers. 
It should provide data for what to look for when planning  and searching for routes on different well know websites. 

## Data sources and AI methods
The data should be collected from hikers with different levels. The hikers should be giving data on how the felt on the hike,  if they felt safe, etc.. 
The data should be biased by hiking professionals’ guidance to ensure safer output data from the model. 

I imagine the tools could be classification for the different routes on the different data. The classification should shed light on unknown parameters for the level of a route. This could also be done by unsupervised learning models. For it to get better it should be updated with data from all users. 
If there seems to be a potential problem in getting the right data (users responding honest) it could be considered to run the model only with know data.  
## Challenges
This program will be dealing with sensitive data. This should be taken care of in the right way. 
The model should be integrated with already existing applications. 
The challenge is also to find a shared language in describing how a hike felt, what is “safe”, etc.. 

Training data:
Getting data from different labeled users. (pulsdata, HM, distance, time)
The training data should be labeled after level of experiance.
The users should be trying and rating different routes, and the fitness data (pulsdata, HM, distance, time) should be analyzed.
Routes will be labeled from the training data users.
Bias should be considuirated and testet. Weihgts should be testet. 

Test data:
Labeling of test users data (pulsdata, HM, distance, time).
The test users should be testing hikes that is macthed with their level acording to the trained model.

Following adjusting data:
Users could be giving data to continuasly update the model to give better predictions.

## What next?

* Compliance and legal for ensuring that det data is collected the right way. 
* Showing it to get the existing websites and applications on board. 
* Finding people who are willing to deliver training data to the model.
* Programmers to develop and test models.
* People who are willing to test the first generation of the model. 


## Acknowledgments

* the data collection will be very difficult because it comes from opinions
* it will be difficult to ensure that the model is used correctly and that no one is suggested at route that ends undesirable. There is definitely a responsibility there. 
