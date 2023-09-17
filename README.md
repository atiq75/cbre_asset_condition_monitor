# CBRE Asset Condition Monitor
## Inspiration
Our initial plan was to create a web application for Commercial Building Managers that could do two things:

- Show the current status of the assets
- Predict future maintenance needs or potential failures

## What we were able to accomplish
- We came up with backend code i.e. the exploratory data analysis, data visualization and prediction model for the asset monitoring app.
- The model can take relevant data like work orders, asset age, repairs etc. and make a prediction of the priority of maintenance.

##How we built it
- Collected the provided fictional data.
- Cleaned irrelevant information and processed the data.
- Implemented feature engineering to add relevant columns.
- Using K-means to perform unsupervised learning and cluster into categories.
- The model gives out the maintenance priority score that is converted into levels i.e. High, moderate, and low.

## Challenges we ran into
Finding the right machine-learning algorithm was the most challenging part since there was no target/label data. That is why we had to perform unsupervised learning. We tried other unsupervised learning algorithms as well. However, K-means fitted exactly how we wanted it to be and seemed to give a comparatively better prediction.

## Limitations and things that could be improved
We started working on the actual front-end website. However, we couldn't finish it. I will add some pictures to demonstrate how we imagined it to look when we actually implemented the backend code to a user-friendly interface. 
Limitations:
- Even though it gives a good maintenance priority rating, it does not show potential failure possibility yet. Further work can be done using anomaly algorithms.
- It does not provide notification to the manager since we could work only a bit on the front-end website.
- The model can be tuned to give more accurate with the larger dataset. Evaluation of the model will also help.
