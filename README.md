# Predicting-Blood-Donations-MTE-Project
Predicting if a Blood Donor will donate within a given time window?

# Abstract
Blood transfusion saves lives - from replacing lost blood during major surgery or a serious injury to treating various illnesses and blood disorders. Ensuring that there's enough blood in supply whenever needed is a serious challenge for the health professionals. According to WebMD, "about 5 million Americans need a blood transfusion every year".

Our dataset is from a mobile blood donation vehicle in Taiwan. The Blood Transfusion Service Center drives to different universities and collects blood as part of a blood drive. We want to predict whether or not a donor will give blood the next time the vehicle comes to campus.

The data is stored in datasets/transfusion.data and it is structured according to RFMTC marketing model (a variation of RFM).

# About the Data
Months since Last Donation: this is the number of months since this donor's most recent donation.
Number of Donations: this is the total number of donations that the donor has made.
Total Volume Donated: this is the total amound of blood that the donor has donated in cubic centimeters.
Months since First Donation: this is the number of months since the donor's first donation.

# Approach
Use Python to explore data related to blood donors and we want to predict whether or not a donor will give blood the next time when the blood donation will be organised.

This process will be done using a Jupyter Notebook.
The code should run w/o errors.
Appropriate use of
data structures/types
loops/conditional statements
Packages
functions
coding practices (i.e. Docstrings, comments, variable names & general readability)
Analysis
Pose questions about the data
Inspect the structure of the original data (very important)
Clean the data
Answer questions about the data using descriptive statistics
Visualize the data (using plt and seaborn)
Perform additional exploratory analysis
Consider where data analysis can be applied to other fields.
Feature Engineering
Using domain knowledge of the data to create features that make machine learning algorithms work.
Machine Learning
Use of Random Forest, Extra Trees, Gradient Boosting, SVC classifiers.

# Result
Now we can target the people who are interested in donating blood and which will results in getting more volunteers and we can save more people.
Blood donation camps can get 40% more blood donors.
Got accuracy upto 78.2%
