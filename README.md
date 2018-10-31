# HTN-Project
HTN Project - Healthcare Chatbot

## Inspiration
We initially took ideas from the existing FAQ chatbots on websites but we wish to further improve the functionalities of chatbots by being more accessible and user friendly through voice recognition technology and simpler user interface. We also implemented ML to achieve more accurate diagnosis for users.

## What it does
iDoc is an ios app that asks the user to talk or write about their medical symptoms. It uses ML to check what medical conditions the user most likely has, then gives advice on how to proceed. May it be immediately going to an ER or just resting well, iDoc gives a preliminary diagnosis for those who are unsure about whether or not to seek medical attention.

## How we built it
We used Tensorflow to train a neural network that takes a string input and compares the root words against an existing database of symptoms. It then returns the most probable condition based on the set of symptoms, as well as the corresponding advice. The training model was converted into CoreML to optimize on-device performance and ensure user privacy. It also ensure that our app is responsive even when internet is unavailable. 

## Accomplishments that we're proud of
We’ve encountered a variety of bugs in the process of building this app. Conversion of our training model into CoreML and correctly formatting the database. Despite the hardships we faced, we were able to solve the those bugs.

## What we learned
Other than learning and solving the hardships that we ran into, we also learned about the implementation of ML in python using Jupyter notebook interface and application of APIs including IBM Watcom and Microsoft Azure to add functions in our app. Furthermore,we also gained additional experiences with designing user interface and animations on IOS devices

## What's next for IDoc
In the short term, we will include an additional user input option using multiple choice style guided instructions to improve flexibility in the event that users are unable to describe their conditions. Beyond that, we wish to include a greater library of diseases and conditions in our database to further improve the usability of this app. We are also planning to include emotion capture technology to make our chatbots more sympathetic. 
