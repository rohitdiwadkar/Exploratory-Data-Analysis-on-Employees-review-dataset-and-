# Exploratory-Data-Analysis-on-Employees-review-dataset-and-Bank Marketing 

In this analysis, We are getting familiar to the tools including Python, numpy, matplotlib, pandas, and Jupyter notebook. 
I chose two dataset i.e one for classification and one for regression. 
The data sets are large enough more than 10,000 samples and more than 10 feature values. 
In this analysis, we are visualizing the data by prepossessing data, and then analyzing it to find some research questions and answering them by visualizing it through graphs and charts. 
While doing this , we learnt a lot of things and went through many resources. 
Concepts of probability theory and linear algebra that are most relevant to deep learning and machine learning.

## I. DATA
### Regression
In this section we will be discusing about the EDA i.e. Exploratory Data Analysis. In Statistics and Data analysis , we have to use an approach named EDA - Exploratory Data Analysis before building or transforming the models or applying any machine learning algorithm. It is an approach for analyzing data sets to describe thier main features through visualization. 
So we have to select two datasets i.e. for regression and classification but have to do only EDA no machine learning algorithms are involved.
Regression
So for Regression I chose " Google, Amazon and more Employee Reviews" data from kaggle (https://www.kaggle.com/petersunga/google-amazon-facebook-employee-reviews). This data consists of detailed employee reviews for Google,Amazon, Facebook, Apple, Microsoft, and Netflix. This data was initially scrapped from Glassdoor. 
These data has in total 67,529 records with 16 Variables i.e. features.
The following are the description of the variables :
company -- Company Name 
location -- Location of Company(May include country)
dates -- Date
job-title -- Job Title
summary -- Summary of Employee Review
pros -- Employee Review (Pros)
cons -- Employee Review (Cons)
advice-to-mgmt -- Advice to Management
overall-ratings -- Overall Rating (1-5)
work-balance-stars -- Work/Life Balance Rating (1-5)
culture-values-stars -- Culture and Values Rating (1-5)
carrer-opportunities-stars -- Career Opportunities Rating (1-5)
comp-benefit-stars -- Comp & Benefits Rating (1-5)
senior-mangemnet-stars -- Senior Management Rating (1-5)
helpful-count -- Helpful Review Count
link -- Link to Review (might be outdated)
Below is the code of EDA ( Google, Amazon and more Employee Reviews ) :

Imported all the important packages which will be required for future process (Calculation, visualization etc.)

### Classification
So for Classification I chose "Bank Marketing" dataset from UCI Machine Learning Repository (https://archive.ics.uci.edu/ml/datasets/bank+marketing). The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.
There are 17 variables and in total 45211 records . The folowing are the attribute Information:
Input variables:
1 - age (numeric) 
2 - job : type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown')
3 - marital : marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)
4 - education (categorical: 'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown')
5 - default: has credit in default? (categorical: 'no','yes','unknown')
6 - housing: has housing loan? (categorical: 'no','yes','unknown')
7 - loan: has personal loan? (categorical: 'no','yes','unknown')
8 - contact: contact communication type (categorical: 'cellular','telephone') 
9 - month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')
10 - day: last contact day.
11 - duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no').
12 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
13 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
14 - previous: number of contacts performed before this campaign and for this client (numeric)
15 - poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')
16 - y : has the client subscribed a term deposit? (binary: 'yes','no')
17 - Balance : balance in the bank account (numeric)

## II. Conclusion
From these data analysis , I could learn many aspects of Data Science/ Data Analysis as I was naive for this domain. I learnt how to visualise certain data and learn to compute certain calculation which I never came across. I could learn many python libraries used for calculation or visualization.
But while doing this , I came across many problems that are:
I was getting confused between the Key , value pair which was difficult to visualise but I overcomed that difficulty by going through many resources and books.
I also faced problem in Latex which I couldnt do it till the end as it was getting crashed. I am going to solve that issue very soon.
The classification data I found was very restricted which I realised at later stage and going to keep it in mind for future data set selection as I could do only basic visulaization and nothing much which my mistake.
Therefore I could learn many things and going to help me in my future analysis.
