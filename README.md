Catcher Frame is a closed source project to detect which catcher caught pitches the best based off the data set given. MLB teams value catchers who can create more called strikes because the more strikes a catcher can obtain for the pitchers the easier it is to get hitters out. Defensive statistics for catchers are one of the least known metrics for players in the MLB. Thus the organization that can best understand the value of defense at the catcher position would have an edge in acquiring and developing the best defensive catchers for their pitching staff. Within the data set the catcherID attribute, which is numeric in value, is the identifier of each catcher that caught each respective pitch. I would recommend searching and viewing through the dataset and understand what each attribute means before embarking on solving the problem.

 

Getting Started

 

First you will need to download the catcherframe data set off my GitHub account and install the devtools package to do so. 

 

Install.packages(“devtools”)

devtools::install_github("Chrisboatto/catcherframe")

library(catcherframe)

 

This allows you to import the dataset to allow you to begin solving the question; which catcher catches pitches the best?

 

The style in which you create the model to test is completely individualistic and as you read through the project you will see five different ways in which you can conclude a metric to depict which catcher catches pitches the best.

 

To improve your findings attach graphs within the project to show accuracy of the models that you created. Below is just one example. It shows the accuracy of the Random Forest model that I created to decipher the best catcher.

 

![A close up of a logo  Description automatically generated](file:///C:/Users/cboat/AppData/Local/Temp/msohtmlclip1/01/clip_image001.jpg)

Lets get started!!